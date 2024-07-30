# Task Management Application

Ứng dụng Quản lý Nhiệm vụ là một dự án mẫu xây dựng bằng Spring Boot, cho phép người dùng quản lý các nhiệm vụ của họ một cách hiệu quả. Dự án này bao gồm các chức năng chính như đăng nhập, quản lý danh sách nhiệm vụ, phân công nhiệm vụ, và báo cáo tiến độ.

## Cấu trúc Dự án

Dưới đây là cấu trúc thư mục của dự án:

taskmanagement/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com/
│ │ │ └── example/
│ │ │ └── taskmanagement/
│ │ │ ├── TaskmanagementApplication.java
│ │ │ └── HomeController.java
│ │ └── resources/
│ │ ├── static/
│ │ │ ├── css/
│ │ │ │ └── styles.css
│ │ │ └── js/
│ │ │ └── scripts.js
│ │ └── templates/
│ │ └── index.html
└── pom.xml

## Các Thành phần

- **TaskmanagementApplication.java**: Lớp chính để khởi động ứng dụng Spring Boot.
- **HomeController.java**: Controller để xử lý các yêu cầu và hiển thị các trang web.
- **index.html**: Trang chính của ứng dụng, được sử dụng để hiển thị giao diện người dùng.
- **styles.css**: Tệp CSS cho các kiểu dáng của trang web.
- **scripts.js**: Tệp JavaScript cho các chức năng động trên trang web.

## Hướng dẫn Cài đặt

1. **Clone Dự án**

   ```bash
   git clone https://github.com/PhuongDaiThang/task-management-app.git
   ```
2. **Đi đến Thư mục Dự án**
   ```bash
   cd taskmanagement
   ```
3. **Cài đặt Maven Dependencies**
   ```bash
   mvn install
   ```
4. **Chạy Ứng dụng**
   ```bash
   mvn spring-boot:run
   ```
5. **Truy cập Ứng dụng**
   Mở trình duyệt và điều hướng đến http://localhost:8080 để xem ứng dụng.
## Các Tính Năng Chính
- **Đăng nhập và Đăng xuất**: Cho phép người dùng đăng nhập và quản lý tài khoản của họ.
- **Quản lý Danh sách Nhiệm vụ**: Tạo, chỉnh sửa, và xóa các nhiệm vụ.
- **Phân công Nhiệm vụ**: Gán nhiệm vụ cho người dùng khác.
- **Báo cáo Tiến độ**: Theo dõi và báo cáo tiến độ của các nhiệm vụ.
## Công Nghệ Sử Dụng
- **Spring Boot**: Framework chính để xây dựng ứng dụng.
- **Thymeleaf**: Công cụ template engine cho các trang web.
- **Maven**: Công cụ quản lý dự án và xây dựng.
- **CSS/JavaScript**: Để tùy chỉnh giao diện và chức năng của trang web.
## Đóng góp
Nếu bạn muốn đóng góp cho dự án này, vui lòng thực hiện một trong các cách sau:
- **Tạo một Pull Request**: Nếu bạn đã thực hiện các thay đổi hoặc cải tiến và muốn thêm chúng vào dự án, hãy tạo một pull request trên GitHub.
- **Gửi một Vấn đề (Issue)**: Nếu bạn phát hiện lỗi hoặc có đề xuất cải tiến, hãy gửi một vấn đề (issue) trên GitHub để thảo luận và làm rõ các thay đổi cần thiết.
## Liên hệ
Nếu bạn có bất kỳ câu hỏi nào hoặc cần thêm thông tin, vui lòng liên hệ với tôi qua email: phuongdaithang2004@gmail.com).
