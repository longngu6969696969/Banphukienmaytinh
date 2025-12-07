# README.md - LLHComputer Website

```
HoTen_MSSV_LLHComputer.zip/
├── 📄 Báo cáo.docx             (Nguyễn Thế Linh - 1120090075)
├── 🎨 Presentation.pptx        (Lê Tiến Hưng - 1120090059)
├── 🌐 Source Code/             (Nguyễn Đức Long - 1120090081)
│   ├── index.html
│   ├── sanpham.html
│   ├── gioithieu.html
│   ├── lienhe.html
│   ├── login.html
│   ├── register.html
│   ├── style.css
│   ├── loginregister.css
│   ├── README.md (file này)
└── └── /image/ (chứa 50+ hình ảnh)
```

---

# 🖥️ LLHComputer - Website Bán Linh Kiện Máy Tính

## 📋 Thông Tin Nhóm
**Lớp học phần:** D20CN01  
**Giáo viên:** Vũ Thị Tuyết Lan  
**Môn học:** Nhập môn công nghệ phần mềm

### 👥 Thành Viên Nhóm:
| STT |       Họ và Tên     |    MSSV    | Công việc                       |
|-----|---------------------|------------|---------------------------------|
|  1  | **Nguyễn Thế Linh** | 1120090075 | 📄 Viết báo cáo Word            |
|  2  | **Nguyễn Đức Long** | 1120090081 | 🌐 Lập trình website (HTML/CSS) |
|  3  | **Lê Tiến Hưng**    | 1120090059 | 🎨 Thiết kế PowerPoint          |

## 🎯 Giới Thiệu Dự Án
**LLHComputer** là website thương mại điện tử chuyên cung cấp linh kiện máy tính, PC Gaming, và thiết bị công nghệ cao. Được phát triển hoàn toàn bằng HTML5 và CSS3, website mang đến trải nghiệm mua sắm trực tuyến chuyên nghiệp và thân thiện với người dùng.

## ✨ Tính Năng Nổi Bật
✅ **5 trang web hoàn chỉnh** với đầy đủ chức năng  
✅ **Responsive Design** - Tối ưu cho Mobile, Tablet, Desktop  
✅ **Giao diện hiện đại** với màu sắc thương hiệu nhất quán  
✅ **Navigation thông minh** - Dễ dàng di chuyển giữa các trang  
✅ **Form validation** sử dụng HTML5  

## 📱 Các Trang Chính

### 1. **Trang Chủ (index.html)**
- Video banner giới thiệu tự động phát
- Hiển thị sản phẩm nổi bật (scroll ngang)
- Danh mục sản phẩm đa dạng
- Tin tức công nghệ mới nhất

### 2. **Trang Sản Phẩm (sanpham.html)**
- Hệ thống lọc đa tiêu chí: Danh mục, hãng sản xuất, khoảng giá
- Hiển thị lưới sản phẩm responsive
- Phân trang dễ sử dụng
- Hiển thị trạng thái tồn kho

### 3. **Trang Giới Thiệu (gioithieu.html)**
- Lịch sử hình thành công ty
- Các dịch vụ chính: PC Gaming, Workstation, PC văn phòng
- Sứ mệnh, tầm nhìn và giá trị cốt lõi
- Hình ảnh minh họa trực quan

### 4. **Trang Liên Hệ (lienhe.html)**
- Form liên hệ với validation
- Google Maps nhúng trực tiếp
- FAQ dạng accordion
- Thông tin giờ làm việc chi tiết

### 5. **Đăng Nhập / Đăng Ký**
- Giao diện form hiện đại
- Validation cơ bản với HTML5
- Thiết kế thân thiện người dùng

## 🛠️ Công Nghệ Sử Dụng
- **HTML5**: Semantic tags, form validation
- **CSS3**: Flexbox, Grid, Media Queries, Variables

## 🎨 Thiết Kế & UI/UX
- **Màu chủ đạo**: Xanh (#2b387a) + Vàng (#ffcc00)
- **Font chữ**: Segoe UI, Tahoma, sans-serif
- **Hình ảnh**: Tối ưu hóa, có đầy đủ alt text

## 📁 Cấu Trúc File
```
Source Code/
├── HTML Files/
│   ├── index.html          # Trang chủ
│   ├── sanpham.html        # Trang sản phẩm
│   ├── gioithieu.html      # Giới thiệu công ty
│   ├── lienhe.html         # Liên hệ + FAQ
│   ├── login.html          # Đăng nhập
│   └── register.html       # Đăng ký
│
├── CSS Files/
│   ├── style.css           # CSS chính 
│   └── loginregister.css   # CSS riêng cho login/register
│
├── Assets/
│   └── image/              # 50+ hình ảnh sản phẩm, logo, banner
│
└── README.md               # Tài liệu này
```

## 🚀 Cách Chạy Website
1. **Tải toàn bộ file** về máy tính
2. **Mở file `index.html`** bằng bất kỳ trình duyệt nào:
   - Google Chrome
   - Firefox
   - Microsoft Edge
   - Safari
3. **Website sẽ chạy ngay lập tức** - Không cần cài đặt server

## 📱 Responsive Testing
Website đã được test trên:
- 📱 **Mobile**: iPhone, Android (360px - 600px)
- 📟 **Tablet**: iPad (768px - 1024px)
- 🖥️ **Desktop**: (1025px+)

## ✅ Đã Kiểm Tra
- [x] Tất cả link hoạt động
- [x] Form validation hoạt động
- [x] Responsive trên tất cả thiết bị
- [x] Hình ảnh có đầy đủ alt text
- [x] Code sạch, có comment

## 🔧 Khó Khăn & Giải Pháp
| Khó Khăn                      | Giải Pháp                                   |
|-------------------------------|---------------------------------------------|
| Responsive cho nhiều thiết bị | Sử dụng Media Queries + Flexbox/Grid        |
| Tổ chức CSS cho 5 trang       | Modular CSS, tách file riêng                |
| Tương thích trình duyệt       | Sử dụng CSS tiêu chuẩn, test đa trình duyệt |
| Quản lý nhiều hình ảnh        | Tổ chức thư mục `image/` có cấu trúc        |

## 🏆 Thành Tựu Đạt Được
- **100% code tự viết** (không dùng template)
- **5 trang web hoàn chỉnh** với đầy đủ tính năng
- **Website chuyên nghiệp** có thể sử dụng thực tế
- **Hiệu suất cao**: Load nhanh, nhẹ, tối ưu
- **Code dễ bảo trì**: Có cấu trúc rõ ràng

## 📈 Hướng Phát Triển Tương Lai
1. **Thêm JavaScript** để tăng tính tương tác
2. **Kết nối Backend** (PHP/Node.js) để xử lý form
3. **Thêm giỏ hàng** và hệ thống thanh toán
4. **Tích hợp CMS** để quản lý sản phẩm
5. **SEO Optimization** để tăng thứ hạng tìm kiếm

## 📞 Liên Hệ Nhóm
Nếu có thắc mắc về dự án, vui lòng liên hệ qua:
- **Nguyễn Đức Long** (Lập trình viên): Qua giáo viên trường / 0368399829 Zalo
- **Nguyễn Thế Linh** (Báo cáo): Qua giáo viên trường  
- **Lê Tiến Hưng** (Presentation): Qua giáo viên trường

## 📄 License
Bài tập môn học ≠ Sản phẩm thương mại
Nên sẽ không cần copyright nghiêm túc
Nhưng nếu muốn Liên hệ có thể liên hệ qua thông tin ở trên 

---
**"Từ code đến thành phẩm - Cam kết chất lượng từng dòng code"**  
*LLHComputer Team*

---

## 📝 Ghi Chú Cho Giảng Viên
- Website được phát triển **100% bằng HTML/CSS thuần**
- **Không sử dụng bất kỳ framework hay thư viện nào**
- Tất cả hiệu ứng đều được thực hiện bằng **CSS thuần**
- Mọi hình ảnh đều có **alt text đầy đủ** cho accessibility
- Code có **comment rõ ràng** để dễ theo dõi

**Chân thành cảm ơn cô Vũ Thị Tuyết Lan đã hướng dẫn chúng em trong môn học này!** 🙏