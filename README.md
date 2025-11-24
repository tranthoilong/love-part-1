# Tỏ Tình Part 1

Trang web tỏ tình được xây dựng hoàn toàn bằng HTML/CSS/JS thuần, tập trung vào hiệu ứng thị giác và câu chuyện tình yêu thông qua dòng thời gian, album ảnh và các đoạn trích cảm xúc. Kho lưu trữ này giúp bạn nhanh chóng tự host hoặc điều chỉnh lời nhắn dành cho người thương.

## Điểm nhấn

- Header lãng mạn với thông điệp tuỳ chỉnh và biểu tượng trái tim động.
- Timeline các mốc kỷ niệm kết hợp hiệu ứng Animate.css và AniJS mượt mà.
- Bộ sưu tập ảnh `photopile` dạng xếp chồng, kéo/thả được trên cả desktop và mobile.
- Modal lời nhắn, nền nhạc `Altro - Epic`, hiệu ứng tuyết/vệt sáng tạo không khí đặc biệt.
- Phân tách rõ nội dung (ảnh, nhạc, script) giúp thay đổi dữ liệu cá nhân nhanh chóng.

## Công nghệ & thư viện

| Nhóm | Chi tiết |
| --- | --- |
| CSS & Font | Bootstrap 3, Animate.css, Google Fonts (Dancing Script, Lobster, Pattaya, Srisakdi) |
| JavaScript | jQuery 1.11, jQuery UI, AniJS, Photopile |
| Tài nguyên | Bộ ảnh tĩnh/gif trong `images/`, âm thanh nền `Altro - Epic` |

## Cấu trúc thư mục

```
.
├── index.html          # Trang chính với toàn bộ nội dung câu chuyện
├── public/
│   ├── css/            # Bootstrap, style tuỳ chỉnh, hiệu ứng animate & photopile
│   └── js/             # jQuery, AniJS, photopile, script tương tác
├── images/             # Hình nhân vật, timeline, album
└── Altro - Epic.mp3    # Nhạc nền (có thể thay bằng bản nhạc bạn muốn)
```

## Hướng dẫn chạy

1. Tải mã nguồn hoặc clone repository này.
2. Mở trực tiếp `index.html` bằng trình duyệt hiện đại (Chrome/Edge/Firefox).
3. Đảm bảo cho phép trình duyệt phát âm thanh tự động nếu muốn nghe nhạc nền.

> Không cần cài đặt phụ thuộc hay build step vì toàn bộ là static asset.

## Tuỳ biến nhanh

- **Thay lời nhắn:** Mở `index.html`, tìm các phần tử có class `txt` hoặc trong danh sách `.timeline` và sửa nội dung HTML.
- **Đổi ảnh:** Ghi đè file trong thư mục `images/` bằng ảnh cùng tên hoặc cập nhật đường dẫn trong HTML.
- **Đổi nhạc:** Thay file `.mp3` và cập nhật thuộc tính `src` trong thẻ `<audio>` (nếu có) hoặc script phát nhạc.
- **Màu sắc/Font:** Điều chỉnh trong `public/css/style.css` hoặc `one.css`.

## Gợi ý phát triển thêm

- Tách nội dung (timeline, album, quotes) thành JSON để dễ chỉnh sửa.
- Bổ sung service worker để chạy offline hoàn toàn trên di động.
- Thêm form bí mật để người nhận phản hồi ngay trên trang.

## Đóng góp

Đây là dự án cảm xúc cá nhân; nếu bạn muốn cải tiến hiệu ứng hoặc tối ưu code, cứ tạo pull request hoặc mở issue để cùng thảo luận.

## Thông tin liên hệ

- GitHub: [Tran Thoi Long](https://github.com/tranthoilong/tranthoilong)


# love-part-1
