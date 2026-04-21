1:
spring-boot-starter-web được gọi là một "Starter" vì nó đóng vai trò là một "tổ hợp phụ thuộc" (dependency descriptor) được cấu hình sẵn. Thay vì bạn phải tự tìm kiếm và nhặt nhạnh từng thư viện để xây dựng một ứng dụng Web, Spring Boot cung cấp một "gói combo" duy nhất để bạn bắt đầu ngay lập tức
Nó giúp bạn không phải khai báo thủ công các thư viện nhỏ lẻ sau:

Spring MVC: Các thư viện cốt lõi để xây dựng RESTful API hoặc Web ứng dụng (spring-web, spring-webmvc).

Embedded Servlet Container: Mặc định là Tomcat (giúp chạy ứng dụng mà không cần cài server rời).

JSON Processing: Thư viện Jackson để tự động chuyển đổi dữ liệu giữa Java Object và JSON.

Logging: Mặc định là Logback và SLF4J.

Validation: Các thư viện để kiểm tra dữ liệu đầu vào (Hibernate Validator).

Auto-configuration: Các cấu hình mặc định để các thành phần trên tự động kết nối và hoạt động với nhau.