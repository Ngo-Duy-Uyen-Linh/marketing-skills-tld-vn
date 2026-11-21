---
name: thu-nhieu-phien-ban
description: Thiết kế và đọc kết quả thử hai hay ba phiên bản của cùng một nội dung (câu mở đầu, ảnh bìa, tiêu đề, lời kêu gọi, giờ đăng) - mỗi lần chỉ đổi một thứ, đủ số người mới kết luận, dùng phép so hai tỷ lệ. Dùng khi người dùng nói "thử hai phiên bản", "câu nào hiệu quả hơn", "so sánh hai bài", "thử nghiệm nội dung", "kết quả thử đã đủ chưa".
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/thu-nhieu-phien-ban/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Thử nhiều phiên bản

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- Mọi phiên bản đều phải qua quy tắc nội dung và duyệt như bài thường. Không dùng phiên bản thử để lách quy tắc.
- Không bịa số liệu; chưa đủ người thì nói "chưa đủ để kết luận".
- Tiếng Việt đầy đủ, không viết tắt.

## Phần 1 - Thiết kế lượt thử
1. **Một câu giả thuyết**: "Câu mở đầu nhóm Nói hộ nỗi lòng giữ người xem 3 giây tốt hơn nhóm Câu hỏi với khách nữ 30 đến 45 tuổi."
2. **Chỉ đổi một thứ**: câu mở đầu, hoặc ảnh bìa, hoặc tiêu đề, hoặc lời kêu gọi, hoặc giờ đăng. Đổi hai thứ cùng lúc thì không biết thứ nào tạo khác biệt.
3. **Chọn một chỉ số chính**, chọn trước khi thử:
   | Thứ đang thử | Chỉ số chính |
   |---|---|
   | Câu mở đầu video | Tỷ lệ còn xem ở giây thứ 3 |
   | Ảnh bìa, tiêu đề | Tỷ lệ bấm xem trên lượt hiển thị |
   | Dòng đầu bài chữ | Tỷ lệ bấm "Xem thêm" hoặc tương tác trên lượt tiếp cận |
   | Lời kêu gọi | Tỷ lệ làm đúng hành động (bình luận, nhắn tin, bấm đường dẫn) |
4. **Chia cho công bằng**: hai phiên bản đăng ở hai nơi tương đương (hai nhóm Zalo cỡ gần nhau, hai khung giờ cùng ngày trong tuần) hoặc dùng công cụ thử của nền tảng nếu có. Ghi rõ cách chia.
5. **Cỡ mẫu tối thiểu**: mỗi phiên bản **ít nhất 50 người** đi tới bước được đo. Đọc số này từ tham số của hệ thống khi có; chưa có thì dùng mặc định ở `tai-lieu-to-chuc/quy-tac-noi-dung.md`. Chưa đủ thì không đọc kết quả.
6. Ghi hạn thử (mặc định 7 ngày).

## Phần 2 - Đọc kết quả
Với hai phiên bản: phiên bản 1 có x1 người làm được trong n1 người, phiên bản 2 có x2 trong n2.
- p1 = x1 / n1, p2 = x2 / n2, p chung = (x1 + x2) / (n1 + n2)
- z = (p1 − p2) / căn bậc hai của [ p chung × (1 − p chung) × (1/n1 + 1/n2) ]
- **|z| từ 1,96 trở lên**: khác biệt đủ tin (độ tin khoảng 95%). Dưới 1,96: **chưa phân thắng thua**, không chọn theo cảm giác.
Ba phiên bản thì so từng cặp với phiên bản đang dùng, nói rõ so nhiều cặp dễ ra kết quả may hơn.

**Chỉ là gợi ý khi người xem không được chia ngẫu nhiên.** Hai bài đăng ở hai nhóm hay hai khung giờ khác nhau thì người xem khác nhau, nên |z| từ 1,96 chỉ ghi là "gợi ý", không ghi là kết luận. Chỉ ghi "đủ tin" khi nền tảng hoặc hệ thống tự chia ngẫu nhiên người xem cho các phiên bản.

Hệ thống đã có phép so này ở chiến dịch chăm sóc khách hàng thì dùng cùng ngưỡng để hai nơi nói cùng một ngôn ngữ.

## Phần 3 - Ghi bài học
- Có phiên bản thắng: ghi giả thuyết, kết quả, z, cỡ mẫu, và **điều rút ra cho lần sau** (ví dụ "nhóm Nói hộ nỗi lòng thắng nhóm Câu hỏi 2 lần trong 3 lượt thử").
- Một lượt thắng chưa phải quy luật. Đề xuất đưa vào Ví dụ sửa của kho tri thức khi **cùng một kết luận lặp lại ít nhất 2 lượt thử**; người duyệt mới nạp.

## Đầu ra
```
LƯỢT THỬ: [tên] · đổi: [một thứ] · chỉ số chính: [tên] · hạn: [ngày]
Phiên bản 1: ... · n1 [số] · x1 [số] · tỷ lệ [số]%
Phiên bản 2: ... · n2 [số] · x2 [số] · tỷ lệ [số]%
Cách chia: [ngẫu nhiên / không ngẫu nhiên]
z = [số] · [đủ tin / gợi ý / chưa phân thắng thua / chưa đủ người]
Điều rút ra: ...
Đề xuất Ví dụ sửa: [có/chưa, vì sao]
```
Kết thúc bằng câu hỏi: **dùng phiên bản nào cho bài tiếp theo?**
