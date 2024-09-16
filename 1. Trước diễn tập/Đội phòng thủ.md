# Chuẩn bị hệ thống

## Rà soát thông tin về hệ thống

Bao gồm các hệ thống liên kết, hệ thống có thể gọi tới hệ thống mục tiêu diễn tập và hệ thống được gọi bởi mục tiêu diễn tập

  - Kiểm tra các kết nối mạng trên hệ thống mục tiêu diễn tập để xây dựng, mô hình hóa mối đe dọa
  - Kiểm tra các công nghệ lập trình, máy chủ, cơ sở dữ liệu của diễn tập để có biện pháp giám sát, ứng cứu
  - Rà soát các tài khoản, mật khẩu. Trong trường hợp cần thiết phải truy cập vào máy chủ hệ thống để điều tra, ứng cứu,...
  - Rà soát các đầu mối phối hợp việc giám sát, ứng cứu

## Kiểm tra các công nghệ giám sát trên hệ thống

  - Bảo đảm các công nghệ giám sát được cài đặt và hoạt động bình thường
  - Bảo đảm việc sử dụng các công nghệ (các tài khoản, mật khẩu của công nghệ)

## Gia cố hệ thống (nếu có)

  - Thực hiện gia cố hệ thống mục tiêu diễn tập ở mức hệ điều hành
  - Gia cố ứng dụng mục tiêu diễn tập

## Xây dựng phương án phòng thủ, ứng phó sự cố (nếu cần thiết)
  - Nếu đơn vị chưa có quy trình, phương án phòng thủ, ứng phó sự cố, cần gấp rút xây dựng để bộ máy hoạt động trơn tru, phối hợp nhịp nhàng.

# Phân vai trong diễn tập
Đội phòng thủ cần trao đổi, họp bàn về việc phòng thủ, phân vai giữa các thành viên trong diễn tập.
Tùy vào kỹ năng, kinh nghiệm của các thành viên, các thành viên lựa chọn nhiệm vụ để bảo đảm an toàn thông tin cho hệ thống mục tiêu.
Chuẩn bị về việc phối hợp giám sát, ngăn chặn, xử lý và ứng cứu sự cố kịp thời.

# Chuẩn bị báo cáo

Chuẩn bị thông tin cho báo cáo sau diễn tập.
Các thông tin cần phù hợp với Hệ thống, ứng dụng mục tiêu của diễn tập.
Các thông tin cần phù hợp theo tiêu chí chấm điểm của BTC đưa ra.
Các thông tin này thường sẽ bao gồm:

## Thông tin về Quy trình

Cần nêu rõ Trích yếu, Số hiệu văn bản, Ngày tháng Quy trình được ban hành.

**Hiện trạng các Quy trình**

  - Quy trình Giám sát
  - Quy trình Phát hiện
  - Quy trình Ngăn chặn
  - Quy trình Ứng cứu và Xử lý sự cố
  - Quy trình Sao lưu và phục hồi

... (diễn giải thêm về các quy trình khác nếu có)

## Thông tin về Công nghệ (với mục đích bảo đảm an toàn thông tin)

Cần nêu rõ Tên giải pháp, mục đích của giải pháp được trang bị, hệ thống mà giải pháp được áp dụng bảo vệ.
Thông tin về Công nghệ cũng cần được thể hiện rõ trong báo cáo, nếu trang thiết bị được trang bị nhưng không được sử dụng trong Diễn tập thực chiến để bảo đảm an toàn thông tin cho hệ thống thì đó là một điểm trừ (được trang bị nhưng không được sử dụng hiệu quả vào công tác bảo đảm an toàn thông tin).

**Các công nghệ/giải pháp có thể nêu ra bao gồm**

  - Công nghệ/giải pháp Tường lửa lớp mạng: Firewall
  - Công nghệ/giải pháp Giám sát lớp mạng: IDS/IPS
  - Công nghệ/giải pháp Giám sát điểm: HIDS, EDR
  - Công nghệ/giải pháp Quản lý nhật ký tập trung: SIEM
  - Công nghệ/giải pháp Tường lửa ứng dụng web: WAF

... (diễn giải thêm về các công nghệ, giải pháp khác được trang bị để bảo đảm an toàn thông tin)

## Thông tin về Con người

Cần nêu rõ Thông tin về các nhân sự tham gia phòng thủ (Đội blueteam).

**Các nhân sự tham gia phòng thủ thông thường bao gồm**

  - Nhân sự của Đơn vị giám sát trực tiếp hệ thống (Đơn vị cung cấp dịch vụ an toàn thông tin)
  - Nhân sự của Cơ quan chủ quản hệ thống (Đơn vị thụ hưởng)
  - Nhân sự của Đơn vị trực tiếp vận hành hệ thống (Quản lý máy chủ, tên miền, IP và ứng dụng)

**Các thông tin về nhân sự có thể bao gồm**

  - Họ và tên
  - Cơ quan/đơn vị Công tác
  - Chức vụ
  - Vị trí công việc: Ví dụ: Được giao chuyên trách ứng cứu sự cố cho hệ thống XXX
  - Bằng cấp/Chứng chỉ: Ví dụ: Được đào tạo về chuyên ngành An toàn thông tin, có bằng kỹ sư An toàn thông tin của Học viện Kỹ thuật Mật mã
  - Số năm kinh nghiệm: Số năm đã hoạt động trong chuyên ngành an toàn thông tin
  - Phân vai trong diễn tập

... (diễn giải thêm về kỹ năng an toàn thông tin như các cuộc thi, giải thưởng...)
