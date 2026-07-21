---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
**Thời gian:** 29/05/2026 – 04/06/2026

### Mục tiêu tuần 7:

* Xây dựng kiến trúc Serverless Backend linh hoạt với các API RESTful và GraphQL kết hợp AWS Lambda và Amazon API Gateway.
* Tìm hiểu lưu trữ đối tượng với Amazon S3 và mô hình cơ sở dữ liệu NoSQL hiệu năng cao Amazon DynamoDB cho ứng dụng cloud-native.
* Thực hành giải pháp xác thực, ủy quyền người dùng an toàn bằng Amazon Cognito (User Pools & Identity Pools).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Tìm hiểu Serverless Services:</b> Học kiến trúc Serverless: AWS Lambda event-driven, Amazon API Gateway routing</li><li>- <b>Tạo Lambda Function:</b> Viết Lambda Function bằng Python (bằng thư viện `boto3`) xử lý request dữ liệu</li></ul> | 29/05/2026 | 29/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Xây dựng RESTful API:</b> Cấu hình API Gateway HTTP API / REST API, định nghĩa các route (GET, POST, PUT, DELETE)</li><li>- <b>Tích hợp Lambda:</b> Tích hợp API Gateway routes với Lambda proxy integration</li></ul> | 30/05/2026 | 30/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Nghiên cứu GraphQL API:</b> Tìm hiểu khái niệm GraphQL, so sánh REST API vs GraphQL</li><li>- <b>Triển khai GraphQL:</b> Cấu hình API Gateway / AWS AppSync tạo GraphQL Schema và Resolvers</li></ul> | 31/05/2026 | 31/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Thực hành Amazon S3:</b> Tạo S3 Bucket, cấu hình S3 Bucket Policy, CORS và quản lý lifecycle rule cho file tải lên</li><li>- <b>Thực hành DynamoDB:</b> Tạo DynamoDB Table (Partition Key, Sort Key, Secondary Indexes)</li></ul> | 01/06/2026 | 01/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Tích hợp Lambda với S3 & DynamoDB:</b> Viết mã Lambda đọc/ghi dữ liệu từ S3 và thực hiện thao tác CRUD trên DynamoDB</li><li>- <b>Cấu hình IAM Role:</b> Thiết lập IAM Role cho Lambda cấp quyền truy cập S3 và DynamoDB chuẩn Least Privilege</li></ul> | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Khởi tạo Amazon Cognito:</b> Khởi tạo Cognito User Pool (đăng ký, đăng nhập, xác minh email OTP)</li><li>- <b>Tạo Identity Pool:</b> Cấu hình Cognito Identity Pool cấp quyền truy cập AWS resources cho người dùng đăng nhập</li></ul> | 03/06/2026 | 03/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Tích hợp Authorizer:</b> Tích hợp Cognito JWT Authorizer vào API Gateway để bảo vệ các endpoints API</li><li>- <b>Kiểm thử & Tổng kết:</b> Dùng Postman kiểm thử đăng nhập, lấy JWT token và gọi API thành công</li></ul> | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 7:

* Xây dựng thành công hệ thống Serverless API hoàn chỉnh với Lambda và API Gateway phục vụ cả hai chuẩn RESTful và GraphQL.
* Làm chủ kỹ năng quản lý lưu trữ dữ liệu không cấu trúc trên Amazon S3 và dữ liệu NoSQL tốc độ cao trên Amazon DynamoDB.
* Triển khai hoàn chỉnh hệ thống xác thực người dùng bảo mật với Amazon Cognito JWT Authorizer bảo vệ API Endpoints.
