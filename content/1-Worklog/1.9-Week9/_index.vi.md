---
title: "Worklog Tuần 9"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
**Thời gian:** 12/06/2026 – 18/06/2026

### Mục tiêu tuần 9:

* Phát triển hoàn chỉnh luồng xử lý hóa đơn tự động end-to-end: Upload file hóa đơn lên Amazon S3 -> Kích hoạt AWS Lambda trigger -> Gọi Amazon Textract trích xuất văn bản -> Gửi dữ liệu tới Amazon Bedrock chuẩn hóa JSON -> Lưu kết quả vào Amazon DynamoDB.
* Thiết kế chi tiết sơ đồ kiến trúc hệ thống tổng thể và sequence diagram mô tả luồng dữ liệu bằng phần mềm Draw.io.
* Ghi chép đầy đủ tài liệu hướng dẫn kỹ thuật, cấu hình các dịch vụ IAM, S3, Lambda và lưu minh chứng hệ thống lên Notion.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Cấu hình S3 Event Notification:</b> Cấu hình S3 Bucket `invoice-upload-bucket` kích hoạt S3 Event Trigger khi có file PDF/Image mới</li><li><b>- Tạo IAM Execution Role:</b> Tạo IAM Role cho Lambda cấp quyền `s3:GetObject`, `textract:AnalyzeDocument`, `bedrock:InvokeModel`, `dynamodb:PutItem`</li></ul> | 12/06/2026 | 12/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Tích hợp Lambda với Textract:</b> Viết mã Python Lambda sử dụng `boto3` gọi Amazon Textract `AnalyzeDocument` lấy thông tin key-value pairs (Vendor Name, Total Amount, Date, Tax)</li></ul> | 13/06/2026 | 13/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Tích hợp Lambda với Bedrock:</b> Gọi Amazon Bedrock (mô hình Anthropic Claude 3 / Titan) để phân tích, chuẩn hóa dữ liệu thô từ Textract thành cấu trúc JSON chuẩn</li></ul> | 14/06/2026 | 14/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Lưu dữ liệu vào DynamoDB:</b> Viết hàm ghi dữ liệu JSON đã chuẩn hóa từ Bedrock vào bảng Amazon DynamoDB `InvoicesTable` với `InvoiceID` tự động tạo</li></ul> | 15/06/2026 | 15/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Kiểm thử luồng tự động:</b> Upload hóa đơn mẫu thực tế lên S3, kiểm tra log trong CloudWatch Logs và kiểm tra dữ liệu xuất hiện trong DynamoDB</li></ul> | 16/06/2026 | 16/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Thiết kế sơ đồ kiến trúc Draw.io:</b> Vẽ sơ đồ kiến trúc hệ thống 3D (Architecture Diagram) và sơ đồ trình tự (Sequence Diagram) trên Draw.io</li></ul> | 17/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Soạn tài liệu trên Notion:</b> Soạn thảo trang Notion dự án: Lưu ảnh chụp màn hình cấu hình IAM Role, S3 Event, Lambda code, DynamoDB Items và tổng kết tuần 9</li></ul> | 18/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 9:

* Xây dựng thành công đường ống xử lý hóa đơn tự động bằng AI serverless hoàn chỉnh (S3 -> Lambda -> Textract -> Bedrock -> DynamoDB).
* Hoàn thiện sơ đồ kiến trúc hệ thống chuẩn mực và sequence diagram mô tả luồng dữ liệu minh bạch trên Draw.io.
* Đã tổng hợp và đóng gói toàn bộ tài liệu kỹ thuật, hướng dẫn triển khai và ảnh chụp màn hình minh chứng cấu hình AWS trên trang Notion.
