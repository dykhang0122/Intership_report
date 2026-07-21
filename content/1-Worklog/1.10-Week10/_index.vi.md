---
title: "Worklog Tuần 10"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
**Thời gian:** 19/06/2026 – 25/06/2026

### Mục tiêu tuần 10:

* Nghiên cứu các nguyên tắc quản trị dữ liệu (Data Governance), phân loại dữ liệu nhạy cảm, bảo vệ quyền riêng tư và thiết lập chính sách mã hóa (AWS KMS / IAM policies).
* Thiết lập kết nối và đồng bộ dữ liệu hóa đơn trích xuất từ Amazon DynamoDB / Athena sang dịch vụ Amazon QuickSight.
* Thiết kế và xây dựng Dashboard tương tác trực quan hóa dữ liệu chi tiêu hóa đơn, phân tích xu hướng tài chính phục vụ báo cáo quản trị.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Nghiên cứu Data Governance:</b> Tìm hiểu các nguyên tắc Data Governance trên AWS: Data Lineage, Data Classification, Encryption at rest & in transit (AWS KMS)</li><li><b>- Cấu hình IAM Data Policy:</b> Viết IAM Resource Policies giới hạn quyền xem thông tin hóa đơn</li></ul> | 19/06/2026 | 19/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Đăng ký Amazon QuickSight:</b> Đăng ký tài khoản Amazon QuickSight Enterprise edition</li><li><b>- Cấu hình Quyền QuickSight:</b> Cấp quyền cho QuickSight truy cập DynamoDB, S3 và AWS Glue Data Catalog</li></ul> | 20/06/2026 | 20/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Kết nối Nguồn Dữ liệu:</b> Tạo Data Source kết nối QuickSight tới bảng DynamoDB `InvoicesTable` (hoặc thông qua Amazon Athena qua Glue Crawler)</li></ul> | 21/06/2026 | 21/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Chuẩn hóa Dataset trong SPICE:</b> Tạo DataSet trên QuickSight, đổi kiểu dữ liệu (Date, Currency, Text), cấu hình SPICE engine nạp dữ liệu vào bộ nhớ</li></ul> | 22/06/2026 | 22/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Thiết kế Visuals Dashboard:</b> Tạo các biểu đồ: Biểu đồ cột (Chi tiêu theo Vendor), Biểu đồ tròn (Phân loại hóa đơn), Biểu đồ đường (Xu hướng chi tiêu theo thời gian)</li></ul> | 23/06/2026 | 23/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Tạo KPIs & Control Filters:</b> Thiết lập các thẻ KPI Card (Tổng chi tiêu, Số hóa đơn đã xử lý, Chi tiêu trung bình) và bộ lọc tương tác Filter Control</li></ul> | 24/06/2026 | 24/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Publish Dashboard & Export:</b> Xuất bản (Publish) Dashboard QuickSight, xuất báo cáo PDF và đánh giá kết quả trực quan hóa dữ liệu tuần 10</li></ul> | 25/06/2026 | 25/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 10:

* Nắm vững kiến thức Data Governance, quy định phân loại và mã hóa dữ liệu nhạy cảm trên môi trường điện toán đám mây AWS.
* Tích hợp thành công Amazon QuickSight với cơ sở dữ liệu DynamoDB thông qua SPICE Engine cho tốc độ truy vấn tức thì.
* Xây dựng thành công Dashboard báo cáo thông minh trực quan hóa toàn bộ dữ liệu hóa đơn với đầy đủ biểu đồ, chỉ số KPI và bộ lọc tương tác.
