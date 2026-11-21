# Ghi chú nguồn gốc và giấy phép

Bộ này do Thế Là Được viết bằng tiếng Việt, phát hành theo giấy phép Apache License 2.0 (tệp `LICENSE`).

## Tham khảo cách làm, không chép nội dung
Các kỹ năng học **cách làm** từ những kho mã nguồn mở dưới đây. Lời văn, ví dụ, danh sách dấu hiệu tiếng Việt, ngưỡng là của bộ này; không chép tệp, mã hay câu mẫu nào từ các kho đó.

| Kho tham khảo | Giấy phép | Học điều gì | Dùng ở kỹ năng |
|---|---|---|---|
| github.com/Jakeschincariol/youtube-agent-skill | MIT | Xếp bài theo bội số so với trung vị của chính kênh, bỏ kênh dưới 4 bài; chấm câu mở đầu năm tiêu chí, điểm cuối 60% trung bình cộng 40% tiêu chí thấp nhất; ba kiểu rò người xem; chọn đoạn tự đứng được khi cắt video dài; chấm tiêu đề và ảnh bìa như một cặp | `nghien-cuu-xu-huong`, `cham-cau-mo-dau`, `doc-so-lieu-rut-bai-hoc`, `cat-video-dai-thanh-video-ngan`, `tieu-de-va-anh-bia` |
| github.com/rediumvex/viral-hooks-skill | MIT | Chia câu mở đầu theo nhóm tâm lý, mỗi lần đưa ba phương án khác nhóm | `viet-cau-mo-dau` |
| github.com/fendouai/ViralForge | Apache-2.0 | Mổ xẻ video thành câu mở đầu, cấu trúc, nhịp, đường cảm xúc, cách chốt; làm nhiều phiên bản để thử | `mo-xe-bai-mau`, `thu-nhieu-phien-ban` |
| github.com/coreyhaines31/marketingskills | MIT | Đọc bối cảnh sản phẩm và thương hiệu trước khi viết; viết riêng cho từng kênh | `viet-bai-dang-mang-xa-hoi`, `lap-ke-hoach-noi-dung` |
| github.com/mvanhorn/last30days-skill | MIT | Nghiên cứu một chủ đề trên nhiều nền tảng trong 30 ngày, tổng hợp có dẫn nguồn | `nghien-cuu-xu-huong` |

| github.com/anthropics/knowledge-work-plugins, thư mục `marketing/skills/` (commit `e91a134584eb798bac7fb0379358006a2b63b965`, 13/11/2026): `campaign-plan`, `performance-report`, `competitive-brief`, `brand-review` | Apache-2.0 | Khung kế hoạch chiến dịch (mục tiêu, khách, thông điệp, kênh, lịch tính ngược từ mốc, chỉ số, ngân sách, rủi ro); khung báo cáo kỳ (bảng chỉ số so mục tiêu và kỳ trước, ba trạng thái, thắng và hụt, đề xuất theo tác động và công sức); khung so đối thủ (hứa gì, chứng minh, cách làm, riêng có; bảng so thông điệp; khoảng trống) ; kiểm bài theo hướng dẫn thương hiệu và các cờ pháp lý luôn kiểm (tuyên bố không chứng minh, thiếu câu lưu ý, so sánh đối thủ, lời chứng thực, sát nghĩa nội dung người khác) | `ke-hoach-chien-dich`, `bao-cao-hieu-qua-ky`, `doi-thu-va-dinh-vi` (bản 0.2.0); `kiem-noi-dung-theo-quy-tac` (bản 0.3.0) |

**Đã kiểm mã chưa:** chưa kiểm mã theo quy trình kiểm repo của dự án. Em chỉ đọc README, các tệp SKILL.md và đầu một vài tệp mã (chấm câu mở đầu, xếp bài vượt trội, đọc tỷ lệ còn xem) để học ý; không cài, không chạy gì. Gói này không chứa tệp, mã hay câu mẫu nào chép từ các kho trên, nên không mang mã của họ vào hệ thống. Không lấy các kỹ năng `content-creation`, `seo-audit`, `email-sequence` và tệp kết nối `.mcp.json` của bộ Anthropic.

Học thêm ở bản 0.4.0 (cũng chỉ đọc README và SKILL.md, chưa kiểm mã, không chép):
| Kho tham khảo | Giấy phép | Học điều gì | Dùng ở kỹ năng |
|---|---|---|---|
| github.com/blader/humanizer | MIT | Các nhóm dấu vết văn do máy viết và cách viết lại giữ nguyên sự thật; danh sách dấu vết tiếng Việt là của bộ này | `bo-giong-van-may` |
| github.com/Jakeschincariol/youtube-agent-skill (`yt-comment`, `yt-package`) | MIT | Phân loại và đếm bình luận trước khi viết, trả lời ngắn, nhận đính chính, chọn một bình luận để ghim; giới hạn ký tự tiêu đề, chữ ảnh bìa tối đa ba từ, viết mười giữ vài | `tra-loi-binh-luan-cong-khai`, `tieu-de-va-anh-bia` |
| github.com/TubeLabHQ/youtube-research-skills (`comment-mining`, `thumbnail-concepts`) | MIT | Trọng số bình luận theo lượt thích, cụm từ khách lặp lại; học ảnh bìa từ bài vượt trội theo hai hướng | `tra-loi-binh-luan-cong-khai`, `tieu-de-va-anh-bia` |
| github.com/1160208849wfl/changkong-live | MIT | Ba hướng thuyết phục khác nhau, câu cứu khi vắng tương tác, học từ số liệu sau buổi | `kich-ban-livestream` |
| github.com/sophie-nguyenthuthuy/livestream-commerce-vn | Không ghi giấy phép (chỉ học ý) | Đo livestream theo từng phút, kịch bản theo giọng vùng miền | `kich-ban-livestream` |

Phép so hai tỷ lệ ở `thu-nhieu-phien-ban` là phương pháp thống kê phổ biến, dùng cùng ngưỡng với chiến dịch chăm sóc khách hàng của hệ thống Thế Là Được.

## Khác với các kho tham khảo
- Viết cho tổ chức Việt Nam, kênh Việt Nam (Facebook, nhóm Zalo, Zalo OA, TikTok).
- Thêm quy tắc chung: em soạn, người duyệt; ba mức rủi ro; học khung không chép nội dung; thu thập dữ liệu theo ba tầng; không lưu danh sách người bình luận của kênh người khác; không viết tắt.
- Không có mã chạy, không có kết nối ra ngoài. Việc lấy số liệu do hệ thống của tổ chức hoặc người dùng cung cấp.
- Dấu hiệu chấm câu mở đầu tiếng Việt và các ngưỡng là điểm khởi đầu, chưa đo trên số liệu thật; tổ chức chỉnh qua `tai-lieu-to-chuc/quy-tac-noi-dung.md`.
