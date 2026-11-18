# Xưởng In ấn

Web sản xuất sản phẩm in: bộ sản phẩm, thiết kế và hình ảnh (ChatGPT qua Bridge), đăng bán Etsy.

- Web tĩnh trong `dist/` (Vercel, `vercel.json`), dữ liệu lưu trong trình duyệt.
- `window.XUONG_SITE='print'` trong `dist/index.html` chỉ bật phần In ấn. Mã gốc tách từ XUONG_NOI_DUNG (18/11/2026).
- Extension: `extension/` (ChatGPT Bridge). Đóng gói: `scripts/package-extension.py`.
- Test: `node --test tests/*.test.cjs`.

Chuyển dữ liệu từ Xưởng Nội Dung: ở web cũ bấm **Sao lưu dữ liệu**, rồi ở web này mở Cài đặt → Dữ liệu → **Khôi phục dữ liệu** và chọn file vừa tải.
