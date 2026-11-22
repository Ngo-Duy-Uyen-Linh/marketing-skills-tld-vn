# Marketing-skills-tld-vn: bộ kỹ năng marketing nội dung tiếng Việt

Bộ kỹ năng chung cho mọi tổ chức (bản 0.6.1). Dùng được trong Claude Code và nạp được vào hệ thống quản trị Thế Là Được như một gói kỹ năng của nhân sự AI.

## Bốn gói theo vai (từ bản 0.5.0)
Hệ thống nạp toàn bộ kỹ năng của gói vào mỗi lượt chạy, nên bộ được tách thành bốn gói theo vai để mỗi nhân sự AI chỉ nạp phần của mình. Thư mục này là **bản gốc duy nhất**; bốn gói sinh tự động bằng `node dong-bo.cjs`.
| Gói | Kỹ năng | Khoảng ký tự mỗi lượt |
|---|---|---|
| `marketing-nghien-cuu-tld-vn` | nghiên cứu xu hướng, mổ xẻ bài mẫu, đối thủ và định vị, kế hoạch chiến dịch, lập kế hoạch nội dung, báo cáo hiệu quả kỳ, đọc số liệu, thử nhiều phiên bản, làm mới bài hiệu quả | 45.000 |
| `marketing-sang-tao-tld-vn` | viết và chấm câu mở đầu, kịch bản video ngắn, bài đăng, cắt video dài, tiêu đề và ảnh bìa, ảnh trích dẫn, kịch bản livestream, bỏ giọng văn máy, dựng giọng văn thương hiệu | 48.000 |
| `marketing-giu-quy-tac-tld-vn` | kiểm nội dung theo quy tắc, bỏ giọng văn máy | 15.000 |
| `marketing-binh-luan-tld-vn` | trả lời bình luận công khai, xử lý sự cố truyền thông, bỏ giọng văn máy | 20.000 |
Số ký tự mỗi lượt = vai trò (`vai-tro.md`, gồm quy tắc chung, khoảng 6.600) cộng mọi kỹ năng trong `ky-nang/`, đếm bằng số ký tự (không đếm byte); không tính `tai-lieu-to-chuc/` vì tệp đó nạp vào kho tri thức. Gói đầy đủ (thư mục này) khoảng 98.000 ký tự (kỹ năng khoảng 91.700), hợp với Claude Code hoặc khi một AI làm hết mọi việc.

## Vòng làm nội dung
```
nghiên cứu xu hướng → mổ xẻ bài mẫu → lập kế hoạch → viết câu mở đầu → chấm câu mở đầu
      ↑                                                   ↓
đọc số liệu, rút bài học ← thử nhiều phiên bản ← đăng (người duyệt) ← kịch bản video / bài đăng / cắt video dài
```

## Hai mươi hai kỹ năng
| Kỹ năng | Việc |
|---|---|
| `ke-hoach-chien-dich` | Kế hoạch cả một đợt: mục tiêu đo được, thông điệp, kênh, lịch tính ngược từ mốc, chỉ số, ngân sách, rủi ro |
| `doi-thu-va-dinh-vi` | So thông điệp của đối thủ bằng nội dung công khai, tìm khoảng trống thông điệp |
| `bao-cao-hieu-qua-ky` | Báo cáo tuần, tháng, đợt: chỉ số so mục tiêu và kỳ trước, thắng, hụt, ưu tiên kỳ sau |
| `nghien-cuu-xu-huong` | Tìm bài vượt trội so với chính kênh, rút chủ đề và kiểu câu mở đầu đang lên, viết bản tin xu hướng |
| `mo-xe-bai-mau` | Mổ xẻ một bài hiệu quả thành thẻ cấu trúc để học khung |
| `lap-ke-hoach-noi-dung` | Kế hoạch tuần hoặc tháng: thu hút, nuôi dưỡng, mời, chăm sóc; gắn nỗi đau và mức rủi ro |
| `viet-cau-mo-dau` | Ba câu mở đầu thuộc ba nhóm tâm lý khác nhau |
| `cham-cau-mo-dau` | Chấm năm tiêu chí, lấy điểm yếu nhất làm trọng tâm, chặn câu dở |
| `viet-kich-ban-video-ngan` | Bảng cảnh: lời nói, chữ trên màn, hình ảnh, thời lượng |
| `viet-bai-dang-mang-xa-hoi` | Bài cho trang Facebook, nhóm Zalo, Zalo OA, Instagram, Threads |
| `cat-video-dai-thanh-video-ngan` | Tìm đoạn tự đứng được trong livestream, buổi học |
| `thu-nhieu-phien-ban` | Thiết kế và đọc kết quả thử, phép so hai tỷ lệ |
| `doc-so-lieu-rut-bai-hoc` | Ba kiểu rò người xem, câu đang nói ở chỗ rò, đề xuất Ví dụ sửa |
| `kiem-noi-dung-theo-quy-tac` | Kiểm bài theo bộ quy tắc: pháp lý, từ ngữ, giọng, mức rủi ro; kết luận Đạt, Cần sửa, Phải người duyệt |
| `viet-anh-trich-dan` | Chọn câu đã duyệt và ảnh nền chưa dùng, đặt chữ lên mẫu, viết chú thích |
| `kich-ban-livestream` | Kịch bản theo khối thời gian, phân vai, việc của người trực bình luận |
| `tra-loi-binh-luan-cong-khai` | Phân loại bình luận, trả lời ngắn công khai, mời nhắn riêng, chuyển người |
| `tieu-de-va-anh-bia` | Viết mười, giữ ba cặp tiêu đề và ảnh bìa; chấm như một cặp; học ảnh bìa từ bài vượt trội |
| `bo-giong-van-may` | Bỏ dấu vết văn do máy viết trong tiếng Việt, giữ nguyên sự thật |
| `dung-giong-van-thuong-hieu` | Dựng giọng văn của tổ chức từ 5 đến 10 bài thật, dấu hiệu có câu trích, viết thử để kiểm |
| `xu-ly-su-co-truyen-thong` | Sự cố: xác minh, phân mức, lên tiếng sớm, đính chính có bằng chứng, tạm dừng lịch đăng, người quyết |
| `lam-moi-bai-hieu-qua` | Chọn bài hiệu quả dùng lâu được, làm mới theo lịch, đổi một yếu tố mỗi lần, đưa sang kênh khác |

## Cấu trúc
```
quy-tac-chung.md        quy tắc mọi kỹ năng làm theo
bai-kiem-tra/           tình huống kiểm tra vào việc của gói (hệ thống Thế Là Được đọc)
skills/<tên>/SKILL.md   kỹ năng (bản gốc, dạng Claude Code)
ky-nang/<tên>/SKILL.md  bản chép cho hệ thống quản trị (tạo tự động)
goi.json, vai-tro.md    tệp cho hệ thống quản trị (tạo tự động)
tai-lieu-to-chuc/       tệp mẫu để tổ chức điền
```

## Tổ chức dùng bộ này thế nào
1. Cài gói (Claude Code: thêm kho làm marketplace; hệ thống Thế Là Được: lập đề xuất tải kho công khai theo thẻ phiên bản hoặc mã commit).
2. Điền năm tệp trong `tai-lieu-to-chuc/` (tệp giọng văn có thể dựng bằng `dung-giong-van-thuong-hieu` từ bài thật) rồi nạp vào kho tri thức của tổ chức: `quy-tac-noi-dung.md`, `giong-van-thuong-hieu.md` là Luật tuân thủ; `khach-hang-va-noi-dau.md`, `san-pham-va-khoa-hoc.md`, `kenh-va-so-lieu.md` là Tài liệu.
3. Bài học rút ra sau mỗi lượt đo, người duyệt nạp vào Ví dụ sửa. Lần sau em dùng lại.

## Giới hạn
- Bộ này không cào dữ liệu, không đăng bài, không có mã chạy. Lấy số liệu và đăng bài là việc của công cụ trong hệ thống hoặc của người dùng.
- Dấu hiệu chấm câu mở đầu và các ngưỡng là điểm khởi đầu, chưa đo trên số liệu thật.

Nguồn tham khảo và giấy phép: `NOTICE.md`.
