# Golf Vegas — bản xem trước website

Bản HTML tĩnh của website **Golf Vegas** (Integrated Media Solutions), doanh nghiệp
truyền thông ngoài trời OOH/DOOH tại TP.HCM.

## 🔗 Xem tại: **https://ali33.github.io/golfvegas.vn_html/**

| Trang | Đường dẫn |
|---|---|
| Trang chủ | https://ali33.github.io/golfvegas.vn_html/ |
| Giới thiệu | https://ali33.github.io/golfvegas.vn_html/gioi-thieu/ |
| Dịch vụ | https://ali33.github.io/golfvegas.vn_html/dich-vu/ |
| Khách hàng | https://ali33.github.io/golfvegas.vn_html/khach-hang/ |
| Tin tức | https://ali33.github.io/golfvegas.vn_html/tin-tuc/ |
| Liên hệ | https://ali33.github.io/golfvegas.vn_html/lien-he/ |

## Đây là gì

Repo này **chỉ chứa HTML tĩnh** đã xuất, dùng để xem trước giao diện. Mã nguồn
thật là một theme WordPress block (FSE) nằm ở repo riêng; bản tĩnh này được sinh
tự động từ đó, không sửa tay.

## Điểm Lighthouse

Đo ở chế độ mobile trên máy phát triển:

| Danh mục | Điểm |
|---|---|
| SEO | 100 |
| Accessibility | 100 |
| Best Practices | 100 |
| Performance | 89–90 |

LCP 2.1s · CLS 0.012 · TBT 0ms. Riêng Performance đo trên máy local nên chưa phản
ánh đúng — thời gian phản hồi server ở đó lên tới 5–10 giây, cần đo lại trên
hosting thật.

## Kỹ thuật

- Font **Be Vietnam Pro** self-host, có subset riêng cho dấu tiếng Việt
- Ảnh định dạng **WebP**, ảnh hero có `srcset` ba khổ (điện thoại chỉ tải ~42KB)
- Bảng màu lấy trực tiếp từ file logo: cam `#FD4401`, mực `#202020`
- Toàn bộ tương phản chữ đạt chuẩn WCAG AA
- Đường dẫn tương đối nên chạy được ở cả đường dẫn con lẫn tên miền riêng

## Lưu ý về bản xem trước

- **Ảnh minh hoạ là ảnh tạm** mượn từ goldsungroup.com.vn, chưa phải ảnh dự án
  của Golf Vegas. Cần thay bằng ảnh thật trước khi phát hành chính thức.
- Nội dung dự án và bài viết **chưa có** — các khối tương ứng đang để trạng thái
  "đang cập nhật".
- **Bản tiếng Anh chưa dựng.**
- Tìm kiếm, phân trang và mọi chức năng cần máy chủ đều không hoạt động, vì đây
  là ảnh chụp tĩnh.
