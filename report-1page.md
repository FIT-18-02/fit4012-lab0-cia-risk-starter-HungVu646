# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm sinh viên
- Tài khoản đăng nhập giảng viên/admin
- Hệ thống máy chủ
**CIA mapping:**
- Sự cố A → Confidentiality
- Sự cố B → Integrity
- Sự cố C → Availability
**Phân tích sự cố B:**
Threat:
- Người dùng trái phép hoặc hacker thay đổi dữ liệu điểm
Vulnerability:
- Phân quyền kém
- Mật khẩu yếu
- Không có log theo dõi
Mitigation:
- Áp dụng phân quyền (RBAC)
- Mã hóa mật khẩu  
- Ghi log và giám sát hệ thống
- Xác thực 2 lớp

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn về ba yếu tố trong mô hình CIA gồm Confidentiality, Integrity và Availability. Việc phân tích từng sự cố giúp em biết cách xác định rủi ro trong hệ thống thông tin. Em nhận thấy rằng ngay cả hệ thống đơn giản như lưu điểm cũng có nhiều nguy cơ bảo mật. Phần khó nhất là phân biệt giữa threat và vulnerability. Khi phân tích, cần xác định rõ nguyên nhân và đưa ra giải pháp phù hợp. Điều này rất quan trọng khi thiết kế hệ thống an toàn.