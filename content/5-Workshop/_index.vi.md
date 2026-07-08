---
title: "Workshop"
date: 2026-06-30
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Workshop: Serverless AI Invoice Scanner

#### Tổng quan

Trong bài thực hành (workshop) này, bạn sẽ tự tay xây dựng và triển khai hệ thống **Serverless AI Invoice Scanner** trên nền tảng AWS. 

Hệ thống cho phép người dùng tải lên hóa đơn dưới dạng hình ảnh hoặc PDF, tự động trích xuất nội dung bằng dịch vụ OCR **Amazon Textract**, chuẩn hóa và phân tích dữ liệu thành cấu trúc JSON thông qua **OpenAI API**, lưu trữ thông tin vào **Amazon DynamoDB** và quản lý danh sách hóa đơn bằng giao diện **ReactJS** được triển khai trên **AWS Amplify**.

![Architecture Diagram](/images/architecture-log.png)