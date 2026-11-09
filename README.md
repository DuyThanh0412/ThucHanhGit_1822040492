# Bài thực hành Git & GitHub

- Họ tên: Nguyễn Duy Thanh
- Mã số sinh viên: 1822040492
- Ngành: Công nghệ thông tin
- Trường: Đại học Công nghệ Đồng Nai

## Chạy website
Mở `index.html` bằng trình duyệt. Không cần cài Node.js.
Font Google là tùy chọn; khi không có Internet, website dùng font Arial.

## Cá nhân hóa
Sửa mã số sinh viên trong `index.html`, file này và tên thư mục trước khi nộp bài.

## Làm theo yêu cầu bài tập
Để minh họa đúng việc thêm giao diện trên nhánh riêng:
1. Giữ riêng `style.css`, tạm bỏ dòng `<link rel="stylesheet" href="style.css">` trong HTML.
2. Commit đầu tiên chỉ gồm README.md và index.html.
3. Tạo nhánh `feature/them-giao-dien`, đưa style.css vào thư mục, thêm lại dòng link và commit.
4. Push nhánh, chuyển về main, merge rồi push main.

## Đưa website lên GitHub Pages
Sau khi push đủ các file lên main: mở repository → Settings → Pages.
Chọn Deploy from a branch, nhánh main, thư mục / (root), rồi Save.
Chờ GitHub cung cấp đường dẫn website. Repository và website là hai đường dẫn riêng.
