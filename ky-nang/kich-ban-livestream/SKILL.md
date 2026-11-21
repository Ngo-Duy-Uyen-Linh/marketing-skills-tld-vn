---
name: kich-ban-livestream
description: Viết kịch bản livestream theo khối thời gian, có hướng thuyết phục, câu chốt, câu tương tác, lời mời, phân vai và việc của người trực bình luận. Dùng khi người dùng nói "kịch bản livestream", "tối nay live nói gì", "chuẩn bị buổi live".
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/kich-ban-livestream/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Kịch bản livestream

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức (khóa học, lịch, giá, ưu đãi, diễn giả, câu bắt buộc): tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`. Thiếu thì ghi `[cần xác nhận: …]`.
- Em soạn; người có quyền duyệt. Lời mời có giá, ưu đãi là mức cao.
- Không hứa kết quả, không khẩn cấp giả. Nội dung tổ chức cấm kể trước (`quy-tac-noi-dung.md` mục 4) không đưa vào phần nội dung.
- Câu chuyện, hình ảnh học viên chỉ dùng khi đã có đồng ý.
- Tiếng Việt đầy đủ, không viết tắt.

## Đầu vào
- Chủ đề, mục tiêu buổi (ví dụ: mời vào lớp trực tuyến tối thứ Hai), nền tảng, thời lượng (mặc định 60 phút).
- Ai lên hình, ai trực bình luận; điều cần mời và đường dẫn.
- Nỗi đau, câu hỏi khách hay hỏi (`khach-hang-va-noi-dau.md`, báo cáo bình luận nếu có).

## Bước 0 - Chọn hướng thuyết phục
Đưa **ba hướng khác nhau**, mỗi hướng một đòn tâm lý riêng (ví dụ: câu chuyện thay đổi có thật, giải đáp nỗi lo thường gặp, làm thử một bài nhỏ ngay trong buổi), ghi hợp với khách nào. Người duyệt chọn một hướng rồi mới viết. Có số liệu buổi trước thì nói hướng nào từng tốt hơn.

## Bước 1 - Trước giờ
Một bài thông báo (`viet-bai-dang-mang-xa-hoi`) và một tin nhắc ngắn trước giờ phát, theo giới hạn kênh của tổ chức.

## Bước 2 - Mở đầu, 0 đến 5 phút
- Câu mở đầu nói ngay buổi này giúp người xem điều gì (`viet-cau-mo-dau`).
- Người xem vào dần: chưa đi vào ý chính trong 2 đến 3 phút đầu, dùng một câu hỏi để người xem bình luận một từ.

## Bước 3 - Các khối nội dung
Chia khối 10 đến 15 phút, mỗi khối:
| Phút | Ý chính | Ví dụ, câu chuyện | Câu chốt | Câu hỏi tương tác | Người nói |
- Mỗi khối một ý, kết bằng một câu chốt ngắn (dùng được để cắt video sau).
- Khoảng 10 phút một lần **nhắc lại cho người mới vào**: buổi này nói gì, đang tới đâu.
- Đổi nhịp mỗi khối: câu chuyện, hỏi đáp, đọc bình luận.
- Chuẩn bị sẵn **câu cứu khi vắng tương tác** (ví dụ một câu hỏi chọn một trong hai, đọc to một bình luận cũ) và **câu lấp chỗ** khi chờ khách mời, chờ kỹ thuật.
- Lời nói theo giọng và cách xưng hô của tổ chức, kể cả giọng vùng miền nếu tổ chức đã chọn.

## Bước 4 - Lời mời
- Chỉ mời điều có trong tài liệu, đúng giá, đúng hạn. Nói rõ người xem được gì, làm gì tiếp theo.
- Lời mời đặt sau khi đã cho giá trị; nhắc lại một lần gần cuối, không mời liên tục.

## Bước 5 - Việc của người trực bình luận
- Câu ghim đầu buổi và đường dẫn theo quy tắc kênh.
- Câu trả lời mẫu cho 5 câu hỏi dự kiến (`tra-loi-binh-luan-cong-khai`).
- Bình luận phàn nàn, nhạy cảm, có dấu hiệu nguy hiểm: không tranh cãi công khai, mời nhắn riêng, báo người phụ trách ngay.

## Bước 6 - Sau buổi
- Ghi mốc thời gian các câu chốt để cắt video ngắn (`cat-video-dai-thanh-video-ngan`); ghi câu hỏi mới của khách cho lần sau.
- Có số liệu theo từng phút (người xem, bình luận, bấm đường dẫn, đăng ký) thì đặt cạnh các khối: khối nào giữ người, khối nào mất người, lời mời lúc nào có đăng ký; đưa sang `doc-so-lieu-rut-bai-hoc`.

## Đầu ra
```
KỊCH BẢN LIVESTREAM: [chủ đề] · [nền tảng] · [ngày giờ] · [thời lượng] · mức rủi ro [vừa/cao]
Mục tiêu: ...
Hướng thuyết phục đã chọn: ... (hai hướng còn lại: ...)
Trước giờ: [bài thông báo, tin nhắc]
[bảng khối nội dung theo phút]
Lời mời: ... (nguồn trong tài liệu: ...)
Câu cứu khi vắng tương tác: ... · câu lấp chỗ: ...
Người trực bình luận: [câu ghim, 5 câu hỏi dự kiến và câu trả lời, việc cần báo]
Cần xác nhận: ...
```
Kết thúc bằng câu hỏi: **duyệt kịch bản này hay sửa khối nào?**
