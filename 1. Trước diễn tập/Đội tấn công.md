# Thực hiện cam kết bảo mật thông tin
Tham khảo mẫu cam kết bảo mật thông tin tại [Quyết định 1439/QĐ-BTTTT ngày 26/07/2022](https://admin.vncert.vn/wp-content/uploads/2022/12/QD-Dientapthucchien.pdf)

# Chuẩn bị công cụ
Chuẩn bị danh sách các công cụ để tấn công vào hệ thống:
- Công cụ thăm dò, khảo sát hệ thống: Chuẩn bị các tài khoản Shodan, Censys, Fofa. Công cụ dirsearch, nuclei, nessus, acunetix,...
- Công cụ kiểm thử an toàn thông tin thủ công: BurpSuite, Trình duyệt web firefox, Tiện ích container proxy,...
- Công cụ hỗ trợ khai thác lỗ hổng: SQLMap, NoSQLMap,...

# Chuẩn bị phương án tấn công

*Lưu ý:* Ở giai đoạn chuẩn bị, các đội tấn công chưa được biết mục tiêu của diễn tập thực chiến.

Đội tấn công xác định mục tiêu của cuộc tấn công, nhắm vào 1 trong 3 yếu tố sau:
- Tài nguyên hệ thống: Máy chủ, domain, IP, năng lực lưu trữ, tính toán, mạng,...
- Dữ liệu của hệ thống
- Người dùng, người dân trên hệ thống

Từ các mục tiêu trên, đội tấn công thực hiện mô hình hóa cuộc tấn công để đạt được mục đích cuối cùng.

**Ví dụ:** Mục đích của đội tấn công là lấy được toàn bộ dữ liệu của hệ thống:

1. Vạch ra các con đường có thể lấy được dữ liệu của hệ thống: Lỗ hổng SQL Injection, Backup database file, IDOR (thực hiện crawl), Chiếm đoạt tài khoản admin,...

2. Chọn ra một con đường và thực hiện các bước để tìm kiếm lỗ hổng đó, ví dụ: SQL Injection

3. Thực hiện các phương pháp tìm kiếm, phát hiện lỗ hổng SQL Injection

4. Thực hiện khai thác thử nghiệm và khai thác hoàn toàn lỗ hổng SQL Injection

5. Mở rộng phạm vi khai thác từ lỗ hổng SQL Injection trên

# Chuẩn bị nhân sự

Phân công nhiệm vụ các thành viên trong đội dựa trên kỹ năng, kinh nghiệm và sở trường của mỗi cá nhân.

Phân chia nhiệm vụ dựa trên các hệ thống khác nhau, các phương án, các mô hình tấn công khác nhau.

Bảo đảm việc thực hiện tấn công cover được càng nhiều thành phần, chức năng, facing của hệ thống càng có lợi với Redteam.
