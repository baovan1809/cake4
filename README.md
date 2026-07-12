# 🍰 CakePro — AI Saving Journey & Financial Assistant (GATO Mascot Demo)

Giao diện giả lập ứng dụng tài chính số **CakePro** kết hợp trợ lý ảo **GATO Mascot** thông minh. Demo được thiết kế tinh tế, trực quan, hỗ trợ đầy đủ các hiệu ứng chuyển động cao cấp (Micro-interactions) và tối ưu hóa hiển thị tiếng Việt.

---

## ✨ Các tính năng nổi bật (Premium Features)

1. **🗺️ GATO Savings Journey (Bản đồ tiết kiệm)**:
   - Bản đồ hành trình đứt nét uốn lượn uốn quanh các mốc tài chính: *Chi tiêu tháng này*, *Mục tiêu tiết kiệm*, và *Sổ tiết kiệm*.
   * Tương tác chuyển màn hình mượt mà, đồng bộ trạng thái điều hướng.

2. **📊 Spending Manager (Thống kê chi tiêu chi tiết)**:
   - Biểu đồ vòng tròn phân bổ (Doughnut Chart) xây dựng bằng **nhiều phân khúc SVG** sắc nét, hiển thị chính xác tỉ lệ phần trăm bay lơ lửng xung quanh biểu đồ.
   - Bảng kê chi tiết các danh mục chính (*Nhà cửa, Học tập, Chợ búa, Ăn uống, Di chuyển, Giải trí*) có màu sắc đồng bộ với biểu đồ tròn.

3. **🎮 Interactive GATO Level-Up (Thanh trượt lên đời)**:
   - Kéo thanh trượt từ `0%` đến `100%` để chứng kiến hành trình "lên đời" diện mạo của linh vật GATO:
     - **0%**: Đầu bù tóc rối chọc chỉa, đội nón lá tre, mặc áo bà ba vá bụng dạo chơi.
     - **20%**: Cắt tóc mái ngố gọn gàng, mặc áo hoodie xám năng động.
     - **50%**: Nhuộm tóc hồng spiky vuốt dựng cực chơi, đeo kính râm, khuyên tai vàng và xích vàng bản to.
     - **100%**: Tóc vuốt ngược bóng lộn của quý ông, đội vương miện, đeo kính râm VIP vàng, mặc Tuxedo thắt nơ đỏ và **siêu xe Rolls-Royce lướt ra đậu bên cạnh**.
   - Số tiền tiết kiệm tích lũy tự động cập nhật theo thời gian thực tương ứng với mức kéo.

4. **🎙️ Voice Chat Assistant (Trợ lý Giọng nói giả lập)**:
   - Nhấp vào nút Micro nhảy nhót góc dưới màn hình hoặc nút Micro trong ô chat để kích hoạt ghi âm giọng nói.
   - Giả lập vòng sóng âm rung động, phát ra **âm thanh Beep** (sử dụng Web Audio API trực tiếp trên trình duyệt) và tự động nhận dạng lời nói của chủ nhân để cấu hình số tiền tiết kiệm.

5. **📱 QR Scanner & Quick Actions**:
   - Quét mã QR mô phỏng camera thực tế, phát tiếng bíp khi quét trúng mã và tự động cộng tiền vào tài khoản tiết kiệm.
   - Nút đăng xuất quay lại màn hình đăng nhập bảo mật.

---

## 🛠️ Hướng dẫn khởi chạy cục bộ (Run Locally)

Ứng dụng được viết hoàn toàn bằng **HTML, Javascript thuần và TailwindCSS** (không có dependencies phức tạp), hoạt động offline 100%.

### Cách 1: Chạy trực tiếp (Nhanh nhất)
1. Tải thư mục này về máy.
2. Nhấp đúp chuột vào tệp **`index.html`** để mở trực tiếp trên trình duyệt (Chrome, Edge, Safari...).

### Cách 2: Chạy qua Live Server (Khuyên dùng để tải font mượt mà)
Nếu máy bạn có cài đặt NodeJS hoặc Python, có thể chạy local server:
* **Với Python**: 
  ```bash
  python -m http.server 8000
  ```
  Sau đó truy cập địa chỉ: `http://localhost:8000` trên trình duyệt.

---

## 🌐 Hướng dẫn đưa lên GitHub Pages (Đăng ký Web chạy thật miễn phí)

Để gửi link demo này cho người khác dùng thử trực tiếp trên điện thoại của họ:

1. Tạo một repository mới trên GitHub (ví dụ đặt tên: `cakepro-gato`).
2. Tải toàn bộ các tệp trong thư mục này lên repository đó:
   - `index.html`
   - `mascot.png`
   - `README.md`
   - `app.js` (nếu có dùng ngoài)
   - `styles.css` (nếu có dùng ngoài)
3. Đi tới mục **Settings** (Cài đặt) của repository trên GitHub.
4. Chọn tab **Pages** ở cột bên trái.
5. Tại mục **Build and deployment** -> **Source**: Chọn `Deploy from a branch`.
6. Tại mục **Branch**: Chọn `main` (hoặc `master`) và thư mục `/ (root)`, sau đó nhấn **Save**.
7. Đợi khoảng 1-2 phút, GitHub sẽ cấp cho bạn một đường link HTTPS dạng: `https://<ten-tai-khoan-github>.github.io/cakepro-gato/`. 

*Bạn có thể gửi link này cho bạn bè hoặc đối tác mở bằng điện thoại để chạy thử giao diện cực kỳ tiện lợi!*
