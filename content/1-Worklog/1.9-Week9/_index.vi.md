---
title: "Worklog Tuần 9"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
**Thời gian:** 12/06/2026 – 18/06/2026

### Mục tiêu tuần 9:

* Dịch và nghiên cứu blog AWS về Carbon Reporting, BYOL và Sustainability.
* Hoàn thiện Project Proposal cho dự án AI Invoice Scanner.
* Kiểm thử chức năng, thiết kế kiến trúc Draw.io và tài liệu hóa trên Notion.
* Chuẩn bị minh chứng cấu hình IAM, S3, Lambda cho báo cáo.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Dịch blog AWS:** Dịch blog AWS Carbon Reporting: metric carbon footprint workload | 12/06/2026 | 12/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Tìm hiểu BYOL:** BYOL (Bring Your Own License) trên EC2/RDS; licensing implications | 13/06/2026 | 13/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Sustainability:** Sustainability: Well-Architected pillar, right-sizing, Graviton | 14/06/2026 | 14/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Viết Đề xuất:** Viết **Project Proposal:** bối cảnh, mục tiêu, phạm vi, kiến trúc, timeline <br> - **Định nghĩa Stack:** Liệt kê stack: S3, Textract, Lambda, Bedrock, DynamoDB, API Gateway, Cognito <br> - **Quản lý rủi ro:** Xác định rủi ro và kế hoạch giảm thiểu | 15/06/2026 | 15/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Kiểm thử chức năng:** Kiểm thử chức năng upload hóa đơn, trích xuất field, lưu DynamoDB <br> - **Sửa lỗi logic:** Fix bug parsing JSON Textract, validate input file type/size <br> - **Kiểm thử biên:** Test edge case: hóa đơn mờ, nhiều trang, tiếng Việt/Anh | 16/06/2026 | 16/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Sơ đồ kiến trúc:** Vẽ **sơ đồ kiến trúc Draw.io:** data flow, trust boundary, IAM role <br> - **Sơ đồ trình tự:** Sequence diagram: user upload → S3 → Lambda → Textract → Bedrock → DB <br> - **Xuất tài nguyên:** Export PNG/SVG cho báo cáo | 17/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Tài liệu kỹ thuật:** Ghi **tài liệu kỹ thuật Notion:** setup, deploy, env vars, API spec <br> - **Chụp ảnh cấu hình:** Chụp màn hình cấu hình IAM policy, S3 bucket policy, Lambda trigger <br> - **Bàn giao giai đoạn:** Checklist deliverable trước khi vào giai đoạn Data/QuickSight | 18/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 9:

* Dịch và nắm nội dung blog AWS về Carbon Reporting, BYOL và Sustainability.
* Hoàn thành Project Proposal chi tiết cho AI Invoice Scanner.
* Kiểm thử và sửa lỗi các luồng chính của ứng dụng.
* Có sơ đồ kiến trúc Draw.io, tài liệu Notion và ảnh minh chứng IAM/S3/Lambda.
