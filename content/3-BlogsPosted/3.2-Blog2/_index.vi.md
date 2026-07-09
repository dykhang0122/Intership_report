---
title: "Giới hạn truy cập AWS Management Console từ các mạng mong muốn"
date: 2026-06-26
weight: 20
chapter: false
pre: " <b> 3.2. </b> "
---

# Biến AWS Console Sign-in thành một lớp kiểm soát bảo mật mạng doanh nghiệp

Để giúp doanh nghiệp giảm rủi ro lạm dụng thông tin đăng nhập (credential abuse) ở ngoài phạm vi mạng nội bộ, tăng khả năng tuân thủ và thiết lập chính sách quản trị bảo mật nhất quán trên nhiều tài khoản, AWS đã giới thiệu giải pháp giới hạn quyền đăng nhập vào **AWS Management Console** và phiên đăng nhập CLI (**aws login CLI**) chỉ từ các mạng được kỳ vọng.

Ví dụ:
* Mạng văn phòng công ty (Corporate office network)
* VPN doanh nghiệp (Corporate VPN)
* Mạng trung tâm dữ liệu on-premises (On-premises data center)
* Mạng VPC của khách hàng trên AWS (Customer VPC)

---

## Sơ đồ kiểm soát truy cập AWS Management Console & CLI (Architecture Diagram)

Dưới đây là sơ đồ mô tả cách AWS Sign-In áp dụng các chính sách kiểm soát dựa trên tài nguyên và RCP để phân loại, cho phép hoặc từ chối các yêu cầu truy cập từ mạng:

![Restrict AWS Management Console & CLI Access](/images/3-BlogsPosted/blog2_restrict_access.png)

---

## 1. Ý nghĩa và cơ chế hoạt động

Cơ chế này đặc biệt quan trọng vì nó đưa kiểm soát bảo mật lên ngay tại lớp **AWS Sign-In**, tức là **trước hoặc trong quá trình** người dùng thiết lập phiên làm việc Console. 

Trước đây, các tổ chức kiểm soát quyền chủ yếu bằng IAM Policy, SCP hoặc network controls riêng lẻ. Với **Sign-in resource-based policies** và **RCPs**, doanh nghiệp có thể chặn đứng hành vi đăng nhập trái phép vào Console từ mạng không mong muốn ngay từ "cửa ngõ" đầu tiên. Điều này mang lại giá trị to lớn cho các ngành có yêu cầu tuân thủ khắt khe như tài chính, ngân hàng, bảo hiểm, y tế, hay chính phủ.

### Hai cơ chế chính từ AWS:
1. **Sign-in Resource-Based Policies**: Áp dụng trực tiếp cho một tài khoản AWS cụ thể.
2. **Resource Control Policies (RCPs)**: Áp dụng ở cấp AWS Organizations (hoặc OU) để mở rộng khả năng kiểm soát nhất quán trên toàn bộ hệ thống đa tài khoản (multi-account).

---

## 2. Vấn đề thực tế của doanh nghiệp

Các doanh nghiệp thường đối mặt với các rủi ro bảo mật nghiêm trọng sau:

- **Đăng nhập không kiểm soát**: Nhân viên hoặc quản trị viên có thể đăng nhập AWS Console từ mạng cá nhân, quán cà phê, sân bay hoặc Wi-Fi công cộng kém an toàn.
- **Thất thoát Credentials**: Kẻ tấn công sở hữu thông tin tài khoản bị lộ (compromised credentials) có thể thực hiện đăng nhập từ bất kỳ đâu trên thế giới.
- **Khó khăn khi Kiểm toán (Auditing)**: Rất khó chứng minh với các kiểm toán viên (auditor) rằng AWS Console chỉ được truy cập duy nhất từ mạng nội bộ doanh nghiệp.
- **Cấu hình phân tán**: Khi quản lý hàng trăm tài khoản AWS, việc cấu hình thủ công chính sách bảo mật cho từng tài khoản rất dễ xảy ra sai sót.
- **Nguy cơ tự khóa (Lockout)**: Nếu cấu hình chính sách chặn quá nghiêm ngặt và không có phương án dự phòng, quản trị viên có nguy cơ tự khóa mình khỏi tài khoản AWS.

---

## 3. Giải pháp toàn diện từ AWS

AWS đề xuất một bộ giải pháp tích hợp để giải quyết các vấn đề trên:

### Sign-in Resource-Based Policy cho từng tài khoản
Quản trị viên cấu hình chính sách phủ quyết (**Deny**) đăng nhập nếu request không đến từ dải IP (Corporate CIDR) hoặc VPC ID được cho phép. Bạn có thể tạo policy này dễ dàng thông qua AWS CLI bằng cách truyền vào các tham số:
* Dải IP (CIDR) mạng công ty.
* VPC ID được phép và Region tương ứng.
* Đối tượng ngoại lệ (Excluded Principal) để tránh bị lockout.

### Cơ chế Excluded Principal (Break-glass account)
Chỉ định cụ thể một tài khoản hoặc vai trò quản trị dự phòng được phép đăng nhập từ mọi mạng (không bị giới hạn IP) để xử lý các sự cố khẩn cấp và tránh rủi ro mất quyền truy cập tài khoản.

### Console Authorization Configuration
Sau khi khởi tạo và kiểm tra nội dung Policy (khi policy chưa có hiệu lực), quản trị viên kích hoạt tính năng thực thi (**Enforcement**) bằng lệnh `put-console-authorization-configuration`.

### Giám sát qua AWS CloudTrail
Toàn bộ lịch sử đăng nhập sẽ được ghi lại chi tiết:
* **Hợp lệ**: Ghi nhận sự kiện `ConsoleLogin` với trạng thái `Success`.
* **Không hợp lệ**: Ghi nhận sự kiện `ConsoleLogin` với trạng thái `Failure` và mã lỗi `AccessDenied`.

### Sử dụng RCPs trong AWS Organizations
Áp dụng Resource Control Policies ở cấp thư mục gốc (Root Organization) hoặc Đơn vị tổ chức (OU) để đồng bộ hóa và thực thi chính sách bảo mật mạng đồng nhất trên toàn bộ các tài khoản con mà không cần cấu hình thủ công từng tài khoản.

### Kết hợp với Console Private Access & Data Perimeter
Sự kết hợp này giúp hình thành một vành đai bảo mật dữ liệu toàn diện:
- **Network Perimeter**: Chỉ cho phép đăng nhập từ mạng tin cậy.
- **Identity Perimeter**: Chỉ cho phép danh tính (identity) tin cậy được đăng nhập.
- **Resource Perimeter**: Giới hạn cụ thể tài khoản AWS nào được phép truy cập từ mạng nội bộ.

---

## Tài liệu tham khảo
* Đọc bài viết gốc trên AWS Security Blog: [Restrict AWS Management Console Access to Expected Networks with Sign-in Resource-Based Policies and RCPs](https://aws.amazon.com/blogs/security/restrict-aws-management-console-access-to-expected-networks-with-sign-in-resource-based-policies-and-rcps/)