# WEBSITE HỆ THỐNG QUẢN LÝ DỊCH VỤ SPA

# Phạm vi dự án

-   Công nghệ: Laravel, ReactJS, MySQL, JWT

-   Mô tả: Nhóm các dự án, quản lý toàn bộ hệ thống cơ sở spa, quản lý hàng tồn kho, nhân viên, ca làm việc, cuộc hẹn và tích hợp cuộc tư vấn cuộc gọi video trực tuyến với khách hàng.

-   Quản lý nhân viên
-   Vị trí nhân viên
-   Quản lý sản phẩm
-   Quản lý loại dịch vụ
-   Quản lý dịch vụ
-   Quản lý cuộc hẹn
-   Quản lý hóa đơn
-   Quản lý tư vấn
-   Thống kê và thông báo
-   Yêu cầu cuộc hẹn
-   Yêu cầu tư vấn

## DEMO

-   Youtube:

# Tài khoản

-   Admin: admin@gmail.com - admin123456
-   Khách hàng: customer@gmail.com - admin123456

# Trang chủ
<img src="https://raw.githubusercontent.com/khoait03/laravel-react-spa-management/main/public/upload/laravel-react-spa-main.png" alt="Megamart Demo" width="900">

## Cài đặt

Để cài đặt dự án, bạn cần thực hiện các bước sau:

1. Clone repository

2. Cài đặt các phụ thuộc:

    ```bash
    composer install

    ```

3. Tạo file .env:

    ```bash
    cp .env.example .env

    ```

4. Cấu hình file .env:
   Mở file .env và cấu hình các thông số kết nối cơ sở dữ liệu, ứng dụng, và các thông tin khác cần thiết cho dự án.

5. Tạo khóa ứng dụng:

    ```bash
    php artisan key:generate

    ```

6. Chạy migration:

    ```bash
    php artisan migrate

    ```

7. Chạy seeder:

    ```bash
    php artisan db:seed

    ```

8. Run project:

    ```bash
    php artisan serve

    ```

9. Truy cập vào đường dẫn để xem ứng dụng:
    ```bash
    http://127.0.0.1:8000
    ```

Đóng góp
Nếu bạn muốn đóng góp cho dự án, vui lòng tạo pull request và tuân thủ các quy tắc đóng góp.
