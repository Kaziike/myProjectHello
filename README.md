1️⃣ body – Toàn bộ trang web
body {
  margin: 0;
  font-family: "Segoe UI", Tahoma, sans-serif;
  background: #ffffff;
  color: #333;
}


📌 Tác dụng

margin: 0; → bỏ khoảng trắng mặc định của trình duyệt

font-family → chọn font chữ (Segoe UI → Tahoma → sans-serif)

background → màu nền trắng

color → màu chữ xám đậm

👉 Áp dụng cho toàn bộ trang
___________________________________________________________________________________________
2️⃣ .header – Phần đầu trang (banner)
.header {
  background: url('C:/Users/kaziila/Downloads/background-trang.jpg') center/cover no-repeat;
  padding: 100px;
  color: #ffffff;
}


📌 Tác dụng

background: url(...) → ảnh nền

center/cover → ảnh nằm giữa & phủ kín

no-repeat → không lặp ảnh

padding: 100px → tạo khoảng trống xung quanh nội dung

color: #fff → chữ màu trắng
___________________________________________________________________________________________

3️⃣ .profile – Khối thông tin cá nhân
.profile {
  display: flex;
  align-items: center;
  gap: 20px;
  background: #ffffff;
  padding: 20px;
  border-radius: 16px;
  max-width: 1100px;
  margin: -80px auto 30px;
  box-shadow: 0 10px 30px rgba(0,0,0,.1);
}


📌 Tác dụng

display: flex → sắp xếp ngang

align-items: center → căn giữa theo chiều dọc

gap → khoảng cách giữa avatar & text

border-radius → bo góc

margin: -80px auto → đẩy khối đè lên header (hiệu ứng nổi)

box-shadow → đổ bóng
___________________________________________________________________________________________
4️⃣ .avatar – Ảnh đại diện
.avatar {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  border: 5px solid #fff;
  object-fit: cover;
}


📌 Tác dụng

border-radius: 50% → ảnh tròn

object-fit: cover → ảnh không bị méo

border → viền trắng

📌 HTML dùng kèm

"<img src="avatar.jpg" class="avatar">"
___________________________________________________________________________________________
5️⃣ .container – Bố cục chính
.container {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 25px;
}


📌 Tác dụng

display: grid → chia layout

260px → sidebar

1fr → nội dung chính
___________________________________________________________________________________________


6️⃣ .sidebar – Thanh bên
.sidebar {
  background: #fff;
  border-radius: 16px;
  padding: 20px;
  box-shadow: 0 6px 20px rgba(0,0,0,.08);
}


👉 Hộp trắng bo góc, đổ bóng
___________________________________________________________________________________________
7️⃣ Menu điều hướng
.menu a {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 12px;
  text-decoration: none;
}


📌 Hover & active

.menu a.active,
.menu a:hover {
  background: #3b82f6;
  color: #fff;
}


👉 Khi rê chuột → đổi màu nền xanh
___________________________________________________________________________________________
8️⃣ .content – Nội dung chính
.content {
  background: #ffffff;
  border-radius: 16px;
  padding: 30px;
  box-shadow: 0 6px 20px rgba(0,0,0,.08);
}


👉 Hộp nội dung lớn bên phải
___________________________________________________________________________________________
9️⃣ .services – Lưới dịch vụ
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 20px;
}


📌 Tác dụng

Tự động co giãn số cột theo màn hình

Rất phù hợp responsive
___________________________________________________________________________________________
🔟 .card – Thẻ dịch vụ
.card {
  padding: 20px;
  border-radius: 14px;
  border: 1px solid #eee;
  text-align: center;
}


🎯 Hiệu ứng hover

.card:hover {
  box-shadow: 0 10px 25px rgba(0,0,0,.1);
  transform: translateY(-4px);
}


👉 Thẻ nổi lên khi rê chuột
___________________________________________________________________________________________
1️⃣1️⃣ Responsive (Mobile)
@media(max-width: 900px) {
  .container {
    grid-template-columns: 1fr;
  }
}
