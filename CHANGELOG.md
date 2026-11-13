# Changelog

Tất cả các thay đổi quan trọng của dự án sẽ được ghi lại tại đây.

## [V1]
- Khởi tạo dự án trang cá nhân cơ bản.
- Tạo cấu trúc HTML ban đầu với phần giới thiệu cá nhân.
- Thêm file CSS để định dạng giao diện và tạo layout đẹp hơn.
- Cập nhật bố cục menu, tiêu đề và ảnh đại diện.

## [2026-11-13]
### Added
- Thêm form gửi lời nhắn với các trường họ tên, email và nội dung.
- Thêm trang `ket-qua.html` làm trang kết quả cho luồng form.

### Changed
- Làm mới giao diện trang chính, form liên hệ và trang kết quả theo cùng tông màu.
- Bố trí thông tin footer theo hàng ngang và cho phép tự xuống dòng khi màn hình hẹp.
- Cập nhật README về cấu trúc dự án, cách chạy và giới hạn của form.

### Improved
- Tối ưu bố cục cho màn hình nhỏ và hỗ trợ tùy chọn giảm chuyển động.
- Bổ sung trạng thái focus cho các thành phần tương tác.

### Notes
- Form dùng phương thức GET đến `ket-qua.html`; dữ liệu có thể xuất hiện trên URL.
- Form chỉ phục vụ minh họa, không gửi email, không lưu dữ liệu và trang kết quả không xử lý các trường đã gửi.
