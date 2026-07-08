---
title: "Worklog Tuần 8"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
**Thời gian:** 05/06/2026 – 11/06/2026

### Mục tiêu tuần 8:

* Nghiên cứu Amazon Bedrock và mô hình RAG (Retrieval-Augmented Generation).
* Phân tích tài liệu AWS/AI; đề xuất kiến trúc dự án cuối khóa AI Invoice Scanner.
* Tích hợp Textract + S3; Lambda kết hợp Textract và Bedrock; lưu trữ DynamoDB.
* Kiểm thử pipeline xử lý hóa đơn end-to-end.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Amazon Bedrock:** Amazon Bedrock: foundation model, inference, prompt engineering cơ bản | 05/06/2026 | 05/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| 7 | - **Kiến thức RAG:** RAG: embedding, vector store, retrieve context trước khi generate | 06/06/2026 | 06/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| CN | - **Tài liệu kỹ thuật:** Đọc và tóm tắt tài liệu kỹ thuật AWS Generative AI | 07/06/2026 | 07/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| 2 | - **Phân tích yêu cầu:** Phân tích yêu cầu dự án cuối khóa: upload hóa đơn → trích xuất → lưu trữ → tra cứu <br> - **Thiết kế kiến trúc:** Vẽ sơ đồ kiến trúc high-level: S3, Textract, Lambda, Bedrock, DynamoDB <br> - **Lập kế hoạch:** Liệt kê user story và tiêu chí chấp nhận (acceptance criteria) | 08/06/2026 | 08/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| 3 | - **Xử lý Textract:** S3 put event trigger; gọi `DetectDocumentText` / `AnalyzeExpense` <br> - **Lưu trữ thô:** Lưu raw JSON kết quả Textract vào S3 prefix hoặc truyền sang Lambda xử lý <br> - **Kiểm thử dữ liệu:** Test với mẫu hóa đơn PDF/ảnh | 09/06/2026 | 09/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| 4 | - **Xử lý Lambda:** Lambda: parse output Textract, chuẩn hóa field (vendor, date, amount, line items) <br> - **Tích hợp Bedrock:** Gọi Bedrock model để enrich/classify/summary (nếu cần) <br> - **Quản lý lỗi:** Xử lý lỗi, timeout, DLQ cho message fail | 10/06/2026 | 10/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |
| 5 | - **Thiết kế DynamoDB:** DynamoDB: thiết kế bảng invoice (PK invoiceId, GSI theo user/date) <br> - **Phát triển API:** Lambda ghi metadata hóa đơn; API GET list/detail (Lambda + API Gateway) <br> - **Kiểm thử tích hợp:** Integration test toàn pipeline: upload → extract → store → query | 11/06/2026 | 11/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/7-ai-ml-service-on-aws/> |

### Kết quả đạt được tuần 8:

* Hiểu Bedrock, RAG và cách áp dụng cho bài toán xử lý tài liệu.
* Hoàn thành phân tích và kiến trúc đề xuất cho dự án AI Invoice Scanner.
* Tích hợp Textract với S3 trigger; trích xuất dữ liệu hóa đơn tự động.
* Xây dựng Lambda pipeline kết hợp Textract, Bedrock và DynamoDB; test end-to-end thành công.
