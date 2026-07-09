---
title: "Các công bố lớn về AI Agent tại AWS Summit New York 2026"
date: 2026-06-26
weight: 10
chapter: false
pre: " <b> 3.1. </b> "
---

# AWS Summit New York 2026: AWS muốn trở thành nền tảng chính cho AI Agent trong doanh nghiệp

AWS đang hướng tới mục tiêu trở thành nền tảng chính để các doanh nghiệp xây dựng, kiểm soát và vận hành AI agent ở quy mô production (môi trường vận hành thực tế). 

Tại **AWS Summit New York 2026**, Swami Sivasubramanian - Phó chủ tịch AWS phụ trách Agentic AI, đã trình bày các công bố lớn xoay quanh AI agent, bảo mật AI, hiện đại hóa phần mềm và giải pháp dữ liệu tối ưu cho workflow tự động.

---

## Sơ đồ quy trình làm việc của AI Agent (AI Agent Workflow)

Dưới đây là sơ đồ tổng quan về quy trình làm việc chuẩn hóa của một AI Agent trong doanh nghiệp, từ khâu tiếp nhận dữ liệu đầu vào cho đến xử lý, kiểm soát và thực thi hành động:

![AI Agent Workflow](/images/3-BlogsPosted/blog1_workflow.png)

---

## 1. Các công bố lớn xoay quanh AI Agent & Tự động hóa

### Amazon Bedrock AgentCore có nhiều năng lực mới
AWS giới thiệu các tính năng giúp AI agent kết nối với tri thức nội bộ doanh nghiệp, web và nguồn dữ liệu trả phí. Mục tiêu là giúp doanh nghiệp xây dựng agent nhanh hơn, có kiểm soát tốt hơn, và liên tục cải thiện agent khi đưa vào môi trường production.

### Amazon Bedrock Managed Knowledge Base
Dịch vụ này giúp xây dựng pipeline RAG (Retrieval-Augmented Generation) cho doanh nghiệp dễ dàng hơn. Nó cung cấp các connector dữ liệu, khả năng xử lý nhiều định dạng tài liệu và cơ chế truy xuất thông minh cho các truy vấn nhiều bước (multi-step queries).

### Web Search trên Amazon Bedrock AgentCore
AI agent có thể tìm kiếm web theo cách được quản lý sẵn (managed search), lấy thông tin mới có trích dẫn nguồn, đồng thời vẫn giữ dữ liệu trong môi trường bảo mật của khách hàng AWS.

### AWS WAF hỗ trợ kiếm tiền từ lưu lượng AI bot
Nhà xuất bản nội dung (content publishers) có thể định giá, đo lường và thu phí khi bot hoặc AI agent truy cập vào nội dung hoặc các API của họ.

### Bedrock AgentCore Harness đã khả dụng rộng rãi (GA)
Nhà phát triển có thể cấu hình model, tool, skill và instruction để chạy AI agent ở mức độ production-grade mà không cần tự viết toàn bộ logic điều phối từ đầu.

### AWS Continuum và Security Agent
AWS giới thiệu công cụ bảo mật dùng AI để ưu tiên lỗ hổng theo tác động kinh doanh, xác minh khả năng bị khai thác, hỗ trợ threat modeling theo STRIDE, quét pull request và đề xuất sửa lỗi ngay trong workflow của nhà phát triển.

### Kiro cho iOS
Kiro có ứng dụng iOS native, cho phép nhà phát triển khởi tạo, theo dõi, điều hướng session, xem diff và duyệt thay đổi mã nguồn ngay từ điện thoại di động.

### AWS DevOps Agent có năng lực quản lý release
Agent này có thể đánh giá mức độ sẵn sàng trước khi release và tự động chạy kiểm thử trong môi trường có cấu trúc tương tự như môi trường production.

### AWS Transform - Hiện đại hóa liên tục (Continuous Modernization)
Công cụ này phân tích repository liên tục, phát hiện nợ kỹ thuật (technical debt), ưu tiên các vấn đề nghiêm trọng và tự động tạo pull request để sửa lỗi.

### Amazon S3 Annotations
S3 cho phép gắn metadata/ngữ cảnh phong phú và có thể truy vấn trực tiếp vào object. Tính năng này cực kỳ hữu ích cho AI agent và workflow tự động cần hiểu dữ liệu ở quy mô lớn.

---

## 2. Vấn đề được đặt ra cho doanh nghiệp

Mặc dù các doanh nghiệp rất muốn ứng dụng AI agent, họ vẫn đang gặp phải nhiều rào cản lớn:

- **Dữ liệu phân tán**: Dữ liệu nằm rải rác trong nhiều hệ thống khác nhau, khó đưa vào AI một cách chính xác và kịp thời.
- **Nhu cầu dữ liệu thời gian thực**: AI agent cần thông tin cập nhật mới nhất từ web nhưng phải đảm bảo tính bảo mật và trích dẫn nguồn rõ ràng.
- **Rủi ro về kiểm soát**: Khi agent trở nên mạnh hơn và tự động hóa nhiều hơn, rủi ro về kiểm soát, quản lý quyền truy cập và quản trị (governance) tăng lên.
- **Bảo mật phần mềm chậm chạp**: Quy trình bảo mật phần mềm hiện nay quá chậm so với tốc độ phát triển và release liên tục của doanh nghiệp.
- **Nợ kỹ thuật (Technical Debt)**: Technical debt tích tụ trong codebase nhưng việc phân tích và sửa chữa thủ công thường mất nhiều tuần.
- **Thất thoát giá trị nội dung**: Nội dung số bị AI bot truy cập tự do nhưng chủ sở hữu nội dung khó kiểm soát hoặc thu phí dịch vụ.
- **Quản lý Metadata phức tạp**: Metadata dữ liệu cho AI thường phải quản lý bằng hệ thống riêng biệt bên ngoài, gây phức tạp cho vận hành.

---

## 3. Giải pháp toàn diện từ AWS

Để giải quyết các thách thức trên, AWS đưa ra một nhóm giải pháp hợp nhất xoay quanh tự động hóa bằng trí tuệ nhân tạo:

1. **Bedrock AgentCore**: Xây dựng và vận hành AI agent có kiểm soát chặt chẽ.
2. **Managed Knowledge Base + Web Search**: Giúp agent truy cập an toàn vào tri thức nội bộ doanh nghiệp cũng như các thông tin web đáng tin cậy.
3. **AWS WAF AI traffic monetization**: Hỗ trợ chủ sở hữu nội dung kiểm soát truy cập và thu phí từ các AI bot.
4. **AWS Continuum / Security Agent**: Phát hiện, ưu tiên mức độ ảnh hưởng và hỗ trợ sửa lỗi bảo mật tự động nhanh chóng.
5. **DevOps Agent**: Đánh giá release và chạy kiểm thử tự động trước khi đưa lên môi trường production.
6. **AWS Transform**: Tự động phát hiện và giảm thiểu nợ kỹ thuật trong codebase.
7. **S3 Annotations**: Cung cấp thêm ngữ cảnh cho dữ liệu trực tiếp tại lớp lưu trữ phục vụ AI agent và workflow tự động.

---

## Tài liệu tham khảo
* Đọc bài viết gốc trên AWS Blog: [Top Announcements of the AWS Summit in New York 2026](https://aws.amazon.com/blogs/aws/top-announcements-of-the-aws-summit-in-new-york-2026/)