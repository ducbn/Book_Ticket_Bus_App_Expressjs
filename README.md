# 🚍 BOOK-TICKET-BUS-APP

## 📝 Giới thiệu

**BOOK-TICKET-BUS-APP** là một ứng dụng đặt vé xe buýt được phát triển bằng **MERN Stack** (MongoDB, Express.js, React.js, Node.js).  
Ứng dụng cho phép người dùng thực hiện các thao tác đặt vé xe, chọn chỗ ngồi, quản lý thông tin cá nhân và xác nhận thông tin đặt vé.

---

## ✅ Các chức năng chính của ứng dụng

### 🎨 Front-End (React.js)

- Trang **Đăng nhập** và **Đăng ký**.
- Hệ thống **xác thực dựa trên Token**, chỉ cho phép người dùng đã đăng ký truy cập (sử dụng `passport.js`).
- **Mã hóa mật khẩu** người dùng trước khi lưu trữ.
- Trang **Hồ sơ cá nhân**, hiển thị đầy đủ thông tin người dùng đã đăng nhập.
- **Danh sách các thành phố** cho phép người dùng chọn thành phố xuất phát và điểm đến.
- **Hiển thị danh sách các chuyến xe buýt** của nhiều nhà xe, bao gồm thông tin chi tiết về từng chuyến.
- Trang **Chọn ghế** với giao diện thân thiện, hỗ trợ chọn chỗ ngồi và nhập thông tin hành khách động.
- Trang **Xác nhận**, thu thập thông tin thẻ ghi nợ (sử dụng `react-credit-cards`).  
*Lưu ý: Ứng dụng phiên bản này không xử lý thanh toán thực tế.*
- Trang **Vé đặt thành công**, hiển thị toàn bộ thông tin hành khách cùng một mã số ID giao dịch ngẫu nhiên.

---

### 🔧 Back-End (Node.js + Express.js)

- Ứng dụng **Express.js** cho toàn bộ xử lý phía server.
- Sử dụng **MongoDB Atlas** làm hệ quản trị cơ sở dữ liệu, lưu trữ thông tin người dùng, chuyến xe, ghế ngồi và vé đặt.
- **Passport.js** được sử dụng để:
  - Xác thực người dùng qua token.
  - Mã hóa mật khẩu trước khi lưu vào database.

---

## ✅ Các chức năng

- Đăng nhập
- Đăng ký vé
- Đăng ký chỗ ngồi
- Thông tin cá nhân
- Quản lý thông tin vé
- Thêm chỗ ngồi
- Thêm vé xe
- Thanh toán (Giả lập)

---
