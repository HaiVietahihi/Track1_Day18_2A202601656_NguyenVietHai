# Prototype Feedback Note — bản cá nhân

**Người phỏng vấn:** Nguyễn Việt Hải
**Tester và bối cảnh:** Nguyễn Thị Thương - phòng D304

## Bảng quan sát

| Observation | Note |
|---|---|
| First action | Bản A người dùng ấn vào nút trích dẫn nguồn trước, Bản B người dùng sẽ ấn nút gửi ẩn danh, Bản C người dùng sẽ ấn vẫn chưa hiểu |
| Chỗ dừng, do dự hoặc hiểu sai | Do dự ở bản B khi chưa rõ về cơ chế của AI khi chờ câu hỏi được coach duyệt |
| Evidence được đọc hay bỏ qua | Evidence được tester đọc và kiểm duyệt |
| Cách tester sửa hoặc lấy lại control | không thu nhập được chủ yếu là các luồng cần Human tester còn chưa hiểu rõ |
| Option được chọn | A |
| Lý do và trade-off | Bản A là bản khả thi nhất vì tester bảo Bản B còn mơ hồ còn Bản C là bản sẽ cần phải chờ lâu vì cần Human In The Loop nhiều |
| Evidence chống lại kỳ vọng của nhóm | Bản A là bản được chọn vì tính đơn giản nhanh chóng |

## Tách bốn lớp

### OBSERVED — tester đã làm hoặc nói gì

- **First action:** Ở Bản A, người dùng bấm vào nút trích dẫn nguồn trước tiên. Ở Bản B, người dùng bấm nút gửi ẩn danh. Ở Bản C, người dùng bấm nút "vẫn chưa hiểu".
- **Evidence:** Evidence (nguồn trích dẫn/bằng chứng) được tester đọc và kiểm duyệt kỹ lưỡng, không bỏ qua.
- **Do dự / Chỗ dừng:** Tester tỏ ra do dự ở Bản B khi chưa rõ về cơ chế xử lý của AI trong thời gian chờ câu hỏi được coach duyệt.
- **Lấy lại control:** Chưa thu thập được thông tin ở luồng này, chủ yếu do các luồng cần có sự tham gia của con người (Human tester) còn chưa được người dùng hiểu rõ.
- **Option được chọn:** Tester chốt chọn **Option A**.
- **Lý do & Trade-off:** Tester đánh giá Bản A là bản khả thi nhất. Tester giải thích rằng Bản B còn mơ hồ, còn Bản C sẽ phải chờ lâu vì cần Human In The Loop (sự can thiệp của con người) nhiều.
- **Evidence chống lại kỳ vọng:** Bản A được chọn vì tính đơn giản và nhanh chóng, trái với suy đoán ban đầu của nhóm rằng các tính năng có sự hỗ trợ trực tiếp từ con người/coach ở Bản B hay C sẽ tạo cảm giác an tâm hơn.

### INTERPRETED — nhóm nghĩ điều đó có thể có nghĩa gì

- Hành vi ấn nút trích dẫn nguồn ngay lập tức ở Bản A cho thấy người dùng có nhu cầu kiểm tra tính minh bạch và độ chính xác của thông tin trước khi tiếp thu.
- Việc do dự ở Bản B xuất phát từ sự thiếu minh bạch trong trạng thái chờ: người dùng không biết AI sẽ phản ứng thế nào hay hệ thống xử lý ra sao trong lúc coach chưa duyệt câu hỏi.
- Sự e ngại đối với Bản C chỉ ra rằng thời gian chờ đợi (latency) do quy trình Human In The Loop gây ra là một ma sát lớn, ảnh hưởng tiêu cực đến trải nghiệm học tập cần sự liên tục.
- Quyết định chọn Bản A phản ánh ưu tiên hàng đầu của người dùng là tính đơn giản, phản hồi nhanh chóng và khả năng tự kiểm chứng hơn là các quy trình phê duyệt phức tạp.

### DECIDED — nhóm sẽ sửa, kết hợp hoặc test gì tiếp

- Giữ **Option A** làm phương án cơ sở, tiếp tục hoàn thiện giao diện trích dẫn nguồn để minh bạch hóa thông tin.
- Làm rõ cơ chế hiển thị trạng thái ở **Option B**: cần có phản hồi giao diện rõ ràng trong lúc câu hỏi chờ coach duyệt để giải tỏa sự mơ hồ của người dùng.
- Xem xét lại thiết kế **Option C**: tối ưu hóa luồng làm việc để giảm thời gian chờ đợi nếu muốn áp dụng mô hình Human In The Loop.
- Bổ sung kịch bản thử nghiệm để quan sát rõ hơn cách người dùng sửa lỗi hoặc lấy lại quyền kiểm soát khi AI trả lời không đúng.

### STILL UNPROVEN — điều gì chưa thể kết luận từ một người

- Chưa thu thập được dữ liệu về cách người dùng sửa hoặc lấy lại quyền kiểm soát khi hệ thống gặp lỗi hoặc đưa ra câu trả lời sai.
- Chưa xác định được cái giá (trade-off) cụ thể mà người dùng chấp nhận đánh đổi khi sử dụng Bản A trong các tình huống câu hỏi nằm ngoài tài liệu khóa học.
- Cần thử nghiệm thêm trên các tester khác để xác nhận liệu việc e ngại thời gian chờ của Human In The Loop (Bản C) có phải là xu hướng chung của mọi learner hay không.

## Ghi chú

Bản ghi chú này phản hồi về prototype dựa trên buổi thử nghiệm với tester Nguyễn Thị Thương (phòng D304), do Nguyễn Việt Hải thực hiện. Dữ liệu được dùng để tổng hợp và đối chiếu với các bản ghi cá nhân khác trong nhóm.

