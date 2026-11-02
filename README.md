# Pơxrăm Nơ̆r Bahnar – Website tĩnh cho Vercel

Mỗi trang nằm trong một thư mục riêng có file `index.html`, nên địa chỉ trang khớp với link sẵn có:

| Địa chỉ        | Trang                     |
|----------------|---------------------------|
| `/`            | Trang chủ (Tiếng Việt)    |
| `/en/`         | Home (English)            |
| `/vi-unit-1/` … `/vi-unit-12/` | Bài 1–12 (Tiếng Việt) |
| `/en-unit-1/` … `/en-unit-12/` | Unit 1–12 (English)   |

Các file thêm vào: `style.css` (font, chống cuộn ngang, thu nhỏ tiêu đề trên điện thoại),
`404.html` (trang báo lỗi), `vercel.json` (cấu hình đường dẫn).

Muốn sửa nội dung bài nào thì mở `ten-thu-muc/index.html` và sửa phần giữa thẻ `<body>`.
