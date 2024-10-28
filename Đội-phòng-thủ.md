<details>
<summary><h1>Trước diễn tập</h1></summary>

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


</details>
<details>
<summary><h1>Trong diễn tập</h1></summary>

# Lưu ý
Trong quá trình diễn tập, mỗi hành động của đội phòng thủ cần được lưu lại bằng chứng cụ thể (bằng hình ảnh) và đưa ra bằng chứng về tính **hiệu quả** của hành động đó.

Ví dụ: Đội phòng thủ nhận thấy địa chỉ IP 1.2.3.4 đang thực hiện rà quét, tấn công vào hệ thống mục tiêu diễn tập, các thành viên trong đội đã thực hiện:
1. Ngăn chặn tấn công bằng cách chặn IP 1.2.3.4: Cần chụp hình ảnh về việc cấu hình thiết bị, giải pháp để ngăn chặn IP này
2. Kiểm tra nhật ký xem IP 1.2.3.4 đã được ngăn chặn thành công hay chưa: Cần chụp hình ảnh về nhật ký thiết bị/công nghệ về việc IP này không còn truy cập được hệ thống
3. Đánh giá hiệu quả của hành động trên và đề xuất các bước tiếp theo

Các sự kiện an toàn thông tin như việc "Đội phòng thủ đã phát hiện và ngăn chặn IP 1.2.3.4 tấn công vào mục tiêu diễn tập" cần được báo cáo, thông báo ngay cho BTC tại nhóm trao đổi chung (instant message) để BTC nắm được và đánh giá hiệu quả phòng thủ cũng như thời gian các đội phòng thủ phát hiện tấn công.

# Thực hiện giám sát, phòng thủ trên hệ thống mục tiêu
- Thường xuyên giám sát, kiểm tra nhật ký, sự kiện an toàn thông tin trên hệ thống qua kỹ thuật, kinh nghiệm chuyên môn và sự trợ giúp của Công nghệ, Quy trình đã được trang bị, lưu lại hình ảnh bằng chứng của cuộc tấn công
- Cần xác định mức độ và có hành động kịp thời ngăn chặn các cuộc tấn công có thể gây ảnh hưởng tới hệ thống
- Cần báo cáo kịp thời cho BTC để ghi nhận quá trình phòng thủ

- Phân tích các payload (tải trọng) và đưa ra nhận định về cuộc tấn công (thành công, thất bại, hệ thống có hay không tồn tại lỗ hổng), đưa ra được mức độ nguy hiểm của lỗ hổng đối với mục tiêu
- Theo dõi cuộc tấn công, theo dõi kẻ tấn công trong suốt quá trình diễn tập

- Thực hiện phát hiện, ngăn chặn cuộc tấn công tương tự bằng việc cập nhật tập luật giám sát dựa trên payload

# Phối hợp với Redteam theo hướng dẫn của BTC

- Trong một số trường hợp, BTC đã ghi nhận được việc đội phòng thủ đã ngăn chặn thành công IP của đội Redteam tấn công vào hệ thống. Tuy nhiên, đội Redteam có thể yêu cầu mở lại địa chỉ IP này (trong khuôn khổ diễn tập thực chiến), vì vậy, BTC sẽ tiếp nhận các yêu cầu mở lại địa chỉ IP cho phép truy cập vào hệ thống. Đội phòng thủ nhận được các yêu cầu này **từ BTC** và thực hiện gỡ bỏ theo yêu cầu.

- Trong trường hợp khác, đội Redteam nhận thấy một số chức năng của hệ thống mục tiêu không hoạt động, đội Redteam có thể yêu cầu để kiểm tra lại chức năng này. BTC sẽ tiếp nhận các yêu cầu của đội Redteam. Đội phòng thủ nhận được các yêu cầu này **từ BTC** và thực hiện kiểm tra lại chức năng.
Ví dụ: Đội Redteam nhận thấy chức năng Đăng ký tài khoản trên hệ thống mục tiêu không hoạt động (email không gửi về). BTC tiếp nhận yêu cầu kiểm tra từ đội Redteam. Đội Blueteam tiếp nhận yêu cầu từ BTC và thực hiện kiểm tra hệ thống gửi email hoặc thực hiện mở tài khoản cho đội Redteam.

</details>
<details>
<summary><h1>Kết thúc diễn tập</h1></summary>

# Thực hiện báo cáo tổng hợp cuối cùng

Báo cáo tổng hợp cuối cùng là một báo cáo quan trọng, nó thể hiện thấy toàn bộ quá trình giám sát, phòng thủ, ngăn chặn và xử lý, ứng cứu, khôi phục của đội phòng thủ trong suốt thời gian diễn tập thực chiến diễn ra. Thể hiện được sự đối kháng, tấn công và phòng thủ qua lại giữa các đội redteam và đội blueteam.

Báo cáo tổng hợp cuối cùng cần đạt được các tiêu chí tương ứng với các tiêu chí chấm điểm đã được quy định trong nội quy của diễn tập và gửi về BTC theo đúng quy định.

## Các phần của báo cáo tổng hợp cuối cùng

### Phần giới thiệu hệ thống mục tiêu diễn tập
Giới thiệu tổng quan, ngắn gọn về hệ thống:
  - Mục đích của hệ thống
  - Các thành phần quan trọng của hệ thống cần bảo vệ
  - Dữ liệu quan trọng của hệ thống
  - Hoạt động business, của hệ thống với cơ quan chủ quản

**Lưu ý:** Ở diễn tập thực chiến, chúng tôi quy định các mục tiêu thực sự của hệ thống mục tiêu là:
  - Tài nguyên của hệ thống: Bao gồm bản thân các máy chủ, năng lực tính toán, lưu trữ, mạng, tên miền,... của hệ thống mục tiêu
  - Dữ liệu (thông tin): Bao gồm dữ liệu được sinh ra bởi hệ thống, dữ liệu được sử dụng bởi hệ thống (có thể là dữ liệu được query ở nơi khác và được hệ thống xử lý, hiển thị hoặc lưu trữ)
  - Người dùng: Ảnh hưởng tới người dùng của hệ thống, như chiếm đoạt tài khoản người dùng hệ thống, tiết lộ tính riêng tư của thông tin người dùng, lừa đảo người dùng, người dân,...
  - Cơ quan chủ quản: Ảnh hưởng tới uy tín, danh tiếng hoặc trực tiếp tới tài chính, hoạt động business của cơ quan chủ quản thông qua mục tiêu diễn tâp

### Phần quy trình, công nghệ, con người
Phần này, đội phòng thủ sử dụng các thông tin đã chuẩn bị **trước diễn tập** về Con người, Công nghệ, Quy trình để làm rõ việc hệ thống được quan tâm, bảo vệ về an toàn thông tin.

### Phần nhận định chung
Đội phòng thủ nhận định về hệ thống sau toàn bộ thời gian diễn ra diễn tập thực chiến. Cần khẳng định được hệ thống đã bị xâm nhập hay chưa, mất an toàn thông tin hay rò rỉ dữ liệu không, người dùng hệ thống, người dân sử dụng hệ thống có an toàn không.

Phần nhận định chung sẽ cho người đọc báo cáo (BGK) có cái nhìn tổng quan về tình hình an toàn thông tin của hệ thống, đánh giá được mức độ an toàn và đánh giá được hoạt động phòng thủ, bảo đảm an toàn thông tin của toàn bộ Hệ thống công nghệ, quy trình, con người.

### Phần chi tiết quá trình phòng thủ
Đội phòng thủ diễn giải quá trình phòng thủ trong thời gian diễn tập diễn ra.
Các diễn giải có thể được thực hiện theo dòng thời gian và mỗi dòng thời gian được phân cách với nhau bởi 01 ngày.

Đội phòng thủ báo cáo chi tiết cần chú ý đến 3 mục sau:
#### Mỗi hành động của kẻ tấn công

Đội phòng thủ cần phát hiện được mỗi hành động của kẻ tấn công trên hệ thống mục tiêu. Sau khi phát hiện, cần đưa ra được biện pháp phòng thủ, chống lại việc tấn công đó, cần đánh giá được hiệu quả của việc phòng thủ.
Một số ý đội phòng thủ cần thể hiện:
  - Hình thức/loại hình tấn công
  - Payload mà đội Redteam đã sử dụng để tấn công
  - Endpoint/Chức năng mà đội Redteam nhắm tới
  - Phân tích payload và đưa ra mức độ ảnh hưởng của cuộc tấn công tới hệ thống mục tiêu
  - Đánh giá thiệt hại, dữ liệu bị rò rỉ
  - Thể hiện được việc cập nhật lại hệ thống giám sát, tự động ngăn chặn dựa trên payload

Tất cả các chi tiết cần có hình ảnh bằng chứng cụ thể chứng minh.

#### Mỗi kẻ tấn công (threat actor)

Đội phòng thủ cần theo dấu kẻ tấn công trên hệ thống hoặc các cuộc tấn công từ cùng 1 kẻ tấn công. Nhận định được thời gian kẻ tấn công bắt đầu tấn công, kết thúc tấn công và các hành động của kẻ tấn công đã thực hiện trên hệ thống. Nhận định được việc kẻ tấn công đã xâm nhập hay chưa xâm nhập thành công vào hệ thống, các mốc thời gian cụ thể và hình ảnh bằng chứng chứng minh.

Ví dụ: Kẻ tấn công có IP 1.2.3.4 đã thực hiện rà quét trên hệ thống, sau đó kẻ tấn công thực hiện đăng ký tài khoản và thực hiện upload một tệp mã độc (shell) lên hệ thống qua chức năng upload avatar. Tuy nhiên việc upload đã không bị hệ thống ngăn chặn dẫn tới việc kẻ tấn công đã xâm nhập được thành công hệ thống.

#### Mỗi ngày

Đội phòng thủ nhận định tình hình hệ thống sau mỗi ngày diễn ra diễn tập thực chiến. Các nhận định sẽ trả lời được các câu hỏi:
- Tình hình an toàn thông tin của hệ thống sau mỗi ngày?
- Các sự kiện an toàn thông tin đáng chú ý sau mỗi ngày?
- Hành động của đội phòng thủ mỗi ngày?

### Phần tổng kết, rút kinh nghiệm
Đội phòng thủ tự nhận định, rà soát lại các lỗ hổng về Con người, quy trình và có kế hoạch bổ sung, khắc phục lỗ hổng kịp thời.
Đội phòng thủ thảo luận, rút kinh nghiệm về việc phối hợp phòng thủ, phát hiện, ngăn chặn, ứng cứu và khôi phục hệ thống.
Đội phòng thủ đề xuất các biện pháp tiếp theo, sắp tới để nâng cấp, bảo đảm an toàn thông tin cho hệ thống.
Cuối cùng là đề xuất với BTC về phản hồi về Diễn tập thực chiến để cải thiện và hoàn thiện quy trình phối hợp giữa redteam, blueteam, BTC, BGK và Nội quy, quy định của diễn tập thực chiến

</details>
