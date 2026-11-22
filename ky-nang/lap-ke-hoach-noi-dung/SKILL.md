---
name: lap-ke-hoach-noi-dung
description: Lập kế hoạch nội dung theo tuần hoặc tháng cho các kênh của tổ chức - cân giữa bốn loại nội dung thu hút, nuôi dưỡng, mời mua và chăm sóc khách đã mua, gắn mỗi bài với nỗi đau của khách, xu hướng đang lên và lịch khóa học, sản phẩm, ghi mức rủi ro và người cần duyệt. Dùng khi người dùng nói "lên kế hoạch nội dung", "lịch đăng tuần sau", "tháng này đăng gì", "kế hoạch nội dung cho khóa", "phân bổ bài cho các kênh".
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/lap-ke-hoach-noi-dung/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Lập kế hoạch nội dung

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức (khóa học, lịch, sản phẩm, ưu đãi, kênh, giọng văn): tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`. Thiếu thì ghi `[cần xác nhận: …]`.
- Em soạn và đề xuất; người có quyền duyệt kế hoạch. Mỗi bài trong kế hoạch vẫn phải duyệt riêng khi viết xong, trừ loại tổ chức đã cho tự đăng.
- Giữ giới hạn số bài mỗi ngày mỗi kênh và giờ được đăng của tổ chức.
- Không khẩn cấp giả: ưu đãi, hạn, số chỗ chỉ nhắc khi tài liệu của tổ chức ghi.
- Tiếng Việt đầy đủ, không viết tắt.

## Đầu vào
- Khoảng thời gian (mặc định 7 ngày tới).
- Mục tiêu của khoảng đó (ví dụ: đưa người vào lớp trực tuyến tối thứ Hai, bán gói video sau buổi học).
- Kênh và số bài tối đa mỗi ngày mỗi kênh (`tai-lieu-to-chuc/kenh-va-so-lieu.md` hoặc tham số của hệ thống).
- Bản tin xu hướng gần nhất (`nghien-cuu-xu-huong`), chủ đề nỗi đau từ bình luận, bài học gần nhất (`doc-so-lieu-rut-bai-hoc`).
- Lịch khóa học, sự kiện, ưu đãi đang có.

## Bước 1 - Chia bốn loại nội dung
| Loại | Để làm gì | Tỷ lệ mặc định |
|---|---|---|
| Thu hút | Người lạ dừng lại, chia sẻ, theo dõi | 40% |
| Nuôi dưỡng | Người đã biết tin hơn: câu chuyện, giải đáp, giá trị dùng ngay | 25% |
| Mời mua, mời tham gia | Lời mời rõ ràng tới khóa, sản phẩm, sự kiện | 15% |
| Chăm sóc | Khách đã mua, học viên dùng hiệu quả hơn và ở lại: mẹo đạt kết quả cao, cách gỡ nút thắt và khiếu nại hay gặp, nhắc lịch, mừng tiến bộ | 20% |
Đọc tỷ lệ từ tham số của hệ thống khi có; chưa có thì dùng mặc định 40/25/15/20 ở `tai-lieu-to-chuc/quy-tac-noi-dung.md`. Gần ngày khai giảng hay sự kiện thì tăng phần mời, nhưng không quá một nửa số bài. Kênh chỉ dành cho khách đã mua (nhóm học viên, nhóm khách hàng) thì không theo tỷ lệ chung: chăm sóc là chính, chỉ mời khi có khóa hay sản phẩm nối tiếp hợp với họ.

**Bài chăm sóc lấy ý từ đâu:** câu hỏi, khiếu nại, chỗ khách hay vướng gom từ bình luận, nhóm, hộp thoại, đánh giá (chỉ dùng số tổng hợp, không nêu tên khách); Ví dụ sửa; tài liệu khóa học, hướng dẫn dùng sản phẩm. Bài về khiếu nại hay gặp nói cách gỡ chung; khiếu nại của một người cụ thể không đưa lên bài mà chuyển người phụ trách. Bài chăm sóc nhắc khiếu nại là mức cao.

## Bước 2 - Gắn từng bài với một lý do
Mỗi bài có đủ: **một nỗi đau hoặc nhu cầu** của khách; **một nguồn ý** (xu hướng, thẻ cấu trúc, câu hỏi khách hay hỏi, bài cũ hiệu quả cần làm lại); **một hành động** mong người xem làm, hợp với loại bài:
- Thu hút: lưu bài, bình luận, chia sẻ, theo dõi.
- Nuôi dưỡng: nhận tài liệu, vào nhóm, nhắn hỏi.
- Mời: đăng ký, tham gia, mua; kèm một điều giảm lo nếu có thật trong tài liệu tổ chức (buổi học thử, chính sách đổi trả).
- Chăm sóc: làm thử rồi kể lại kết quả, hỏi khi vướng, đánh giá; giới thiệu người quen chỉ khi khách đã hài lòng.
Bài làm lại từ bài cũ hiệu quả: theo `lam-moi-bai-hieu-qua` (đổi câu mở đầu hoặc cách kể, không đăng lại y nguyên).

## Bước 3 - Xếp lịch
- Theo giờ được đăng và khung giờ khách của tổ chức hay xem (từ số liệu; chưa có thì ghi "chưa có số liệu, đề xuất thử").
- Không xếp hai bài mời liền nhau trên cùng kênh.
- Cùng một ý trên nhiều kênh thì viết bản riêng từng kênh (`viet-bai-dang-mang-xa-hoi`).
- Đặt sẵn lượt thử phiên bản nếu có giả thuyết cần kiểm (`thu-nhieu-phien-ban`).

## Bước 4 - Ghi mức rủi ro và người duyệt
Mỗi bài ghi mức rủi ro dự kiến. Đếm số bài mức vừa và mức cao để người duyệt biết khối lượng duyệt trong tuần; quá nhiều thì đề xuất giãn ra.

## Đầu ra
```
KẾ HOẠCH NỘI DUNG: [từ ngày] đến [ngày] · mục tiêu: ...
Tỷ lệ: thu hút [số] · nuôi dưỡng [số] · mời [số] · chăm sóc [số] · khối lượng duyệt: [số] bài mức vừa, [số] bài mức cao

| Ngày, giờ | Kênh | Loại | Chủ đề | Nỗi đau | Nguồn ý | Định dạng | Hành động | Mức rủi ro | Kỹ năng viết |
|---|---|---|---|---|---|---|---|---|---|

Lượt thử phiên bản trong kỳ: ...
Cần xác nhận: ...
```
Kết thúc bằng câu hỏi: **duyệt kế hoạch này hay đổi bài nào?**
