# SEE THE LIGHT — Skill tạo video kèm nhạc

Bản đầy đủ cập nhật 25/11/2026: **toàn bộ skill + file MP3 FICTION – VIETZ REMIX** trong một ZIP.

## Tải bản có nhạc

**[Tải SEE_THE_LIGHT_Skill_Va_Nhac_2026-11-25.zip](SEE_THE_LIGHT_Skill_Va_Nhac_2026-11-25.zip)** → chọn **Download raw file**.

ZIP khoảng **5,4 MiB**, gồm **52 tệp**: SKILL.md tổng hợp, tài liệu tham chiếu, scripts, template SEE THE LIGHT, font kèm giấy phép, phiên âm tên, danh sách chống trùng, bộ 40 kịch bản, thiết lập và file nhạc.

Nhạc nằm tại `see-the-light-video-skill/assets/music/fiction-vietz-remix.mp3`, dài khoảng **2 phút 48,41 giây**. File giữ nguyên bản gốc và được kiểm tra SHA-256 khớp nguồn đã nạp.

Thiết lập đã chốt: **bắt đầu 00:00, gain -17 dB**, không normalize nhạc hoặc ducking; fade đầu 0,4 giây và cuối 1 giây. Script áp dụng -17 dB khi mix, không giảm sẵn trong MP3.

## Cách dùng

1. Giải nén ZIP và đọc `see-the-light-video-skill/SKILL.md` cùng `HUONG_DAN_NHAC.md`.
2. Để cài skill Codex, đặt thư mục `see-the-light-video-skill` vào `~/.codex/skills/`.
3. Cài Python/ffmpeg theo README trong gói.
4. Sao chép `config/series-settings.example.json` vào `work/production/series-settings.json` của dự án. Nếu dự án ở nơi khác, đặt `background_music.file` thành đường dẫn tuyệt đối tới MP3 trong gói.
5. Yêu cầu ví dụ: “Dùng skill SEE THE LIGHT, tạo video cho kịch bản 8 trong bộ đã duyệt.”

## Quy trình trong gói

Tìm câu nói có nguồn → Việt hóa và duyệt hook → viết kịch bản → tạo giọng Vbee Ngọc Huyền 1.1x bằng computer use → bóc lời và căn từng từ → chọn ảnh thật → dựng hook đỏ/phụ đề karaoke → mix nhạc → preview/render/QA → lưu video và đối chiếu hash.

Video mặc định **25–30 giây**, 1080×1920, 30 fps. Chủ đề phát triển nội tại, cuộc sống, sự nghiệp và tư duy công việc; không dùng tình huống vợ chồng, hôn nhân, hàng xóm/láng giềng. Hook tách riêng và giữ nguyên sau khi duyệt.

Video cuối được lưu vào **Tải về/SEE THE LIGHT - Video**. Pipeline đã chạy thử với bài 7: 26,6 giây, karaoke lệch tối đa 45 ms, -15,8 LUFS, QA ĐẠT; bản lưu khớp bản xuất.

Gói không chứa tài khoản, token/cookie, ảnh báo chí tải về hoặc giọng/video đã trả phí. Vbee cần phiên đăng nhập của người sử dụng. Nhạc được kèm theo yêu cầu của người dùng và giữ quyền của các chủ thể tương ứng; gói skill không tái cấp phép bản nhạc.

## Bản skill không kèm nhạc

[Bản ZIP chỉ có skill trước đó](SEE_THE_LIGHT_Full_Skill_2026-11-25.zip) vẫn được giữ lại.

## Kiểm tra và xuất xứ

SHA-256 ZIP kèm nhạc:

```
68926d3db9dd65ea451348fa55fb5da5f156344366fe0bc4c2c86fc83e4f1fb3
```

Quy trình gốc: [phamthevu15/sansan-video-bai-hoc](https://github.com/phamthevu15/sansan-video-bai-hoc), gồm hai skill viết kịch bản/Vbee và dựng video. Bản tổng hợp thêm lựa chọn của người dùng và các chỉnh sửa thực tế. Nguồn/font/giấy phép nằm trong `NOTICE.md`; không tự tái cấp phép toàn bộ mã/template của nguồn gốc.
