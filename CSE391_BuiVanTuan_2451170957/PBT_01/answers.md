Câu A1:
1.
B1:Trình duyệt kiểm tra cache hỏi DNS Lookup tìm địa chỉ của máy chủ shopee.vn
B2:Thiết lập kết nối (TCP/IP) (và TLS Handshake để bảo mật HTTPS) giữa máy tính của bạn và server Shopee
B3:Trình duyệt gửi request(thường là GET /)kèm header(Host,User-Agent,Cookie..)đến server
B4:Server xử lý và trả HTTP Response gồm:HTML + CSS + JavaScript + status code(200 OK)
B5:Trình duyệt nhận các file(HTML, CSS, JS)và thực hiện quá trình Render để hiển thị giao diện hoàn chỉnh cho người dùng
2.
Trong Google Chrome, tab Network hiển thị:
1.Danh sách tất cả HTTP requests và responses giữa Client và Server
2.Status Code (200, 404, 500…) → kết quả phản hồi từ server
3.Thời gian tải của từng request và tổng thời gian load trang
4.Loại tài nguyên (HTML, CSS, JS, ảnh…)
5.Kích thước dữ liệu truyền tải
![alt text](<Screenshot 2026-04-19 235752.png>) 
![alt text](<Screenshot 2026-04-19 235838.png>)
Câu A2:
Trang web bị SEO thấp vì không sử dụng Semantic HTML,dùng div cho mọi thứ, khiến Google không hiểu cấu trúc nội dung
Các lỗi semantic:
-không dùng <header> cho phần đầu.Google khong biết đây la phần đầu trang
-menu khong dùng <nav>. Sai semantic cho điều hướng 
-nội dung chính không dùng <main>. Không xác định được vùng content chính
-sản phẩm không dùng <article>
-tiêu đề không dùng heading(<h1>,<h2>).Google không biết đây là tiêu đề quan trọng
Câu A3:
Hộp 1
Text A Text B
Hộp 2
Text C Text D
Hộp 3
Câu A4:
-Sự khác nhau giữa <thead>,<tbody>,<tfoot>
+<thead> chứa phần tiêu đề của bảng , gồm các<th>,xác định tên các cột
+<tbody> chứa dữ liệu chính của bảng, gồm nhiều hàng<tr> với các ô<td>
<tfoot>chứa phần tổng kết/kết luận
-Không nên dùng table để layout cho trang web vì:
+sai mục đính semantic
+khó semantic
+code phức tạp, khó bảo trì
+hiệu năng kém