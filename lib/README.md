# Bài Tập Nâng Cao – Lab F2

* **Họ và tên:** Trương Phước Sang
* **MSSV:** 221A010861
* **Môn học:** Lập trình trên các thiết bị di động

---

## Các bài nâng cao đã thực hiện:

### 1. NC1: Chế độ tối (Dark/Light Theme)
* **Mô tả tính năng:** Thêm tùy chọn chuyển đổi linh hoạt trực tiếp trên giao diện giữa chế độ sáng (Light Mode) và chế độ tối (Dark Mode).
* **Cách triển khai:** 
  * Cấu hình đồng thời `theme` và `darkTheme` kèm theo `ThemeMode` quản lý trong trạng thái của `MyApp`.
  * Bổ sung nút bấm icon đổi giao diện (biểu tượng sáng/tối) ngay trên thanh tiêu đề của `HeaderBanner` để người dùng dễ dàng thao tác trực tiếp.

### 2. NC4: Màn hình Đăng ký tài khoản (RegisterPage)
* **Mô tả tính năng:** Xây dựng thêm một màn hình đăng ký phụ hoàn chỉnh để người dùng có thể điều hướng qua lại từ trang đăng nhập.
* **Cách triển khai:** 
  * Tạo class `RegisterPage` với các ô nhập liệu tương tự (Họ tên, MSSV, Mật khẩu).
  * Sử dụng `Navigator.push()` khi người dùng bấm vào nút "Đăng ký" ở trang đăng nhập để chuyển màn hình, và dùng `Navigator.pop()` để quay lại khi hoàn tất.