### Công nghệ

- **Xây dựng:** Node.js, Express
- **Thư viện và công cụ sử dụng:**
  - `"bcrypt": "Công cụ mã hóa mật khẩu để bảo vệ thông tin người dùng"`
  - `"cookie-parser": "Middleware để xử lý cookie trong Express"`
  - `"cors": "Middleware cho phép các domain khác nhau có thể gửi yêu cầu tới server"`
  - `"dotenv": "Thiết lập biến môi trường cho ứng dụng"`
  - `"express": "Framework Node.js để xây dựng các ứng dụng web"`
  - `"joi": "Thư viện validation schema cho dữ liệu trong Node.js"`
  - `"mongoose": "Thư viện tương tác với MongoDB dựa trên schema"`
  - `"multer": "Middleware để xử lý tải lên file trong Express"`
  - `"nodemon": "Công cụ giúp tự động khởi động lại server khi có thay đổi trong mã nguồn"`
  - `"socket.io": "Thư viện để xử lý real-time communication qua WebSockets"`

### Cấu trúc dự án

- **Thư mục `src`:** Chứa mã nguồn chính

  - `db/`: Chứa các tập tin liên quan đến cơ sở dữ liệu của dự án, chẳng hạn như bảng, truy vấn và mô hình dữ liệu.
  - `middleware/`: Chứa các phần mềm trung gian (middleware) được sử dụng để xử lý các yêu cầu HTTP trước khi chúng được chuyển đến bộ điều khiển.
  - `models/`: Chứa các mô hình dữ liệu được sử dụng để tương tác với cơ sở dữ liệu.
  - `node_modules/`: Chứa các thư viện Node.js của bên thứ ba được sử dụng bởi dự án.
  - `router/`: Chứa các bộ định tuyến (router) được sử dụng để định tuyến các yêu cầu HTTP đến các bộ điều khiển thích hợp.
  - `socket/`: Chứa các tập tin liên quan đến tính năng socket.io của dự án.
  - `validate/`: Chứa các hàm xác thực được sử dụng để kiểm tra dữ liệu đầu vào.
  - `.env`: Tập tin này chứa các biến môi trường được sử dụng bởi dự án.
  - `.gitignore`: Tập tin này chứa danh sách các tập tin và thư mục không nên được theo dõi bởi hệ thống kiểm soát phiên bản Git.
  - `README.md`: Tập tin này chứa tài liệu hướng dẫn sử dụng cho dự án.
  - `server.js`: Tập tin này chứa mã khởi động cho dự án.

- `.gitignore`: Danh sách các file và thư mục Git nên bỏ qua.
- `package.json`: File cấu hình npm, chứa danh sách dependencies và scripts.
