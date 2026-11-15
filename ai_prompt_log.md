# Lịch sử Tương tác AI (AI Prompt Log) - Dự án TechBugs Refactor

File này ghi lại các câu lệnh (prompts) chính đã trao đổi với AI trong quá trình chuẩn hóa cấu trúc HTML theo chuẩn Semantic và quản lý mã nguồn Git, kèm theo mục đích sử dụng.

---

### 1. Phân tích và Xây dựng Ý tưởng
* **Prompt đã dùng:** 
  > *"Giải thích cho tôi tại sao dùng thẻ `<ul>`, `<li>` cho thanh điều hướng lại tốt hơn việc dùng nhiều thẻ `<a>` đặt cạnh nhau, và cách phân biệt thẻ `<section>` với `<article>`?"*
* **Mục đích / Giải thích:** 
  Hiểu rõ bản chất ngữ nghĩa của các thẻ HTML (Semantic tags). Việc dùng `<ul>` và `<li>` giúp trình đọc màn hình cho người khiếm thị nhận diện danh sách menu và giúp các công cụ tìm kiếm (SEO) cấu trúc trang web chính xác hơn thay vì lạm dụng thẻ `<div>`.

---

### 2. Thiết kế và Quản lý Nhánh Git
* **Prompt đã dùng:** 
  > *"Tôi đã tạo xong nhánh `feature/nav-bar` và muốn tạo thêm nhánh `feature/semantic-content` từ `main`. Tại sao tôi bắt buộc phải gõ lệnh `git checkout main` trước khi tạo nhánh mới? Nếu không gõ thì hậu quả là gì?"*
* **Mục đích / Giải thích:** 
  Nắm vững tư duy phân nhánh (Branching) trong Git. Tránh việc rẽ nhánh nhầm từ một nhánh tính năng đang dang dở (dẫn đến bị dính code thừa), đảm bảo mỗi nhánh tính năng đều xuất phát từ điểm neo gốc `main` sạch sẽ.

---

### 3. Xử lý Vận hành và Hợp nhất (Merge / Conflict)
* **Prompt đã dùng:** 
  > *"Hãy đưa ra một tình huống giả định khiến việc Merge 2 nhánh của tôi bị Conflict (xung đột). Làm thế nào để tôi nhận biết code đang bị conflict và cách giải quyết thủ công?"*
* **Mục đích / Giải thích:** 
  Chuẩn bị kiến thức xử lý sự cố khi làm việc nhóm. Hiểu cách Git đánh dấu vùng xung đột (`<<<<<<<`, `=======`, `>>>>>>>`) và cách phối hợp code thủ công trong VS Code trước khi chạy lệnh `git add` và `git commit` để hoàn tất merge.