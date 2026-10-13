# Hồ Sơ Scan

App cá nhân để scan giấy tờ (CCCD, CMND, kết hôn, khai sinh, khai tử, hộ khẩu, sổ đỏ, giấy mua bán), tự xếp thư mục theo tên người, đối chiếu dữ liệu lệch giữa các giấy tờ và in A4.

## Cài lên iPhone

1. Mở bằng **Safari**: `https://tuantapvibecoding.github.io/ho-so-scan/`
2. Bấm nút **Chia sẻ**, chọn **Thêm vào MH chính**.
3. Mở app từ icon trên màn hình chính.

## Dữ liệu

- Mọi giấy tờ lưu ngay trên iPhone, không gửi lên mạng.
- Đọc chữ chạy ngay trên máy. Lần đầu cần mạng để tải bộ đọc chữ tiếng Việt (khoảng 2–3 MB).
- Sao lưu định kỳ: bấm **⚙ → Sao lưu ra file** và lưu vào Tệp hoặc iCloud Drive. Xoá app khỏi màn hình chính sẽ mất dữ liệu.

## Cập nhật app

1. Sửa hoặc thay file trong kho này (**Add file → Upload files**, chọn file mới cùng tên để ghi đè).
2. Mỗi lần cập nhật, tăng số `VERSION` trong `sw.js` (ví dụ `v1.0.0` → `v1.0.1`).
3. Khoảng 1–2 phút sau, đóng hẳn app trên iPhone rồi mở lại là có bản mới.

## Các file

| File | Vai trò |
|---|---|
| `index.html` | Toàn bộ app (giao diện, cắt ảnh, đọc chữ, so sánh, in) |
| `sw.js` | Cho app chạy offline và tự cập nhật |
| `manifest.webmanifest` | Tên, icon, màu khi cài lên màn hình chính |
| `*.png` | Icon app |
