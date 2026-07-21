---
title: "Worklog Tuần 11"
date: 2026-06-26
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
**Thời gian:** 26/06/2026 – 02/07/2026

### Mục tiêu tuần 11:

* Tối ưu hóa mã nguồn AWS Lambda: tinh chỉnh cấu hình Memory/Timeout, tối ưu hóa các lệnh gọi SDK `boto3`, áp dụng Provisioned Concurrency nhằm giảm cold start và tiết kiệm chi phí vận hành.
* Thực hiện Integration Testing toàn diện cho toàn bộ hệ thống xử lý hóa đơn tự động end-to-end, phát hiện và sửa các lỗi phát sinh (handling timeout, format JSON lỗi, network retry).
* Hoàn thiện nội dung báo cáo thực tập, chụp đầy đủ ảnh minh chứng cấu hình hệ thống thực tế trên AWS Management Console.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Phân tích hiệu năng Lambda:</b> Dùng AWS Lambda Power Tuning / CloudWatch Insights phân tích mức tiêu thụ Memory và thời gian thực thi (Execution Duration)</li><li>- <b>Tối ưu mã nguồn Lambda:</b> Refactor code Python, tái sử dụng các kết nối HTTP/boto3 client bên ngoài handler</li></ul> | 26/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Tối ưu chi phí & Cold Start:</b> Điều chỉnh cấu hình RAM từ 1024MB xuống 512MB tối ưu hóa chi phí, cấu hình Provisioned Concurrency loại bỏ Cold Start</li></ul> | 27/06/2026 | 27/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Thực hiện Integration Testing:</b> Chạy kịch bản kiểm thử tải liên tục upload 20 hóa đơn (PDF, PNG, JPG) đủ kích thước lên S3</li><li>- <b>Ghi nhận log kiểm thử:</b> Kiểm tra CloudWatch Logs để phát hiện các lỗi trích xuất dữ liệu</li></ul> | 28/06/2026 | 28/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Khắc phục lỗi vận hành:</b> Bổ sung try-except catch lỗi JSON decode từ Bedrock, thiết lập Dead Letter Queue (DLQ) cho SQS/Lambda xử lý các message lỗi</li></ul> | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Chụp ảnh minh chứng AWS:</b> Chụp ảnh màn hình chi tiết cấu hình S3 Bucket, IAM Roles, Lambda Triggers, DynamoDB Table, QuickSight Dashboard</li></ul> | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Soạn thảo báo cáo kỹ thuật:</b> Đưa các biểu đồ, ảnh chụp màn hình minh chứng cấu hình vào tài liệu báo cáo thực tập trên Hugo site</li></ul> | 01/07/2026 | 01/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Review & Tổng kết tuần 11:</b> Rà soát lại toàn bộ mã nguồn, kiểm tra lại trang web Hugo và tổng hợp kết quả đạt được tuần 11</li></ul> | 02/07/2026 | 02/07/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 11:

* Tối ưu hóa thành công AWS Lambda: giảm 35% thời gian chạy và tối ưu chi phí vận hành dịch vụ trên AWS.
* Hoàn thành Integration Testing cho toàn bộ hệ thống xử lý hóa đơn, xử lý triệt để các trường hợp ngoại lệ với DLQ và retry logic.
* Đã thu thập và lưu trữ đầy đủ hình ảnh minh chứng cấu hình AWS thực tế, đưa vào báo cáo thực tập chuẩn hóa trên Hugo site.
