# Trang cá nhân của An

Bài tập lớn cá nhân môn Thiết kế web và Triển khai hệ thống phần mềm. Dự án là một trang giới thiệu cá nhân được xây dựng bằng HTML và CSS thuần.

## Tính năng

- Thanh điều hướng và phần giới thiệu cá nhân.
- Ảnh đại diện hiển thị dạng hình tròn.
- Form gửi lời nhắn gồm họ tên, email và nội dung; có kiểm tra dữ liệu bắt buộc và độ dài.
- Giao diện responsive cho màn hình máy tính và điện thoại.
- Hiệu ứng hover/focus và hỗ trợ giảm chuyển động theo cài đặt của hệ điều hành.

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
└── index.html              # Trang chính
```

## Chạy dự án

Không cần cài đặt thư viện. Mở `index.html` bằng trình duyệt hoặc chạy một máy chủ tĩnh tại thư mục dự án.

## Lưu ý về form

Form hiện dùng `GET` và trỏ đến `ket-qua.html`. Đây là form thực hành, chưa gửi email và không lưu dữ liệu lên máy chủ; dữ liệu form sẽ được thêm vào URL. Cần tạo trang `ket-qua.html` để xử lý/hiển thị kết quả khi gửi form.

## Tài liệu

- [Changelog](./CHANGELOG.md)
- [AI Log](./docs/AI_LOG.md)
- [Release Notes](./docs/RELEASE_NOTES.md)
