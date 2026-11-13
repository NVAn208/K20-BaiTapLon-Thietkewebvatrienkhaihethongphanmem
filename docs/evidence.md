# Evidence kiểm thử

## Thông tin kiểm thử

- Ngày kiểm thử: 2026-11-13.
- Cách chạy: mở các trang HTML trực tiếp bằng trình duyệt.
- Phạm vi: trang chính, kiểm tra form liên hệ và điều hướng đến trang kết quả.
- Dữ liệu nhập trong lần kiểm thử hợp lệ là dữ liệu giả lập, không phải thông tin cá nhân thật.

## Kết quả

| Mã | Bước kiểm thử | Kết quả mong đợi | Kết quả |
| --- | --- | --- | --- |
| E-01 | Mở [index.html](../index.html). | Trang chính hiển thị menu, phần giới thiệu, form và footer. | Đạt |
| E-02 | Bấm gửi khi để trống các trường trong form. | Trình duyệt chặn gửi do các trường bắt buộc chưa được điền; URL không đổi. | Đạt |
| E-03 | Nhập họ tên, email hợp lệ và lời nhắn đủ độ dài, sau đó gửi form. | Trình duyệt chuyển đến `ket-qua.html`; các giá trị form xuất hiện trong query string của URL. | Đạt |
| E-04 | Kiểm tra trang [ket-qua.html](../ket-qua.html) sau khi gửi. | Hiển thị tiêu đề kết quả, lưu ý đây là nội dung minh họa và liên kết quay lại form. | Đạt |

## Ghi chú

- Form sử dụng phương thức `GET`, không gửi email và không lưu dữ liệu lên máy chủ.
- Trang kết quả hiện không đọc hoặc hiển thị lại các giá trị đã gửi.
- Các kết quả trên là kiểm thử thủ công trên trình duyệt; dự án chưa có bộ kiểm thử tự động.