---
title: "Worklog Tuần 1"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---
**Thời gian:** 17/04/2026 – 23/04/2026

### Mục tiêu tuần 1:

* Làm quen môi trường AWS, tạo tài khoản và nắm các nhóm dịch vụ nền tảng (Compute, Storage, Networking, Database).
* Thực hành quản lý truy cập với IAM, thiết lập mạng cơ bản với VPC và khởi tạo máy chủ ảo EC2.
* Tìm hiểu cách theo dõi chi phí, sử dụng Billing Dashboard và các kênh hỗ trợ của AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Đăng ký tài khoản:** AWS Free Tier và kích hoạt tài khoản <br> - **Tìm hiểu:** Các vùng (Region) và Availability Zone (AZ) | 17/04/2026 | 17/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Mô hình trách nhiệm:** Tìm hiểu mô hình Shared Responsibility | 18/04/2026 | 18/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Khám phá dịch vụ:** Compute, Storage, Networking, Database trên Console | 19/04/2026 | 19/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Làm quen Console:** AWS Management Console: tìm kiếm dịch vụ, xem dashboard <br> - **Cấu hình CLI:** Cài đặt và cấu hình AWS CLI (Access Key, Secret Key, default Region) <br> - **Thực hành CLI:** Chạy các lệnh CLI cơ bản: `aws sts get-caller-identity`, `aws ec2 describe-regions` | 20/04/2026 | 20/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành IAM:** Tạo IAM User, Group, Policy (JSON) và gán quyền theo nguyên tắc least privilege <br> - **Bảo mật tài khoản:** Bật MFA cho tài khoản root/admin <br> - **Khái niệm IAM:** Phân biệt IAM User, Role và Policy | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Thực hành VPC:** Tạo VPC, Public/Private Subnet, CIDR block <br> - **Thực hành EC2:** Chọn AMI, Instance Type, tạo Key Pair, launch instance <br> - **Kết nối máy chủ:** Kết nối SSH vào EC2, kiểm tra trạng thái instance trên Console | 22/04/2026 | 22/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Quản lý chi phí:** Tìm hiểu AWS Billing & Cost Management: Cost Explorer, Budgets, Free Tier usage <br> - **Hỗ trợ kỹ thuật:** Đọc tài liệu AWS Support Plans (Basic, Developer, Business) <br> - **Tổng kết tuần:** Tổng hợp ghi chú tuần 1 và rà soát tài nguyên đã tạo | 23/04/2026 | 23/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 1:

* Đã tạo và xác minh tài khoản AWS Free Tier; hiểu cấu trúc Region/AZ và mô hình trách nhiệm dùng chung.
* Sử dụng thành thạo AWS Console và AWS CLI cho các thao tác tra cứu, cấu hình cơ bản.
* Thiết lập IAM User, Group, Policy; áp dụng phân quyền theo least privilege và bật MFA.
* Tạo VPC, Subnet; khởi tạo EC2 instance, kết nối SSH và quản lý Key Pair.
* Nắm cách theo dõi chi phí qua Billing Dashboard và tìm tài liệu/hỗ trợ trên AWS.
