# SocketProject
VAI TRÒ:
- Lê Ngọc Trung: tạo giao diện, tạo kết nốt chat socket với port và ip mặc định, viết báo cáo
- Nguyễn Đắc Sơn : update giao diện, thêm input truyền port từ bàn phím, thêm button tạo kết nối giữa client và server
- Đỗ Quang Huynh: thêm button đóng kết nối ở client và server, clean code, fix bug

CÁCH THỨC HOẠT ĐỘNG:
Khởi chạy song song 2 file chatServer.java và chatClient.java
Nhập port vào server, tạo kết nối. Phía client sẽ nhập đúng port để kết nối, nếu nhập sai sẽ ở trạng thái connecting do không thể kết nối được server với port đã nhập.
Khi kết nối thành công , có thể chat giữa client và server.
Khi server/client muốn đóng kết nối thì click button ngắt kết nối.

LOG COMMIT:
