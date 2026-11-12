# 🛡️ GRAPHIELD - REAL-TIME AML & MULE NETWORK GRAPH INTELLIGENCE

> **Dự án cuối kỳ môn Công nghệ tài chính và ứng dụng (FinTech)**  
> **Repository:** [https://github.com/MKII3184/GraphShield](https://github.com/MKII3184/GraphShield)  
> **Tuân thủ:** Quyết định 2345/QĐ-NHNN & Nghị định 13/2023/NĐ-CP  
> **Kiến trúc:** Real-time In-Memory Graph Traversal, Low-latency Detection Engine (< 30ms)

---

## 🚀 HƯỚNG DẪN KHỞI CHẠY NHANH (QUICK START)

Bạn có 2 cách chạy cực kỳ đơn giản:

### Cách 1: Chạy ngay không cần cài đặt (Khuyên dùng khi cần demo gấp)
* Vào thư mục: `GraphShield/`
* Bấm đúp chuột mở file **`index.html`** trên trình duyệt Chrome, Edge hoặc Brave.
* Giao diện Dashboard sẽ hoạt động mượt mà 100%, có đầy đủ đồ thị tương tác, 3 kịch bản tấn công và nút khóa khẩn cấp.

### Cách 2: Chạy qua Python Flask Server (Dành cho việc bảo vệ trước hội đồng)
1. Mở Terminal / PowerShell tại thư mục `GraphShield/`:
   ```bash
   cd "c:\Users\24110\OneDrive\Desktop\Công nghệ tài chính và ứng dụng\GraphShield"
   ```
2. Chạy server Flask:
   ```bash
   python app.py
   ```
3. Mở trình duyệt và truy cập: **`http://127.0.0.1:5000`**

---

## 📂 DANH MỤC TÀI LIỆU & MÃ NGUỒN TRONG THƯ MỤC

1. **`app.py`**: Mã nguồn Backend Flask cung cấp REST API phân tích rủi ro đồ thị (`/api/analyze`) và API phong tỏa tài khoản (`/api/freeze`).
2. **`templates/index.html`** & **`index.html`**: Giao diện Dashboard Trung tâm điều hành an ninh (SOC) phong cách Dark Mode chuyên nghiệp, tích hợp thư viện Vis.js đồ thị động.
3. **`PROJECT_REPORT_GRAPHIELD.md`**: Báo cáo cuối kỳ hoàn chỉnh chuẩn 11 phần theo đề cương yêu cầu (Problem $\to$ Solution $\to$ Architecture $\to$ Business Model $\to$ Regulations...). Có thể copy thẳng vào Word để nộp.
4. **`PRESENTATION_SLIDES_AND_SCRIPT.md`**: Dàn bài 10 Slide thuyết trình, kịch bản nói chi tiết từng phút (10–15 phút), và bộ 5 câu hỏi phản biện hóc búa kèm câu trả lời điểm 10.

---

## 🎯 CÁC TÍNH NĂNG VÀ KỊCH BẢN DEMO "WOW"
* **Kịch bản 1: VietQR Thường Ngày:** Giao dịch hợp lệ, đồ thị xanh, Risk Score 5/100.
* **Kịch bản 2: Smurfing né QĐ 2345:** 500 triệu bị băm nhỏ thành các món 9.2M – 9.8M qua nhiều tài khoản rác mới lập để né sinh trắc học, gom về tài khoản trùm. Đồ thị bừng sáng đỏ, bắt trong 18.4ms.
* **Kịch bản 3: Rửa tiền vòng tròn (Circular Layering):** Dòng tiền khép kín qua 4 ngân hàng (VCB $\to$ MB $\to$ TCB $\to$ VPB $\to$ VCB). Thuật toán Tarjan khoanh vùng chu trình.
* **Nút bấm ⚡ KHÓA KHẨN CẤP MẠNG LƯỚI MULE:** Phong tỏa tức thì toàn bộ node tài khoản rác, ngăn chặn rút tiền tại ATM và bảo toàn tài sản.
