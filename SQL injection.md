### SQL Injection

#### SQL Injection là gì?

- SQL Injection là một lỗ hổng bảo mật web cho phép kẻ tấn công can thiệp vào các truy vấn mà ứng dụng gửi đến cơ sở dữ liệu (database).
- Hậu quả: Kẻ tấn công có thể xem những dữ liệu mà bình thường họ không được phép thấy (như dữ liệu của người dùng khác), sửa đổi hoặc xóa dữ liệu, gây thay đổi vĩnh viễn cho ứng dụng. Trong một số trường hợp, nó có thể dẫn đến việc chiếm quyền kiểm soát máy chủ hoặc tấn công từ chối dịch vụ (DoS).

#### Tác động của cuộc tấn công SQLi
- Nếu tấn công thành công, hậu quả có thể bao gồm:
  - Truy cập trái phép vào dữ liệu nhạy cảm: mật khẩu, thông tin thẻ tín dụng, thông tin cá nhân.
  - Tổn hại uy tín và bị phạt tiền theo quy định pháp luật.
  - Kẻ tấn công có thể cài đặt backdoor để truy cập hệ thống lâu dài.
#### Cách phát hiện SQL injection
- Có thể phát hiện SQL injection bằng cách thủ công là một quy trình kiểm thử hệ thống (systematic set of tests) lên mọi điểm đầu vào (entry point) của ứng dụng:
  - 
