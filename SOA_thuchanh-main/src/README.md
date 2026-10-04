## 1. Giới thiệu
Xây dựng dịch vụ RESTful API với ASP.NET Core, tập trung vào:
- Router và RESTful API
- Middleware
- Đăng ký tài khoản
- Đăng nhập người dùng
- Phát hành JWT Token
- Xác thực JWT
- Phân quyền người dùng theo Role
- Kiểm thử API thông qua giao diện web và Swagger

Project được xây dựng theo mô hình gồm các service:
- LoginService: xử lý đăng ký, đăng nhập và phát hành JWT.
- AuthenticationService: xử lý xác thực JWT, thông tin người dùng và phân quyền.
- SOA.Shared: chứa các model, cấu hình JWT và các hàm dùng chung giữa các service.

## 2. Mục tiêu
- Xây dựng API bằng ASP.NET Core.
- Sử dụng Controller và Route để xây dựng RESTful API.
- Sử dụng Middleware để xử lý request.
- Sử dụng JWT để xác thực người dùng.
- Kiểm tra JWT Token trước khi cho phép truy cập các endpoint được bảo vệ.
- Phân quyền người dùng dựa trên Role.
- Sử dụng Swagger để kiểm thử API.

## 3. Công nghệ sử dụng
- C#
- ASP.NET Core
- .NET 9
- RESTful API
- JWT (JSON Web Token)
- ASP.NET Core Middleware
- Swagger / OpenAPI
- HTML / CSS / JavaScript
- Visual Studio / Visual Studio Code
- Swagger / OpenAPI
- HTML / CSS / JavaScript
- Visual Studio / Visual Studio Code
