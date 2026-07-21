---
title: "Worklog Tuần 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
**Thời gian:** 24/04/2026 – 30/04/2026

### Mục tiêu tuần 2:

* Hiểu sâu mô hình mạng AWS VPC, cấu hình dải địa chỉ IP (CIDR), tạo Public/Private Subnet và phân chia Route Table.
* Thực hành thiết lập Internet Gateway (IGW), NAT Gateway cho mạng nội bộ và mô phỏng kết nối VPN Site-to-Site.
* Thiết lập các lớp bảo mật mạng chuyên sâu bằng Security Group (stateful) và Network ACL (stateless).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tìm hiểu VPC:** Nghiên cứu tổng quan Amazon VPC, CIDR block, cách phân chia IP Private và IP Public</li><li>- **Thiết kế sơ đồ:** Vẽ sơ đồ hạ tầng mạng VPC với 2 AZs</li></ul> | 24/04/2026 | 24/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Khởi tạo VPC & Subnets:** Tạo Custom VPC (`10.0.0.0/16`), tạo Public Subnet và Private Subnet trên các AZs</li><li>- **Cấu hình Route Table:** Khởi tạo Public Route Table và Private Route Table</li></ul> | 25/04/2026 | 25/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Cấu hình Internet Gateway:** Tạo và gắn Internet Gateway (IGW) vào Custom VPC</li><li>- **Định tuyến Public:** Thêm route `0.0.0.0/0` trỏ tới IGW trong Public Route Table</li></ul> | 26/04/2026 | 26/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Khởi tạo NAT Gateway:** Khởi tạo Elastic IP (EIP) và tạo NAT Gateway nằm trong Public Subnet</li><li>- **Định tuyến Private:** Cấu hình Private Route Table cho phép máy chủ trong Private Subnet truy cập Internet outbound qua NAT Gateway</li></ul> | 27/04/2026 | 27/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Nghiên cứu VPN:** Tìm hiểu kiến trúc VPN Site-to-Site, Virtual Private Gateway (VGW), Customer Gateway (CGW)</li><li>- **Mô phỏng VPN:** Thiết lập Virtual Private Gateway và cấu hình IPSec Tunnel kết nối mạng doanh nghiệp với VPC</li></ul> | 28/04/2026 | 28/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Thực hành Security Group:** Tạo Security Group (stateful) cho Web Server (bật port 80, 443, 22)</li><li>- **Thực hành Network ACL:** Cấu hình Network ACL (stateless) cho Subnet, kiểm soát quy tắc inbound/outbound theo rule number</li></ul> | 29/04/2026 | 29/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Kiểm thử & Đánh giá:** Khởi tạo EC2 thử nghiệm ở 2 Subnet, test khả năng kết nối ping, SSH, HTTP và rà soát các quy tắc firewall</li></ul> | 30/04/2026 | 30/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 2:

* Nắm vững kiến thức VPC, tự tay thiết kế và cấu hình hoàn chỉnh mạng ảo phân lớp Public/Private Subnet.
* Đã định tuyến thành công luồng mạng: Public Subnet ra Internet qua IGW, Private Subnet truy cập outbound an toàn qua NAT Gateway.
* Hiểu cơ chế hoạt động của VPN Site-to-Site và quy trình mở rộng kết nối từ On-Premises lên AWS Cloud.
* Phân biệt rõ ràng sự khác nhau giữa Security Group (Instance-level, stateful) và Network ACL (Subnet-level, stateless), thiết lập bảo mật nhiều lớp an toàn.
