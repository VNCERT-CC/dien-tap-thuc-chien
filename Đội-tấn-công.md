<details>
<summary><h1>Trước diễn tập</h1></summary>

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
- Hoạt động của cơ quan chủ quản trên hệ thống (business)

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

</details>
<details>
<summary><h1>Trong diễn tập</h1></summary>

# Tuân thủ Nội quy diễn tập
Đội tấn công cần tuân thủ nội quy và cách thức tấn công, sử dụng công cụ, các loại tấn công được phép và bảo đảm bảo mật dữ liệu được quy định tại Nội quy của diễn tập.

# Thực hiện tấn công vào mục tiêu diễn tập
Các đội tấn công thực hiện tấn công vào hệ thống mục tiêu diễn tập dựa trên phương án đã thiết lập trước đó hoặc có thể tấn công tự do vào hệ thống diễn tập để tìm kiếm lỗ hổng

**Mỗi lỗ hổng được tìm thấy**
Các đội Redteam cần chụp hình ảnh cách khai thác lỗ hổng, chụp hình ảnh về tác động của lỗ hổng vào hệ thống và diễn giải được tác động của lỗ hổng này đến hệ thống diễn tập.
Các đội Redteam cần báo cáo lỗ hổng này về BTC để BTC nắm được tình hình tấn công và thông báo, chúc mừng tới toàn thể hội nghị.
Các đội Redteam cần xác định đúng mức độ ảnh hưởng của Lỗ hổng đánh giá dựa trên 3 tiêu chí về Tài nguyên hệ thống, Dữ liệu và Người dùng.

**Sau khi phát hiện lỗ hổng**
Thông báo với BTC về việc phát hiện và có hình ảnh chứng minh, việc này là cơ sở để BTC và BGK đánh giá thứ hạng các đội Redteam dựa trên thời gian phát hiện lỗ hổng.
Các đội có thể tìm kiếm con đường khác để vào hệ thống, nhằm mục tiêu phát hiện càng nhiều lỗ hổng càng tốt và càng nhiều điểm, nhằm giữ và tăng thứ hạng của đội mình.

# Phối hợp với Ban tổ chức về các vấn đề của diễn tập
Trong thời gian diễn ra diễn tập thực chiến, các đội Redteam có thể gặp khó khăn, trục trặc khi sử dụng các chức năng của hệ thống (ví dụ: Chức năng Đăng ký không hoạt động hoặc Trang web không thể truy cập được, hoặc đã bị chặn IP bởi Blueteam), với các trường hợp này, các đội Redteam có thể gửi yêu cầu tới BTC để BTC điều phối Blueteam thực hiện khắc phục để tạo điều kiện thuận lợi cho các đội tấn công vào hệ thống (trong khuôn khổ diễn tập).

</details>
<details>
<summary><h1>Kết thúc diễn tập</h1></summary>

# Thực hiện báo cáo cuối cùng

Báo cáo cuối cùng thể hiện được và có đầy đủ các tiêu chí chấm điểm được quy định tại Nội quy và gửi về BTC theo đúng quy định.

Báo cáo cuối cùng được thực hiện bởi các đội tấn công cần bao gồm các nội dung sau:

- Khẳng định việc tuân thủ nội quy diễn tập trong toàn bộ thời gian diễn tập diễn ra
- Thông tin tóm tắt về tình hình an toàn thông tin của mục tiêu diễn tập (nhận định chung)
- Danh sách các lỗ hổng và số lượng lỗ hổng theo từng mức độ khác nhau
- Chi tiết từng lỗ hổng bao gồm
  + Số thứ tự
  + Tên lỗ hổng kèm ảnh hưởng của lỗ hổng tới 3 tiếu chí (Tài nguyên hệ thống - máy chủ, dữ liệu, người dùng & người dân);
  + Mô tả sơ qua về chức năng gặp lỗ hổng, Mô tả về lỗ hổng (tại sao tồn tại lỗ hổng này)
  + Mức độ lỗ hổng
  + Chi tiết cách thức khai thác và hình ảnh kèm theo
  + Hướng dẫn chi tiết cách khắc phục (theo tiêu chí được quy định tại nội quy)
  + Hình ảnh bằng chứng về ảnh hưởng của lỗ hổng (ví dụ RCE thì thực hiện được câu lệnh, dữ liệu nhạy cảm thì cần có ảnh chụp chứng minh)
- Đề xuất, góp ý chung về trung hạn và dài hạn, các biện pháp, chính sách tổng quan để nâng cao khả năng bảo đảm an toàn thông tin cho cơ quan chủ quản hệ thống

Sau khi thực hiện báo cáo cuối cùng, các đội redteam thực hiện mã hóa báo cáo với mật khẩu mạnh và gửi cho BTC. Xóa và làm sạch toàn bộ các hình ảnh, bằng chứng, dữ liệu,... liên quan tới hệ thống mục tiêu và liên quan tới diễn tập thực chiến.

</details>
