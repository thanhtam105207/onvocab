# ENT303 - Top Notch 3 Master Hub — FULL v3

Bản FULL này bắt đầu từ đúng project GitHub Pages/PWA trước đó và thêm giao diện học mới.

## Có gì mới
- Trang chủ riêng với ảnh cá nhân (upload hoặc Ctrl+V), chuỗi ngày học và thống kê.
- Chuỗi chỉ được tính khi hoàn thành một bài Quiz/Nghe chép/Quiz 2 cột.
- Thống kê: tổng từ, đã học, chưa học.
- Quiz có 2 bước: chọn **từ chưa thuộc / toàn bộ**, rồi chọn **Quiz Slide / Quiz 2 cột / Nghe chép**.
- Bỏ nút Cài app trong giao diện; trình duyệt vẫn có thể cung cấp Install/Add to Home Screen trong menu của nó.
- Sao lưu/khôi phục bằng JSON để chuyển toàn bộ dữ liệu giữa các máy.
- Thanh điều hướng cố định phía dưới theo kiểu app học tập.
- Có màn hình loading cute và icon/emoji thân thiện.

## Sao lưu qua máy khác
Trang chủ → **Xuất bản sao lưu** → giữ file JSON. Trên máy khác → **Khôi phục từ file**.

GitHub Pages là static site nên dữ liệu học mặc định nằm trong LocalStorage của từng trình duyệt; file backup là cách chuyển dữ liệu giữa các máy mà không cần tài khoản/server.

## GitHub Pages
Upload toàn bộ file/thư mục lên repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
