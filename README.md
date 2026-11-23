# Lịch Âm Việt Nam (bản chạy trên GitHub Pages)

Web tra lịch âm dương Việt Nam, chạy hoàn toàn offline (PWA).

**Đây là bản build đã minify** (JS/CSS/HTML rút gọn, tên biến top-level giữ nguyên để
các module tham chiếu lẫn nhau). Repo này chỉ chứa bản build phục vụ GitHub Pages;
repo nguồn giữ riêng tư.

- Trang web: https://zthanhluan.github.io/lich-am-web/
- Build từ repo nguồn bằng: `node scripts/build.js` (đầu ra `dist/`)
- PWA: service worker `sw.js` (cache v17)

Dữ liệu tra cứu mang tính tham khảo dân gian; nguồn đối chiếu được ghi trong giao diện.
