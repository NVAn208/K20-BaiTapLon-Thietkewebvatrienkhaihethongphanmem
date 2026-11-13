# Trang cá nhân của An

Bài tập lớn cá nhân môn Thiết kế web và Triển khai hệ thống phần mềm. Dự án là trang cá nhân tĩnh được xây dựng bằng HTML và CSS thuần.

## Tính năng

- Trang chính có menu điều hướng, phần giới thiệu và ảnh đại diện.
- Form liên hệ gồm họ tên, email và lời nhắn; trình duyệt kiểm tra trường bắt buộc, định dạng email và độ dài nội dung.
- Trang kết quả có thông báo xác nhận, lưu ý về tính minh họa và liên kết quay lại form.
- Giao diện thích ứng với màn hình nhỏ, có trạng thái hover/focus và hỗ trợ cài đặt giảm chuyển động.
- Footer hiển thị thông tin theo hàng ngang khi đủ không gian và tự xuống dòng trên màn hình hẹp.

## Cấu trúc dự án

```text
.
├── assets/                 # Ảnh đại diện
├── css/
│   └── style.css           # Giao diện và responsive
├── docs/
│   ├── AI_LOG.md           # Nhật ký quá trình phát triển
│   └── RELEASE_NOTES.md    # Ghi chú phát hành
├── CHANGELOG.md            # Lịch sử thay đổi
├── index.html              # Trang chính và form liên hệ
└── ket-qua.html            # Trang kết quả gửi form
```

## Chạy dự án

Không cần cài đặt thư viện hoặc bước build. Mở `index.html` bằng trình duyệt hoặc chạy máy chủ tĩnh tại thư mục dự án.

## Lưu ý về form

Form dùng phương thức `GET` để mở `ket-qua.html`; dữ liệu nhập có thể xuất hiện trên URL. Đây chỉ là luồng minh họa cho bài tập: không gửi email, không lưu dữ liệu lên máy chủ và trang kết quả không xử lý nội dung đã nhập. Không gửi thông tin cá nhân thật.

## Tài liệu

- [Changelog](./CHANGELOG.md)
- [AI Log](./docs/AI_LOG.md)
- [Release Notes](./docs/RELEASE_NOTES.md)
