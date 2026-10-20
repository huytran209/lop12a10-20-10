# 20/10 — Những Bông Hoa Của 12A10 (bản không ảnh)

Website tĩnh chúc mừng 20/10 dành cho lớp 12A10. Bản này đã gỡ toàn bộ ảnh chụp, ảnh gallery, trình xem ảnh và tài nguyên hình ảnh. Hình minh họa ở đầu trang được tạo bằng CSS và ký tự trang trí, không dùng tệp ảnh. Tệp âm thanh `Chuyện rằng — Thịnh Suy` bạn cung cấp được giữ trong dự án.

## Tính năng

- Màn hình mở quà và giao diện pastel responsive.
- Phong thư tương tác và lá thư chúc mừng.
- Trình phát nhạc với phát/tạm dừng, thanh thời gian, tua bài, âm lượng và thông báo lỗi tải nhạc.
- Đủ 20 lời chúc cá nhân hóa; tìm kiếm và lọc theo chủ đề.
- Vườn 20 bông hoa tương tác.
- Bói vui tạo thông điệp ngẫu nhiên.
- Pháo hoa Canvas có nút bật/tắt, tự dừng và hỗ trợ giảm chuyển động.
- Không dùng ảnh raster, thẻ `<img>`, gallery hoặc lightbox.

## Cấu trúc thư mục

```text
lop12a10/
├── index.html
├── styles.css
├── script.js
├── README.md
├── .nojekyll
└── assets/
    └── audio/
        └── chuyen-rang.m4a
```

## Chạy thử

1. Giải nén ZIP.
2. Mở `index.html` bằng Chrome hoặc Edge.
3. Nhấn **Mở món quà 20/10**. Đây là thao tác của người dùng để trình duyệt cho phép bắt đầu phát nhạc.
4. Nếu nhạc không chạy khi mở tệp cục bộ, thử qua GitHub Pages hoặc chạy website bằng máy chủ cục bộ. Trình duyệt di động thường chặn autoplay nếu chưa có thao tác của người dùng.

## Cập nhật repository GitHub Pages hiện tại

1. Giải nén ZIP ra một thư mục.
2. Mở repository `lop12a10` trên GitHub.
3. Chọn **Add file → Upload files**.
4. Tải các tệp bên trong thư mục đã giải nén lên **thư mục gốc** của repository, bao gồm `index.html`, `styles.css`, `script.js`, `README.md`, `.nojekyll` và thư mục `assets`.
5. Nếu GitHub hỏi ghi đè `index.html` hoặc `README.md`, chấp nhận để dùng bản mới; nhớ giữ nguyên cấu trúc `assets/audio/chuyen-rang.m4a`.
6. Nhấn **Commit changes**, đợi GitHub Pages triển khai lại rồi mở website và nhấn `Ctrl + F5`.

Đường dẫn nhạc phải đúng chính xác là `assets/audio/chuyen-rang.m4a`. Không tải riêng `index.html`, vì khi đó CSS, JavaScript và tệp nhạc sẽ thiếu.

## Trình phát nhạc

Âm thanh dùng HTML `<audio>` và tệp AAC trong vỏ M4A/MP4, định dạng đã đọc được trong bước kiểm tra cục bộ. Nhạc không tự chạy ngay khi tải trang; nó được gọi sau khi người xem bấm mở quà hoặc nhấn nút phát. Khi đưa lên GitHub, hãy kiểm tra nhạc có phát được trên thiết bị thực tế hay không.

## Trạng thái bàn giao

- **Đã tạo:** bản website không ảnh và gói ZIP.
- **Đã kiểm tra tĩnh:** không còn thẻ `<img>`, không còn đường dẫn `gallery`, `lightbox` hoặc `og:image`; mã nguồn vẫn giữ nguyên danh sách 20 người và các tính năng tương tác không phụ thuộc ảnh.
- **Đã kiểm tra tệp nhạc:** tệp M4A có luồng âm thanh AAC stereo 44.1 kHz, thời lượng khoảng 4 phút 37 giây; bộ giải mã cục bộ đọc được tệp.
- **Chưa xác minh trực tiếp trên GitHub Pages sau khi tải lên:** cần commit bản này vào repository và thử trên URL thực tế.
