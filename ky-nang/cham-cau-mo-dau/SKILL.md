---
name: cham-cau-mo-dau
description: Chấm câu mở đầu của video hoặc bài đăng trước khi đăng theo năm tiêu chí, lấy điểm yếu nhất làm trọng tâm, gợi ý sửa. Dùng khi người dùng nói "chấm câu này", "câu mở đầu này ổn không", "câu nào mạnh hơn", hoặc dán một hay nhiều câu mở đầu.
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/cham-cau-mo-dau/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Chấm câu mở đầu

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- Điểm chỉ để **chặn câu dở**, không phải lời hứa câu điểm cao sẽ nhiều lượt xem. Không nói "câu này chắc chắn lên".
- Câu vi phạm quy tắc nội dung của tổ chức (từ cấm, hứa kết quả, khẩn cấp giả, con số không nguồn) thì **không chấm**, ghi lý do và trả về để viết lại.
- Tiếng Việt đầy đủ, không viết tắt.

## Năm tiêu chí, mỗi tiêu chí 0 đến 100
Mỗi tiêu chí bắt đầu từ điểm nền, cộng trừ theo dấu hiệu, giới hạn trong 0 đến 100.

**1. Cụ thể** (nền 35)
- Cộng 20 mỗi con số, giờ, ngày, lượng cụ thể; cộng 6 mỗi tên riêng hay đồ vật cụ thể (tối đa cộng 18).
- Trừ 15 mỗi từ to tát chung chung: tuyệt vời, bí mật, bí quyết, đỉnh cao, siêu, cực kỳ, thay đổi cuộc đời, không thể tin nổi, mạnh mẽ nhất.
- Trừ 5 mỗi từ đệm: thì là, kiểu như, nói chung, thật ra thì, xin chào cả nhà, hôm nay mình.

**2. Nói thẳng với người xem** (nền 25)
- Cộng 20 mỗi lần **gọi người xem**: bạn, anh, chị, mẹ, bố, các chị, vợ chồng mình. "Em" người nói tự xưng thì không tính.
- Cộng 30 nếu lời gọi nằm trong 6 tiếng đầu.

**3. Cái giá phải trả** (nền 20)
- Cộng 25 mỗi dấu hiệu mất mát hoặc rủi ro: mất, tốn, sai, hối hận, bỏ lỡ, đổ vỡ, trước khi, đừng, ngừng, quá muộn.
- Cộng 15 nếu có con số đi kèm.
- Cái giá phải là thật; phóng đại để dọa thì không cộng và ghi chú.

**4. Khoảng tò mò** (nền 25)
- Cộng 15 mỗi dấu hiệu: vì sao, tại sao, làm sao, điều gì, ai ngờ, cho đến khi, nhưng, không ai, hóa ra.
- Cộng 15 nếu kết thúc bằng dấu hỏi.
- Trừ 20 nếu câu tự giải luôn: bởi vì, vì vậy, tức là, nghĩa là.

**5. Độ dài** (tính bằng số tiếng; nói khoảng 4 tiếng mỗi giây)
- Video ngắn, lời trong 3 giây đầu: 8 đến 15 tiếng được 100.
- Video dài, lời trong 15 giây đầu; dòng đầu bài chữ (phần hiện trước "Xem thêm"): 15 đến 40 tiếng được 100.
- Ngoài dải: trừ 8 mỗi tiếng thiếu (thấp nhất 30), trừ 6 mỗi tiếng thừa (thấp nhất 10). Bài chữ cắt giữa ý thì trừ 20.

**Chống nhồi:** dấu hiệu gượng, nhồi vào để lấy điểm thì không cộng. Điểm có thể lệch vài điểm giữa hai lần chấm; câu sát ngưỡng thì ghi "sát ngưỡng".

## Điểm cuối
**Điểm = 0,6 × trung bình năm tiêu chí + 0,4 × tiêu chí thấp nhất**, làm tròn.
Một câu có bốn điểm mạnh và một điểm chết vẫn rò người xem ở điểm chết; lấy trung bình sẽ che mất chỗ đó.

| Điểm | Mức | Làm gì |
|---|---|---|
| Từ 72 | Mạnh | Giao |
| 55 đến 71 | Dùng được | Giao, ghi tiêu chí yếu nhất |
| Dưới 55 | Yếu | Viết lại trước khi giao |
Dấu hiệu và ngưỡng là điểm khởi đầu cho tiếng Việt, chưa đo trên số liệu thật; có đủ số liệu (`doc-so-lieu-rut-bai-hoc`) thì đề xuất chỉnh qua Ví dụ sửa.

## Cách làm
Đầu vào: một hay nhiều câu mở đầu; tiêu đề, ảnh bìa; nền tảng, định dạng.
1. Kiểm quy tắc nội dung trước. Vi phạm thì dừng, ghi lý do.
2. Chấm năm tiêu chí, ghi dấu hiệu đã thấy để người duyệt kiểm lại; tính điểm cuối và mức.
3. Ghi thêm (không tính điểm): có xác nhận tiêu đề, mở câu hỏi, cho thấy phần thưởng không.
4. Với câu Yếu hoặc Dùng được: chỉ ra tiêu chí thấp nhất và viết **một** câu sửa nhắm đúng tiêu chí đó.

## Đầu ra
```
[câu]
Cụ thể [số] · Nói thẳng [số] · Cái giá [số] · Tò mò [số] · Độ dài [số]
Điểm [số] · [Mạnh/Dùng được/Yếu] · yếu nhất: [tiêu chí] vì [dấu hiệu]
Ba việc: xác nhận tiêu đề [có/không] · mở câu hỏi [có/không] · cho thấy phần thưởng [có/không]
Gợi ý sửa: ...
```
Nhiều câu thì xếp theo điểm giảm dần. Kết thúc bằng câu hỏi: **dùng câu nào?**
