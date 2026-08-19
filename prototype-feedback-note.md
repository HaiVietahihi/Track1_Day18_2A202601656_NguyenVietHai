# Prototype Feedback Note — bản cá nhân

Người phỏng vấn: Nguyễn Hoàng Minh
Tester và bối cảnh: Learner. Người này từng dùng AI để hỏi bài học, và dùng ChatGPT là nhiều nhất trong số các công cụ đã dùng.

## Bảng quan sát

| Observation | Note |
|---|---|
| First action | Ở bản A, ngay khi câu trả lời hiện ra, việc đầu tiên tester làm là bấm vào nút trích nguồn. |
| Chỗ dừng, do dự hoặc hiểu sai | Tester dừng lại khá lâu ở đúng chỗ vừa bấm trích nguồn trong bản A. Tester đọc kỹ để rà lại xem nguồn có đúng và có minh bạch hay không, chứ không bấm qua nhanh. |
| Evidence được đọc hay bỏ qua | Tester đọc, không bỏ qua. Tester tự nói ra tiêu chí mình dùng để đánh giá nguồn, đó là đúng và minh bạch. Khi thấy nguồn đạt hai tiêu chí này thì tester mới tin và học tiếp. |
| Cách tester sửa hoặc lấy lại control | Chưa quan sát được ở lượt này, vì tester dừng lại ngay ở bước rà nguồn của bản A và không đi tới tình huống cần sửa hay cần lấy lại quyền kiểm soát. |
| Option được chọn | A |
| Lý do và trade-off | Tester chọn A vì cách này giúp tester dễ tin tưởng hơn và học tiếp được. Đây là lý do gắn trực tiếp với hành vi rà nguồn vừa quan sát được, không phải một câu khen chung chung. |
| Evidence chống lại kỳ vọng của nhóm | Với bản B, nhóm kỳ vọng cơ chế ẩn danh sẽ đủ để hạ rào cản tâm lý và khiến learner chịu gửi câu hỏi. Nhưng tester nói rõ là chưa chắc sẽ gửi, và tự ước tính khoảng sáu mươi phần trăm gửi, bốn mươi phần trăm không gửi, tùy vào việc còn tra được ở nơi khác ngoài AI tutor hay không. Điều này cho thấy ẩn danh không phải rào cản duy nhất; còn có việc tester ưu tiên tự tra trước khi mới tính đến việc phiền một người thật, kể cả khi đã được giấu tên. |

## Tách bốn lớp

### OBSERVED — tester đã làm hoặc nói gì

Ở bản A, tester bấm vào nút trích nguồn, dừng lại đọc, và nói rằng mình đang xem nguồn có đúng và có minh bạch hay không. Tester nói cách này giúp mình dễ tin tưởng và học tiếp hơn.

Ở bản B, tester có để ý dòng trợ giảng tự chấm là chưa chắc. Tester nói dù không hiểu bài, tester cũng không chắc mình sẽ hỏi hay không. Với việc gửi ẩn danh, tester tự ước tính sáu mươi phần trăm sẽ gửi và bốn mươi phần trăm sẽ không gửi, tùy vào việc còn tra được bên ngoài AI tutor hay không.

Ở bản C, tester nói không thích lắm, vì AI làm hết mọi việc trong khi quyền tin hay không vẫn nằm ở tester, nên tester thấy có hay không cũng như nhau, và tester vẫn sẽ phải tự đi tra AI ở bên ngoài.

Cuối buổi, tester chốt chọn bản A.

### INTERPRETED — nhóm nghĩ điều đó có thể có nghĩa gì

Việc tester dừng lại lâu ở đúng nút trích nguồn, và tự nói ra hai tiêu chí đúng và minh bạch, cho thấy hành vi kiểm chứng ở bản A không phải một thao tác chiếu lệ. Tester thực sự dùng phần trích nguồn để ra quyết định, không phải bấm cho có rồi bỏ qua.

Câu tester nói về bản C, rằng AI làm hết còn quyền tin hay không vẫn ở mình, cho thấy vấn đề của bản C có thể không nằm ở việc thiếu người thật duyệt, mà nằm ở chỗ bản thân việc có người duyệt sẵn không thay đổi được gánh nặng tự phán đoán mà tester vẫn phải mang. Với tester này, một câu trả lời đã duyệt không tự động trở nên đáng tin hơn một câu trả lời có nguồn để tự kiểm.

Con số sáu mươi trên bốn mươi ở bản B gợi ý rằng cơ chế ẩn danh có tác dụng nhưng không phải yếu tố quyết định duy nhất. Việc tester còn kênh nào khác để tự tra hay không mới là yếu tố tester cân nhắc trước, và việc hỏi coach chỉ được tính đến sau đó.

### DECIDED — nhóm sẽ sửa, kết hợp hoặc test gì tiếp

Đây là dữ liệu từ một người, nên nhóm chưa quyết định thay đổi thiết kế ngay ở bước này. Nhóm ghi lại hai hướng cần đối chiếu tiếp với hai tester còn lại.

Hướng thứ nhất là kiểm tra xem cơ chế trích nguồn của bản A có tạo được cùng một mức tin tưởng với những tester khác không, đặc biệt với người không có thói quen tự tra cứu như tester này.

Hướng thứ hai là kiểm tra xem nhận định của tester về bản C, rằng có người duyệt sẵn không thay đổi được gánh nặng tự phán đoán, có lặp lại ở người khác không. Nếu lặp lại, nhóm cần xem lại phần diễn đạt của bản C, vì có thể cách trình bày hiện tại không truyền tải được rằng câu trả lời đã qua một người thật kiểm tra trước, khiến tester đọc nó giống như một câu do AI tự sinh bình thường.

### STILL UNPROVEN — điều gì chưa thể kết luận từ một người

Nhóm chưa biết liệu việc tester ưu tiên tự tra cứu bên ngoài trước khi nghĩ đến việc hỏi coach có phải là hành vi phổ biến của learner nói chung, hay chỉ là thói quen riêng của người đã quen dùng ChatGPT.

Nhóm cũng chưa quan sát được cách tester xử lý khi gặp ngõ cụt thật sự, vì tester dừng lại và chốt bản A ngay từ bước rà nguồn, chưa đi tới tình huống ý thứ ba không có gì chống lưng, và cũng chưa đi tới màn coach trả lời ở bản B hay màn câu chưa ai duyệt ở bản C. Đây là khoảng trống cần tester tiếp theo lấp vào.

Nhóm chưa biết bản A có giữ được sức hút này khi câu trả lời không phải một khái niệm rõ ràng có sẵn trong tài liệu, mà rơi vào loại tình huống nằm ngoài tài liệu khóa, tức là đúng loại tình huống mà bản A yếu nhất theo dự đoán ban đầu của nhóm.

## Ghi chú

Đây là dữ liệu từ một người, dùng để đối chiếu chứ chưa dùng để kết luận. Nhóm không tuyên bố phương án nào đã được validated.
