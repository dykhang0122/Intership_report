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
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Đăng ký tài khoản AWS:</b> Đăng ký thành công AWS Free Tier và hoàn tất xác minh</li><li><b>- Tìm hiểu khái niệm:</b> Khái niệm Region, Availability Zone (AZ) và AWS Global Infrastructure</li></ul> | 17/04/2026 | 17/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Khám phá Console:</b> Tìm hiểu giao diện AWS Management Console và các nhóm dịch vụ cơ bản</li><li><b>- Cấu hình AWS CLI:</b> Cài đặt AWS CLI v2, cấu hình credentials (`aws configure`)</li></ul> | 18/04/2026 | 18/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Thực hành AWS CLI:</b> Chạy các lệnh CLI kiểm tra tài khoản: `aws sts get-caller-identity`, `aws s3 ls`</li></ul> | 19/04/2026 | 19/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Bảo mật IAM:</b> Bật MFA (Multi-Factor Authentication) cho tài khoản Root</li><li><b>- Tạo IAM User & Group:</b> Khởi tạo các IAM User, gán vào IAM Group theo chức danh</li></ul> | 20/04/2026 | 20/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Viết IAM Policy:</b> Soạn thảo IAM Policy dạng JSON và gán quyền theo nguyên tắc Least Privilege</li><li><b>- Phân biệt IAM Roles:</b> Tìm hiểu sự khác biệt giữa IAM User, Group, Role và Policy</li></ul> | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Cấu hình AWS Budgets:</b> Thiết lập ngân sách AWS Budgets cảnh báo khi chi phí vượt ngưỡng $5</li><li><b>- Kích hoạt Cost Explorer:</b> Bật AWS Cost Explorer để theo dõi biểu đồ chi tiêu hàng ngày</li></ul> | 22/04/2026 | 22/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Tổng kết & Đánh giá:</b> Rà soát các tài nguyên đã tạo, kiểm tra nhật ký chi phí và tổng hợp báo cáo tuần 1</li></ul> | 23/04/2026 | 23/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 1:

* Đã tạo thành công tài khoản AWS Free Tier và hiểu rõ hạ tầng đám mây toàn cầu (Regions & Availability Zones).
* Nắm vững các khái niệm dịch vụ nền tảng của AWS và sử dụng thành thạo cả AWS Console lẫn AWS CLI.
* Thiết lập hệ thống bảo mật IAM an toàn: bật MFA root, chia nhóm người dùng và viết policy chuẩn Least Privilege.
* Thiết lập cảnh báo chi phí tự động qua AWS Budgets và theo dõi luồng dòng tiền thực tế bằng Cost Explorer.
