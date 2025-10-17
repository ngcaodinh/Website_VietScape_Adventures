# VietScape Adventures ✈️

Website du lịch khám phá và mạo hiểm tại Việt Nam - Nơi bắt đầu những hành trình phiêu lưu đáng nhớ!

## 📋 Tổng Quan Dự Án

VietScape Adventures là website chuyên về dịch vụ du lịch mạo hiểm tại Việt Nam, tập trung vào các hoạt động như:
- 🏔️ Trekking và leo núi
- 🤿 Lặn biển và khám phá đại dương
- 🕳️ Khám phá hang động
- 🌄 Các trải nghiệm phiêu lưu độc đáo

## 🎨 Phong Cách Thiết Kế

### Màu Sắc Chủ Đạo
- **Xanh lá cây đậm** (#228B22) - Núi rừng và thiên nhiên hoang dã
- **Xanh dương** (#1E90FF) - Biển cả và sự tươi mát
- **Vàng cam** (#FFD700) - Năng lượng và lời kêu gọi hành động

### Typography
- **Heading**: Montserrat (Bold) - Mạnh mẽ, hiện đại
- **Body**: Lato - Dễ đọc, sạch sẽ

## 💻 Công Nghệ Sử Dụng

- **Framework**: Bootstrap 5
- **HTML5 & CSS3**
- **JavaScript** (Vanilla JS cho các hiệu ứng)
- **Google Fonts**: Montserrat, Lato
- **Icons**: Bootstrap Icons / Font Awesome
- **Hình ảnh**: Unsplash, Pexels (miễn phí bản quyền)

## 📱 Tính Năng Nổi Bật

### ✅ Responsive Design
- Mobile-first approach
- Tối ưu cho mọi thiết bị (mobile, tablet, desktop)
- Sử dụng breakpoints của Bootstrap (xs, sm, md, lg, xl)

### ✅ Bootstrap Components Được Áp Dụng
- Navbar với dropdown và form tìm kiếm
- Carousel cho hero sections
- Cards với hover effects
- Offcanvas cho bộ lọc mobile
- Tabs và Accordion
- Modal cho forms
- Pagination
- Breadcrumb navigation
- Scrollspy
- List Group & Badges
- Tables (striped, hover)
- Form controls (input, select, range)

### ✅ Tối Ưu Hóa
- Tốc độ tải trang nhanh
- SEO cơ bản (meta tags, alt text)
- Lazy loading cho hình ảnh
- Clean code và comments

## 📄 Cấu Trúc Trang

### 1. Trang Chủ (index.html)
**Mục đích**: Tạo ấn tượng đầu tiên, giới thiệu tours nổi bật

**Nội dung chính**:
- Hero section với carousel full-screen
- Tour nổi bật (grid cards)
- Lý do chọn VietScape
- Footer với liên kết social

**Components Bootstrap**:
- Navbar transparent → solid on scroll
- Carousel fade với CTA buttons
- Grid system (responsive)
- Cards với shadow và hover effects
- Flexbox utilities

---

### 2. Danh Sách Tour (tours.html)
**Mục đích**: Tìm kiếm, lọc và so sánh tours

**Nội dung chính**:
- Bộ lọc thông minh (sidebar/offcanvas)
- Danh sách tour với cards
- Pagination

**Components Bootstrap**:
- Offcanvas cho bộ lọc mobile
- Form controls (checkbox, range, select)
- Grid layout responsive
- Cards với giá và CTA
- Pagination

---

### 3. Chi Tiết Tour (tour-detail.html)
**Mục đích**: Thông tin chi tiết tour, thuyết phục đặt tour

**Nội dung chính**:
- Breadcrumb navigation
- Gallery ảnh tour
- Tabs: Lịch trình, Dịch vụ, Đánh giá
- Box đặt tour sticky
- Form đặt tour

**Components Bootstrap**:
- Breadcrumb
- Tabs navigation
- Accordion cho lịch trình
- Table cho chi tiết dịch vụ
- Modal cho xác nhận đặt tour
- Form controls

---

### 4. Cẩm Nang Du Lịch (blog.html)
**Mục đích**: Cung cấp nội dung hữu ích, tăng SEO

**Nội dung chính**:
- Danh sách bài viết
- Sidebar với bài mới nhất
- Tags và categories
- Pagination

**Components Bootstrap**:
- Horizontal cards
- Badges cho tags
- List group cho sidebar
- Grid layout (8-4 columns)
- Blockquote (trong chi tiết bài)

---

### 5. Về Chúng Tôi (about.html)
**Mục đích**: Xây dựng niềm tin, giới thiệu đội ngũ

**Nội dung chính**:
- Câu chuyện thương hiệu
- Đội ngũ hướng dẫn viên
- Form liên hệ
- Social media links

**Components Bootstrap**:
- Scrollspy navigation
- Figure cho team members
- Form liên hệ đầy đủ
- Button group cho social links
- Sections với padding utilities

## 🚀 Hướng Dẫn Cài Đặt

### Yêu Cầu
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Không cần server (website tĩnh)

### Cài Đặt
# Clone repository
git clone https://github.com/yourusername/vietscape-adventures.git

# Di chuyển vào thư mục dự án
cd vietscape-adventures

# Mở file index.html bằng trình duyệt
Nhấn đúp vào file index.html

### Cấu Trúc Thư Mục
```
vietscape-adventures/
│
├── index.html              # Trang chủ
├── tours.html              # Danh sách tour
├── tour-detail.html        # Chi tiết tour
├── blog.html               # Cẩm nang du lịch
├── about.html              # Về chúng tôi
│
├── css/
│   ├── bootstrap.min.css   # Bootstrap 5
│   └── custom.css          # CSS tùy chỉnh
│
├── js/
│   ├── bootstrap.bundle.min.js
│   └── custom.js           # JavaScript tùy chỉnh
│
├── images/
│   ├── hero/               # Ảnh hero sections
│   ├── tours/              # Ảnh tours
│   ├── blog/               # Ảnh blog
│   └── team/               # Ảnh đội ngũ
│
└── README.md               # File này


## 📱 Responsive Breakpoints

| Breakpoint | Kích thước | Thiết bị |
|------------|------------|----------|
| xs | <576px | Mobile nhỏ |
| sm | ≥576px | Mobile lớn |
| md | ≥768px | Tablet |
| lg | ≥992px | Desktop nhỏ |
| xl | ≥1200px | Desktop lớn |


## 🤝 Đóng Góp

Mọi đóng góp đều được chào đón! Vui lòng:
1. Fork repository
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📝 License

Dự án này được phát hành dưới [MIT License](LICENSE).

## 👨‍💻 Tác Giả

**VietScape Development Team**
    ✨ Nguyễn Cao Đỉnh
    ✨ Nguyễn Hải Đăn

**⭐ Nếu bạn thấy dự án hữu ích, đừng quên để lại một star!**
