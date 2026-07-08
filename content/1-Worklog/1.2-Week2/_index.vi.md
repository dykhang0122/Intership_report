---
title: "Worklog Tuần 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
**Thời gian:** 24/04/2026 – 30/04/2026

### Mục tiêu tuần 2:

* Hiểu sâu Amazon VPC và mô hình mạng phân lớp trên AWS.
* Thực hành thiết kế Subnet, Route Table, Internet Gateway, NAT Gateway và VPN Site-to-Site.
* Cấu hình Security Group, Network ACL và kiểm tra luồng traffic giữa các lớp mạng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Tìm hiểu VPC:** Tìm hiểu Amazon VPC: CIDR, Public/Private Subnet, route propagation | 24/04/2026 | 24/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Mô hình mạng:** So sánh mô hình mạng hub-spoke và multi-tier trên AWS | 25/04/2026 | 25/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Thiết kế mạng:** Vẽ sơ đồ kiến trúc mạng tham khảo cho lab | 26/04/2026 | 26/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Thực hành VPC:** Tạo VPC mới, chia Public và Private Subnet theo AZ <br> - **Cấu hình định tuyến:** Cấu hình Route Table, gắn Internet Gateway cho Public Subnet <br> - **Kiểm tra kết nối:** Kiểm tra routing và connectivity từ EC2 public | 27/04/2026 | 27/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành NAT Gateway:** Cho phép Private Subnet ra Internet an toàn <br> - **Cấu hình NAT:** Cấu hình route `0.0.0.0/0` qua NAT cho private route table <br> - **Kiểm tra NAT:** Test outbound connection từ instance trong Private Subnet | 28/04/2026 | 28/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Thực hành VPN:** VPN Site-to-Site: Virtual Private Gateway, Customer Gateway, VPN connection <br> - **Thiết lập IPSec:** Thiết lập tunnel IPSec giữa mạng on-premises (mô phỏng) và VPC <br> - **Kiểm tra VPN:** Kiểm tra trạng thái tunnel và route table liên quan | 29/04/2026 | 29/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Bảo mật mạng:** Cấu hình Security Group (stateful) và Network ACL (stateless) <br> - **So sánh tường lửa:** So sánh quy tắc inbound/outbound, thứ tự rule NACL <br> - **Kiểm tra truy cập:** Kiểm tra và ghi nhận luồng traffic cho phép/từ chối | 30/04/2026 | 30/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 2:

* Hiểu rõ kiến trúc VPC, vai trò của Subnet, Route Table, IGW và NAT Gateway.
* Triển khai mạng phân lớp Public/Private; instance private truy cập Internet qua NAT.
* Thiết lập VPN Site-to-Site và hiểu cách routing giữa on-premises với VPC.
* Phân biệt và cấu hình Security Group vs Network ACL; kiểm soát traffic hiệu quả.
