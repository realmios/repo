# Kho game của NES Retro

App đọc `games.json` trong thư mục này (https://realmios.github.io/repo/nes/games.json).
Mỗi game gồm file `.nes` và ảnh bìa đặt cùng thư mục, rồi thêm một dòng vào `games.json`:

```json
[
  { "title": "Contra", "note": "Bắn súng chạy ngang", "rom": "Contra.nes", "thumb": "Contra.jpg", "ver": 1 }
]
```

- `ver`: tăng số này khi thay file game hoặc ảnh bìa để app tải lại bản mới.
- GitHub Pages cần vài phút để cập nhật sau mỗi lần commit.
