# Đội Bóng Akatsuki - Website

Website giới thiệu đội bóng Akatsuki được xây dựng bằng HTML, CSS và JavaScript thuần túy.

## 🚀 Tính năng

- **Responsive Design**: Tương thích với mọi thiết bị (desktop, tablet, mobile)
- **Modern UI/UX**: Giao diện hiện đại với hiệu ứng mượt mà
- **Thông tin đầy đủ**: Giới thiệu đội bóng và thông tin chi tiết từng thành viên
- **GitHub Pages Ready**: Sẵn sàng deploy lên GitHub Pages

## 📁 Cấu trúc dự án

```
Akatsuki/
├── index.html          # Trang chủ
├── css/
│   └── style.css       # Stylesheet chính
├── js/
│   └── script.js       # JavaScript cho tương tác
├── images/             # Thư mục chứa ảnh
│   ├── README.md       # Hướng dẫn thêm ảnh
│   ├── team-photo.jpg  # Ảnh đội bóng (cần thêm)
│   └── member*.jpg     # Ảnh các thành viên (cần thêm)
└── README.md           # File này
```

## 🎯 Nội dung website

### 1. Trang chủ

- Hero section với tên đội và ảnh đội bóng
- Slogan: "Đam mê - Tốc độ - Chiến thắng"

### 2. Giới thiệu đội bóng

- Lịch sử và tinh thần đội bóng
- Thống kê cơ bản (năm thành lập, số thành viên, số trận thắng)

### 3. Đội hình

Thông tin chi tiết 8 thành viên:

- **Nguyễn Văn A** - Thủ môn (1995)
- **Trần Văn B** - Hậu vệ trái (1997)
- **Lê Văn C** - Trung vệ (1996)
- **Phạm Văn D** - Hậu vệ phải (1998)
- **Hoàng Văn E** - Tiền vệ phòng ngự (1999)
- **Đỗ Văn F** - Tiền vệ tấn công (1997)
- **Vũ Văn G** - Tiền đạo (2000)
- **Bùi Văn H** - Tiền vệ cánh (1998)

Mỗi thành viên bao gồm: Tên, năm sinh, vị trí, sở thích, kỹ năng và ảnh cá nhân.

### 4. Liên hệ

- Email, điện thoại và địa chỉ đội bóng

## 🛠️ Cài đặt và sử dụng

### 1. Clone repository

```bash
git clone <repository-url>
cd Akatsuki
```

### 2. Thêm ảnh

- Thêm ảnh đội bóng và ảnh các thành viên vào thư mục `images/`
- Xem hướng dẫn chi tiết trong `images/README.md`

### 3. Chạy local

- Mở file `index.html` trực tiếp trong trình duyệt
- Hoặc sử dụng Live Server extension trong VS Code

## 🌐 Deploy lên GitHub Pages

### Cách 1: Từ Settings

1. Push code lên GitHub repository
2. Vào **Settings** > **Pages**
3. Chọn source: **Deploy from a branch**
4. Chọn branch: **main** và folder: **/ (root)**
5. Click **Save**
6. Website sẽ có sẵn tại: `https://<username>.github.io/<repository-name>`

### Cách 2: Tự động với GitHub Actions

Repository đã cấu hình sẵn để tự động deploy khi push code.

## 🎨 Tùy chỉnh

### Thay đổi màu sắc

Chỉnh sửa các biến CSS trong `css/style.css`:

```css
/* Màu chủ đạo */
background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);

/* Màu accent */
color: #667eea;
```

### Thêm/sửa thành viên

Chỉnh sửa trong file `index.html` tại section `.team-grid`

### Thay đổi thông tin đội

Chỉnh sửa trong section `.about` và `.hero`

## 📱 Tương thích

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Mobile, Tablet, Desktop
- ✅ Các độ phân giải từ 320px trở lên

## 🤝 Đóng góp

1. Fork repository
2. Tạo branch mới: `git checkout -b feature/AmazingFeature`
3. Commit thay đổi: `git commit -m 'Add some AmazingFeature'`
4. Push lên branch: `git push origin feature/AmazingFeature`
5. Tạo Pull Request

## 📄 License

Dự án được phát hành dưới MIT License. Xem file `LICENSE` để biết thêm chi tiết.

## 📞 Liên hệ

- **Email**: akatsuki.fc@gmail.com
- **Website**: [Đội Bóng Akatsuki](https://akatsuki-fc.github.io)

---

⚽ **Akatsuki FC** - Đam mê, Tốc độ, Chiến thắng! ⚽
