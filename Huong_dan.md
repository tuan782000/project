# Thêm icon cho thanh title:
- lấy icon từ figma xuống. Sau đó đưa lên trang: https://realfavicongenerator.net/
- Trang này giúp tạo Favicon hỗ trợ nền trong suốt
- Nhớ kiểm tra các đường dẫn thay cho đúng tên thư mục để tránh không hiển thị hình ảnh

# Thêm font cho toàn bộ trang web:
- fonts này là "Gordita", download về zip, xong up lên https://transfonter.org/ chuyển đổi
- sau khi chuyển đổi copy toàn bộ fonts bỏ vào assets, sau đó link file css đó vào trang html, bên css chính dùng font-family là "Gordita" font-family: Gordita, sans-serif;



# Cấu hình Sass cho dự án:

Bước 1 khỏi tạo, -y để đồng ý tất cả: npm init -y 
Bước 2 vào package.json, thêm câu lệnh biên dịch sass: "sass": "sass scss:assets/css -w"
(Lưu ý: ở bước này tùy dự án mà cấu hình cho đúng mục đích).

Chú ý: Thư mục scss đặt ngoài file assets

file main.scss là nơi sử dụng các file scss trong thư mục base

# Học cách tái sử dụng Header, Footer trong trang

Sử dụng JavaScript để giải quyết vấn đề này

Các file html nào dùng chung mình sẽ để vào thư mục template

