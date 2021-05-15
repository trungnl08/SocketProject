# SocketProject
VAI TRÒ:
- Lê Ngọc Trung: tạo giao diện, tạo kết nốt chat socket với port và ip mặc định, viết báo cáo
- Nguyễn Đắc Sơn : update giao diện, thêm input truyền port từ bàn phím, thêm button tạo kết nối giữa client và server
- Đỗ Quang Huynh: thêm button đóng kết nối ở client và server, clean code, fix bug

CÁCH THỨC HOẠT ĐỘNG:
-Khởi chạy song song 2 file chatServer.java và chatClient.java
-Nhập port vào server, tạo kết nối. Phía client sẽ nhập đúng port để kết nối, nếu nhập sai sẽ ở trạng thái connecting do không thể kết nối được server với port đã nhập.
-Khi kết nối thành công , có thể chat giữa client và server.
![Screen Shot 2021-05-15 at 12 24 38 PM](https://user-images.githubusercontent.com/70845041/118349372-865fe080-b57a-11eb-80dc-4c9eec19e0bb.png)
-Khi server/client muốn đóng kết nối thì click button ngắt kết nối.

LOG COMMIT:
![Screen Shot 2021-05-15 at 12 42 56 PM](https://user-images.githubusercontent.com/70845041/118349489-29b0f580-b57b-11eb-8212-de107a235941.png)
