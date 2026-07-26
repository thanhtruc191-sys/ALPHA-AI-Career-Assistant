# 🤖 DỰ ÁN: ALPHA - TRỢ LÝ HƯỚNG NGHIỆP SỐ AI

> **Giải pháp Trợ lý ảo tư vấn hướng nghiệp tự động dành cho học sinh THPT & Lớp 9 chuyển cấp theo Chương trình GDPT 2018.**

---

## 🌐 1. ĐƯỜNG DẪN TRẢI NGHIỆM THỰC TẾ
* **Website Cổng thông tin:** https://sites.google.com/view/alpha-trolyhuongnghiepso
* **Trợ lý ảo ALPHA (Telegram Bot):** https://t.me/Trolyhuongnghiepso2026_Bot

---

## 🏗️ 2. KIẾN TRÚC VẬN HÀNH (WORKFLOW COZE)
Hệ thống vận hành tự động dựa trên **7 khối chức năng chính**:
1. **Start:** Tiếp nhận tương tác ban đầu từ học sinh.
2. **Phân loại học sinh:** Rẽ nhánh kịch bản theo đúng đối tượng (Lớp 9 lên 10 hoặc THPT).
3. **AI Chào hỏi & Khởi tạo (GPT-4o):** Đón tiếp, tạo không khí thân thiện và thu thập thông tin nền.
4. **Kho trí thức (Knowledge):** Chứa ma trận hướng nghiệp Lớp 9 lên 10, ma trận hướng nghiệp Lớp 10, 11, 12, ma trận chấm điểm, Khung năng lực số, bộ 65 câu hỏi trắc nghiệm tương tác và Mô hình ALPHA 5D.
5. **AI Phân tích hướng nghiệp ALPHA (GPT-4o mini):** Truy xuất kho tri thức, đưa ra câu hỏi trắc nghiệm/tình huống đào sâu để thử thách phản xạ và năng lực.
6. **AI Đối chiếu Sở thích & Học lực (GPT-4o mini):** So sánh học lực thực tế với sở thích trắc nghiệm để xác định "Điểm ngọt ngào hướng nghiệp" và xuất Báo cáo tư vấn chuyên sâu.
7. **Tổng hợp kết quả & End:** Quản lý số lần tương tác, đóng gói và hiển thị câu trả lời trực quan ra giao diện.

---

## 📂 3. CẤU TRÚC THƯ MỤC KHO MÃ NGUỒN
* `Prompts/`: Chứa kịch bản Prompt chi tiết cho từng khối AI.
* `Knowledge/`: Chứa bộ dữ liệu ma trận hướng nghiệp (Lớp 9->10 và THPT), ma trận chấm điểm, khung năng lực số, bộ 65 câu hỏi trắc nghiệm và tài liệu hướng nghiệp GDPT 2018.
* `Export_Workflow/`: Cấu hình kỹ thuật Workflow xuất từ Coze (file `.json`).
Ghi rõ ràng như thế này vừa thể hiện được hàm lượng tri thức sư phạm, vừa làm nổi bật "linh hồn" chuyên môn của dự án ALPHA!

---

## 📂 3. CẤU TRÚC THƯ MỤC KHO MÃ NGUỒN
* `Prompts/`: Chứa kịch bản Prompt cho từng khối AI.
* `Knowledge/`: Chứa ma trận năng lực ALPHA 5D, bộ 65 câu hỏi và dữ liệu ngành nghề.
* `Export_Workflow/`: Cấu hình kỹ thuật Workflow xuất từ Coze.
