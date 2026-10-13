# Website quà 20/10 💗

Deploy bằng **Vercel**, dùng một **repository GitHub mới** để không ghi đè website BBQ. Hoặc đặt website vào thư mục con của repository cũ và cấu hình Root Directory tương ứng trong Vercel.

Environment Variables của Vercel:
- `GITHUB_TOKEN`: fine-grained token có quyền Issues: Read and write cho repository nhận kết quả.
- `GITHUB_OWNER`: `namvtk34-boop`
- `GITHUB_REPO`: `bbq-date-invitation` (hoặc repo khác bạn chọn).

Bật Issues ở GitHub repository Settings → General → Features → Issues. Token không được đưa vào HTML.

Vòng quay 40 ô: Hoa 16 (40%), Anh Nam 2 (5%), may mắn lần sau 4 (10%), nước hoa 4 (10%), 1000 yen 8 (20%), 2000 yen 4 (10%), 3000 yen 2 (5%). Kết quả **được định trước**, không phải ngẫu nhiên: Hoa → Nước hoa → Anh Nam :v.

Lưu ý: API công khai chưa có chống spam và có thể bị gọi nhiều lần để tạo Issue trùng. Nếu phát hành rộng rãi nên bổ sung rate limit hoặc xác thực một lần. Trên GitHub Pages API sẽ không hoạt động; hãy dùng link Vercel.

## V2 visual changes
Replaced the three top emojis with three local transparent PNG images in order: waving, sunglasses, cute pose. Larger kawaii typography via Google Fonts (Baloo 2 / Nunito) with offline fallbacks. Upload `assets/` with the HTML.
