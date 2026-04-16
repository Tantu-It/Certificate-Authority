Hệ Thống Quản Lý Chứng Chỉ Số (Certificate Authority Management System)
Dự án này là một ứng dụng web cơ bản nhằm cung cấp thông tin về hệ thống chứng chỉ số, vai trò của tổ chức phát hành chứng chỉ (CA) và các dịch vụ bảo mật liên quan. Hệ thống bao gồm giao diện người dùng hiện đại, tích hợp xác thực đăng nhập cơ bản.

📌 Giới thiệu dự án
Tên dự án: Certificate Authority (Chứng Chỉ Số)

Mục tiêu: Cung cấp nền tảng kiến thức về bảo mật thông tin, SSL/TLS, và chữ ký điện tử.

Công nghệ sử dụng:

Frontend: HTML5, CSS3 (Custom styles & Tailwind CSS).

Icons & Fonts: Font Awesome, Google Fonts (Roboto).

Scripting: JavaScript (ES6).

Lưu trữ: LocalStorage (dùng để duy trì trạng thái đăng nhập).

✨ Các tính năng chính
Xác thực người dùng: Hệ thống yêu cầu đăng nhập để truy cập nội dung.

Trang chủ (Index): Giới thiệu khái niệm, vai trò và quy trình hoạt động của CA.

Giới thiệu (About): Chi tiết về tầm quan trọng của chứng chỉ số và các dịch vụ cung cấp.

Liên hệ (Contact): Biểu mẫu gửi phản hồi cho đội ngũ hỗ trợ.

Responsive Design: Giao diện hiển thị tốt trên cả máy tính và thiết bị di động.

🛠 Hướng dẫn cài đặt và sử dụng
1. Chuẩn bị
Bạn không cần cài đặt môi trường server phức tạp, dự án này chạy trực tiếp trên trình duyệt.

2. Cách chạy dự án
Tải toàn bộ thư mục dự án về máy tính.

Mở tệp login.html bằng trình duyệt web (Chrome, Edge, Firefox).

Thông tin đăng nhập:

Tên đăng nhập: nhom15

Mật khẩu: 123

(Lưu ý: Hệ thống kiểm tra điều kiện đăng nhập qua tệp script.js và lưu trạng thái vào localStorage).

3. Cấu trúc thư mục
Plaintext
├── index.html      # Trang chủ (Thông tin chính)
├── about.html      # Trang giới thiệu chi tiết
├── contact.html    # Trang liên hệ
├── login.html      # Trang đăng nhập
├── style.css       # Tệp định dạng giao diện tùy chỉnh
└── script.js      # Xử lý logic đăng nhập/đăng xuất
🛡 Bảo mật và Điều hướng
Dự án sử dụng cơ chế kiểm tra window.onload để đảm bảo người dùng chưa đăng nhập sẽ bị chuyển hướng về trang login.html.

Khi nhấn Đăng xuất, hệ thống sẽ xóa sạch dữ liệu trong localStorage để bảo mật thông tin phiên làm việc.

Được thực hiện bởi: Nhóm 15 - UTH (University of Transport and Communications Ho Chi Minh City)
