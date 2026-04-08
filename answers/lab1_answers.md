# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Vũ Khánh Hùng    

**MSSV:** 1871020266

**Lớp/Nhóm:** CNTT18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Cơ sở dữ liệu điểm sinh viên
- Asset 2:Tài khoản đăng nhập của giảng viên / admin
- Asset 3 (nếu có):Hệ thống máy chủ lưu trữ dữ liệu

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality 
ví dụ :lộ điểm sinh viên cho người không có quyền
- Sự cố B -> Integrity
Ví dụ: điểm bị sửa trái phép
- Sự cố C -> Availability
Ví dụ: hệ thống không truy cập được

---

## 3. Phân tích sự cố B
- Threat:Người dùng trái phép hoặc hacker chỉnh sửa điểm trong hệ thống
- Vulnerability:
Không kiểm tra phân quyền chặt chẽ
Mật khẩu yếu hoặc dễ bị đoán
Không có cơ chế log/kiểm tra thay đổi dữ liệu
- Mitigation:
Áp dụng phân quyền (role-based access control)
Mã hóa và bảo vệ mật khẩu (hash + salt)
Ghi log và theo dõi thay đổi dữ liệu
Xác thực 2 lớp (2FA)
---

## 4. Reflection
Viết 5-7 dòng.

Qua bài lab này, em hiểu rõ hơn về ba yếu tố quan trọng trong an toàn thông tin là Confidentiality, Integrity và Availability. Việc phân tích từng sự cố giúp em biết cách xác định vấn đề thuộc loại nào trong CIA. Phần khó nhất là phân biệt giữa threat và vulnerability vì đôi khi dễ bị nhầm lẫn. Em cũng nhận ra rằng một hệ thống đơn giản như lưu điểm vẫn có nhiều rủi ro bảo mật nếu không thiết kế cẩn thận. Khi phân tích sự cố, cần xem xét từ nguyên nhân đến cách phòng tránh. Điều này rất quan trọng trong thực tế khi xây dựng hệ thống


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-C-B-I-C-A}

