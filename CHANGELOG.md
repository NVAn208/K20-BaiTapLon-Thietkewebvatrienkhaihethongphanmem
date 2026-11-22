# Changelog

Tất cả các thay đổi quan trọng của dự án sẽ được ghi lại tại đây.

## [Bài Tập Lớn]
- Khởi tạo dự án trang cá nhân cơ bản.
- Tạo cấu trúc HTML ban đầu với phần giới thiệu cá nhân.
- Thêm file CSS để định dạng giao diện và tạo layout đẹp hơn.
- Cập nhật bố cục menu, tiêu đề và ảnh đại diện.

## [2026-11-13]
### Thêm vào
- Thêm form gửi lời nhắn với các trường họ tên, email và nội dung.
- Thêm trang `ket-qua.html` làm trang kết quả cho luồng form.
- Thêm bảng thông tin học tập và các thẻ giới thiệu dự án C++, hồ sơ GitHub, website thực hành.
- Thêm nhóm kỹ năng trình bày bằng các thẻ responsive.

### Thay đổi
- Làm mới giao diện trang chính, form liên hệ và trang kết quả theo cùng tông màu.
- Làm mới bảng học tập; trên màn hình nhỏ các hàng chuyển thành thẻ có nhãn cho từng cột.
- Trang trí khu vực dự án với nền gradient, điểm nhấn trang trí và các thẻ dự án đồng bộ.
- Đồng bộ nền gradient cho các phần học tập, dự án, kỹ năng và liên hệ.
- Bổ sung trạng thái hover cho hàng trong bảng, thẻ dự án và liên kết dự án.
- Thu gọn ảnh đại diện trên header thành logo tròn và thêm gạch chân chuyển động cho menu.
- Bố trí thông tin footer theo hàng ngang và cho phép tự xuống dòng khi màn hình hẹp.
- Cập nhật README, AI Log và Release Notes theo nội dung hiện tại của dự án.
- Bổ sung `docs/evidence.md` ghi lại các bước kiểm tra form thủ công.

### Cải tiến
- Tối ưu bố cục các phần nội dung cho màn hình nhỏ và hỗ trợ tùy chọn giảm chuyển động.
- Bổ sung trạng thái focus cho các thành phần tương tác.

### Ghi chú
- Form dùng phương thức GET đến `ket-qua.html`; dữ liệu có thể xuất hiện trên URL.
- Form chỉ phục vụ minh họa, không gửi email, không lưu dữ liệu và trang kết quả không xử lý các trường đã gửi.
- Liên kết "Trang Web này" trong thẻ dự án hiện chưa có địa chỉ đích và cần được cập nhật.
