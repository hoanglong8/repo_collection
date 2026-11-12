# Repo Collection

Bộ sưu tập các repo GitHub hữu ích trong dự án tại FOXAI và cá nhân, trình bày dạng trang web tĩnh để dễ tra cứu theo chủ đề, ngôn ngữ và số sao.

**Xem trực tuyến:** https://hoanglong8.github.io/repo_collection/

## Nguồn dữ liệu

Dữ liệu được tổng hợp từ [Kho Repo của Phan Đông Giang](https://phandonggiang.com/kho-repo) (phandonggiang.com/kho-repo), gồm tên repo, liên kết GitHub, mô tả, số sao, ngôn ngữ chính và nhãn chủ đề. File dữ liệu nằm tại `data/repos.json`.

## Cập nhật hàng tuần

Danh sách được làm mới tự động hàng tuần: crawl lại trang nguồn, so số lượng và nội dung, sinh lại `data/repos.json` rồi commit và push lên nhánh `main`. GitHub Pages tự động xuất bản lại trang sau mỗi lần push.
