# Shopify 3D Theme

Theme Shopify với tính năng 3D hiện đại, tối ưu trải nghiệm người dùng và hiệu suất.

## 🚀 Tính năng

- **3D Product View**: Xem sản phẩm ở chế độ 3D tương tác
- **Responsive Design**: Tối ưu cho mọi thiết bị
- **Performance Optimized**: Tải nhanh và mượt mà
- **Modern UI/UX**: Giao diện hiện đại, dễ sử dụng

## 📋 Yêu cầu

- Node.js (phiên bản 18 trở lên)
- Yarn hoặc npm
- Shopify CLI

## 🛠️ Cài đặt

1. Clone repository:
```bash
git clone <repository-url>
cd ThemeThree
```

2. Cài đặt dependencies:
```bash
yarn install
```

3. Kết nối với Shopify store:
```bash
shopify theme dev
```

## 📁 Cấu trúc dự án

```
ThemeThree/
├── assets/          # CSS, JS, images
├── config/          # Theme settings
├── layout/          # Theme layouts
├── locales/         # Translation files
├── sections/        # Theme sections
├── snippets/        # Reusable code snippets
├── templates/       # Page templates
└── README.md
```

## 🎨 Customization

### Cấu hình theme

Chỉnh sửa các file trong thư mục `config/` để tùy chỉnh theme settings.

### Thêm sections mới

Tạo file mới trong thư mục `sections/` để thêm các sections tùy chỉnh.

## 🚀 Development

Chạy development server:

```bash
yarn dev
```

Theme sẽ tự động sync với Shopify store của bạn.

## 📦 Build

Build theme cho production:

```bash
shopify theme push
```

## 🤝 Contributing

1. Tạo nhánh mới từ `develop`
2. Commit các thay đổi
3. Tạo Pull Request

## 📝 License

[MIT License](LICENSE)

## 👨‍💻 Author

ThemeThree Team

