---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
**Thời gian:** 22/05/2026 – 28/05/2026

### Mục tiêu tuần 6:

* Đóng gói ứng dụng bằng Docker; quản lý image trên Amazon ECR.
* Triển khai container trên Lightsail Containers và Amazon EKS.
* Chuyển Monolithic sang Microservices với Docker và AWS Fargate.
* Xây dựng CI/CD (CodePipeline + GitHub); giám sát và bảo mật môi trường container.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Thực hành Docker:** Viết Dockerfile cho app mẫu; build image, chạy container local | 22/05/2026 | 22/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Đẩy image lên ECR:** Push image lên Amazon ECR; tag, lifecycle policy cơ bản | 23/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Tối ưu Docker:** Hiểu layer cache và best practice giảm kích thước image | 24/05/2026 | 24/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Lightsail Containers:** Deploy service từ ECR image, cấu hình port và scale <br> - **Giám sát Lightsail:** Kiểm tra health check, log và public endpoint <br> - **So sánh dịch vụ:** So sánh Lightsail vs ECS/EKS về độ phức tạp và chi phí | 25/05/2026 | 25/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành EKS:** Cluster, node group (hoặc Fargate profile), kubectl cơ bản <br> - **Deploy lên EKS:** Deploy Deployment + Service (LoadBalancer/Ingress) <br> - **Kiểm tra EKS:** Kiểm tra pod scheduling và rolling update | 26/05/2026 | 26/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Kiến trúc Container:** Tách Monolithic thành 2–3 microservice container <br> - **Thực hành ECS Fargate:** Task definition, service, không quản lý EC2 worker <br> - **Giao tiếp nội bộ:** Service discovery và giao tiếp nội bộ giữa các container | 27/05/2026 | 27/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **CI/CD Container:** GitHub → CodePipeline → CodeBuild → deploy ECR/Fargate <br> - **Giám sát & Bảo mật:** Container Insights, CloudWatch log driver; giới hạn IAM task role <br> - **Bảo mật bí mật:** Scan image (ECR scan), secrets qua Secrets Manager/SSM Parameter Store | 28/05/2026 | 28/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 6:

* Đóng gói ứng dụng Docker và publish image lên ECR.
* Triển khai container trên Lightsail và EKS; hiểu vòng đời pod/service.
* Chuyển đổi sang microservices chạy trên Fargate với service độc lập.
* Tự động hóa build/deploy qua CodePipeline; áp dụng giám sát và hardening container.
