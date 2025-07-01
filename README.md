# MultiSource-VidDownloader_codonqua


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

### 1. Cài Python

- Yêu cầu **Python 3.9 trở lên**
- Tải tại: https://www.python.org/downloads/
- Khi cài đặt, nhớ tick vào **"Add Python to PATH"**

### 2. Cài các thư viện cần thiết

Tại thư mục dự án, mở terminal/cmd và chạy:
```sh
pip install -r requirements.txt
```

### 3. Chạy ứng dụng

```sh
python web_gui.py
```
- Ứng dụng sẽ chạy tại địa chỉ: [http://localhost:5000](http://localhost:5000)

---

## Hướng dẫn sử dụng

### Đăng nhập & Quản lý tài khoản

- Tài khoản mặc định: `admin` (mật khẩu do bạn tự tạo hoặc chỉnh trong file `users.json`)
- Admin có thể tạo, xóa, đổi mật khẩu, phân quyền cho user khác
- Mỗi user có thể bị giới hạn số lượt tải, quyền tải playlist, v.v.

### Tải video/audio

1. Đăng nhập vào hệ thống qua trình duyệt web
2. Nhập link video/audio cần tải vào ô tương ứng
3. Chọn định dạng, chất lượng (nếu có)
4. Nhấn nút **Tải về** và chờ kết quả

### Lịch sử tải

- Mỗi tài khoản đều có thể xem lại lịch sử các lần tải của mình

---

## Lưu ý

- **Nên cài đặt thêm [ffmpeg](https://ffmpeg.org/download.html)** để hỗ trợ xử lý video/audio tốt nhất (thêm vào PATH).
- Nếu gặp lỗi thiếu thư viện, hãy kiểm tra lại file requirements.txt và cài lại bằng lệnh trên.
- Dự án sử dụng mã nguồn yt-dlp, tuân thủ giấy phép [Unlicense](LICENSE).

---

## 📞 Liên hệ & Hỗ trợ

<div align="center">

<a href="https://zalo.me/0858925890" target="_blank">
  <img src="https://img.shields.io/badge/Zalo-0858925890-blue?style=for-the-badge&logo=zalo" alt="Zalo" />
</a>

<br/>
<b>Hotline/Zalo:</b> <a href="https://zalo.me/0858925890">0858 925 890</a>

</div>

Nếu có thắc mắc, cần hỗ trợ hoặc muốn đóng góp, vui lòng liên hệ qua Zalo hoặc tạo issue trên GitHub.

---

**Chúc bạn sử dụng vui vẻ!**
