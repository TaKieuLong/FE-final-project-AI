# 🛒 Nền tảng E-commerce AI

## 📖 Tổng quan

E-commerce AI là một nền tảng hiện đại kết hợp chức năng thương mại điện tử truyền thống với các khả năng AI tiên tiến. Dự án này cung cấp giao diện thân thiện với người dùng để quản lý người dùng, sản phẩm và tương tác, đồng thời tận dụng AI để phân loại sản phẩm và phân tích cảm xúc.

## 🌐 Truy cập Online

Bạn có thể truy cập ứng dụng trực tiếp tại:
- **[fe-final-project-ai.vercel.app](https://fe-final-project-ai.vercel.app)**

## ✨ Tính năng

- **👤 Quản lý người dùng**
  - Tạo người dùng mới
  - Xem danh sách người dùng

- **📦 Quản lý sản phẩm**
  - Thêm sản phẩm mới với chi tiết
  - Duyệt danh sách sản phẩm
  - Xem thông tin chi tiết sản phẩm

- **🔄 Tương tác người dùng**
  - Theo dõi các hành động của người dùng (xem, thích, thêm vào giỏ hàng, mua hàng)
  - Ghi lại tất cả tương tác giữa người dùng và sản phẩm

- **🧠 Gợi ý được hỗ trợ bởi AI**
  - Tạo gợi ý sản phẩm cá nhân hóa
  - Dựa trên lịch sử và sở thích của người dùng

- **🤖 Tính năng AI**
  - 📷 Phân loại sản phẩm dựa trên hình ảnh
  - 💬 Phân tích cảm xúc từ nhận xét

## 🚀 Bắt đầu

### Cách 1: Truy cập trực tuyến
Đơn giản chỉ cần truy cập ứng dụng tại [fe-final-project-ai.vercel.app](https://fe-final-project-ai.vercel.app)

### Cách 2: Chạy cục bộ

#### Yêu cầu tiên quyết
- Trình duyệt web (Khuyến nghị Chrome, Firefox, Safari)
- Kết nối internet

#### Cài đặt
1. Sao chép kho lưu trữ:
   ```bash
   git clone https://github.com/yourusername/FE-final-project-AI.git
   ```

2. Mở `index.html` trong trình duyệt của bạn:
   ```bash
   cd FE-final-project-AI
   open index.html
   ```

## 🔧 Cách sử dụng

### Quản lý người dùng
- Điền tên người dùng và email để tạo người dùng mới
- Nhấp vào "Lấy danh sách người dùng" để xem tất cả người dùng

### Quản lý sản phẩm
- Thêm sản phẩm bằng cách cung cấp tên, giá và mô tả tùy chọn
- Xem tất cả sản phẩm hoặc xem chi tiết cho ID sản phẩm cụ thể

### Ghi nhận tương tác
- Chọn ID người dùng và ID sản phẩm
- Chọn loại tương tác (xem, thích, thêm vào giỏ hàng, mua hàng)
- Gửi để ghi lại tương tác

### Nhận gợi ý
- Nhập ID người dùng và tùy chọn danh sách ID sản phẩm
- Hệ thống sẽ cung cấp gợi ý sản phẩm cá nhân hóa

### Tính năng AI
- Tải lên hình ảnh để phân loại danh mục sản phẩm
- Nhập nhận xét để phân tích cảm xúc

## 🔌 Tham chiếu API

Ứng dụng kết nối với dịch vụ backend tại:
```
https://final-project-ai-production.up.railway.app
```

### Các endpoint:

| Endpoint | Phương thức | Mô tả |
|----------|--------|-------------|
| `/users` | GET | Lấy tất cả người dùng |
| `/users` | POST | Tạo người dùng mới |
| `/products` | GET | Lấy tất cả sản phẩm |
| `/products` | POST | Tạo sản phẩm mới |
| `/products/:id` | GET | Lấy chi tiết sản phẩm |
| `/user_interaction` | POST | Ghi lại tương tác người dùng |
| `/recommend_products` | POST | Nhận gợi ý sản phẩm |
| `/classify_image` | POST | Phân loại hình ảnh bằng AI |
| `/analyze_review` | POST | Phân tích cảm xúc nhận xét bằng AI |

## 💻 Stack công nghệ

- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5
- **Backend**: RESTful API
- **Hosting**: 
  - Frontend: Vercel
  - Backend: Railway

## 📜 Giấy phép

Dự án này được cấp phép theo Giấy phép MIT - xem tệp LICENSE để biết chi tiết.

## 🙏 Lời cảm ơn

- Bootstrap cho các thành phần UI responsive
- Vercel cho việc hosting ứng dụng frontend
- Railway cho việc hosting các dịch vụ backend

---

Làm với ❤️ cho dự án cuối kỳ E-commerce AI
