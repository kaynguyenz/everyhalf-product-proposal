# Every Half — Product Proposal / Thế Bảo

Bản GitHub Pages v3 · 20/09/2026

Đề xuất phát triển sản phẩm Every Half trong 12 tháng, gồm khảo sát sản phẩm, hành trình khách hàng, case study, roadmap thay đổi theo kết quả pilot và các mô phỏng tương tác.

## Repository đề xuất

`everyhalf-product-proposal`

Mô tả repository có thể dùng:

> A bilingual product proposal for Every Half: customer journeys, research, an adaptive roadmap and interactive prototypes.

## Các file trong gói

- `index.html`: toàn bộ website song ngữ, gồm nội dung, CSS, JavaScript và hình ảnh nhúng sẵn. Mặc định tiếng Anh; nút VI / EN chuyển ngôn ngữ trên cùng trang.
- `.nojekyll`: yêu cầu GitHub Pages phục vụ các file tĩnh trực tiếp.
- `README.md`: hướng dẫn này.

Không cần giữ hai file HTML riêng cho tiếng Việt và tiếng Anh. Không cần chạy npm, cài dependencies hoặc thiết lập GitHub Actions riêng. Google Fonts được tải khi có mạng; trình duyệt dùng font dự phòng nếu không tải được.

## Đưa lên GitHub bằng trình duyệt

1. Tạo repository `everyhalf-product-proposal`. Chọn **Public** nếu dùng GitHub Free. Có thể bật **Add a README file** để tạo sẵn nhánh `main`.
2. Giải nén file ZIP trên máy.
3. Trong repository, chọn **Add file → Upload files**. Tải các file bên trong gói lên thư mục gốc. `index.html` phải nằm trực tiếp ở gốc repository. Không tải nguyên file ZIP và không đặt thêm thư mục bao ngoài.
4. Nếu máy ẩn `.nojekyll`, trên macOS dùng **Command + Shift + .** để hiện file ẩn. Hoặc tạo file này trên GitHub bằng **Add file → Create new file**, tên `.nojekyll`; có thể để một dòng trống.
5. Chọn **Commit changes** để lưu lên nhánh `main`.
6. Mở **Settings → Pages**. Tại **Build and deployment**, chọn **Source: Deploy from a branch**; **Branch: main**; **Folder: /(root)**; rồi **Save**.
7. Đợi quá trình xuất bản hoàn tất. GitHub hiển thị địa chỉ website trong **Settings → Pages**.

Địa chỉ dự kiến theo cấu trúc GitHub Pages:

`https://<github-username>.github.io/everyhalf-product-proposal/`

`<github-username>` là tài khoản thực tế của bạn. Đây là mẫu địa chỉ, chưa phải website đã được xuất bản.

## Ngôn ngữ và kiểm tra sau khi xuất bản

- Mở địa chỉ gốc: tiếng Anh.
- Bấm **VI**: chuyển tiếng Việt; **EN**: trở lại tiếng Anh.
- Link tiếng Việt trực tiếp: thêm `?lang=vi` sau dấu `/` cuối cùng.
- Link tiếng Anh trực tiếp: thêm `?lang=en` hoặc dùng địa chỉ gốc.
- Chuyển ngôn ngữ giữ nguyên đường dẫn repository và mục đang xem.
- Thử mở chi tiết case study, đổi kết quả pilot trong roadmap và bấm các bước trong mô phỏng để kiểm tra bản xuất bản.

## Cập nhật về sau

Thay `index.html` bằng bản mới, commit lên `main`. GitHub Pages sẽ xuất bản lại từ nhánh đã chọn. Nội dung song ngữ và mã nguồn phía trình duyệt đều nằm trong `index.html`.

Bản v3 này giữ nội dung proposal v2 đã duyệt và mặc định tiếng Anh; chỉ đóng gói lại để chạy độc lập trên GitHub Pages. Hai file HTML v2 trước đó vẫn có thể lưu làm bản đối chiếu.

## Tài liệu GitHub chính thức

- [About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

Các nguồn nghiên cứu và nguồn ảnh của proposal được giữ trong website.
