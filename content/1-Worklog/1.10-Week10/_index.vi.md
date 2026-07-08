---
title: "Worklog Tuần 10"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
**Thời gian:** 19/06/2026 – 25/06/2026

### Mục tiêu tuần 10:

* Tìm hiểu Data Governance: quyền truy cập, bảo mật, chất lượng dữ liệu trên cloud.
* Thực hành Amazon QuickSight: kết nối nguồn dữ liệu, dashboard và báo cáo phân tích hóa đơn.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - **Quản trị dữ liệu:** Data Governance: data owner, steward, classification (public/internal/confidential) | 19/06/2026 | 19/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Bảo mật dữ liệu:** IAM và resource policy cho dữ liệu S3/DynamoDB; encryption at rest (SSE-S3/KMS) | 20/06/2026 | 20/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Kiểm toán truy cập:** Audit: CloudTrail log truy cập API liên quan data | 21/06/2026 | 21/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Chất lượng dữ liệu:** Data quality: completeness, accuracy, timeliness cho metadata hóa đơn <br> - **Quy tắc validate:** Validation rule trong Lambda trước khi ghi DynamoDB <br> - **Chính sách xóa:** Chiến lược retention và xóa dữ liệu test | 22/06/2026 | 22/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành QuickSight:** Tạo dataset từ DynamoDB hoặc S3/Athena export <br> - **Chuẩn hóa dữ liệu:** Join/filter field: vendor, amount, date, status <br> - **Phân quyền QuickSight:** Phân quyền dataset theo user/group QuickSight | 23/06/2026 | 23/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Xây dựng Dashboard:** Biểu đồ tổng chi tiêu theo tháng, top vendor, số hóa đơn processed <br> - **KPI & Chỉ số:** KPI card: success rate Textract, avg processing time <br> - **Tính năng nâng cao:** Drill-down và filter theo khoảng thời gian | 24/06/2026 | 24/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Xuất báo cáo:** Tạo báo cáo PDF/scheduled email (nếu có) cho stakeholder mẫu <br> - **Đánh giá trực quan:** Review dashboard với dữ liệu thật và dummy <br> - **Ghi chú insight:** Ghi chú insight và hạn chế hiện tại của dataset | 25/06/2026 | 25/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 10:

* Nắm nguyên tắc Data Governance và áp dụng cho dữ liệu hóa đơn trên AWS.
* Thiết lập validation và audit trail cho pipeline dữ liệu.
* Kết nối QuickSight với nguồn DynamoDB/S3 và tạo dataset phân tích.
* Xây dashboard trực quan hóa chi tiêu, vendor và hiệu suất xử lý hóa đơn.
