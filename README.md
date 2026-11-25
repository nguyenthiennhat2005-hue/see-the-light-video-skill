# SEE THE LIGHT — Skill tạo video trọn bộ

Một file ZIP tổng hợp toàn bộ quy trình đã dùng cho series **Bài học từ doanh nhân**. Cập nhật **25/11/2026**.

## Tải gói đầy đủ

**[Tải SEE_THE_LIGHT_Full_Skill_2026-11-25.zip](SEE_THE_LIGHT_Full_Skill_2026-11-25.zip)** → chọn **Download raw file**.

Gói có **50 tệp**, khoảng **1,56 MiB**: một SKILL.md chung, hướng dẫn tham chiếu, scripts, template SEE THE LIGHT, font kèm giấy phép, phiên âm, danh sách chống trùng, bộ 40 kịch bản và thiết lập mẫu.

## Quy trình trong gói

1. Tìm câu nói có nguồn, Việt hóa và duyệt hook riêng.
2. Viết kịch bản về nội tại, cuộc sống, sự nghiệp và tư duy công việc.
3. Tạo MP3 Vbee **HN – Ngọc Huyền 1.1x** qua computer use.
4. Bóc lời, sửa tên riêng và căn từng từ bằng wav2vec2 tiếng Việt.
5. Chọn ảnh thật, soát ảnh trùng, tạo hook đỏ và phụ đề karaoke.
6. Mix **FICTION – VIETZ REMIX từ 00:00, gain −17 dB** theo settings mới nhất.
7. Preview → render → QA → xem contact sheet.
8. Lưu MP4 vào **Tải về/SEE THE LIGHT - Video**, xác nhận SHA-256 bản lưu khớp bản xuất.

Mặc định **25–30 giây**, 1080×1920, 30 fps. Không dùng tình huống vợ chồng, hôn nhân hoặc hàng xóm/láng giềng. Hook đã duyệt được giữ nguyên.

## Cách dùng

Giải nén và đọc `see-the-light-video-skill/SKILL.md`. Để dùng như skill Codex, đặt thư mục này vào `~/.codex/skills/`. README trong ZIP có hướng dẫn cài Python, ffmpeg và các thư viện.

Ví dụ: “Dùng skill SEE THE LIGHT, tạo video cho kịch bản 8 trong bộ đã duyệt.”

Gói không chứa tài khoản, token/cookie, nhạc thương mại, ảnh báo chí tải về hoặc MP3/MP4 trả phí. Người dùng cấp media và phiên Vbee khi chạy; file nhạc được cấu hình trong `work/production/series-settings.json`.

## Kiểm tra và xuất xứ

Đã chạy thử mix → render → QA → lưu với bài 7: **26,6 giây, karaoke lệch tối đa 45 ms, −15,8 LUFS, QA ĐẠT**. Bản lưu khớp bản xuất. Chi tiết trong `VERIFICATION.md` của gói.

SHA-256 của ZIP:

```
b1080e096ba88cffb33962bdf3059406bf80a1a62bb76f8486471266ab79faa9
```

Quy trình gốc: [phamthevu15/sansan-video-bai-hoc](https://github.com/phamthevu15/sansan-video-bai-hoc), gồm hai skill viết kịch bản/Vbee và dựng video. Bản này gộp thêm lựa chọn đã chốt của người dùng và các chỉnh sửa thực tế. Ghi công và giấy phép từng thành phần nằm trong `NOTICE.md`; không tự tái cấp phép toàn bộ mã/template của nguồn gốc.
