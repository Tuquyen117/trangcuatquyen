# Portfolio - Trương Hà Tú Quyên

## 🌟 Giới Thiệu
Đây là một website portfolio chuyên nghiệp hiện đại dành cho Trương Hà Tú Quyên, chuyên gia về Đồ họa Kỹ thuật số. Portfolio được thiết kế với các animations kiểu Apple, hỗ trợ Dark/Light theme, và responsive design tối ưu.

## ✨ Tính Năng Nổi Bật

### 🌓 Chế Độ Tối/Sáng Hiện Đại
- **Nút thay đổi theme** nằm ở góc trên cùng bên phải của trang
- **Chế độ sáng (Light)**: Giao diện trắng sạch với màu hồng chủ đạo tươi sáng
- **Chế độ tối (Dark)**: Giao diện xanh đen xen lẫn màu hồng nhẹ nhàng cho mắt
- **Lưu trữ tự động**: Lựa chọn của bạn sẽ được lưu trong Local Storage

### 🎬 Animations Kiểu Apple
- **Scroll Reveal Animations**: Các phần tử xuất hiện mượt mà khi cuộn trang
- **Smooth Transitions**: Chuyển cảnh mượt mà giữa các trạng thái
- **Floating Effects**: Icon và phần tử chính động
- **Parallax Effects**: Hiệu ứng parallax trên hero section
- **Cubic Bezier Curves**: Animations chuyên nghiệp như Apple

### 📱 Responsive Design Tuyệt Vời
- **Desktop**: Bố cục tối ưu với Grid layout
- **Tablet**: Điều chỉnh kích thước font và spacing thích hợp
- **Mobile**: Hiển thị đẹp trên tất cả kích thước màn hình
- **Using CSS Clamp**: Kích thước font co giãn dệt hợp lý

### 🎯 Màu Chủ Đạo: Hồng
- **Light Theme**: #ec4899 (Hồng sáng)
- **Dark Theme**: #f472b6 (Hồng nhẹ nhàng)
- Gradient tuyệt đẹp từ hồng đậm đến hồng nhạt

## 📋 Nội Dung Chính

1. **Hero Section**: Giới thiệu ấn tượng với tên và chuyên ngành
2. **About**: Mô tả kinh nghiệm chuyên môn
3. **Achievements**: 
   - 16 bài viết Q1 ✓
   - 2 bằng sáng chế ✓
4. **Projects**: 3 dự án chính
   - 5G Technology 📡
   - 6G Vision 🚀
   - AI Automation 🤖
5. **Research Timeline**: Công trình nghiên cứu từ 2017-2025
   - 18 bài báo Q1 (2 bài/năm)
   - Timeline trực quan
   - Hover animations
6. **Interests**: Sở thích và đam mê
   - Vẽ Tranh & Thiết Kế 🎨
   - Truyện Tranh 2D 📚
   - Sáng Tạo Công Nghệ 💡

## 🚀 Cách Sử Dụng

### Cách 1: Mở file HTML trực tiếp
```bash
# Mở file trong trình duyệt
open index.html
# hoặc
firefox index.html
```

### Cách 2: Dùng Live Server (VS Code) - Khuyến nghị ⭐
1. Cài đặt extension "Live Server"
2. Chuột phải vào `index.html` → "Open with Live Server"
3. Trình duyệt sẽ tự mở với hot reload

### Cách 3: Sử dụng Python
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Sau đó truy cập: `http://localhost:8000`

### Cách 4: Sử dụng Node.js
```bash
# Cài đặt http-server
npm install -g http-server

# Chạy
http-server
```

## 📁 Cấu Trúc Dự Án

```
trangcuatquyen/
├── index.html          # File HTML chính (Semantic HTML5)
├── styles.css          # File CSS với animations & themes
├── README.md           # Hướng dẫn sử dụng (tệp này)
└── .gitignore          # Git ignore file
```

## 🛠️ Công Nghệ Sử Dụng

- **HTML5**: Semantic markup, accessibility
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS Gradients
  - CSS Animations & Transitions
  - CSS Custom Properties (Variables)
  - Media Queries
- **JavaScript**: 
  - Intersection Observer API (Scroll animations)
  - LocalStorage (Theme persistence)
  - Event listeners
- **Responsive**: Mobile-first approach dengan clamp()

## 🎨 Hệ Thống Màu Sắc

### Light Theme (Sáng mặc định)
| Yếu tố | Màu | Mã Hex |
|--------|-----|--------|
| Nền chính | Trắng | #ffffff |
| Nền phụ | Xám nhạt | #f5f5f5 |
| Text chính | Đen | #1a1a1a |
| Text phụ | Xám | #666666 |
| Accent (Chính) | Hồng | #ec4899 |
| Accent (Hover) | Hồng đậm | #db2777 |

### Dark Theme (Tối)
| Yếu tố | Màu | Mã Hex |
|--------|-----|--------|
| Nền chính | Xanh đen sâu | #0f172a |
| Nền phụ | Xanh đen | #1e293b |
| Text chính | Trắng lạnh | #f1f5f9 |
| Text phụ | Xanh xám | #cbd5e1 |
| Accent (Chính) | Hồng sáng | #f472b6 |
| Accent (Hover) | Hồng nóc | #fb7185 |

## 🎭 Animations Được Sử Dụng

1. **fadeInUp**: Fade in với di chuyển lên
2. **float**: Icon nổi nhẹ nhàng
3. **pulse**: Nhác nhác nhẹ nhàng (pulse effect)
4. **slideInFromLeft**: Trượt vào từ trái
5. **scrollReveal**: Hiệu ứng Intersection Observer

## ⌚ Hiệu Suất & Tối Ưu Hóa

- ✅ Hỗ trợ `prefers-reduced-motion` (Accessibility)
- ✅ Hỗ trợ `prefers-contrast` (High contrast mode)
- ✅ Tối ưu hóa cho in ấn
- ✅ Lazy loading ready
- ✅ Performance optimized CSS

## 📱 Hỗ Trợ Thiết Bị

| Thiết bị | Trình duyệt | Phiên bản |
|---------|-----------|---------|
| Desktop | Chrome | 90+ |
| Desktop | Firefox | 88+ |
| Desktop | Safari | 14+ |
| Desktop | Edge | 90+ |
| Mobile | Chrome Mobile | 90+ |
| Mobile | Firefox Mobile | 88+ |
| Mobile | Safari iOS | 14+ |
| Tablet | Tất cả | Hỗ trợ đầy đủ |

## 📊 Kích Thước & Breakpoints

```css
/* Mobile First */
Mặc định: < 360px
Small: 360px - 480px
Mobile: 480px - 768px
Tablet: 768px - 1024px
Desktop: 1024px+
```

## ✏️ Tùy Chỉnh

### Thay đổi thông tin cá nhân
Chỉnh sửa `index.html`:
- **Tên**: Dòng 44 - `<h1 class="hero-title">`
- **Chuyên ngành**: Dòng 45 - `<p class="hero-subtitle">`
- **Icon dự án**: Thay đổi emoji trong project cards
- **Nội dung timeline**: Chỉnh sửa các phần `<h4>` trong `.timeline-content`

### Thêm dự án mới
1. Nhân bản một `.project-card` trong phần Projects
2. Cập nhật icon, tên, và mô tả
3. CSS sẽ tự responsive

### Thay đổi màu sắc
Chỉnh sửa biến CSS trong `styles.css` dòng 1-22:
```css
html {
    --accent-color: #ec4899;        /* Nút thay đổi vào đây */
    --accent-hover: #db2777;        /* Hover effect */
    --accent-light: #fbcfe8;        /* Light variant */
}
```

### Thêm timeline mới
1. Nhân bản `.timeline-year` section
2. Cập nhật năm và các items
3. Styling sẽ tự apply

## 🐛 Troubleshooting

| Vấn đề | Giải pháp |
|-------|----------|
| Theme không lưu | Kiểm tra LocalStorage có enabled không |
| Animations chậm | Tắt effects nặng hoặc dùng `prefers-reduced-motion` |
| Responsive không hoạt động | Kiểm tra viewport meta tag ở `<head>` |
| Font lạ | Đảm bảo system fonts được cài đặt |

## 📚 Tài liệu Tham Khảo

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)
- [Web.dev by Google](https://web.dev/)
- [CSS Tricks](https://css-tricks.com/)

## 📝 License

Tự do sử dụng cho mục đích cá nhân và thương mại.
© 2024 Trương Hà Tú Quyên

---

**Xây dựng bởi**:  UI/UX
**Ngày tạo**: 2024
**Phiên bản**: 2.0 (với Apple-style animations)
**Last Updated**: May 5, 2026