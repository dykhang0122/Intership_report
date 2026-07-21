---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
**Thời gian:** 08/05/2026 – 14/05/2026

### Mục tiêu tuần 4:

* Tích hợp môi trường lập trình VS Code với EC2 qua Remote - SSH và phân tích connectivity mạng bằng AWS VPC Reachability Analyzer.
* Quản trị máy chủ EC2 an toàn không cần cấp Public IP hay mở cổng SSH (port 22) bằng EC2 Instance Connect Endpoint (EICE) và AWS Systems Manager (SSM) Session Manager.
* Cài đặt CloudWatch Agent giám sát chỉ số tài nguyên chuyên sâu (RAM, Disk, CPU) và thiết lập hệ thống cảnh báo CloudWatch Alarms tự động.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Kết nối VS Code Remote SSH:** Cấu hình file `~/.ssh/config` trên VS Code để kết nối trực tiếp vào máy chủ EC2 Linux</li><li>- **Thực hành lập trình từ xa:** Chỉnh sửa file mã nguồn web trực tiếp trên VS Code SSH</li></ul> | 08/05/2026 | 08/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Sử dụng Reachability Analyzer:** Tìm hiểu AWS VPC Reachability Analyzer</li><li>- **Phân tích luồng mạng:** Tạo Analysis Path từ Internet Gateway/Subnet đến EC2 để kiểm tra rào cản firewall</li></ul> | 09/05/2026 | 09/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Chẩn đoán sự cố mạng:** Giả lập lỗi đóng port Security Group/NACL và dùng Reachability Analyzer chẩn đoán chính xác vị trí bị chốt chặn</li></ul> | 10/05/2026 | 10/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Cấu hình SSM Session Manager:** Gán IAM Role `AmazonSSMManagedInstanceCore` cho EC2 instance</li><li>- **Truy cập bảo mật qua SSM:** Kết nối Terminal vào EC2 thông qua SSM Session Manager trên AWS Console/CLI không cần cổng 22</li></ul> | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Thiết lập EC2 Instance Connect Endpoint:** Khởi tạo EICE trong VPC Private Subnet</li><li>- **Thực hành kết nối private:** Kết nối SSH tới EC2 nằm trong Private Subnet không có Public IP qua EICE tunnel</li></ul> | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Cài đặt CloudWatch Agent:** Cài đặt gói `amazon-cloudwatch-agent` lên EC2 Linux</li><li>- **Cấu hình file json Agent:** Cấu hình thu thập métrics bộ nhớ RAM (`mem_used_percent`) và dung lượng ổ đĩa (`disk_used_percent`)</li></ul> | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tạo CloudWatch Alarms:** Cấu hình Alarm gửi thông báo qua SNS Email khi CPU > 80% hoặc RAM > 85%</li><li>- **Tổng kết & Đánh giá:** Kiểm thử trigger cảnh báo và tổng hợp tài liệu quản trị hệ thống tuần 4</li></ul> | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

* Thiết lập môi trường phát triển hiện đại: kết nối VS Code Remote SSH làm việc trực tiếp trên máy chủ đám mây.
* Làm chủ công cụ VPC Reachability Analyzer giúp chẩn đoán và khắc phục nhanh các tắc nghẽn định tuyến mạng.
* Nâng cao tiêu chuẩn bảo mật hệ thống: loại bỏ cổng 22 công cộng, quản trị an toàn bằng SSM Session Manager và EC2 Instance Connect Endpoint.
* Triển khai giải pháp giám sát toàn diện với CloudWatch Agent và thiết lập hệ thống tự động gửi email cảnh báo sự cố qua SNS.
