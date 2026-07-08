---
title: "Nhật ký công việc"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Trong suốt chương trình thực tập First Cloud Journey, tôi đã ghi nhận lại tiến trình và các kiến thức đã tích lũy qua từng tuần. Dưới đây là tóm tắt công việc thực hiện trong 12 tuần:

#### **[Tuần 1 (17/04/2026 – 23/04/2026)](1.1-week1/)**
- Tạo tài khoản AWS và tìm hiểu các dịch vụ cơ bản.
- Thực hành IAM, VPC và Amazon EC2.
- Tìm hiểu cách quản lý chi phí và hỗ trợ trên AWS.

#### **[Tuần 2 (24/04/2026 – 30/04/2026)](1.2-week2/)**
- Tìm hiểu Amazon VPC và mô hình mạng trên AWS.
- Thực hành VPN Site-to-Site, Subnet, Route Table, Internet Gateway và NAT Gateway.
- Cấu hình Security Group và Network ACL.

#### **[Tuần 3 (01/05/2026 – 07/05/2026)](1.3-week3/)**
- Tìm hiểu về dịch vụ Amazon EC2 và các thành phần quan trọng như Instance Type, AMI, Backup, Key Pair và Elastic Block Store (EBS).
- Thực hành tạo máy ảo EC2, cấu hình lưu trữ và quản lý kết nối bảo mật.

#### **[Tuần 4 (08/05/2026 – 14/05/2026)](1.4-week4/)**
- Kết nối VPC với Visual Studio Code, kiểm tra kết nối và tìm hiểu Amazon EC2 cơ bản.
- Biến máy ảo "trống" thành web server, dùng VPC Reachability Analyzer kiểm tra luồng mạng.
- Thiết lập EC2 Instance Connect Endpoint và SSM Session Manager để truy cập bảo mật không cần SSH trực tiếp.
- Cấu hình CloudWatch Logs, Metrics và Alarm giám sát & cảnh báo sự cố.

#### **[Tuần 5 (15/05/2026 – 21/05/2026)](1.5-week5/)**
- Tìm hiểu chuyển đổi Monolithic sang Microservices và kiến trúc Cloud-Native trên AWS.
- Xây dựng app Serverless (Lambda, API Gateway, DynamoDB, S3), kết hợp các dịch vụ SQS, SNS và Step Functions.
- Triển khai RESTful API, AppSync GraphQL, kết nối SPA frontend và Cognito User Pool xác thực.
- Sử dụng AWS SAM deploy ứng dụng, thiết lập CodePipeline/CodeBuild CI/CD và theo dõi qua X-Ray.
- Tìm hiểu khái quát các dịch vụ trí tuệ nhân tạo (AI) trên AWS.

#### **[Tuần 6 (22/05/2026 – 28/05/2026)](1.6-week6/)**
- Đóng gói ứng dụng bằng Docker, build và quản lý ECR image repository.
- Triển khai ứng dụng container trên Amazon Lightsail Containers và Amazon EKS cluster.
- Thực hiện chia nhỏ Monolithic thành Microservices chạy trên ECS Fargate với AWS Service Discovery.
- Thiết lập CI/CD tự động build ECR và deploy ECS Fargate bằng CodePipeline từ GitHub source.
- Cấu hình giám sát qua Container Insights và quản lý bí mật bảo mật qua Secrets Manager.

#### **[Tuần 7 (29/05/2026 – 04/06/2026)](1.7-week7/)**
- Tìm hiểu vai trò của EC2 và máy chủ ảo trong hệ thống 3-tier.
- Thực hành launch Amazon Linux 2023 EC2, cấu hình AMI, Instance Type và quản lý Key Pair.
- Thiết lập VPC, Subnet, Public IP và Security Group bảo mật cổng kết nối.
- Quản lý lifecycle máy chủ ảo (start/stop/reboot), theo dõi trạng thái mạng & cấu hình EBS.
- Thực hành SSH truy cập từ xa và cấu hình bảo mật máy chủ.

#### **[Tuần 8 (05/06/2026 – 11/06/2026)](1.8-week8/)**
- Nghiên cứu Amazon Bedrock và kiến trúc mô hình RAG (Retrieval-Augmented Generation).
- Đọc hiểu, tóm tắt và dịch tài liệu kỹ thuật chuyên sâu về AWS Generative AI.
- Phân tích yêu cầu nghiệp vụ, lên ý tưởng và đề xuất kiến trúc dự án cuối khóa.
- Tích hợp S3 upload event trigger với Textract để trích xuất thông tin hóa đơn.
- Phát triển Lambda function gọi Bedrock AI model để chuẩn hóa và phân tích dữ liệu hóa đơn.
- Ghi dữ liệu vào DynamoDB và chạy kiểm thử tích hợp (integration test) luồng pipeline.

#### **[Tuần 9 (12/06/2026 – 18/06/2026)](1.9-week9/)**
- Dịch và tìm hiểu bài viết chuyên sâu về AWS Carbon Reporting, BYOL và Sustainability.
- Viết và hoàn thiện Project Proposal cho dự án AI Invoice Scanner.
- Kiểm thử chức năng, sửa lỗi JSON parsing và hoàn thiện toàn bộ ứng dụng AI Invoice Scanner.
- Thiết kế sơ đồ kiến trúc hệ thống bằng Draw.io và sequence diagram.
- Viết tài liệu kỹ thuật trên Notion, lưu minh chứng cấu hình IAM, S3, Lambda.

#### **[Tuần 10 (19/06/2026 – 25/06/2026)](1.10-week10/)**
- Tìm hiểu Data Governance, phân loại dữ liệu và cấu hình IAM/Resource policies mã hóa dữ liệu.
- Cấu hình Amazon QuickSight kết nối nguồn dữ liệu DynamoDB/S3.
- Xây dựng dashboard trực quan hóa chi tiêu hóa đơn, thiết lập KPI và các biểu đồ phân tích.
- Tạo báo cáo PDF và đánh giá các mặt hạn chế của dataset.

#### **[Tuần 11 (26/06/2026 – 02/07/2026)](1.11-week11/)**
- Hoàn thiện luồng xử lý hóa đơn tự động end-to-end, đồng bộ S3 metadata & xử lý trùng lặp.
- Tối ưu Lambda memory/timeout và cấu hình provisioned concurrency giảm cold start.
- Hoàn thiện giao diện dashboard QuickSight, rà soát IAM roles & bảo mật S3 bucket.
- Chạy Integration Testing, kiểm thử tải nhẹ và sửa lỗi vận hành hệ thống.
- Viết tài liệu kỹ thuật cuối kỳ, làm slide thuyết trình và diễn tập demo live.

#### **[Tuần 12 (03/07/2026 – 09/07/2026)](1.12-week12/)**
- Tổng hợp toàn bộ tài liệu báo cáo, slide thuyết trình và định dạng chuẩn hóa theo template FCJ.
- Chuẩn bị môi trường demo, test luồng demo live 3 lần và thực hiện báo cáo cuối khóa.
- Dọn dẹp và xóa các tài nguyên AWS đã sử dụng tránh phát sinh chi phí sau thực tập.
- Viết báo cáo tự đánh giá kết quả đạt được, tổng hợp kỹ năng mới và góp ý cho chương trình.
