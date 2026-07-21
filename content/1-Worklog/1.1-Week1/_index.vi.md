---
title: "Worklog Tuần 1"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---
**Thời gian:** 17/04/2026 – 23/04/2026

### Mục tiêu tuần 1:

* Đăng ký tài khoản AWS Free Tier và làm quen với các khái niệm dịch vụ nền tảng (Compute, Storage, Networking, Database).
* Thực hành quản lý tài khoản, tạo IAM User, Group, Policy và thiết lập phân quyền theo nguyên tắc Least Privilege (quyền tối thiểu).
* Khởi tạo AWS Budgets và Cost Explorer để quản lý, giám sát ngân sách và cảnh báo chi phí tự động.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Đăng ký tài khoản AWS:** Đăng ký thành công AWS Free Tier và hoàn tất xác minh</li><li>- **Tìm hiểu khái niệm:** Khái niệm Region, Availability Zone (AZ) và AWS Global Infrastructure</li></ul> | 17/04/2026 | 17/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Khám phá Console:** Tìm hiểu giao diện AWS Management Console và các nhóm dịch vụ cơ bản</li><li>- **Cấu hình AWS CLI:** Cài đặt AWS CLI v2, cấu hình credentials (`aws configure`)</li></ul> | 18/04/2026 | 18/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Thực hành AWS CLI:** Chạy các lệnh CLI kiểm tra tài khoản: `aws sts get-caller-identity`, `aws s3 ls`</li></ul> | 19/04/2026 | 19/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Bảo mật IAM:** Bật MFA (Multi-Factor Authentication) cho tài khoản Root</li><li>- **Tạo IAM User & Group:** Khởi tạo các IAM User, gán vào IAM Group theo chức danh</li></ul> | 20/04/2026 | 20/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Viết IAM Policy:** Soạn thảo IAM Policy dạng JSON và gán quyền theo nguyên tắc Least Privilege</li><li>- **Phân biệt IAM Roles:** Tìm hiểu sự khác biệt giữa IAM User, Group, Role và Policy</li></ul> | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Cấu hình AWS Budgets:** Thiết lập ngân sách AWS Budgets cảnh báo khi chi phí vượt ngưỡng $5</li><li>- **Kích hoạt Cost Explorer:** Bật AWS Cost Explorer để theo dõi biểu đồ chi tiêu hàng ngày</li></ul> | 22/04/2026 | 22/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tổng kết & Đánh giá:** Rà soát các tài nguyên đã tạo, kiểm tra nhật ký chi phí và tổng hợp báo cáo tuần 1</li></ul> | 23/04/2026 | 23/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 1:

* Đã tạo thành công tài khoản AWS Free Tier và hiểu rõ hạ tầng đám mây toàn cầu (Regions & Availability Zones).
* Nắm vững các khái niệm dịch vụ nền tảng của AWS và sử dụng thành thạo cả AWS Console lẫn AWS CLI.
* Thiết lập hệ thống bảo mật IAM an toàn: bật MFA root, chia nhóm người dùng và viết policy chuẩn Least Privilege.
* Thiết lập cảnh báo chi phí tự động qua AWS Budgets và theo dõi luồng dòng tiền thực tế bằng Cost Explorer.
