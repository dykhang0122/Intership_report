---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
**Thời gian:** 22/05/2026 – 28/05/2026

### Mục tiêu tuần 6:

* Tìm hiểu mô hình kiến trúc Microservices, so sánh Amazon ECS (Elastic Container Service) launch type EC2 vs serverless AWS Fargate, và tổng quan Amazon EKS (Kubernetes).
* Thiết lập đường ống CI/CD tự động (Continuous Integration & Continuous Deployment) bằng AWS CodePipeline, AWS CodeBuild kết hợp kho mã nguồn GitHub.
* Cấu hình giải pháp giám sát tài nguyên chuyên sâu bằng Amazon CloudWatch Container Insights và áp dụng các chính sách bảo mật IAM/Secrets Manager cho môi trường Container.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Tìm hiểu ECS & Fargate:</b> Nghiên cứu kiến trúc Amazon ECS Cluster, Task Definition, Service và AWS Fargate serverless launch type</li><li>- <b>Tổng quan EKS:</b> Tìm hiểu vai trò của Amazon EKS trong việc điều phối Kubernetes cluster</li></ul> | 22/05/2026 | 22/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Khởi tạo ECS Cluster:</b> Tạo Amazon ECS Cluster chạy trên serverless AWS Fargate</li><li>- <b>Tạo Task Definition:</b> Viết Task Definition khai báo CPU, RAM, container image từ ECR, port mappings và IAM Task Role</li></ul> | 23/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Triển khai ECS Service:</b> Khởi tạo ECS Service duy trì các Task running, kết nối với Application Load Balancer (ALB)</li></ul> | 24/05/2026 | 24/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Kết nối GitHub Source:</b> Cấu hình AWS CodeStar Connections liên kết kho mã nguồn GitHub với AWS CodePipeline</li></ul> | 25/05/2026 | 25/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Cấu hình AWS CodeBuild:</b> Viết file `buildspec.yml` tự động build Docker Image, login ECR, tag image và push lên ECR repository</li></ul> | 26/05/2026 | 26/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Hoàn thiện CI/CD Pipeline:</b> Thêm giai đoạn Deploy vào CodePipeline, tự động cập nhật ECS Task Definition khi có commit mới trên GitHub</li><li>- <b>Kiểm thử CI/CD:</b> Commit code thay đổi giao diện lên GitHub và kiểm tra pipeline tự động kích hoạt</li></ul> | 27/05/2026 | 27/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Giám sát Container Insights:</b> Bật CloudWatch Container Insights theo dõi chỉ số CPU, Memory, Network của ECS Tasks</li><li>- <b>Bảo mật & Quản lý bí mật:</b> Tích hợp AWS Secrets Manager truyền biến môi trường bảo mật vào container và tổng kết tuần 6</li></ul> | 28/05/2026 | 28/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 6:

* Hiểu sâu kiến trúc Microservices và ưu điểm vận hành container serverless không cần quản lý máy chủ với AWS Fargate.
* Xây dựng thành công quy trình CI/CD hoàn toàn tự động từ bước push code GitHub -> CodeBuild đóng gói ECR -> CodePipeline cập nhật ECS Fargate.
* Triển khai giải pháp quan sát toàn diện với CloudWatch Container Insights và quản lý bí mật bảo mật với AWS Secrets Manager.
