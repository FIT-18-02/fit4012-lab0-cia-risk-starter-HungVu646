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
- Threat: Người dùng trái phép hoặc hacker thay đổi dữ liệu điểm
- Vulnerability:Phân quyền kém ,Mật khẩu yếu ,Không có log theo dõi
- Mitigation:Áp dụng phân quyền (RBAC) , Mã hóa mật khẩu ,Ghi log và giám sát hệ thống ,Xác thực 2 lớp

### 4. Kết luận ngắn

Qua bài lab, em hiểu rõ hơn ba yếu tố Confidentiality, Integrity và Availability trong mô hình CIA, đồng thời nhận thấy ngay cả hệ thống đơn giản như lưu điểm cũng tiềm ẩn nhiều nguy cơ bảo mật. Việc phân tích từng sự cố giúp em biết cách xác định rủi ro trong hệ thống thông tin, chẳng hạn như thiếu phân quyền dẫn đến lộ điểm (vi phạm tính bảo mật), sửa điểm trái phép ảnh hưởng đến tính toàn vẹn, và tấn công từ chối dịch vụ gây mất tính sẵn sàng. Phần khó nhất đối với em là phân biệt giữa threat (mối đe dọa) và vulnerability (lỗ hổng), vì nhiều khi dễ nhầm lẫn nguyên nhân với điểm yếu. Qua đó, em rút ra rằng khi phân tích cần xác định rõ nguyên nhân gốc rễ mới đưa ra giải pháp phù hợp. Nguyên tắc "phòng vệ theo chiều sâu" rất quan trọng: phải kết hợp xác thực mạnh, mã hóa, ghi nhật ký và sao lưu định kỳ. Em nhận thấy chi phí xử lý sự cố sau khi hệ thống bị tấn công cao hơn nhiều so với chi phí phòng ngừa từ đầu. Môn học này thực sự cần thiết cho người học công nghệ thông tin, đặc biệt là trong thiết kế hệ thống an toàn bảo mật. Những bài lab thực tế như vậy nên được lồng ghép nhiều hơn để sinh viên vừa học vừa rèn tư duy phản biện về bảo mật