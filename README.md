# kmb.vn – static site

Triển khai với **GitHub Pages**:

1. Tạo repo và commit toàn bộ file.
2. Vào *Settings → Pages*: Chọn **Deploy from a branch**, branch `main`, root.
3. Trong *Custom domain*, nhập `kmb.vn`. Giữ file `CNAME` trong repo.
4. Cập nhật DNS: A/ALIAS/ANAME cho apex domain hoặc CNAME cho `www` (nếu dùng).
5. Bật **Enforce HTTPS** khi chứng chỉ sẵn sàng.

**Tùy biến**: Sửa hotline, Zalo, email, địa chỉ trong từng file HTML hoặc tách ra JS config nếu cần.