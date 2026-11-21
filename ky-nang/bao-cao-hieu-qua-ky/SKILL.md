---
name: bao-cao-hieu-qua-ky
description: Viết báo cáo hiệu quả marketing theo tuần, tháng hoặc một đợt chiến dịch - tóm tắt hai ba câu, bảng chỉ số so với mục tiêu và kỳ trước kèm trạng thái đạt, có nguy cơ, lệch, điểm thắng, điểm hụt, đề xuất ưu tiên kỳ sau. Dùng khi người dùng nói "báo cáo tuần", "báo cáo tháng", "tổng kết đợt", "kỳ này marketing thế nào", "số liệu kỳ này".
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/bao-cao-hieu-qua-ky/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Báo cáo hiệu quả theo kỳ

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- **Không bịa số.** Thiếu số thì ghi "chưa có số liệu", không ước đoán để lấp bảng.
- Tách rõ điều thấy trong số liệu với điều em đoán. Ít dữ liệu thì nói "chưa đủ để kết luận".
- Không lưu, không trích tên người bình luận; chỉ dùng số tổng hợp.
- Tiếng Việt đầy đủ, không viết tắt.

Kỹ năng này nhìn **cả kỳ**. Đọc từng bài và chỗ người xem bỏ đi là việc của `doc-so-lieu-rut-bai-hoc`.

## Đầu vào
1. Loại báo cáo: tuần, tháng, một đợt chiến dịch, một kênh.
2. Kỳ báo cáo và kỳ so sánh (mặc định kỳ liền trước).
3. Mục tiêu của kỳ (từ `ke-hoach-chien-dich` hoặc người dùng).
4. Số liệu: công cụ của hệ thống nếu AI được cấp, không thì người dùng dán hoặc gửi tệp xuất. Công cụ "Đọc số liệu bài đăng của kênh" và "Tính điểm hiệu quả và khách đăng ký" **đang thiết kế, chưa có trong hệ thống**; chưa có thì nhờ người dùng dán số.
5. Người đọc báo cáo: lãnh đạo (ngắn) hay người làm (chi tiết).

## Chỉ số dùng
| Chỉ số | Cách hiểu |
|---|---|
| Lượt xem, thích, bình luận, chia sẻ, lưu | Theo kênh, cộng cả kỳ |
| Điểm hiệu quả | Tương tác trong 7 ngày của bài chia **trung vị** các bài cùng loại nội dung, cùng kênh (trung vị không bị một bài đột biến kéo lệch). Hệ thống tính theo cách khác thì ghi rõ cách hệ thống tính |
| Khách đăng ký thật | Hồ sơ mới đến qua đường dẫn theo dõi, không trùng 9 số cuối số điện thoại với hồ sơ đã có |
| Chi phí mỗi khách đăng ký thật | Tiền đã chi chia số khách đăng ký thật (chỉ khi có chi tiền) |
Nền tảng không có chỉ số nào thì ghi "nền tảng không cung cấp".

## Bước 1 - Bảng chỉ số
| Chỉ số | Kỳ này | Kỳ trước | Thay đổi | Mục tiêu | Trạng thái |
Trạng thái:
- **Đạt**: bằng hoặc vượt mục tiêu.
- **Có nguy cơ**: dưới mục tiêu nhưng còn trong mức chấp nhận (mặc định đạt từ 80% mục tiêu).
- **Lệch**: dưới 80% mục tiêu.
Không có mục tiêu thì chỉ so kỳ trước, cột trạng thái ghi "chưa có mục tiêu".

## Bước 2 - Xu hướng
Chỉ số nào lên, xuống, đứng yên qua ít nhất ba kỳ (nếu có số). Một kỳ thay đổi lớn mà chưa rõ lý do thì ghi là câu hỏi, không tự giải thích.

## Bước 3 - Thắng và hụt
- Ba điểm thắng, mỗi điểm chỉ vào bài, kênh hoặc việc cụ thể, kèm số.
- Ba điểm hụt, cùng cách viết. Điểm hụt nào trùng bài học đã có trong Ví dụ sửa thì ghi rõ "lặp lại".

## Bước 4 - Đề xuất kỳ sau
Mỗi đề xuất ghi tác động (cao, thấp) và công sức (cao, thấp). Làm trước: tác động cao, công sức thấp. Tối đa năm đề xuất, xếp theo thứ tự làm.

## Đầu ra
```
BÁO CÁO [tuần/tháng/đợt]: [từ ngày] đến [ngày] · so với [kỳ]
Tóm tắt: [2 đến 3 câu: chỉ số chính, hướng đi, một điểm thắng, một điểm lo]
[bảng chỉ số]
Xu hướng: ...
Thắng: 1 ... 2 ... 3 ...
Hụt: 1 ... 2 ... 3 ...
Đề xuất kỳ sau: | Việc | Tác động | Công sức |
Chưa có số liệu: [chỉ số nào, vì sao]
```
Kết thúc bằng câu hỏi: **kỳ sau ưu tiên việc nào?**
