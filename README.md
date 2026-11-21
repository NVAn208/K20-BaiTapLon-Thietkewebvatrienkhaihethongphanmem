# Trang cá nhân của An

Bài tập lớn cá nhân môn Thiết kế web và Triển khai hệ thống phần mềm. Dự án là trang cá nhân tĩnh được xây dựng bằng HTML và CSS thuần.

## Sản Phẩm
- Sản phẩm này là Trang Fortfolio Báo cáo trình bày trang web cá nhân của một sinh viên CNTT.
## Tính Năng 
- Trang chính có menu điều hướng, phần giới thiệu và ảnh đại diện.
- Phần học tập trình bày học kỳ, học phần và sản phẩm, trên điện thoại mỗi dòng chuyển thành thẻ có nhãn.
- Phần dự án giới thiệu bài học C++, hồ sơ GitHub và website HTML/CSS bằng các thẻ responsive.
- Nhóm kỹ năng hiển thị dưới dạng các thẻ nhỏ có điểm nhấn và hiệu ứng hover.
- Form liên hệ gồm họ tên, email và lời nhắn, có ví dụ minh họa về thông tin cần điền, trình duyệt kiểm tra trường bắt buộc, định dạng email và độ dài nội dung.
- Trang kết quả có thông báo xác nhận.
- Giao diện thích ứng với màn hình nhỏ, có hiệu ứng hover/focus cho menu, ảnh, bảng và thẻ dự án.
- Footer hiển thị thông tin theo hàng ngang khi đủ không gian và tự xuống dòng trên màn hình hẹp.
## Cách mở là mở thủ công trực tiếp trên URL đã triển khai trên gihub bằng cách vào phần Action, tiếp theo nhấn vào pages-build-deployment trên cùng trong danh sách All workflows và nhấn URL bên dưới mục deploy  hoặc mở trực tiếp tệp .html trong file gốc trên máy.
## DEMO
### Chạy trên máy
- B1:Tìm và giải nén thư mục có tên "K20-BaiTapLon-Thietkewebvatrienkhaihethongphanmem-main"vừa tải về từ github.
- B2:Nhấn đúp chuột trái truy cập thư mục
- B3:Tìn file có tên "index.html", sau đó nhấn chuột phải chọn "Oqen with" và chọn trình duyệt để mở file.
### DEMO công khai
- B1:Vào phần Actions trên thanh điều hướng
- B2:Tại mục All workflows chọn pages build and deployment mới nhất
- B3:Tại pages-build-deployment nhấn truy câp URL dưới phần deploy
## Cấu trúc dự án

```
fortfolio/ 
|
├── assets/                 # Ảnh đại diện
│   ├── *.jpg               # Ảnh đại diện
│   └── *.png               # Hình minh họa dự án
├── css/
│   └── fortfolio.css       # Giao diện và responsive
├── docs/
│   ├── AI_LOG.md           # Nhật ký quá trình phát triển
│   ├── evidence-index.md   # Ghi nhận kiểm thử thủ công
│   └── RELEASE_NOTES.md    # Ghi chú phát hành
├── README.md               # Hướng dẫn dụ án
├── CHANGELOG.md            # Lịch sử thay đổi
├── index.html              # Trang chính và form liên hệ
└── ket-qua.html            # Trang kết quả gửi form
```

## ĐÃ kiểm tra
- URL sản phẩm hoạt động bình thường
- cấu trúc bên trong dự án y hệt như mô tả
- có thể mở kiểm thử trực tiếp bằng 2 phương thức nêu trên và đưa ra kết quả như nhau
- moitj thành phần, nội dung đều đủ 
## Giới hạn/ chưa kiểm tra
- Phần kết quả liên hệ chỉ là mô phỏng còn thông báo hoàn thành không phải là kết quả thực
- Một vài phần nội dung chưa xác thực hoàn toàn
## Nguồn và khai báo AI
### Nguồn
- Sử dụng mã nguồn khung HTML cơ bản (source code) (HTML5) trong tệp index.html và ket-qua.html
- Ảnh minh họa và đường dẫn cho "Chương Trình C++ cơ bản" của dự án lấy từ trang web ngoài
- Ảnh chụp màn hình và đường dẫn hồ sơ GitHub, trang web tự thực hiện
- Cách viết code:có tham khảo W3Schools, MDN, YouTube, StackOverflow, bạn bè, bài giảng và giảng viên trên lớp.
- Nội dung chữ: phần giới thiệu bản thân và mô tả dự án là bản thân tôi tự viết
### Khai bái AI
- Có sử dụng AI hỗ trợ (Copilot)
- Sử dụng AI để soát lỗi và nâng cấp giao diện người xem như vẽ thêm dấu tích xác nhận kết quả trong ket-qua.html
