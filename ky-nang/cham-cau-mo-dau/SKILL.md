---
name: cham-cau-mo-dau
description: Chấm câu mở đầu của video hoặc bài đăng trước khi đăng theo năm tiêu chí - cụ thể, nói thẳng với người xem, cái giá phải trả, khoảng tò mò, độ dài - lấy điểm yếu nhất làm trọng tâm, chỉ ra chỗ hở và gợi ý sửa. Dùng khi người dùng nói "chấm câu này", "câu mở đầu này ổn không", "so mấy câu mở đầu", "câu nào mạnh hơn", hoặc dán một hay nhiều câu mở đầu.
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
- Cộng 20 mỗi lần gọi người xem: bạn, anh, chị, em, mẹ, bố, các chị, vợ chồng mình.
- Cộng 30 nếu lời gọi nằm trong 6 tiếng đầu.

**3. Cái giá phải trả** (nền 20)
- Cộng 25 mỗi dấu hiệu mất mát hoặc rủi ro: mất, tốn, sai, hối hận, bỏ lỡ, đổ vỡ, trước khi, đừng, ngừng, quá muộn.
- Cộng 15 nếu có con số đi kèm.
- Cái giá phải là thật; phóng đại để dọa thì không cộng và ghi chú.

**4. Khoảng tò mò** (nền 25)
- Cộng 15 mỗi dấu hiệu: vì sao, tại sao, làm sao, điều gì, ai ngờ, cho đến khi, nhưng, không ai, hóa ra.
- Cộng 15 nếu kết thúc bằng dấu hỏi.
- Trừ 20 nếu câu tự giải luôn: bởi vì, vì vậy, tức là, nghĩa là.

**5. Độ dài** (lời nói video tính bằng số tiếng)
- 12 đến 40 tiếng: 100.
- Dưới 12: trừ 8 mỗi tiếng thiếu, thấp nhất 30.
- Trên 40: trừ 6 mỗi tiếng thừa, thấp nhất 10.
- Bài chữ: chấm dòng hiện trước chữ "Xem thêm"; cắt giữa ý thì trừ 20.

## Điểm cuối
**Điểm = 0,6 × trung bình năm tiêu chí + 0,4 × tiêu chí thấp nhất**, làm tròn.
Lấy tiêu chí thấp nhất làm trọng tâm vì một câu có bốn điểm mạnh và một điểm chết vẫn rò người xem ở điểm chết; lấy trung bình sẽ che mất chỗ đó.

| Điểm | Mức | Làm gì |
|---|---|---|
| Từ 72 | Mạnh | Giao |
| 55 đến 71 | Dùng được | Giao, ghi tiêu chí yếu nhất |
| Dưới 55 | Yếu | Viết lại trước khi giao |
Tổ chức đổi được hai ngưỡng này.

Dấu hiệu ở trên là điểm khởi đầu em đặt cho tiếng Việt, chưa đo trên số liệu thật. Khi tổ chức có đủ số liệu bài đã đăng (`doc-so-lieu-rut-bai-hoc`), đề xuất chỉnh dấu hiệu và ngưỡng qua Ví dụ sửa.

## Đầu vào
Một hoặc nhiều câu mở đầu; tiêu đề, ảnh bìa; nền tảng, định dạng.

## Cách làm
1. Kiểm quy tắc nội dung trước. Vi phạm thì dừng, ghi lý do.
2. Chấm năm tiêu chí, ghi dấu hiệu đã thấy cho từng tiêu chí để người duyệt kiểm lại được.
3. Tính điểm cuối và mức.
4. Kiểm thêm ba việc (không tính điểm, chỉ ghi): có xác nhận tiêu đề không; có mở câu hỏi không; có cho thấy phần thưởng không.
5. Với câu Yếu hoặc Dùng được: chỉ ra tiêu chí thấp nhất và viết **một** câu sửa nhắm đúng tiêu chí đó.

## Đầu ra
```
[câu]
Cụ thể [số] · Nói thẳng [số] · Cái giá [số] · Tò mò [số] · Độ dài [số]
Điểm [số] · [Mạnh/Dùng được/Yếu] · yếu nhất: [tiêu chí] vì [dấu hiệu]
Ba việc: xác nhận tiêu đề [có/không] · mở câu hỏi [có/không] · cho thấy phần thưởng [có/không]
Gợi ý sửa: ...
```
Nhiều câu thì xếp theo điểm giảm dần. Kết thúc bằng câu hỏi: **dùng câu nào?**
