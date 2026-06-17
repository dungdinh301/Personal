# Personal — public web (Rung Rinh)

Repo **public** cho web công khai của Dũng. Song song với repo private `deploy` (kênh kín, đồ nhạy cảm).

- **Hosting:** GitHub Pages → live tại `https://dungdinh301.github.io/Personal/`
- **Push = build:** push lên `main` là Pages tự build lại (sau khi bật Pages 1 lần).

## Bật Pages (làm 1 lần, để site lên web)
Repo trên GitHub → **Settings → Pages** → *Source:* `Deploy from a branch` → *Branch:* `main` / `/ (root)` → Save.
Vài phút sau site live ở URL trên.

## Thêm trang mới lên public
1. Copy file `.html` (self-contained) vào folder này.
2. Thêm 1 card link tới nó trong `index.html` (chỗ `<!-- THÊM CARD MỚI -->`).
3. `git add . && git commit -m "mô tả" && git push` → tự lên web.

## ⛔ TUYỆT ĐỐI KHÔNG để vào repo này
Đây là repo **public** — mọi thứ push lên là cả internet xem được, Google index, xóa rồi vẫn bị cache.
- **Health/fitness thật** (HRV, sleep, cân, **GPS** lộ vị trí) → ở repo private `deploy`.
- **Dữ liệu nội bộ PVcomBank thật** (KPI thật, roadmap/EPIC, quy trình nghiệp vụ nhạy cảm).
- File có EXIF/GPS trong ảnh → strip metadata trước khi đưa vào.

Chỉ để ở đây: nội dung Dũng chủ động duyệt cho công khai (mockup, phương pháp luận, portfolio).
