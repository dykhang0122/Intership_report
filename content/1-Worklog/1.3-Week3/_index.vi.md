---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
**Thời gian:** 01/05/2026 – 07/05/2026

### Mục tiêu tuần 3:

* Tìm hiểu chi tiết dịch vụ Amazon EC2, các nhóm Instance Type (t3.micro, c5, r5,...), Amazon Machine Image (AMI) và quản lý SSH Key Pair.
* Thực hành tạo máy ảo EC2 Linux, mở rộng lưu trữ với Elastic Block Store (EBS), thiết lập EBS Snapshot và tự động hóa sao lưu (Backup).
* Cài đặt, cấu hình và vận hành ứng dụng Web Server cơ bản (Nginx) trên máy chủ EC2 Linux, kiểm tra truy cập công cộng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tìm hiểu Amazon EC2:** Học lý thuyết EC2: Instance Types, EC2 Lifecycle (Launch, Stop, Terminate, Reboot)</li><li>- **Phân loại AMI:** Tìm hiểu Amazon Machine Image (Quick Start AMI, Custom AMI, Marketplace AMI)</li></ul> | 01/05/2026 | 01/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tạo SSH Key Pair:** Khởi tạo Key Pair `.pem` an toàn cho kết nối máy chủ Linux</li><li>- **Launch EC2 Instance:** Khởi tạo EC2 Amazon Linux 2023 (`t3.micro`), gán Public IP và Security Group</li></ul> | 02/05/2026 | 02/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Kết nối SSH:** Truy cập máy chủ EC2 Linux từ máy cục bộ bằng SSH client (`ssh -i key.pem ec2-user@public-ip`)</li><li>- **Cập nhật hệ thống:** Cập nhật các gói phần mềm hệ thống (`sudo dnf update -y`)</li></ul> | 03/05/2026 | 03/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Quản lý EBS Volume:** Tìm hiểu các loại EBS (gp3, io2, st1), khởi tạo thêm ổ đĩa EBS bổ sung</li><li>- **Mount ổ đĩa:** Thực hành `fdisk`, định dạng filesystem (ext4/xfs) và mount ổ đĩa EBS mới vào thư mục `/data`</li></ul> | 04/05/2026 | 04/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tạo EBS Snapshot:** Thực hành chụp ảnh ổ đĩa (Snapshot) thủ công cho EBS Volume</li><li>- **Cấu hình AWS Backup:** Cấu hình AWS Backup Plan tự động sao lưu định kỳ ổ đĩa EBS và tạo Custom AMI từ instance</li></ul> | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Cài đặt Nginx:** Cài đặt Web Server Nginx trên máy chủ EC2 Linux (`sudo dnf install nginx -y`)</li><li>- **Cấu hình Web Server:** Viết trang `index.html` tùy biến, khởi động dịch vụ Nginx và kích hoạt auto-start</li></ul> | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Kiểm thử Web Server:** Mở port HTTP (80) trên Security Group và kiểm tra truy cập Nginx qua trình duyệt</li><li>- **Đánh giá & Tổng kết:** Rà soát dung lượng EBS, quy trình Backup và viết báo cáo tổng kết tuần 3</li></ul> | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:

* Hiểu rõ cách lựa chọn EC2 Instance Type và AMI phù hợp với từng tải công việc nghiệp vụ.
* Đã khởi tạo và làm chủ máy ảo EC2 Amazon Linux 2023, kết nối SSH an toàn thông qua Key Pair.
* Thành thạo thao tác quản lý ổ đĩa EBS: khởi tạo, định dạng, mount vào hệ điều hành và thiết lập quy trình sao lưu Snapshot/AWS Backup tự động.
* Biến thành công EC2 Linux thành Web Server Nginx hoạt động ổn định, phục vụ nội dung web qua giao thức HTTP công cộng.
