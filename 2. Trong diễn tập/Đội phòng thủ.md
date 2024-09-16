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
