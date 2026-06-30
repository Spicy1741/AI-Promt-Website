# AI4LEARNING

Trang giới thiệu khóa học **AI4LEARNING** — khóa học AI dành cho sinh viên, giúp học viên sử dụng các công cụ AI (ChatGPT, Gemini, Claude...) một cách hiệu quả và có trách nhiệm.

Trang web tĩnh, không backend, không framework — chỉ HTML, CSS và Vanilla JavaScript.

## Demo

Sau khi bật GitHub Pages (xem hướng dẫn dưới), trang sẽ chạy tại:

```
https://<tên-người-dùng>.github.io/<tên-repo>/
```

## Cấu trúc dự án

```
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    ├── images/
    └── icons/
```

## Chạy thử trên máy (local)

1. Cài extension **Live Server** trong VS Code.
2. Mở thư mục dự án trong VS Code.
3. Click phải vào `index.html` → **Open with Live Server**.

## Deploy lên GitHub Pages

1. Tạo repo mới trên GitHub (public).
2. Trong thư mục dự án, chạy:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<tên-người-dùng>/<tên-repo>.git
   git push -u origin main
   ```
3. Vào repo trên GitHub → **Settings** → **Pages**.
4. Ở mục **Source**, chọn branch `main` và folder `/ (root)`, rồi **Save**.
5. Sau 1-2 phút, trang sẽ live tại `https://<tên-người-dùng>.github.io/<tên-repo>/`.

## Đăng ký khóa học

Nút "Đăng ký ngay" trên trang dẫn đến Google Form đăng ký, không cần xử lý backend hay email.

## Công nghệ sử dụng

- HTML5
- CSS3 (responsive, animation, custom properties)
- Vanilla JavaScript (scroll reveal, accordion, mobile nav)
- Google Fonts (Sora, Inter)
- Font Awesome (qua CDN)
