---
title: quy-trinh-3-buoc
date: 2026-11-04T14:12:40+07:00
lastmod: 2026-11-04T14:12:40+07:00
draft: true
tags:
  - 中文
description: ""
---
Quy Trình 3 Bước: Từ Tạo Bài Đến Xuất Bản

1. Khi Tạo Bài Mới (Trên Obsidian Android)

- **Đặt tên file dạng Slug:** Viết chữ thường, không dấu, nối bằng dấu gạch ngang (Ví dụ: `huong-dan-obsidian`). _Tuyệt đối không gõ thêm đuôi `.md`._
- **Chèn Mẫu:** Bấm nút **Insert template** trên thanh công cụ bàn phím ảo.
- **Sửa Tiêu Đề Hiển Thị:** Chạm vào dòng `title: "..."` sửa lại thành Tiếng Việt có dấu chuẩn hoặc chữ Trung Quốc (Ví dụ: `title: "Hướng Dẫn Cấu Hình Obsidian"`).
- **Chọn Thẻ:** Chạm vào giữa cặp ngoặc vuông `tags: []` để chọn tag cũ từ danh sách xổ xuống, hoặc gõ tag mới rồi nhấn Enter.

2. Khi Chỉnh Sửa / Cập Nhật Bài Viết Cũ

- **Cập nhật dòng sửa đổi:** Đưa con trỏ vào sau dòng `lastmod:` , xóa chuỗi thời gian cũ, rồi bấm nút **Insert current time** trên thanh công cụ bàn phím để ghi đè giờ mới.

3. Trước Khi Đẩy Lên Web (Kiểm Tra Lỗi Kỹ Thuật)

- **Khoảng trắng:** Đảm bảo luôn có **1 dấu cách** sau các dấu hai chấm (Ví dụ: `draft: true` -> Đúng, `draft:true` -> Sai/Lỗi).
- **Dấu băm thẻ:** Kiểm tra xem có lỡ gõ dấu `#` trong ô `tags` không (Ví dụ: `tags: [astro]` -> Đúng, `tags: [#astro]` -> Lỗi hệ thống build).
- **Trạng thái bài viết:** Đổi `draft: true` thành `draft: false` khi bài viết đã sẵn sàng lên sóng để Astro/Hugo chịu duyệt xuất bản.

🛠️ Nhắc Nhở Cấu Hình Hệ Thống (Chỉ Làm 1 Lần)

- **Tắt Wikilinks:** Vào `Settings` > `Files and links` > Tắt **Use [[Wikilinks]]** để ảnh và link tự sinh ra dạng chuẩn `[Text](URL)` hoàn hảo cho Astro/Hugo.
- **Định dạng thời gian Templates:** Vào cài đặt Core plugin Templates, chỉnh `Date format`
    
    thành `YYYY-MM-DD` và `Time format` thành `HH:mm:ss`.
