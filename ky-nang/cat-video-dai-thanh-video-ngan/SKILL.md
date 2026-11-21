---
name: cat-video-dai-thanh-video-ngan
description: Tìm trong một video dài (buổi livestream, buổi học trực tuyến, buổi chia sẻ, phỏng vấn) những đoạn 20 đến 55 giây tự đứng được, xếp hạng, rồi viết cho mỗi đoạn câu mở đầu mới, chữ trên màn và điểm cắt. Dùng khi người dùng nói "cắt video này thành video ngắn", "tìm đoạn hay trong livestream", "làm clip từ buổi học", "tái sử dụng video", hoặc dán phụ đề có mốc thời gian.
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/cat-video-dai-thanh-video-ngan/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Cắt video dài thành video ngắn

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- **Nội dung bài học không được kể trước** nếu tổ chức đã cấm (xem `tai-lieu-to-chuc/quy-tac-noi-dung.md`): chỉ chọn phần chia sẻ chung, câu chuyện của diễn giả, lời mời; không chọn phần bài tập, phương pháp cốt lõi của khóa.
- Đoạn có **hình ảnh, giọng nói, câu chuyện của học viên hoặc khách hàng** là mức cao: ghi rõ, người duyệt quyết, cần có đồng ý sử dụng hình ảnh.
- Em soạn và đề xuất; người có quyền duyệt mới cắt, đăng.
- Tiếng Việt đầy đủ, không viết tắt.

Một video ngắn cắt từ video dài **không phải** khoảnh khắc hay nhất. Nó là khoảnh khắc **đứng được một mình** khi không có phần trước và phần sau, và tập đó nhỏ hơn nhiều.

## Đầu vào
- Phụ đề hoặc bản bóc băng có mốc thời gian. Chưa có thì nhờ người dùng dán, hoặc dùng công cụ bóc băng của hệ thống nếu có.
- Video là gì (livestream, buổi học, phỏng vấn), ai nói, có học viên xuất hiện không.
- Số đoạn cần (mặc định 5).

## Bước 1 - Tìm đoạn đủ ba điều kiện
Đoạn dài 20 đến 55 giây, cả ba điều đều đúng:
1. **Mở bằng một ý trọn vẹn.** Câu đầu cần phút trước mới hiểu thì không dùng được.
2. **Có một chỗ ngoặt**: một nhận định, rồi một điều làm nó phức tạp hơn hoặc chứng minh nó.
3. **Kết bằng một câu chốt**, không kết lửng.

## Bước 2 - Loại theo quy tắc
Bỏ đoạn: kể trước nội dung bài học bị cấm; có học viên mà chưa có đồng ý hình ảnh; nhắc giá, ưu đãi đã hết hạn; nói về người vắng mặt.

## Bước 3 - Xếp hạng
Xếp theo: chỗ ngoặt mạnh tới đâu; khớp nỗi đau của khách mình tới đâu (từ số liệu bình luận nếu có); có cần chỉnh nhiều không. Giữ năm đoạn đầu.

## Bước 4 - Viết cho từng đoạn
- **Câu mở đầu mới**: câu gốc thường cần bối cảnh người xem mới không có. Viết câu thay bằng `viet-cau-mo-dau`, chấm bằng `cham-cau-mo-dau`. Câu mới đặt bằng chữ trên màn hoặc lồng tiếng, không sửa lời của diễn giả.
- **Chữ trên màn 2 giây đầu**, khác chữ với lời nói.
- **Điểm nối vòng**: câu cuối gợi gì để câu đầu trả lời, nếu hợp.
- **Khung dọc**: cắt khung ngang sang dọc thì mất gì (chữ trên bảng, người thứ hai), có sao không.

## Đầu ra
Với mỗi đoạn:
```
ĐOẠN [số] · [giờ:phút:giây bắt đầu] đến [kết thúc] · [số] giây · mức rủi ro dự kiến [thấp/vừa/cao]
Câu đầu của đoạn: "..."
Chỗ ngoặt: ...
Câu chốt: "..."
Câu mở đầu mới: ... (điểm [số]) · chữ trên màn: ...
Điểm nối vòng: ...
Khung dọc: ...
Ghi chú cho người duyệt: [học viên, quyền hình ảnh, nội dung bài học]
```
Kết thúc bằng câu hỏi: **cắt đoạn nào, hay đổi đoạn nào?**
