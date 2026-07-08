---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
**Thời gian:** 01/05/2026 – 07/05/2026

### Mục tiêu tuần 3:

* Nắm vững Amazon EC2 và các thành phần: Instance Type, AMI, Key Pair, EBS, snapshot/backup.
* Thực hành tạo máy ảo, gắn volume, quản lý lưu trữ và kết nối bảo mật.
* Hiểu cách chọn cấu hình EC2 phù hợp workload và chi phí.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Tìm hiểu EC2:** Tìm hiểu EC2: Instance Family (t, m, c, r…), vCPU, RAM, network performance | 01/05/2026 | 01/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Tìm hiểu AMI:** AMI: Amazon Linux, Ubuntu; custom AMI và lifecycle | 02/05/2026 | 02/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Tìm hiểu Key Pair:** Key Pair: cách tạo, lưu trữ và dùng cho SSH/RDP | 03/05/2026 | 03/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Lưu trữ EBS:** Tìm hiểu EBS: gp3, io2, st1; root volume vs additional volume <br> - **Chiến lược sao lưu:** Snapshot, AMI từ snapshot; chiến lược backup định kỳ <br> - **So sánh lưu trữ:** So sánh EBS với Instance Store | 04/05/2026 | 04/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành EC2:** Launch EC2 (Amazon Linux), chọn Instance Type và Security Group <br> - **Địa chỉ IP:** Gán Elastic IP (nếu cần), kiểm tra public/private IP <br> - **Cấu hình ban đầu:** Kết nối SSH, cập nhật hệ thống và cài gói cơ bản | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Thực hành EBS:** Tạo EBS volume mới, attach/detach, format và mount filesystem <br> - **Thực hành Snapshot:** Tạo snapshot volume; restore từ snapshot sang volume/instance mới <br> - **Quy trình backup:** Ghi chú quy trình backup trước khi thay đổi cấu hình | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Bảo mật SSH:** Quản lý Key Pair và hardening SSH (disable password login, restrict SG) <br> - **Giám sát EC2:** Theo dõi instance qua Console: CPU, status check, reboot/stop/start <br> - **Tối ưu chi phí:** Tổng kết best practice chọn Instance Type và quản lý chi phí EC2 | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:

* Hiểu Instance Type, AMI, Key Pair và cách chọn cấu hình EC2 theo nhu cầu.
* Thực hành tạo EC2, gắn EBS, snapshot và khôi phục dữ liệu từ backup.
* Thiết lập kết nối SSH bảo mật và quản lý vòng đời instance trên Console.
* Nắm chiến lược backup EBS/AMI và tối ưu chi phí lưu trữ.
