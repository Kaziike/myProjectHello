1️⃣ body – Toàn bộ trang web

📌 Tác dụng

margin: 0; → bỏ khoảng trắng mặc định của trình duyệt

font-family → chọn font chữ (Segoe UI → Tahoma → sans-serif)

background → màu nền trắng

color → màu chữ xám đậm

👉 Áp dụng cho toàn bộ trang
___________________________________________________________________________________________
2️⃣ .header – Phần đầu trang (banner)

📌 Tác dụng

background: url(...) → ảnh nền

center/cover → ảnh nằm giữa & phủ kín

no-repeat → không lặp ảnh

padding: 100px → tạo khoảng trống xung quanh nội dung

color: #fff → chữ màu trắng
___________________________________________________________________________________________

3️⃣ .profile – Khối thông tin cá nhân

📌 Tác dụng

display: flex → sắp xếp ngang

align-items: center → căn giữa theo chiều dọc

gap → khoảng cách giữa avatar & text

border-radius → bo góc

margin: -80px auto → đẩy khối đè lên header (hiệu ứng nổi)

box-shadow → đổ bóng
___________________________________________________________________________________________
4️⃣ .avatar – Ảnh đại diện

📌 Tác dụng

border-radius: 50% → ảnh tròn

object-fit: cover → ảnh không bị méo

border → viền trắng

📌 HTML dùng kèm

"<img src="avatar.jpg" class="avatar">"
___________________________________________________________________________________________
5️⃣ .container – Bố cục chính

📌 Tác dụng

display: grid → chia layout

260px → sidebar

1fr → nội dung chính
___________________________________________________________________________________________

6️⃣ .sidebar – Thanh bên

👉 Hộp trắng bo góc, đổ bóng
___________________________________________________________________________________________
7️⃣ Menu điều hướng

📌 Hover & active

👉 Khi rê chuột → đổi màu nền xanh
___________________________________________________________________________________________
8️⃣ .content – Nội dung chính

👉 Hộp nội dung lớn bên phải
___________________________________________________________________________________________
9️⃣ .services – Lưới dịch vụ

📌 Tác dụng

Tự động co giãn số cột theo màn hình

Rất phù hợp responsive
___________________________________________________________________________________________
🔟 .card – Thẻ dịch vụ

🎯 Hiệu ứng hover

👉 Thẻ nổi lên khi rê chuột
___________________________________________________________________________________________
1️⃣1️⃣ Responsive (Mobile)

