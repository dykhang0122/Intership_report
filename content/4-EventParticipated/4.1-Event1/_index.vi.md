---
title: "Event 1"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch "Context Is Everything: Making AI Actually Work for You"

### Mục Đích Của Sự Kiện

- Hiểu lý do tại sao AI phản hồi kém và cách khắc phục thông qua việc cung cấp bối cảnh (context) chất lượng cao.
- Tìm hiểu cấu trúc 4 yếu tố cốt lõi để biến một câu lệnh mơ hồ thành một nhiệm vụ có thể giải quyết chính xác bởi AI.
- Nhận diện các sai lầm phổ biến khi tương tác với AI và nắm bắt xu hướng phát triển từ các câu lệnh đơn lẻ dịch chuyển sang "Bộ não thứ hai" (Second AI Brain).

### Danh Sách Diễn Giả

- **Anh Tịnh** – Platform Engineer tại GoTymeX, AWS Community Builder. Chủ đề: Build second brain.
- **Hải Anh** – Chủ đề: Friendly AI Assistant with Amazon Quick.
- **Thịnh** – Chủ đề: From Edge To Origin: CloudFront as Your Foundation.
- **Team VIB** – Chủ đề: 36 hrs with LotusHacks – Building UTMorpho from Scratch.
- **Đào Đức** – Chủ đề: Deep dive talk: How LLM actually works?
- **Cát Vy** – Chủ đề: Enterprise-Grade Multi-Agent System: The Case of UTMorpho.

### Nội Dung Nổi Bật

#### PHẦN 1: Vấn đề cốt lõi - Tại sao AI phản hồi kém?

Nhiều kết quả phản hồi từ AI gây thất vọng (như trả lời chung chung, sai hướng, quá dài dòng hoặc thiếu ràng buộc) không phải do mô hình AI kém thông minh, mà là do người dùng thiếu bối cảnh (context). 
- AI không thể tự đọc suy nghĩ hay đoán ý định của bạn.
- AI chỉ xử lý và đưa ra kết quả dựa trên chính xác những gì bạn cung cấp đầu vào.

#### PHẦN 2: Cấu trúc của "Context" (Bối cảnh) chất lượng

Để chuyển đổi một câu lệnh mơ hồ thành một nhiệm vụ cụ thể mà AI có thể giải quyết một cách chính xác, bối cảnh cần chứa đầy đủ 4 yếu tố sau:

1. **Mục tiêu (Your goal):** Định hình kết quả đầu ra mong muốn một cách rõ ràng và cụ thể.
2. **Tình huống (Your situation):** Làm rõ vị trí của bạn (người mới bắt đầu, sinh viên hay lập trình viên có kinh nghiệm), bối cảnh làm việc (dự án nhóm hay đang chạy deadline gấp).
3. **Ràng buộc (Your constraints):** Giới hạn về công nghệ sử dụng (tech stack), phong cách code/viết, ngân sách, định dạng đầu ra mong muốn.
4. **Bằng chứng liên quan (Relevant evidence):** Cung cấp các đoạn mã nguồn hiện tại, tài liệu liên quan, ví dụ mẫu hoặc yêu cầu kỹ thuật chi tiết.

#### PHẦN 3: 3 Sai lầm phổ biến khi cung cấp bối cảnh cho AI

- **Sai lầm #1: Nhồi nhét dữ liệu ("Internet Puller" Problem)**
  - *Thói quen xấu:* Sao chép nguyên vẹn cả bài báo, file PDF dung lượng lớn, ảnh chụp màn hình ngẫu nhiên và ghi chú lộn xộn vào chung một ô chat.
  - *Hậu quả:* Dữ liệu rác làm AI bị "nhiễu" thông tin, giảm độ chính xác của câu trả lời và làm lãng phí số lượng token không cần thiết. Nhiều bối cảnh hơn không đồng nghĩa với bối cảnh tốt hơn.
- **Sai lầm #2: Nói lại những điều AI đã biết**
  - *Ví dụ dở:* Tải lên một đoạn code Node.js Express rồi ra lệnh: "Hãy viết cái này bằng Node.js và Express". Việc này làm lãng phí không gian xử lý dữ liệu hữu ích.
  - *Cách làm tốt:* Đi thẳng vào yêu cầu nâng cấp: "Hãy refactor API này để thêm tính năng phân trang (pagination), kiểm định dữ liệu đầu vào (validation) và quản lý lỗi (error handling) rõ ràng hơn".
- **Sai lầm #3: Ra lệnh không mục tiêu, không ràng buộc**
  - *Ví dụ dở:* "Xây dựng cho tôi một website portfolio" (Yêu cầu quá mơ hồ sẽ dẫn tới kết quả chung chung và rập khuôn).
  - *Cách làm tốt:* "Xây dựng một portfolio tối giản cho một lập trình viên là sinh viên. Sử dụng React + Tailwind, thiết kế ưu tiên hiển thị trên di động (mobile-first) và hỗ trợ chế độ tối (dark mode)".

#### PHẦN 4: Giải pháp - Tập trung vào "Chất lượng" thay vì "Số lượng"

- Tránh gửi ảnh chụp màn hình ngẫu nhiên hoặc các tài liệu dài dòng không liên quan trực tiếp.
- Chỉ trích dẫn các đoạn mã/văn bản quan trọng (snippets), đưa ra ràng buộc kỹ thuật rõ ràng và định nghĩa cấu trúc định dạng đầu ra mong muốn.
- Mục tiêu không phải là cung cấp thật nhiều thông tin, mà là cung cấp những dữ liệu chuẩn xác và cô đọng nhất.

#### PHẦN 5: Xu hướng phát triển - Từ Câu lệnh đến "Bộ não thứ hai"

Sự tiến hóa trong tương tác với AI đang dịch chuyển mạnh mẽ theo mô hình:
$$\text{Prompt (Câu lệnh đơn lẻ)} \rightarrow \text{Context (Bối cảnh kèm tài liệu)} \rightarrow \text{Memory (Trí nhớ dài hạn)}$$

Khi hệ thống AI kết hợp cả **Bối cảnh** và **Trí nhớ dài hạn**, nó sẽ trở thành **Bộ não thứ hai (Second AI Brain)** của bạn nhờ năng lực:
- Ghi nhớ tiến trình học tập và làm việc của bạn.
- Hiểu rõ các dự án, định hướng công việc và mục tiêu cá nhân.
- Tự động tìm kiếm, phân tích và truy xuất đúng bối cảnh trước khi phản hồi.
- Càng ngày càng trở nên thông minh, tối ưu hơn khi kho kiến thức cá nhân của bạn dày lên.

---

### Những Gì Học Được

#### Tư Duy Thiết Kế
- **Tập trung vào chất lượng ngữ cảnh:** Học được tư duy chắt lọc thông tin đầu vào. Thay vì nhồi nhét dữ liệu rác, việc định hình rõ ràng các ràng buộc và mục tiêu giúp AI hoạt động hiệu quả tối đa.
- **Tư duy cộng tác với AI:** Chuyển đổi từ việc "ra lệnh" một chiều sang xây dựng một quy trình làm việc song hành, nơi con người đóng vai trò định hướng ngữ cảnh và AI thực thi nhiệm vụ kỹ thuật.

#### Kiến Trúc Kỹ Thuật
- **Mô hình Prompt - Context - Memory:** Hiểu rõ cách các hệ thống AI hiện đại lưu trữ và truy xuất thông tin để cá nhân hóa câu trả lời.
- **Cách xây dựng Second AI Brain:** Nắm được cơ chế kết hợp giữa cơ sở dữ liệu tri thức (Knowledge Base) và bộ nhớ dài hạn của AI để phục vụ công việc dài hạn.

---

### Ứng Dụng Vào Công Việc

- Áp dụng cấu trúc prompt 4 yếu tố (Mục tiêu, Tình huống, Ràng buộc, Bằng chứng) vào mọi tác vụ hàng ngày khi sử dụng AI để viết code, gỡ lỗi và nghiên cứu công nghệ.
- Tối ưu hóa các tài liệu dự án bằng cách chia nhỏ thành các đoạn snippet và tài liệu đặc tả rõ ràng trước khi cấp dữ liệu cho AI.
- Bắt đầu xây dựng một kho tri thức cá nhân có cấu trúc (Markdown-based wiki) làm cơ sở ngữ cảnh/bộ nhớ dài hạn cho AI đồng hành trong suốt quá trình học tập và làm việc.

---

### Trải nghiệm trong event

Tham gia buổi chia sẻ trong chuỗi sự kiện **AWS First Cloud Journey** mang lại những bài học vô cùng thiết thực về phương pháp sử dụng AI thế hệ mới:
- **Tiếp cận thực tế:** Được học hỏi từ trải nghiệm triển khai thực tế của anh Tinh Truong (Platform Engineer tại GoTymeX), giúp rút ngắn khoảng cách giữa lý thuyết prompt engineering và thực tế công việc.
- **Thay đổi góc nhìn:** Nhận thức rõ ràng AI là một người đồng nghiệp cần được cung cấp đầy đủ thông tin bối cảnh cụ thể để hoạt động hiệu quả nhất, thay vì là một công cụ "vạn năng" tự đoán trước mọi yêu cầu.

---

### Hình ảnh sự kiện

![Ảnh sự kiện 1](/images/4-EventParticipated/event1_1.jpg)
![Ảnh sự kiện 2](/images/4-EventParticipated/event1_2.jpg)
