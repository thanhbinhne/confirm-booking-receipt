eFMS · Booking Receipt mobile prototype — phiên bản tham khảo file người dùng

CÁCH MỞ
Giải nén và mở index.html bằng Chrome, Edge, Firefox hoặc Safari.
Giữ index.html, styles.css, app.js và thư mục assets ở cùng vị trí.
Không cần cài đặt, không cần mạng. assets chứa font Inter trích từ file tham khảo.

LUỒNG THỬ
Home → Duyệt chứng từ → Approval Center → Booking Receipt → Chi tiết.
Home → Chuông thông báo → Thông báo của booking → Chi tiết booking tương ứng.
Menu bên trái chuyển nhanh qua 6 màn hình để xem thiết kế.

CHI TIẾT
Các nhóm General, Cargo Information, Customs, Good Info, Buying & Selling,
Stages và Attach Files được hiển thị đầy đủ theo màn hình web đã trao đổi.
Mở dòng phí và Stage để xem toàn bộ thông tin.
Bấm file để xem nội dung chứng từ mô phỏng.
Rê chuột hoặc chạm trường để đọc chú thích tại khung bên phải.
Nút Ẩn/Hiện vùng chú thích tắt/bật đường viền gợi ý.

CONFIRM
Kéo Header chi tiết sang phải tối thiểu 90px, hoặc dùng nút Confirm Booking.
Có 5 giây Undo trước khi trạng thái mẫu thay đổi.
Rời màn hình hoặc chuyển ứng dụng xuống nền sẽ hủy hành động đang chờ.
Confirm không Convert booking thành Job/Shipment.

PHẠM VI
Đây là phương án giao diện để trao đổi, chưa phải đặc tả nghiệp vụ đã chốt.
Không gọi API, không kiểm tra quyền thật, không phát notification thật.
Các bản ghi và file xem trước là dữ liệu mẫu; chỉ lưu trong bộ nhớ phiên mở file.
Tải lại trang hoặc bấm Khôi phục dữ liệu mẫu để bắt đầu lại.
Đã kiểm tra cú pháp và logic dựng nội dung / tìm kiếm / lọc / Confirm / Undo.
Chưa kiểm tra hiển thị trực tiếp bằng trình duyệt do giới hạn môi trường.
