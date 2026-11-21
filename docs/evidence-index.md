# Evidence kiểm thử

## Thông tin kiểm thử

- Ngày kiểm thử: 2026-11-13.
- Cách chạy: mở các trang HTML trực tiếp bằng trình duyệt.
- Phạm vi: trang chính, bảng học tập responsive, khu vực dự án, form liên hệ và trang kết quả.
- Dữ liệu nhập trong lần kiểm thử hợp lệ là dữ liệu giả lập, không phải thông tin cá nhân thật.

## Kết quả

| Mã | Bước kiểm thử | Kết quả mong đợi | Kết quả |
| --- | --- | --- | --- |
| E-01 | Mở [index.html](../index.html). | Trang chính hiển thị menu, phần giới thiệu, form và footer. | Đạt | Ming chứng: https://nvan208.github.io/K20-BaiTapLon-Thietkewebvatrienkhaihethongphanmem/
| E-02 | Bấm gửi khi để trống các trường trong form. | Trình duyệt chặn gửi do các trường bắt buộc chưa được điền; URL không đổi. | Đạt |
| E-03 | Nhập họ tên, email hợp lệ và lời nhắn đủ độ dài, sau đó gửi form. | Trình duyệt chuyển đến `ket-qua.html`; các giá trị form xuất hiện trong query string của URL. | Đạt | Minh chứng: https://nvan208.github.io/K20-BaiTapLon-Thietkewebvatrienkhaihethongphanmem/ket-qua.html?fullname=Nguy%E1%BB%85n+V%C4%83n+An&email=nguyenvanan16032008pnkt%40gmail.com&message=hjgjhgujyuguj
| E-04 | Kiểm tra trang [ket-qua.html](../ket-qua.html) sau khi gửi. | Hiển thị tiêu đề kết quả | Đạt | Minh chứng: https://nvan208.github.io/K20-BaiTapLon-Thietkewebvatrienkhaihethongphanmem/ket-qua.html?fullname=Nguy%E1%BB%85n+V%C4%83n+An&email=nguyenvanan16032008pnkt%40gmail.com&message=hjgjhgujyuguj
| E-05 | Kiểm tra trang chính ở viewport 1280 × 900. | Bảng học tập hiển thị dạng bảng; khu vực dự án hiển thị ba thẻ trên một hàng. | Đạt |
| E-06 | Kiểm tra trang chính ở viewport 390 × 844. | Ba hàng học tập chuyển thành thẻ có nhãn; khu vực dự án xếp một cột và trang không tràn ngang. | Đạt |
| E-07 | Kiểm tra khu vực dự án trên desktop và mobile. | Nền `.section-alt`, ba thẻ dự án và liên kết vẫn hiển thị trong bố cục responsive. | Đạt |
| E-08 | Kiểm tra nhóm kỹ năng và các nền ở viewport 1280 × 900, 390 × 844. | Sáu kỹ năng hiển thị thành lưới ba cột trên desktop, một cột trên mobile; nền Học tập, Dự án, Kỹ năng và Liên hệ dùng cùng gradient. | Đạt |

## Chưa kiểm tra 
- Thông tin liên hệ chưa được gửi do chỉ là mô phỏng

## Ghi chú

- Form sử dụng phương thức `GET`, không gửi email và không lưu dữ liệu lên máy chủ.
- Trang kết quả hiện không đọc hoặc hiển thị lại các giá trị đã gửi.
- Kiểm tra responsive được thực hiện bằng cách đổi viewport trong trình duyệt, không phải trên thiết bị di động thật.
- Nền các khu vực được so sánh qua computed styles trong trình duyệt.
- Các kết quả trên là kiểm thử thủ công trên trình duyệt; dự án chưa có bộ kiểm thử tự động.