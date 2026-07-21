---
title: "Nhật ký công việc"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Trong suốt chương trình thực tập First Cloud Journey, tôi đã ghi nhận lại tiến trình và các kiến thức đã tích lũy qua từng tuần. Dưới đây là tóm tắt công việc thực hiện trong 12 tuần:

#### **[Tuần 1 (17/04/2026 – 23/04/2026)](1.1-week1/)**
- Tạo tài khoản AWS, tìm hiểu các dịch vụ cơ bản (Compute, Storage, Networking, Database).
- Thực hành quản lý tài khoản, thiết lập IAM Users/Groups/Policies và phân quyền theo nguyên tắc Least Privilege.
- Thiết lập AWS Budgets và Cost Explorer để quản lý, giám sát và cảnh báo chi phí.

#### **[Tuần 2 (24/04/2026 – 30/04/2026)](1.2-week2/)**
- Tìm hiểu mô hình mạng AWS VPC, tạo Public/Private Subnet và Route Table phân lớp.
- Thực hành cấu hình Internet Gateway, NAT Gateway cho Private Subnet và VPN Site-to-Site kết nối on-premises.
- Thiết lập bảo mật tầng mạng chi tiết với Security Group (stateful) và Network ACL (stateless).

#### **[Tuần 3 (01/05/2026 – 07/05/2026)](1.3-week3/)**
- Tìm hiểu chuyên sâu Amazon EC2 (Instance Type, AMI, Key Pair, Lifecycle máy chủ).
- Thực hành tạo máy ảo EC2 Linux, cấu hình lưu trữ ổ đĩa EBS và cơ chế Backup/Snapshot tự động.
- Cài đặt và cấu hình ứng dụng Web Server cơ bản (Nginx/Apache) trên EC2, phục vụ website thử nghiệm.

#### **[Tuần 4 (08/05/2026 – 14/05/2026)](1.4-week4/)**
- Kết nối VS Code với EC2; kiểm tra, phân tích luồng kết nối mạng bằng AWS VPC Reachability Analyzer.
- Quản trị máy chủ bảo mật không cần SSH cổng public qua EC2 Instance Connect Endpoint và SSM Session Manager.
- Cài đặt CloudWatch Agent giám sát hiệu năng hệ thống (CPU, RAM, Disk) và thiết lập cảnh báo CloudWatch Alarms tự động.

#### **[Tuần 5 (15/05/2026 – 21/05/2026)](1.5-week5/)**
- Học cách sử dụng Docker, quy trình đóng gói ứng dụng và viết Dockerfile tối ưu.
- Xây dựng, quản lý và lưu trữ Docker Image trên Amazon ECR (Elastic Container Registry).
- Triển khai và chạy ứng dụng container thử nghiệm trên môi trường Amazon Lightsail Containers.

#### **[Tuần 6 (22/05/2026 – 28/05/2026)](1.6-week6/)**
- Tìm hiểu kiến trúc Microservices và cơ chế vận hành container serverless trên AWS Fargate, Amazon ECS/EKS.
- Thiết lập quy trình CI/CD tự động bằng AWS CodePipeline kết hợp GitHub để tự động build ECR và deploy ECS/Fargate.
- Cấu hình giám sát tài nguyên với Container Insights và thiết lập chính sách bảo mật cho môi trường Container.

#### **[Tuần 7 (29/05/2026 – 04/06/2026)](1.7-week7/)**
- Học cách xây dựng API RESTful và GraphQL bằng AWS Lambda và API Gateway.
- Tìm hiểu lưu trữ đối tượng với Amazon S3 và cơ sở dữ liệu NoSQL Amazon DynamoDB cho ứng dụng Serverless.
- Thực hành cơ chế xác thực và phân quyền người dùng bảo mật bằng Amazon Cognito User Pools/Identity Pools.

#### **[Tuần 8 (05/06/2026 – 11/06/2026)](1.8-week8/)**
- Nghiên cứu Amazon Bedrock, mô hình RAG (Retrieval-Augmented Generation) và dịch vụ trích xuất dữ liệu Amazon Textract.
- Viết tài liệu Project Proposal chi tiết cho dự án cuối khóa: AI Invoice Scanner (Hệ thống quét & xử lý hóa đơn tự động).
- Dịch các bài blog kỹ thuật chuyên sâu về phát triển bền vững đám mây (AWS Carbon Footprint, BYOL).

#### **[Tuần 9 (12/06/2026 – 18/06/2026)](1.9-week9/)**
- Xây dựng luồng xử lý tự động: Upload hóa đơn lên S3 -> Lambda trigger gọi Textract trích xuất dữ liệu -> Bedrock chuẩn hóa thông tin -> Lưu vào DynamoDB.
- Thiết kế sơ đồ kiến trúc hệ thống tổng thể và sequence diagram bằng Draw.io.
- Ghi chép tài liệu kỹ thuật, hướng dẫn triển khai và minh chứng cấu hình IAM, S3, Lambda lên Notion.

#### **[Tuần 10 (19/06/2026 – 25/06/2026)](1.10-week10/)**
- Tìm hiểu nguyên tắc Data Governance (quản lý quyền truy cập, bảo mật dữ liệu và mã hóa dữ liệu).
- Kết nối dữ liệu đã trích xuất từ DynamoDB sang Amazon QuickSight.
- Xây dựng Dashboard trực quan hóa dữ liệu hóa đơn, tổng hợp chi tiêu và thống kê chỉ số phục vụ báo cáo.

#### **[Tuần 11 (26/06/2026 – 02/07/2026)](1.11-week11/)**
- Tối ưu hóa mã nguồn AWS Lambda (tối ưu memory, timeout, giảm thời gian thực thi và chi phí vận hành).
- Thực hiện Integration Testing toàn bộ hệ thống end-to-end và khắc phục các lỗi vận hành phát sinh.
- Hoàn thiện báo cáo kỹ thuật, chụp ảnh minh chứng cấu hình thực tế trên AWS Console.

#### **[Tuần 12 (03/07/2026 – 09/07/2026)](1.12-week12/)**
- Hoàn thành tất cả các sản phẩm cho báo cáo cuối cùng (tài liệu báo cáo, slide thuyết trình, video demo).
- Đánh giá, tổng kết toàn bộ quá trình thực tập và rút ra các bài học kinh nghiệm.
- Dọn dẹp và hủy tất cả tài nguyên AWS đã khởi tạo để tránh phát sinh chi phí sau thực tập.

