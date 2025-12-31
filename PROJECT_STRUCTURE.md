# YouTube Clone - Cấu trúc Project

## 📁 Cấu trúc thư mục

```
Youtube-Clone/
├── index.html              # File HTML chính
├── README.md              # Thông tin về project
├── PROJECT_STRUCTURE.md   # File này - mô tả cấu trúc
│
├── css/                   # Thư mục chứa các file CSS
│   └── style.css          # File CSS chính (trước đây là index.css)
│
├── js/                    # Thư mục chứa các file JavaScript
│   └── (sẵn sàng cho các file JS trong tương lai)
│
└── images/                # Thư mục chứa tất cả hình ảnh
    ├── icons/             # Icons và logos
    │   ├── menu.png
    │   ├── bell.png
    │   ├── plus.png
    │   ├── house.png
    │   ├── short-icon.webp
    │   ├── user-logo.jpg
    │   ├── YouTube-Logo-2017-present.jpg
    │   └── ... (các icon khác)
    │
    ├── thumbnails/        # Thumbnails của video
    │   ├── hq720.avif
    │   ├── hq720 (1).avif
    │   ├── hq720 (2).avif
    │   ├── hq720 (3).avif
    │   ├── hq720 (4).avif
    │   ├── hq720 (5).avif
    │   ├── v10.avif
    │   └── oar2.avif
    │
    └── shorts/            # Thumbnails của YouTube Shorts
        ├── short2.avif
        ├── short3.avif
        ├── short4.avif
        ├── short5.avif
        ├── short10.avif
        ├── short11.avif
        ├── short12.avif
        └── short13.avif
```

## 🎯 Mục đích

Cấu trúc này giúp:
- ✅ **Dễ quản lý**: Phân loại rõ ràng các loại file
- ✅ **Dễ mở rộng**: Thêm tính năng mới dễ dàng hơn
- ✅ **Chuyên nghiệp**: Tuân theo best practices trong web development
- ✅ **Hiệu suất**: Tối ưu hóa loading và caching

## 📝 Lưu ý

- Tất cả đường dẫn trong `index.html` đã được cập nhật để phù hợp với cấu trúc mới
- Thư mục `js/` đã sẵn sàng cho việc thêm JavaScript trong tương lai
- Hình ảnh được phân loại theo mục đích sử dụng (icons, thumbnails, shorts)
