phần 1:

- tình huống 1: phishing và typosquatting do tên miền giả mạo github
- tình huống 2: mã độc crack, không tắt windows defender
- 4 bước cấp cứu: ngắt internet, đổi mật khẩu bằng máy sạch, quét mã độc, kiểm tra tài khoản và dữ liệu

phần 2:

- dùng chung mật khẩu có thể khiến nhiều tài khoản bị chiếm, gọi là credential stuffing
- zero-knowledge giúp máy chủ không đọc được dữ liệu đã mã hóa
- cấu hình mật khẩu: 16 ký tự, bật chữ hoa, chữ thường, chữ số và ký tự đặc biệt
- tạo 3 mật khẩu riêng cho github, vercel và email

phần 3: 

- nên dùng authenticator vì sms có nguy cơ sim swapping và cần sóng điện thoại
- vào settings, chọn password and authentication, bật two-factor authentication
- chọn authenticator app, quét qr bằng google authenticator và nhập mã 6 số
- lưu mã khôi phục trong trình quản lý mật khẩu hoặc két an toàn

phần 4: 

- 2 secrets bị hardcode là api key và database password

- trước khi push cần kiểm tra code không có secrets thật, .env đã được gitignore, .env.example chỉ có tên biến và kiểm tra git diff

