# math — Web app học Toán

Web app học Toán, khởi đầu với **Xác suất – Thống kê**. Định hướng phát triển thành nền tảng học mọi chủ đề Toán (đại số, giải tích, hình học, ...).

## Trang web

Sau khi bật GitHub Pages, truy cập tại: **https://linkhoang19931-hub.github.io/math/**

## Công nghệ

- HTML/CSS/JS thuần, không cần build.
- [KaTeX](https://katex.org/) (qua CDN) để render công thức Toán.
- Font: Spectral + Be Vietnam Pro (Google Fonts).

## Cấu trúc

- `index.html` — trang hiện tại (Xác suất – Thống kê).

Khi mở rộng nhiều chủ đề, dự kiến `index.html` trở thành trang chủ (hub) và mỗi chủ đề là một trang riêng.

## Phát triển cục bộ

Chỉ cần mở `index.html` bằng trình duyệt, hoặc chạy một server tĩnh:

```bash
python -m http.server 8000
# rồi mở http://localhost:8000
```
