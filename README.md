# Bài 2: Chuỗi tấn công từ mật khẩu bị rò rỉ

## 1. Cơ chế tấn công Domino Effect

- Hacker đánh cắp dữ liệu tài khoản từ một diễn đàn nhỏ.
- Hacker lấy mật khẩu bị rò rỉ và thử đăng nhập vào Gmail, Facebook, GitHub.
- Do sử dụng chung mật khẩu `123456`, hacker có thể chiếm quyền truy cập nhiều tài khoản.
- Đây là hình thức tấn công Credential Stuffing (thử thông tin đăng nhập bị rò rỉ trên nhiều website).

## 2. So sánh mật khẩu cảm tính và mật khẩu ngẫu nhiên

- Mật khẩu cảm tính như `123456`, `password`, ngày sinh dễ đoán và dễ bị bẻ khóa bằng công cụ tự động.
- Mật khẩu do máy tính sinh ra thường dài, kết hợp chữ hoa, chữ thường, số và ký tự đặc biệt, khó đoán hơn.

## 3. Bảo vệ mật khẩu bằng Password Manager

Password Manager như Bitwarden giúp lưu trữ và quản lý mật khẩu an toàn.

- Sử dụng mã hóa AES-256 để bảo vệ dữ liệu lưu trữ.
- Dữ liệu được mã hóa trước khi lưu trữ, giúp người khác không thể đọc trực tiếp nếu không có khóa giải mã.
- Chỉ cần nhớ một Master Password mạnh để truy cập kho mật khẩu.
- Có thể tự động tạo mật khẩu dài, ngẫu nhiên và khác nhau cho từng tài khoản.

So sánh với ghi chép thủ công:

- Ghi mật khẩu vào giấy hoặc file văn bản dễ bị xem trộm, thất lạc hoặc sao chép.
- Password Manager mã hóa dữ liệu, giúp tăng khả năng bảo vệ khi lưu trữ.

## 4. Kết luận

Sử dụng chung mật khẩu cho nhiều tài khoản có thể gây ra hiệu ứng Domino khi một website bị rò rỉ dữ liệu. Vì vậy, cần sử dụng mật khẩu mạnh, riêng biệt cho từng tài khoản và quản lý bằng Password Manager có mã hóa AES-256 như Bitwarden. Đồng thời, nên bật xác thực hai yếu tố (2FA) để tăng cường bảo mật.
