---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
**Thời gian:** 15/05/2026 – 21/05/2026

### Mục tiêu tuần 5:

* Tìm hiểu kiến thức nền tảng về Containerization, cài đặt Docker Engine và viết file Dockerfile tối ưu để đóng gói ứng dụng web.
* Khởi tạo container repository trên Amazon Elastic Container Registry (ECR), thực hành đẩy (push) và quản lý Docker Images trên đám mây AWS.
* Triển khai thử nghiệm ứng dụng container hóa lên Amazon Lightsail Containers, cấu hình domain, SSL và kiểm tra khả năng phục vụ ứng dụng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tìm hiểu Docker:** Học lý thuyết Containerization, so sánh Virtual Machine vs Docker Container</li><li>- **Cài đặt Docker:** Cài đặt Docker Desktop/Engine, chạy container mẫu `hello-world`</li></ul> | 15/05/2026 | 15/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Viết Dockerfile:** Viết Dockerfile cho ứng dụng web Node.js/Python (dùng multi-stage build để giảm dung lượng image)</li><li>- **Build & Test local:** Chạy lệnh `docker build` và kiểm thử container chạy cục bộ tại `http://localhost:8080`</li></ul> | 16/05/2026 | 16/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Tối ưu hóa Docker Image:** Tối ưu kích thước image dùng Alpine base image, dọn dẹp cache layers</li><li>- **Quản lý Docker CLI:** Thực hành các lệnh `docker ps`, `docker logs`, `docker exec`</li></ul> | 17/05/2026 | 17/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Khởi tạo Amazon ECR:** Khởi tạo ECR Repository dạng Private trên AWS Console</li><li>- **Xác thực AWS CLI với ECR:** Đăng nhập Docker CLI vào ECR Registry bằng token (`aws ecr get-login-password`)</li></ul> | 18/05/2026 | 18/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Push Image lên ECR:** Đánh thẻ tag (`docker tag`) và đẩy Docker Image (`docker push`) lên Amazon ECR</li><li>- **Quản lý Image Vulnerability:** Bật tính năng Scan on push kiểm tra lỗ hổng bảo mật image trên ECR</li></ul> | 19/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Khởi tạo Lightsail Container:** Khởi tạo dịch vụ Amazon Lightsail Container Service</li><li>- **Triển khai ứng dụng:** Cấu hình deployment lấy image từ ECR, thiết lập port mapping (port 80/8080) và biến môi trường</li></ul> | 20/05/2026 | 20/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Kiểm thử ứng dụng Lightsail:** Truy cập URL mặc định của Lightsail Container, kiểm tra SSL certificate</li><li>- **Tổng kết & Đánh giá:** Rà soát quy trình build-push-deploy và tổng hợp tài liệu báo cáo tuần 5</li></ul> | 21/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

* Nắm vững kỹ thuật đóng gói ứng dụng với Dockerfile, sử dụng multi-stage build để tạo image nhỏ gọn và tối ưu.
* Xây dựng thành thạo kho lưu trữ Docker Image bảo mật trên Amazon ECR và quy trình đẩy image tự động qua AWS CLI.
* Triển khai ứng dụng container chạy thử nghiệm trên Amazon Lightsail Containers thành công, nắm được quy trình vận hành container đơn giản trên AWS.
