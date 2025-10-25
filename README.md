# MultiSource-VidDownloader-codonquaVN

**MultiSource-VidDownloader** là công cụ tải video/audio từ nhiều trang web khác nhau, hỗ trợ giao diện web hiện đại, quản lý người dùng, dựa trên yt-dlp.

---

## Tính năng nổi bật

- **Tải video/audio** từ hàng ngàn trang web (YouTube, Facebook, TikTok, v.v.)
- **Giao diện web** thân thiện, dễ sử dụng
- **Quản lý người dùng**: phân quyền, giới hạn lượt tải, đổi mật khẩu, xóa user
- **Lưu lịch sử tải về** cho từng tài khoản
- **Hỗ trợ playlist, tải hàng loạt**
- **Dựa trên yt-dlp**: cập nhật nhanh, mạnh mẽ, hỗ trợ nhiều định dạng
- **Tùy biến dễ dàng** cho nhu cầu cá nhân hoặc doanh nghiệp

---

## Hướng dẫn cài đặt

### 1️⃣ Cài đặt Python

- Yêu cầu **Python 3.9 trở lên**
- Tải tại: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Khi cài đặt, nhớ tick vào **"Add Python to PATH"**

### 2️⃣ Cài đặt thư viện cần thiết

Tại thư mục dự án, mở terminal/cmd và chạy:

pip install -r requirements.txt

text

### 3️⃣ Cài đặt FFmpeg (rất quan trọng để tải video chất lượng cao)

#### 🔹 Bước 1: Tải FFmpeg

Truy cập trang chính thức: [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)

Chọn phiên bản phù hợp với hệ điều hành:

**Windows:**
- Tải từ: [https://www.gyan.dev/ffmpeg/builds/](https://www.gyan.dev/ffmpeg/builds/)

**macOS:**
brew install ffmpeg

text

**Linux (Ubuntu/Debian):**
sudo apt update
sudo apt install ffmpeg

text

#### 🔹 Bước 2: Thêm FFmpeg vào PATH (Windows)

1. Giải nén thư mục tải về (ví dụ: `C:\ffmpeg`)
2. Mở menu Start → tìm "Environment Variables" → Edit the system environment variables
3. Trong tab Advanced, chọn **Environment Variables...**
4. Ở mục System variables, chọn **Path** → **Edit** → **New**
5. Dán đường dẫn đến thư mục bin (ví dụ: `C:\ffmpeg\bin`)
6. Nhấn **OK** → **OK** → **OK** để lưu
7. Mở CMD và gõ:

ffmpeg -version

text

→ Nếu hiện thông tin phiên bản là đã cài thành công ✅

### 4️⃣ Chạy ứng dụng

python web_gui.py

text

Ứng dụng sẽ chạy tại địa chỉ: [http://localhost:5000](http://localhost:5000)

---

## 💡 Hướng dẫn sử dụng

### 🔐 Đăng nhập & Quản lý tài khoản

- **Tài khoản mặc định:** `admin` (mật khẩu do bạn tự tạo hoặc chỉnh trong file `users.json`)
- **Admin có thể:**
  - Tạo / xóa user
  - Đổi mật khẩu
  - Phân quyền
  - Giới hạn lượt tải, quyền tải playlist

### 🎬 Tải video/audio

1. Đăng nhập vào hệ thống qua trình duyệt
2. Nhập link video/audio cần tải
3. Chọn định dạng & chất lượng
4. Nhấn **Tải về** và chờ kết quả

### 🕒 Lịch sử tải

- Mỗi user có thể xem lại lịch sử tải của mình
- Admin có thể xem tổng thể toàn hệ thống

---

## ⚠️ Lưu ý quan trọng

- **Nên cài đặt thêm [FFmpeg](https://ffmpeg.org/download.html)** để đảm bảo tải được video/audio chất lượng cao nhất
- Nếu gặp lỗi thiếu thư viện → chạy lại lệnh:
pip install -r requirements.txt

text
- Dự án sử dụng mã nguồn yt-dlp, tuân thủ giấy phép [Unlicense](LICENSE)

---

## 📞 Liên hệ & Hỗ trợ

<div align="center">

<a href="https://zalo.me/0858925890" target="_blank">
<img src="https://img.shields.io/badge/Zalo-0858925890-blue?style=for-the-badge&logo=zalo" alt="Zalo" />
</a>

<br/><br/>

📱 **Hotline/Zalo:** [0858 925 890](https://zalo.me/0858925890)

</div>

Nếu có thắc mắc, cần hỗ trợ hoặc muốn đóng góp,  
👉 vui lòng liên hệ qua Zalo hoặc tạo issue trên GitHub.

---

**🎉 Chúc bạn sử dụng vui vẻ và tải video chất lượng cao nhất!**
