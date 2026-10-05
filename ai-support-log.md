# AI Support Log

## 1. Thông tin người nộp
 
- **Họ và tên:** Vũ Quốc Bảo
- **Mã học viên:** 2A202602829
- **Tên nhóm:** BLBD
- **Case:** AI Notes - Personal Learning Notes
- **Phần việc cá nhân:** Option A

## 2. AI hỗ trợ theo hoạt động

| STT | Công cụ AI | Mục đích sử dụng | Kết quả AI hỗ trợ | Cách kiểm tra, chỉnh sửa |
|---|---|---|---|---|
| 1 | Claude | Hiểu đề và quy trình của bài lab, giải thích dễ hiểu từng chặng | Tóm tắt việc cần làm ở mỗi chặng và giải thích | Đối chiếu với thông tin trong lab VLearn |
| 2 | Claude | Gợi ý thêm 1 hướng cho Solution Parking Lot | 1 hướng gợi ý, phần Option A/B/C và Parking Lot hoàn chỉnh | Claude đưa ra 2 option để chọn nhưng chỉ lấy 1 |
| 3 | Claude | Dựng prototype Option A dựa trên giao diện VLearn tôi cung cấp | Prototype 3 trạng thái: highlight và ghi chú do user tự tạo, Sổ ghi chú gom theo mục realtime, màn Ôn bài, bản ghi chú ôn tập | Mở và trải nghiệm thử trước khi đưa cho các thành viên khác trong nhóm duyệt |
| 4 | Claude | Chuyển bộ slide PDF của nhóm thành ảnh slide, trích toạ độ chữ từ PDF để cho phép bôi đen chữ; gán slide vào 3 mục và 2 slide không thuộc mục nào | 11 ảnh slide, lớp chữ có thể bôi đen, bút chọn vùng cho hình/biểu đồ, danh sách mục của slide | Đã kiểm tra lại tính năng bôi đen trong prototype và hoạt động được |
| 5 | Claude | Gợi ý cấu trúc các file nộp và soạn khung `prototype-feedback-note.md`, `group-feedback-synthesis.md` | Hai mẫu file để trống | Đưa bản khung cho các thành viên trong nhóm check trước khi duyệt |
| 6 | Claude | Sinh file `ai-support-log.md` | Tạo ra file AI log dựa theo lịch sử cuộc trò chuyện | Kiểm tra lại file trước khi nộp |

## 3. Một ví dụ AI trả lời chưa phù hợp

**AI đã đề xuất:** Bản prototype Option A đầu tiên có highlight và ghi chú dựng sẵn; sau khi tôi đưa bộ slide PDF của nhóm, AI chuyển PDF thành ảnh slide.
 
**Vấn đề:** Highlight và ghi chú dựng sẵn không cho thấy việc user tự tạo nội dung. Slide dạng ảnh nên không bôi đen chữ được, và tôi không highlight được trên prototype.
 
**Tôi đã sửa:** Yêu cầu bỏ dữ liệu dựng sẵn để highlight và ghi chú do chính người dùng tạo, rồi tổng hợp lại theo thời gian thực. Sau đó hỏi có cách nào không dát phẳng PDF, và yêu cầu dùng chữ trong PDF để bôi đen. AI bổ sung lớp chữ lấy từ PDF, giữ bút chọn vùng cho hình và biểu đồ.

**Bài học:** Nên nêu rõ ràng hơn các điều kiện ngay từ đầu trước khi cho AI tạo bản prototype.

## 4. Reflection về AI Support

AI thực sự hữu ích khi có thể từ ý tưởng thô sơ ban đầu và chuyển hóa thành dạng giao diện có thể thao tác trực tiếp được một cách nhanh chóng.