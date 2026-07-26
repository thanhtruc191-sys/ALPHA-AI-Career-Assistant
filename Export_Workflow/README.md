# CẤU TRÚC WORKFLOW TỰ ĐỘNG - BOT ALPHA (COZE PLATFORM)

Thư mục này lưu trữ sơ đồ quy trình tự động hóa (Workflow Canvas) của Trợ lý Hướng nghiệp số ALPHA được thiết kế trên nền tảng Coze.

## 🎯 CÁC NODE CHỨC NĂNG CHÍNH TRONG WORKFLOW

1. **Start Node (Khởi tạo):** Tiếp nhận thông tin tương tác đầu vào từ học sinh.
2. **Phân loại học sinh (Condition Node):** Rẽ nhánh xử lý tự động dựa trên khối lớp (`Lớp 9 lên 10`, `Lớp 10`, `Lớp 11`, `Lớp 12`).
3. **Kho trí thức (Knowledge Base Nodes):**
   - *Kho trí thức lớp 9 lên 10:* Tra cứu ma trận hướng nghiệp dành cho lớp 9 lên 10, bộ 65 câu hỏi hướng nghiệp, ma trận chấm điểm, khung năng lực số
   - *Kho trí thức THPT:* Tra cứu ngành nghề đón đầu xu hướng 2035 và các khối thi xét tuyển,bộ 65 câu hỏi hướng nghiệp, ma trận chấm điểm, khung năng lực số
4. **AI Chào hỏi & Khởi tạo (LLM Node):** Xử lý kịch bản lời chào và kích hoạt quy trình thu thập thông tin gộp.
5. **AI Phân tích hướng nghiệp ALPHA (LLM Node - GPT-4o):** Phân tích ma trận năng lực 5D và đưa ra định hướng chuyên sâu.
6. **AI Đối chiếu Sở thích & Học lực (LLM Node):** Chuẩn hóa điểm số trung bình môn, tính toán Chỉ số Sẵn sàng Học thuật (AR).
7. **Tổng hợp kết quả (Batch / Code Node):** Tổng hợp dữ liệu từ các nhánh AI và Kho trí thức thành báo cáo hoàn chỉnh.
8. **End Node (Xuất kết quả):** Trả Báo cáo Tư vấn Hướng nghiệp chuẩn hóa về giao diện người dùng.

---
*Ghi chú: Toàn bộ tác vụ lưu trữ biến dữ liệu và trích xuất thông tin chạy ngầm 100% (Asynchronous) để đảm bảo tốc độ phản hồi tối ưu cho học sinh.*
