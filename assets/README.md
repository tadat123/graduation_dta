# 📁 Thư mục Assets — Hành Lang Ký Ức

## Cấu trúc thư mục

```
assets/
├── images/
│   ├── invite.jpg          ← 🎓 Ảnh thiệp mời (POPUP cuối hành trình)
│   ├── milestone_1.jpg     ← Ảnh cột mốc 1 (Khởi Đầu)
│   ├── milestone_2.jpg     ← Ảnh cột mốc 2 (Thử Thách)
│   ├── milestone_3.jpg     ← Ảnh cột mốc 3 (Trưởng Thành)
│   ├── milestone_4.jpg     ← Ảnh cột mốc 4 (Đỉnh Cao)
│   └── milestone_5.jpg     ← Ảnh cột mốc 5 (Tốt Nghiệp)
│
└── music/
    └── background.mp3      ← 🎵 Nhạc nền (tự động phát khi bắt đầu)
```

## Hướng dẫn

### 🖼️ Ảnh thiệp mời (`invite.jpg`)
- Đây là ảnh xuất hiện trong **popup** ở cuối hành trình
- Định dạng khuyên dùng: **JPG hoặc PNG**
- Kích thước lý tưởng: **800×600px** hoặc tỉ lệ 4:3
- Nếu chưa có ảnh, web sẽ hiển thị placeholder tự động

### 🎵 Nhạc nền (`background.mp3`)
- File nhạc sẽ **tự phát** khi người dùng nhấn "Bắt Đầu Hành Trình"
- Có nút 🎵 góc trên phải để **tắt/bật** nhạc
- Định dạng: **MP3** (hoặc OGG cũng được)
- Khuyên dùng nhạc nhẹ nhàng, instrumental, khoảng 3-5 phút
- Gợi ý: Tìm trên [pixabay.com/music](https://pixabay.com/music/) (miễn phí)

## Lưu ý
- Nếu file không tìm thấy, web vẫn chạy bình thường (graceful fallback)
- Chạy qua local server (`http-server`) thay vì mở file trực tiếp để tránh lỗi CORS
