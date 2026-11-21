---
name: doc-so-lieu-rut-bai-hoc
description: Đọc số liệu bài đã đăng và tỷ lệ người xem còn ở lại theo từng giây của video, tìm ba kiểu rò người xem - rò ở đầu, tụt dốc đột ngột, tụt đều ở giữa - chỉ ra câu đang nói ở chỗ rò, so bài với mức thường ngày của chính kênh, rồi đề xuất bài học đưa vào Ví dụ sửa. Dùng khi người dùng nói "vì sao bài này ít xem", "người xem bỏ ở đâu", "đọc số liệu tuần này", "rút kinh nghiệm bài đăng", hoặc dán tệp xuất số liệu.
---

<!-- BẢN CHÉP: bản gốc ở marketing-skills-tld-vn/skills/doc-so-lieu-rut-bai-hoc/SKILL.md. Không sửa ở đây; sửa bản gốc rồi chạy: node dong-bo.cjs -->

# Đọc số liệu, rút bài học

**Quy tắc (áp dụng mọi bước; bản đầy đủ ở `quy-tac-chung.md` của gói):**
- Thông tin của tổ chức: tìm ở kho tri thức trước (Luật tuân thủ, Tài liệu, Ví dụ sửa); không có thì đọc `tai-lieu-to-chuc/`.
- Không bịa số liệu. Tách rõ **điều thấy trong số liệu** với **điều em đoán**.
- Ít dữ liệu thì nói "chưa đủ để kết luận". Một bài thấp chưa phải quy luật.
- Bài học chỉ là đề xuất; người duyệt mới nạp vào kho tri thức. Em không tự sửa quy tắc nội dung.
- Tiếng Việt đầy đủ, không viết tắt.

## Đầu vào
- Số liệu bài: lượt hiển thị hoặc tiếp cận, lượt xem, thích, bình luận, chia sẻ, lưu, bấm đường dẫn; ngày giờ đăng; kênh; định dạng.
- Video: tệp xuất **tỷ lệ còn xem theo thời gian** (hai cột: thời điểm và phần trăm người còn xem) từ trang số liệu của nền tảng; phụ đề có mốc thời gian.
- Số liệu các bài trước của chính kênh (ít nhất 10 bài để có mức thường ngày).

## Phần 1 - Bài này so với chính kênh
- Mức thường ngày = **trung vị** của 10 bài gần nhất cùng kênh, cùng định dạng.
- Bội số = số liệu bài này chia mức thường ngày, cho lượt xem và cho tỷ lệ tương tác ((thích + bình luận + chia sẻ + lưu) chia lượt xem).
- Dưới 10 bài để so thì ghi "chưa có mức thường ngày" và chỉ mô tả.

## Phần 2 - Ba kiểu rò người xem (video)
Ba kiểu là ba vấn đề khác nhau, sửa khác nhau:
1. **Rò ở đầu**: phần người xem mất trong 3 giây đầu (video ngắn) hoặc 30 giây đầu (video dài). Sửa ở **câu mở đầu, ảnh bìa, tiêu đề** (`cham-cau-mo-dau`).
2. **Tụt dốc**: một chỗ mất nhiều người trong thời gian ngắn, mặc định mất từ 5 điểm phần trăm trở lên trong không quá 5% thời lượng video. Sửa ở **đúng khoảnh khắc đó**.
3. **Tụt đều**: tốc độ mất người đều đều ở phần giữa, tính bằng điểm phần trăm mỗi 10 giây. Sửa ở **nhịp**: đổi hình chậm, nói dài, thiếu chỗ ngoặt.

Có phụ đề thì với mỗi chỗ tụt dốc ghi **câu đang nói** ở giây đó và 3 giây trước. Đây là phần làm được ngay mà không phải tua lại video.

## Phần 3 - Tìm nguyên nhân có thể
Với mỗi chỗ rò, đưa tối đa hai nguyên nhân có thể, đánh dấu là đoán:
- Câu mở đầu không xác nhận điều tiêu đề hứa.
- Chỗ tụt dốc trùng lúc giới thiệu bản thân, nhắc giá, chuyển chủ đề, nói chung chung.
- Tụt đều do đoạn dài không đổi hình, không có câu chốt.
So với thẻ cấu trúc của bài mẫu nếu bài này được làm theo thẻ: lệch khung ở đâu.

## Phần 4 - Bình luận nói gì
Nếu có số liệu bình luận đã gom theo chủ đề nỗi đau và nhu cầu: chủ đề nào nổi lên, có khớp ý bài không. Chỉ dùng số tổng hợp, không trích tên người bình luận.

## Phần 5 - Đề xuất bài học
- Mỗi bài học một câu, kèm bằng chứng (bài nào, số nào).
- Chỉ đề xuất đưa vào **Ví dụ sửa** khi cùng một kết luận thấy ở **ít nhất 3 bài** hoặc **2 lượt thử** (`thu-nhieu-phien-ban`).
- Đề xuất chỉnh ngưỡng hoặc dấu hiệu chấm câu mở đầu khi bài điểm cao mà rò ở đầu nhiều, hay ngược lại, lặp lại ít nhất 5 bài.

## Đầu ra
```
BÀI: [tên] · [kênh] · [ngày] · [định dạng]
So với chính kênh: lượt xem [bội số] lần · tương tác [bội số] lần (trung vị của [số] bài)
Rò ở đầu: mất [số]% trong [số] giây đầu
Tụt dốc: [giây] mất [số] điểm · đang nói: "..." · có thể vì: ... (đoán)
Tụt đều: [số] điểm mỗi 10 giây ở đoạn [giây] đến [giây]
Bình luận: [chủ đề nổi lên]
Bài học đề xuất: ... · bằng chứng: ... · đưa vào Ví dụ sửa: [có/chưa, vì sao]
```
Kết thúc bằng câu hỏi: **nạp bài học nào vào Ví dụ sửa?**
