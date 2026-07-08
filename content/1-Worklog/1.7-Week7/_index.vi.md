---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
**Thời gian:** 29/05/2026 – 04/06/2026

### Mục tiêu tuần 7:

* Củng cố kiến thức EC2 và vai trò máy chủ ảo trong triển khai ứng dụng.
* Thực hành tạo Amazon Linux EC2 với AMI, Instance Type, Key Pair phù hợp.
* Cấu hình mạng (VPC, Subnet, Public IP, Security Group) và truy cập SSH an toàn.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Ôn tập 3-Tier:** Ôn tập EC2 trong kiến trúc 3-tier: web, app, database layer | 29/05/2026 | 29/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **So sánh chi phí:** So sánh On-Demand, Reserved, Spot instance về chi phí | 30/05/2026 | 30/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Cấu hình khởi động:** User data script: bootstrap package khi launch instance | 31/05/2026 | 31/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Thực hành EC2:** Launch Amazon Linux 2023, chọn AMI và Instance Type t2/t3 <br> - **Quản lý Key Pair:** Tạo và download Key Pair (.pem), set permission file <br> - **Quyền truy cập:** Gán IAM role cho EC2 (SSM, S3 read nếu cần) | 01/06/2026 | 01/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Mạng cho EC2:** Cấu hình VPC/Subnet cho instance; Elastic IP vs auto public IP <br> - **Security Group:** Chỉ mở port cần thiết (22 restricted hoặc SSM-only) <br> - **Kiểm tra định tuyến:** Kiểm tra route table và NACL không chặn traffic hợp lệ | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Lifecycle máy chủ:** Quản lý lifecycle trên Console: monitor, reboot, stop/start, terminate <br> - **Kiểm tra trạng thái:** Status check: system vs instance; xử lý khi fail <br> - **Lưu trữ EBS:** Gắn thêm EBS, mở rộng volume online (nếu hỗ trợ) | 03/06/2026 | 03/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Truy cập từ xa:** SSH: `ssh -i key.pem ec2-user@ip`; cấu hình `~/.ssh/config` <br> - **Deploy ứng dụng:** Deploy ứng dụng demo (static site hoặc API nhỏ) lên EC2 <br> - **Checklist bảo mật:** Patch OS, firewall, không dùng root trực tiếp | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 7:

* Hiểu vai trò EC2 trong kiến trúc ứng dụng và các mô hình mua instance.
* Tạo và cấu hình Amazon Linux EC2 với AMI, Instance Type, Key Pair, IAM role.
* Thiết lập mạng VPC/Subnet/Public IP/Security Group đúng nguyên tắc least exposure.
* Quản lý instance trên Console; truy cập SSH và triển khai ứng dụng demo thành công.
