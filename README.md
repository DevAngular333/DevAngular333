# DevAngular333

## Tôi xây AI systems và developer tools thành sản phẩm thực dụng, có demo và quy trình kiểm chứng.

Tôi tập trung vào ba trụ cột:

- **Local-first AI workflows** — dữ liệu, trạng thái và giới hạn được nói rõ.
- **Developer tools có bằng chứng** — đầu ra có thể chạy lại, xem diff và kiểm tra.
- **Learning và creative systems** — biến ý tưởng thành luồng sử dụng cụ thể.

## Dự án nổi bật

### [Agent Teacher · Vietnamese fraction rehearsal](https://github.com/DevAngular333/design-os-pedagogy)

**Đã phát hành · v0.1.0-devangular333**

Fork PolyForm Shield của [`jangtrinh/design-os-pedagogy`](https://github.com/jangtrinh/design-os-pedagogy). Tôi thêm smoke runner bằng Python standard library để khởi động HTTP server thật, hoàn tất một phiên rehearsal, kiểm tra replay và đọc Markdown export.

- [Release đã xác minh](https://github.com/DevAngular333/design-os-pedagogy/releases/tag/v0.1.0-devangular333)
- [Case study](https://github.com/DevAngular333/design-os-pedagogy/blob/main/docs/case-study.md)
- Thử nhanh: `python3 scripts/smoke_flow.py`
- Giới hạn: authored simulation; chưa semantic grading, expert review, pilot hay certification.

### [Code2Flow](https://github.com/DevAngular333/design-os-code)

**Đã phát hành · v0.2.0-devangular333**

Công cụ chuyển codebase web thành flow canvas có screenshot và evidence `file:line`. Tôi thêm smoke offline để scan fixture static HTML và xuất viewer self-contained.

- [Release đã xác minh](https://github.com/DevAngular333/design-os-code/releases/tag/v0.2.0-devangular333)
- [Case study](https://github.com/DevAngular333/design-os-code/blob/master/docs/case-study.md)
- Thử nhanh: `npm ci && npm run smoke`
- Giới hạn: smoke dùng fixture tổng hợp; browser capture của app bất kỳ cần môi trường riêng.

### [InkOS × PrintFilm Lab](https://github.com/DevAngular333/inkos-printfilm-lab)

**Đã phát hành · v0.2.0-devangular333**

Bridge file-based từ Markdown/JSON export sang project fields, có smoke CLI và case study. InkOS được ghi nhận AGPL-3.0; license PrintFilm chưa xác minh.

- [Release đã xác minh](https://github.com/DevAngular333/inkos-printfilm-lab/releases/tag/v0.2.0-devangular333)
- [Case study](https://github.com/DevAngular333/inkos-printfilm-lab/blob/main/docs/case-study.md)
- Thử nhanh: `npm test && npm run smoke`

## Cách tôi kiểm chứng

1. Chốt input, thao tác, output và lỗi quan trọng trước khi sửa.
2. Chạy luồng chính bằng dữ liệu mẫu có nhãn hoặc dữ liệu local.
3. Đọc lại commit, release, tree và URL công khai sau khi phát hành.
4. Ghi rõ phần đã đọc code, đã chạy, đã phát hành và chưa kiểm chứng.

## Portfolio và bằng chứng trực quan

Xem [portfolio đã triển khai](https://devangular333.github.io/devangular333-portfolio/) để đi từ vấn đề → luồng dùng thử → repo, release, case study và ảnh chụp từ phiên bản đã chạy.

## Selected work

- [design-os-knowledge-builder](https://github.com/DevAngular333/design-os-knowledge-builder) — compiler tạo knowledge packs local-first; backlog ưu tiên tiếp theo.
- [marketing-seeding](https://github.com/DevAngular333/marketing-seeding) — dashboard local cho campaign brief, draft, review, approval và evidence; public-safe audit tiếp tục.
- [DevAngular333 repositories](https://github.com/DevAngular333?tab=repositories)

## Liên hệ

GitHub là kênh công khai hiện đã xác minh: [@DevAngular333](https://github.com/DevAngular333).

<sub>Profile này ưu tiên bằng chứng có thể chạy lại. Dữ liệu tài khoản, runtime local và thông tin riêng không được đưa vào repo công khai.</sub>
