<!--
Họ tên: Trần Minh Nguyệt
Mã sinh viên: 23810310081
Lớp: D18CNPM2
-->

# Laravel Social Login Demo

## 1. Giới thiệu
Dự án xây dựng chức năng đăng nhập bằng tài khoản bên thứ ba (Google và Facebook) sử dụng Laravel Socialite.

## 2. Chức năng
- Đăng nhập Google
- Đăng nhập Facebook
- Lưu thông tin người dùng vào database
- Nếu tài khoản đã tồn tại thì đăng nhập
- Nếu chưa tồn tại thì tạo mới và đăng nhập
- Hiển thị thông tin người dùng sau khi đăng nhập
- Đăng xuất
- Xử lý lỗi đăng nhập

## 3. Công nghệ sử dụng
- Laravel
- Laravel Socialite
- MySQL

## 4. Cài đặt
```bash
git clone <link-github>
cd social-login-demo
composer install
cp .env.example .env
php artisan key:generate