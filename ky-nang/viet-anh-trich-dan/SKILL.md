---
name: viet-anh-trich-dan
description: Soạn bài ảnh trích dẫn - chọn câu trong ngân hàng câu trích dẫn đã duyệt, chọn ảnh nền, đặt chữ lên mẫu ảnh, viết chú thích đăng kèm, không lặp câu và ảnh trong khoảng tổ chức đặt. Dùng khi người dùng nói "làm ảnh trích dẫn", "câu nói hay của cô", "đăng câu trích dẫn mỗi ngày", "chọn câu cho nhóm Zalo sáng mai", hoặc khi lịch đăng định kỳ cần bài.
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/viet-anh-trich-dan/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Viết ảnh trích dẫn

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- **Chỉ dùng câu đã duyệt** trong ngân hàng câu của tổ chức. Không sửa lời của diễn giả, không cắt câu làm đổi nghĩa. Thấy câu hay ngoài ngân hàng thì đề xuất thêm vào ngân hàng, không dùng ngay.
- Ảnh có người thật (diễn giả, học viên) phải còn quyền sử dụng; không có thì dùng ảnh nền không có người.
- Em soạn; bài đăng theo quy định duyệt của tổ chức. Câu đã duyệt ghép mẫu ảnh thường là mức thấp; câu hay ảnh mới là mức vừa.
- Tiếng Việt đầy đủ, không viết tắt.

## Đầu vào
- Ngày đăng, kênh, chủ đề hoặc dịp (nếu có).
- Ngân hàng câu: câu, diễn giả, nguồn (buổi nào, phút nào), trạng thái duyệt, ngày dùng gần nhất. Trong hệ thống thì đọc bằng công cụ chọn câu; ngoài hệ thống thì người dùng dán.
- Kho ảnh nền và mẫu ảnh của tổ chức, ngày dùng gần nhất của mỗi ảnh.
- Khoảng không lặp: đọc từ tham số của hệ thống khi có; chưa có thì mặc định 30 ngày.

## Bước 1 - Chọn câu
- Bỏ câu đã dùng trong khoảng không lặp **trên cùng nơi đăng**.
- Ưu tiên câu khớp chủ đề, dịp, hoặc nỗi đau đang nổi trong bình luận của khách.
- Câu dài quá thì chọn câu khác, không cắt.
- Hết câu phù hợp thì báo "hết câu", không lặp câu, không tự viết câu mới gắn tên diễn giả.

## Bước 2 - Chọn ảnh nền
- Bỏ ảnh đã dùng trong khoảng không lặp trên cùng nơi đăng.
- Ảnh hợp cảm xúc của câu; đủ khoảng trống cho chữ.
- Hết ảnh thì báo "hết ảnh nền".

## Bước 3 - Đặt chữ lên mẫu
- Dùng mẫu ảnh của tổ chức (khung, phông, màu, logo, vị trí chữ).
- Chữ đọc được trên điện thoại: câu dài thì chia dòng theo ý, không ngắt giữa cụm từ.
- Ghi tên diễn giả đúng cách tổ chức quy định.

## Bước 4 - Chú thích đăng kèm
- Hai đến bốn câu: gợi một câu hỏi hoặc một tình huống người đọc nhận ra mình; không giải thích lại câu trích dẫn.
- Một lời kêu gọi nhẹ hợp kênh (bình luận một từ, lưu lại, chia sẻ cho người cần).
- Nhóm Zalo: ngắn, ấm, không kèm đường dẫn nếu quy tắc kênh cấm.

## Bước 5 - Kiểm
Dùng `kiem-noi-dung-theo-quy-tac` cho chú thích. Ghi lại câu và ảnh đã chọn để lần sau không lặp.

## Đầu ra
```
ẢNH TRÍCH DẪN: [ngày đăng] · [nơi đăng] · mức rủi ro [thấp/vừa]
Câu: "..." · [diễn giả] · nguồn [buổi, phút] · dùng lần trước [ngày hoặc chưa dùng]
Ảnh nền: [mã ảnh] · dùng lần trước [ngày] · mẫu: [tên mẫu]
Chữ trên ảnh (chia dòng): ...
Chú thích: ...
Ghi chú cho người duyệt: [hết câu, hết ảnh, quyền hình ảnh]
```
Kết thúc bằng câu hỏi: **dùng câu và ảnh này hay đổi?**
