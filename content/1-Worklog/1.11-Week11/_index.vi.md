---
title: "Worklog Tuần 11"
date: 2026-06-26
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
**Thời gian:** 26/06/2026 – 02/07/2026

### Mục tiêu tuần 11:

* Hoàn thiện pipeline hóa đơn Textract → Bedrock → DynamoDB; tối ưu Lambda.
* Hoàn thiện dashboard QuickSight; rà soát bảo mật IAM, S3, Lambda.
* Integration Testing toàn hệ thống; chuẩn bị báo cáo cuối kỳ (tài liệu, slide, demo).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Hoàn thiện luồng:** Hoàn thiện luồng end-to-end: S3 upload → Textract → Lambda enrich (Bedrock) → DynamoDB | 26/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Đồng bộ siêu dữ liệu:** Đồng bộ metadata file gốc trên S3 với bản ghi DB | 27/06/2026 | 27/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Xử lý trùng lặp:** Xử lý duplicate invoice và idempotency key | 28/06/2026 | 28/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Tối ưu Lambda:** Tối ưu Lambda: memory/timeout, reuse boto3 client, batch write DynamoDB <br> - **Giảm Cold Start:** Giảm cold start (provisioned concurrency nếu cần demo) <br> - **Tối ưu log:** Review CloudWatch Logs để loại bỏ log thừa và metric custom | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Hoàn thiện QuickSight:** Hoàn thiện dashboard QuickSight: filter, theme, mobile layout <br> - **Rà soát IAM:** Rà soát IAM: least privilege cho Lambda role, Textract, Bedrock invoke <br> - **Bảo mật S3:** S3 block public access, encryption, bucket policy deny insecure transport | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Kiểm thử tích hợp:** Integration Testing: upload batch file, API list/search, dashboard refresh <br> - **Sửa lỗi hồi quy:** Ghi nhận bug, fix regression, retest <br> - **Kiểm thử tải:** Load test nhẹ (10–20 file) đo thời gian xử lý trung bình | 01/07/2026 | 01/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Tài liệu cuối kỳ:** Viết tài liệu kỹ thuật final: architecture, deployment guide, lessons learned <br> - **Chuẩn bị slide:** Slide thuyết trình: problem, solution, demo flow, KPI <br> - **Diễn tập demo:** Rehearsal demo live: upload hóa đơn → xem kết quả → QuickSight dashboard | 02/07/2026 | 02/07/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 11:

* Pipeline AI Invoice Scanner hoạt động ổn định từ upload đến lưu trữ và truy vấn.
* Lambda được tối ưu hiệu suất; dashboard QuickSight hoàn chỉnh và dễ đọc.
* IAM, S3, Lambda được rà soát bảo mật theo best practice.
* Integration Testing pass; sẵn sàng tài liệu, slide và demo báo cáo cuối kỳ.
