# 20/10 — Những Bông Hoa Của 12A10 (bản không ảnh, đã sửa nhạc)

Website tĩnh chúc mừng 20/10 dành cho lớp 12A10. Không dùng ảnh chụp, gallery hay tệp ảnh. Hình trang trí được tạo bằng CSS và ký tự.

## Các tệp cần có

```text
lop12a10-20-10/
├── index.html
├── styles.css
├── script.js
├── chuyen-rang.mp3
├── .nojekyll
└── README.md
```

**Quan trọng:** `chuyen-rang.mp3` nằm ngay cạnh `index.html`, không nằm trong thư mục `assets`.

## Cập nhật website trên GitHub Pages

1. Tải ZIP và giải nén.
2. Mở repository `huytran209/lop12a10-20-10`.
3. Chọn **Add file → Upload files**.
4. Tải toàn bộ các tệp bên trong thư mục giải nén vào thư mục gốc repository.
5. Ghi đè `index.html`, `styles.css`, `script.js` và `README.md` nếu GitHub hỏi; đảm bảo `chuyen-rang.mp3` có mặt ở thư mục gốc.
6. Nhấn **Commit changes**.
7. Đợi GitHub Pages cập nhật. Mở `https://huytran209.github.io/lop12a10-20-10/`, sau đó nhấn `Ctrl + F5`.

## Kiểm tra đường dẫn nhạc

Mở trực tiếp `https://huytran209.github.io/lop12a10-20-10/chuyen-rang.mp3`. Nếu tệp được phát hoặc tải xuống, đường dẫn MP3 tồn tại. Sau đó quay lại website và bấm **Mở món quà 20/10** hoặc nút phát trong phần **Âm nhạc**.

Trình phát dùng HTML `<audio>` với nguồn `chuyen-rang.mp3` và loại `audio/mpeg`. Nó có nút phát/tạm dừng, tua bài, âm lượng, hiển thị thời lượng và thông báo khi trình duyệt không tải được tệp. Trình duyệt có thể chặn tự phát, nên âm thanh được gọi sau thao tác của người xem.

## Trạng thái kiểm tra

- Mã nguồn được cấu hình để dùng `chuyen-rang.mp3` ở thư mục gốc.
- Tệp MP3 đã được đóng gói và kiểm tra giải mã cục bộ.
- Mã JavaScript được rà soát cú pháp và các đường dẫn tương đối.
- Chưa thể xác nhận triển khai trực tuyến cho đến khi commit các tệp này vào repository và thử lại trang GitHub Pages.
