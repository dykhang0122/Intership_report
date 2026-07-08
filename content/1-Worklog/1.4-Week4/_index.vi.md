---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
**Thời gian:** 08/05/2026 – 14/05/2026

### Mục tiêu tuần 4:

* Kết nối VPC với Visual Studio Code, kiểm tra connectivity và triển khai ứng dụng trên EC2.
* Sử dụng Reachability Analyzer đánh giá khả năng kết nối mạng.
* Thiết lập EC2 Instance Connect Endpoint và SSM Session Manager thay cho SSH trực tiếp.
* Cấu hình CloudWatch Monitoring & Alerting cho hệ thống.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Cấu hình môi trường:** Kết nối môi trường dev (VS Code) với tài nguyên trong VPC | 08/05/2026 | 08/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Kiểm tra mạng:** Test ping/traceroute, kiểm tra Security Group và route | 09/05/2026 | 09/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Thực hành EC2:** Thực hành EC2 cơ bản: deploy file, chạy service thử nghiệm | 10/05/2026 | 10/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Máy chủ ứng dụng:** Biến EC2 "trống" thành application server: cài web server/runtime, deploy app mẫu <br> - **Kiểm tra luồng mạng:** Tìm hiểu VPC Reachability Analyzer: tạo path analysis giữa nguồn và đích <br> - **Khắc phục lỗi mạng:** Phân tích kết quả blocked/reachable và sửa cấu hình mạng | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Kết nối bảo mật:** Thực hành EC2 Instance Connect Endpoint cho private instance <br> - **Quản trị máy chủ:** Cấu hình SSM Session Manager: IAM role, SSM Agent, không mở port 22 public <br> - **So sánh kết nối:** Truy cập shell qua Console/CLI và so sánh với SSH truyền thống | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Giám sát CloudWatch:** CloudWatch: metric EC2 (CPU, network), custom metric, log group <br> - **Cảnh báo tự động:** Tạo dashboard giám sát và CloudWatch Alarm (email/SNS) <br> - **Thiết lập ngưỡng:** Thiết lập ngưỡng cảnh báo khi CPU cao hoặc status check failed | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Kiểm tra hệ thống:** Kiểm tra end-to-end: app chạy ổn, Session Manager hoạt động, alarm kích hoạt đúng <br> - **Vận hành & Bảo mật:** Ghi chú runbook vận hành và checklist bảo mật tuần 4 <br> - **Tối ưu tài nguyên:** Dọn dẹp/tối ưu tài nguyên test không cần thiết | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

* Kết nối VPC với VS Code và triển khai ứng dụng mẫu trên EC2 thành công.
* Sử dụng Reachability Analyzer để chẩn đoán và sửa lỗi connectivity.
* Truy cập instance an toàn qua EC2 Instance Connect Endpoint và SSM Session Manager.
* Thiết lập CloudWatch dashboard và alarm; giám sát hệ thống chủ động.
