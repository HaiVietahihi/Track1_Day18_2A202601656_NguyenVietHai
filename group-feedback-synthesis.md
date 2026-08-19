# Group Feedback Synthesis — sau khi có đủ ba bản

**Nguồn:** Feedback 1 là bản của Nguyễn Hoàng Minh, một learner từng dùng AI hỏi bài học và dùng ChatGPT nhiều nhất. Feedback 2 là bản của Nguyễn Việt Hải, chưa có ghi chép chi tiết tại thời điểm tổng hợp. Feedback 3 là bản của Trịnh Hải Đăng, buổi này chạy theo hình thức giới thiệu và xin đề xuất, không theo đúng luật không thuyết minh mà nhóm đã chốt, nên phần lớn ô quan sát hành vi trực tiếp không có dữ liệu.

## Bảng tổng hợp

| Nội dung | Feedback 1 | Feedback 2 | Feedback 3 | Pattern hoặc khác biệt |
|---|---|---|---|---|
| First action | Ở bản A, bấm ngay vào nút trích nguồn và dừng lại đọc. | Chưa có ghi chép. | Không quan sát được, vì người dẫn giới thiệu cơ chế trước khi học viên thao tác. | Chưa đủ hai điểm dữ liệu để so sánh. Chỉ có Feedback 1 cho thấy hành vi tự bấm kiểm chứng ngay từ đầu. |
| Breakdown chính | Không quan sát được ở bản B và C vì tester dừng lại và chốt A ngay sau bước rà nguồn của bản A. | Chưa có ghi chép. | Ở bản C, học viên hỏi ngược người dẫn có xem được câu chưa duyệt không, thay vì tự tìm hiểu qua thao tác. | Cả hai buổi có dữ liệu đều cho thấy bản C là nơi phát sinh câu hỏi hoặc sự lấn cấn nhiều nhất, dù bối cảnh hai buổi khác nhau. |
| Cách lấy lại control | Chưa quan sát được, vì tester không đi tới tình huống cần sửa hay cần lấy lại quyền kiểm soát. | Chưa có ghi chép. | Không quan sát được. | Chưa có dữ liệu nào ở mục này từ cả ba nguồn. Đây là khoảng trống lớn nhất của đợt test này. |
| Option được chọn | A | Chưa có ghi chép, nhưng theo tổng kết nhanh của nhóm thì người này cũng chọn A. | A | Ba trên ba người chọn A theo tổng kết nhanh của nhóm. Feedback 3 không có dòng trade-off nên theo quy tắc đã chốt, lựa chọn này không được tính vào kết quả chính thức; kết quả có căn cứ đầy đủ hiện chỉ có Feedback 1. |
| Trade-off | Không có, vì tester dừng ở A ngay từ đầu nên không tự nói ra mình đánh đổi gì khi chọn A. | Chưa có ghi chép. | Không có. Học viên không nêu điều gì mình phải đánh đổi khi chọn A. | Không nguồn nào trong ba nguồn nêu được trade-off của chính lựa chọn A. Theo quy tắc, không dòng nào đủ điều kiện tính vào kết quả tổng hợp. |

## Ghi chú riêng ngoài bảng: lý do chọn A và lý do loại B, C

Theo tóm tắt nhanh từ ba buổi, ba người đều nghiêng về A vì hai lý do phía B và C bị loại, không phải vì trade-off của A được nói ra rõ ràng.

Với bản B, lý do bị loại là cơ chế phải hỏi lại TA, và người tham gia lo ngại điều này dẫn đến việc TA dễ bị quá tải. Đây là một quan sát về phía hệ thống chứ không phải về lợi ích cá nhân của người dùng, và đáng chú ý là nó xuất hiện độc lập ở nhiều người tham gia.

Với bản C, lý do bị loại là cảm thấy không hợp lý, và người tham gia vẫn phải quay lại hỏi AI bên ngoài. Điều này khớp với chi tiết trong Feedback 1, nơi tester nói thẳng rằng AI làm hết còn quyền tin hay không vẫn ở mình, nên có hay không cũng như nhau.

## Một Next Change nhóm chốt

Giữ Option A làm cơ chế chính, và sửa lại phần diễn đạt của B và C thay vì loại hẳn hai bản này. Với B, cần thiết kế thêm cơ chế gom câu hỏi hoặc giới hạn tần suất để giảm rủi ro TA quá tải, vì đây là lo ngại lặp lại ở nhiều người chứ không phải ý kiến cá nhân. Với C, cần làm rõ hơn rằng câu trả lời đã qua người thật duyệt là khác với câu AI tự sinh, vì hiện tại người dùng đang không cảm nhận được sự khác biệt đó và vẫn thấy cần đi tra cứu ở nơi khác.

## Evidence nào dẫn tới quyết định này

Ba trên ba người tham gia đều nghiêng về A theo ghi nhận nhanh của nhóm, dù chỉ có Feedback 1 đủ điều kiện tính vào kết quả chính thức vì có đủ dòng trade-off. Feedback 1 cho thấy hành vi rà nguồn là thật, không phải thao tác chiếu lệ, vì tester dừng lại đọc kỹ và tự nói ra hai tiêu chí đúng và minh bạch trước khi quyết định tin. Feedback 3 cho thấy lý do chọn A gắn trực tiếp với nhu cầu kiểm chứng nguồn gốc, khớp với quan sát ở Feedback 1 dù hai buổi chạy theo hai cách khác nhau. Lý do loại B là lo ngại TA quá tải, và lý do loại C là cảm thấy không hợp lý và vẫn phải tra cứu ngoài, đều được nhắc tới độc lập ở nhiều người, nên nhóm coi đây là tín hiệu đáng tin hơn một ý kiến đơn lẻ.

## Still Unproven sau ba feedback

Nhóm chưa có đủ ba bản ghi chi tiết theo đúng bảng quan sát, vì Feedback 2 chưa được ghi lại và Feedback 3 không chạy theo đúng luật không thuyết minh nên thiếu phần lớn dữ liệu hành vi trực tiếp. Vì vậy kết luận "cả ba đều chọn A" hiện chỉ có một nguồn được xác nhận đầy đủ theo quy tắc của nhóm.

Nhóm chưa quan sát được cách bất kỳ tester nào xử lý khi thật sự gặp ngõ cụt, vì không ai trong hai buổi có ghi chép đi tới tình huống ý thứ ba không có gì chống lưng ở bản A, tình huống chờ coach trả lời ở bản B, hay tình huống kho trống ở bản C.

Nhóm chưa biết trade-off thật sự của việc chọn A là gì, vì không người nào tự nói ra mình phải đánh đổi điều gì. Theo quy tắc đã chốt, một lựa chọn không có trade-off đi kèm không được tính là dữ liệu đầy đủ, nên đây vẫn là câu hỏi mở cần hỏi kỹ hơn ở lượt test tiếp theo.

Nhóm cũng chưa kiểm chứng được liệu lo ngại TA quá tải ở bản B và cảm giác không hợp lý ở bản C có phải là rào cản mang tính hệ thống hay chỉ là ấn tượng ban đầu khi mới xem giới thiệu, vì phần lớn các nhận xét này đến từ buổi giới thiệu chứ không phải từ việc tự thao tác và tự trải qua ngõ cụt của từng bản.

Nhóm không tuyên bố bất kỳ phương án nào đã được validated.
