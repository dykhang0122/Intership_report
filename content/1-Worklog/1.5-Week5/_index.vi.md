---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
**Thời gian:** 15/05/2026 – 21/05/2026

### Mục tiêu tuần 5:

* Tìm hiểu chuyển đổi từ Monolithic sang Microservices và kiến trúc Cloud-Native trên AWS.
* Xây dựng ứng dụng Serverless với Lambda, API Gateway, DynamoDB, S3 và messaging (SQS, SNS, Step Functions).
* Triển khai API RESTful/GraphQL, SPA với Cognito; CI/CD bằng SAM, CodePipeline; giám sát CloudWatch, X-Ray.
* Tiếp cận các dịch vụ AI trên AWS phục vụ ứng dụng hiện đại.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Kiến trúc Monolithic:** So sánh Monolithic vs Microservices: coupling, scalability, deploy độc lập | 15/05/2026 | 15/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Kiến trúc Cloud-Native:** Cloud-Native: 12-factor, managed services, event-driven | 16/05/2026 | 16/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Kế hoạch dự án:** Lập kế hoạch tách domain cho bài lab serverless | 17/05/2026 | 17/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Thực hành Serverless:** Tạo Lambda function (Python/Node), trigger từ API Gateway <br> - **Cơ sở dữ liệu:** DynamoDB table (PK/SK), CRUD cơ bản qua Lambda <br> - **Lưu trữ S3:** S3 bucket: upload/download file, bucket policy và IAM role cho Lambda | 18/05/2026 | 18/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thông điệp & Sự kiện:** SQS queue: producer/consumer pattern; SNS topic: fan-out notification <br> - **Điều phối quy trình:** Step Functions: orchestrate workflow nhiều bước (Lambda + wait + choice) <br> - **Xử lý lỗi:** Test luồng bất đồng bộ và xử lý lỗi/retry | 19/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Phát triển API:** RESTful API trên API Gateway; giới thiệu GraphQL (AppSync hoặc proxy) <br> - **Tích hợp Frontend:** SPA frontend (React/Vue mẫu) gọi API <br> - **Xác thực Cognito:** Amazon Cognito User Pool: đăng ký, đăng nhập, JWT authorizer cho API | 20/05/2026 | 20/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Triển khai bằng SAM:** AWS SAM: template.yaml, `sam build`, `sam deploy` <br> - **Quy trình CI/CD:** CodePipeline + CodeBuild: tự động build/deploy khi push code <br> - **Giám sát & Tracing:** CloudWatch Logs/Metrics, X-Ray tracing; tìm hiểu Amazon Bedrock/Rekognition ở mức overview | 21/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

* Hiểu lợi ích Microservices/Cloud-Native và khi nào nên tách service.
* Xây dựng backend serverless hoàn chỉnh: Lambda, API Gateway, DynamoDB, S3.
* Vận hành workflow bất đồng bộ với SQS, SNS và Step Functions.
* Tích hợp Cognito cho SPA; thiết lập pipeline CI/CD và quan sát hệ thống bằng CloudWatch, X-Ray.
