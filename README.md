# README - Day 18

| | |
|---|---|
| **Tên nhóm** | 333 |
| **Case đã chọn** | **A — AI Tutor · Diagnostic Refresher** |
| **Sản phẩm** | VLearn |

**Thành viên nhóm**

| # | Họ và tên | MHV |
|---|---|---|
| 1 | Nguyễn Hoàng Minh | 2A202601764 |
| 2 | Nguyễn Việt Hải | 2A202601656 |
| 3 | Trịnh Hải Đăng | 2A202601602 |

## Chặng 1: Evidence huddle và chốt Hypothesis Problem

### Phần 1. Evidence huddle

Nhóm đặt ba practice note cạnh nhau và đọc như ba nguồn riêng biệt. Mỗi thành viên chọn ra một chi tiết trong bản ghi của mình rồi đọc lại đúng nguyên văn hoặc mô tả đúng hành vi đã ghi nhận. Nhóm giữ nguyên tắc tách bạch: cột giữa là lời nói và việc làm của người được phỏng vấn, cột phải là phần suy luận của nhóm, và hai cột này không được trộn vào nhau.

#### 1.1. Bảng ba practice notes

| Practice Note | User đã thực sự làm hoặc nói gì | Điều nhóm đang diễn giải |
|---|---|---|
| Note 1: Lab coach, mã LC-01. Người phỏng vấn là Nguyễn Hoàng Minh. Người này không đúng tiêu chí tuyển của case, được phỏng vấn với tư cách nhân chứng phía hỗ trợ. | Coach cho biết chỉ cần nhìn vào là biết learner đang gặp lỗi gì, nhưng thường ít hỏi để learner tự chủ động hơn. Câu hỏi dồn vào giữa và cuối buổi, trong đó phần bị hỏi nhiều nhất là setup môi trường. Với những câu hỏi lạ, coach phải hỏi lại, mất khoảng ba mươi giây tới một phút mới biết learner cần gì, và có nhiều trường hợp coach hiểu sai ý hỏi. Ngoài giờ, coach vẫn trả lời tiếp qua tin nhắn và email, cách này chỉ giúp được một phần nhưng hiện vẫn đang dùng. Những câu ngoài lề, không đúng trọng tâm thì coach bỏ ra và không trả lời. Có lúc coach trả lời không kịp, và việc này chiếm rất nhiều thời gian, ảnh hưởng tới các công việc khác. | Nhóm cho rằng khoảng trống ở đây không phải là thiếu tín hiệu để phát hiện learner đang kẹt, mà là một lựa chọn sư phạm có chủ đích cộng với giới hạn về khả năng xử lý tuần tự của một người. Nói cách khác, kênh hỏi người thật đang bị nghẽn ngay từ phía người trả lời, chứ không chỉ từ phía learner. |
| Note 2: Learner Nguyễn Đức Đạt. Người phỏng vấn là Nguyễn Việt Hải. Người này đúng tiêu chí tuyển. | Đạt kẹt ở các bài học có kiến thức chuyên sâu về xây dựng ứng dụng AI. Việc đầu tiên khi kẹt là hỏi coach hoặc giảng viên, nhưng phải giơ tay, có thể làm chậm mạch bài giảng, và câu hỏi cũng có thể không được giải đáp. Khi đó Đạt chuyển sang hỏi bạn bè về phần còn mơ hồ, hoặc hỏi các model AI bên ngoài như Claude và ChatGPT. Việc đọc lại slide ngoài buổi học có được nhắc tới nhưng theo lời kể là chưa nhiều, phần lớn Đạt chỉ học tập trung trên lớp. Câu trả lời từ bạn bè chỉ đáp ứng được khoảng tám mươi phần trăm hoặc có lúc sai lệch, khiến Đạt phải tốn công học lại và tìm hiểu thêm. Còn hỏi AI bên ngoài thì tốn thêm token và chi phí. | Nhóm cho rằng khó khăn không nằm ở việc thiếu tài liệu để tự ôn, bởi vì việc xem lại slide ngoài giờ vốn đã ít. Khó khăn nằm ở chỗ thiếu một kênh giải đáp tức thời và ít ma sát ngay trong hoặc sát buổi học. Khi kênh chính bị nghẽn, learner chấp nhận đánh đổi độ chính xác bằng cách hỏi bạn bè, hoặc đánh đổi chi phí bằng cách hỏi AI bên ngoài, để lấp vào khoảng trống đó. |
| Note 3: Learner Đỗ Duy Đức. Người phỏng vấn là Trịnh Hải Đăng. Người này đúng tiêu chí tuyển. | Đức dùng AI tutor tích hợp sẵn trước, và khi thấy không thỏa đáng thì chụp ảnh slide đưa lên ChatGPT ở ngoài nền tảng để tra cứu. Khi có kết quả, Đức không kiểm chứng lại mà buộc phải tin. Đức ngại hỏi lab coach để xác minh, nên chọn bỏ qua phần chưa chắc chắn. Hai câu nguyên văn được ghi lại là: "Anh chụp slide lên... anh buộc phải tin thôi." và "Anh bị vấn đề là ngại hỏi lab coach. Nên anh bỏ qua." | Nhóm cho rằng vấn đề không nằm ở việc learner không biết mình hổng ở đâu, tức là giả thuyết ban đầu của nhóm đã sai ở điểm này. Vấn đề nằm ở chỗ thiếu cơ chế kiểm chứng câu trả lời của AI, cộng thêm rào cản tâm lý khi phải hỏi người thật. Hệ quả là learner chủ động chọn bỏ qua kiến thức thay vì đi xác minh. |

#### 1.2. Có situation, behavior hay workaround nào xuất hiện nhiều hơn một lần

Nhóm tìm thấy bốn điểm lặp lại, trong đó điểm đầu tiên là điểm hội tụ mạnh nhất.

Điểm lặp lại thứ nhất là kênh hỏi người thật đang bị nghẽn, và điểm này xuất hiện ở cả ba nguồn nhưng nhìn từ ba góc khác nhau. Với Đạt, chỗ nghẽn là ma sát về mặt cấu trúc, cụ thể là phải giơ tay, sợ làm chậm mạch bài giảng, và câu hỏi có thể không được giải đáp. Với Đức, chỗ nghẽn là rào cản tâm lý, cụ thể là ngại hỏi lab coach. Còn với LC-01, chỗ nghẽn đến từ chính phía coach, khi coach cố ý ít hỏi để learner tự chủ, đồng thời loại bỏ những câu ngoài trọng tâm và có lúc trả lời không kịp. Ba dạng nghẽn này khác nhau về nguyên nhân nhưng cùng dẫn tới một hệ quả: learner không lấy được câu trả lời từ người thật vào đúng thời điểm cần.

Điểm lặp lại thứ hai là workaround chính của learner đều là AI ngoài nền tảng, và điểm này đúng với cả hai learner. Đạt hỏi Claude và ChatGPT, còn Đức chụp ảnh slide đưa lên ChatGPT. Không learner nào coi việc đọc lại slide là workaround chính của mình.

Điểm lặp lại thứ ba là chi phí của workaround không nằm ở thời gian mà nằm ở độ tin cậy, và điểm này cũng đúng với cả hai learner. Đạt cho biết câu trả lời từ bạn bè chỉ đúng khoảng tám mươi phần trăm và có lúc sai lệch nên phải học lại. Đức thì nói thẳng là không kiểm chứng được nên buộc phải tin. Cả hai người đều đang đi tiếp trên một câu trả lời mà chính họ không chắc là đúng.

Điểm lặp lại thứ tư là hành vi bỏ qua, với một nguồn nói thẳng và một nguồn xác nhận gián tiếp. Đức chủ động bỏ qua phần chưa chắc. LC-01 thì cho biết có một nhóm câu hỏi bị coach loại và không trả lời, nghĩa là vẫn tồn tại một phần learner đã đặt câu hỏi nhưng không nhận được gì.

#### 1.3. Evidence nào mâu thuẫn hoặc làm nhóm bất ngờ

Bất ngờ thứ nhất là giả thuyết ban đầu của nhóm bị chính hai learner phủ định. Pain hypothesis mà nhóm viết ở Day 17 nói rằng learner không xác định được mình đang thiếu chính xác kiến thức nền nào. Nhưng Đạt chỉ rõ được mình kẹt ở mảng kiến thức chuyên sâu nào, còn Đức thì biết chính xác khái niệm nào mình chưa chắc, chỉ là không xác minh được. Như vậy rào cản không phải là chẩn đoán, mà là xác minh và tiếp cận.

Bất ngờ thứ hai là giải pháp trong directive vốn đã tồn tại, đã được dùng, và đã thất bại. Đức dùng AI tutor tích hợp sẵn trước, thấy không thỏa đáng rồi mới chụp slide ra ChatGPT. Đây là bằng chứng trực tiếp nhất chống lại directive được giao: một AI đọc nội dung bài rồi giải thích lại đã có sẵn trong luồng, learner đã thử, và vẫn phải đi ra ngoài.

Bất ngờ thứ ba là nội dung slide không phải nơi vấn đề tập trung. Đạt cho biết việc đọc lại slide ngoài buổi học là ít, còn LC-01 cho biết phần bị hỏi nhiều nhất là setup môi trường, tức là lỗi kỹ thuật khi thao tác. Điều đáng chú ý là Đức vẫn dùng slide, nhưng dùng làm vật liệu đầu vào để hỏi AI chứ không phải để đọc lại. Nói cách khác, slide đóng vai trò nguyên liệu chứ không phải câu trả lời.

Ngoài ra nhóm giữ lại hai mâu thuẫn thay vì làm phẳng chúng. Mâu thuẫn thứ nhất là hai learner đều nói mình biết rõ đang vướng gì, trong khi LC-01 lại nói có nhiều trường hợp coach hiểu sai ý hỏi của learner. Cách hòa giải khả dĩ là learner biết mình kẹt ở đâu nhưng diễn đạt không đủ chính xác cho người khác, tức đây là vấn đề truyền đạt chứ không phải vấn đề chẩn đoán. Nhóm ghi lại cách hòa giải này như một suy đoán và không dùng nó làm evidence. Mâu thuẫn thứ hai là Đức ngại hỏi coach còn Đạt lại hỏi coach trước tiên, cho thấy rào cản tâm lý không phải là hiện tượng phổ quát, nên nhóm không gộp hai người này thành một mẫu chung.

#### 1.4. Điều gì vẫn chỉ là suy đoán của nhóm

| Suy đoán | Vì sao chưa được tính là evidence |
|---|---|
| Hậu quả thật của việc bỏ qua kiến thức | Cả ba nguồn đều mỏng ở phần này. Đức nói mình bỏ qua nhưng không kể ra hậu quả cụ thể, còn Đạt nói tốn công học lại nhưng chưa nêu được bài tập sai, điểm kém hay sự cố nào. |
| Tần suất xảy ra | Không nguồn nào cho được con số theo tuần. Nhóm chưa biết đây là chuyện xảy ra mỗi buổi hay chỉ vài lần trong cả khóa. |
| Chi phí token khi hỏi AI bên ngoài | Đạt có nêu đây là một chi phí, nhưng chưa có con số hay ngưỡng nào khiến anh phải dừng lại. |
| Việc buộc phải tin có gây thiệt hại thật hay không | Chưa nguồn nào kể được một lần AI trả lời sai mà họ phát hiện ra sau đó. |
| Nhóm learner im lặng hoàn toàn nghĩ gì | Cả hai người được phỏng vấn đều là người có hành động khi kẹt. Người chọn không làm gì cả vẫn nằm ngoài dữ liệu của nhóm. |
| Việc coach cố ý ít can thiệp có phổ biến hay không | Chỉ mới có một nguồn duy nhất, nên chưa rõ đây là phong cách cá nhân hay chuẩn mực chung. |

#### 1.5. Hai chỗ nhóm đã sửa so với bản nháp ban đầu

Bản nháp Hypothesis Problem do Đăng viết đã bắt đúng rào cản, nhưng nhóm chỉnh lại hai chỗ trước khi dùng.

Chỗ thứ nhất là situation. Bản nháp mở đầu bằng cụm khi đọc slide bài giảng, trong khi Đạt nói rõ việc đọc slide ngoài buổi học là ít, và cả ba nguồn đều đặt sự kiện vào trong hoặc sát buổi học. Vì vậy nhóm đổi situation cho khớp với nơi sự kiện thực sự xảy ra.

Chỗ thứ hai là job. Bản nháp viết job là xác minh độ tin cậy của câu trả lời AI. Job này sẽ biến mất nếu bỏ AI ra khỏi bối cảnh, nghĩa là nó đang mang sẵn solution vào bên trong phần problem. Job đúng phải sống được kể cả khi không có AI, nên nhóm viết lại thành có được một câu trả lời đủ tin cậy để đi tiếp. Việc xác minh AI khi đó trở thành một trong các rào cản, chứ không còn là job nữa.

### Phần 2. Chốt Hypothesis Problem

#### 2.1. Hypothesis Problem nhóm tiếp tục

Khi đang học trong hoặc sát buổi lab và gặp một khái niệm hoặc một lỗi thao tác chưa hiểu, learner gặp khó khăn trong việc có được một câu trả lời đủ tin cậy để đi tiếp. Nguyên nhân là kênh hỏi người thật đang bị nghẽn, cụ thể là phải giơ tay giữa buổi, có người thì ngại hỏi, còn coach thì chủ động ít can thiệp và loại bỏ những câu nằm ngoài trọng tâm. Trong khi đó các kênh thay thế là bạn bè và AI ngoài nền tảng lại trả về những câu trả lời không kiểm chứng được. Hệ quả là learner hoặc đi tiếp trên một câu trả lời mà chính họ không chắc đúng, hoặc bỏ hẳn phần kiến thức đó.

#### 2.2. Evidence ban đầu hỗ trợ giả thuyết

| Thành phần của giả thuyết | Evidence tương ứng |
|---|---|
| Situation | Đạt cho biết mình kẹt ở bài học chuyên sâu, phần lớn học tập trung trên lớp và ít đọc lại slide ngoài giờ. LC-01 cho biết câu hỏi dồn vào giữa và cuối buổi. |
| Kênh hỏi người thật bị nghẽn | Ba nguồn cùng chỉ vào một chỗ. Đạt phải giơ tay, sợ làm chậm mạch bài, và câu hỏi có thể không được giải đáp. Đức nói rõ mình ngại hỏi lab coach. LC-01 xác nhận từ phía mình rằng coach cố ý ít hỏi để learner tự chủ, đồng thời loại bỏ câu ngoài trọng tâm và có lúc trả lời không kịp. |
| Workaround | Cả hai learner đều chuyển sang AI ngoài nền tảng. Riêng Đức còn đi qua AI tutor tích hợp trước khi ra ngoài, cho thấy workaround được xếp thành nhiều tầng. |
| Rào cản xác minh | Đạt cho biết câu trả lời từ bạn bè chỉ đáp ứng khoảng tám mươi phần trăm và có lúc sai lệch nên phải tốn công học lại. Đức nói thẳng là buộc phải tin. |
| Hậu quả | Đức chủ động bỏ qua phần chưa chắc. Đạt tốn công học lại và tốn thêm token khi hỏi AI bên ngoài. |

#### 2.3. Điều vẫn chưa được chứng minh

Thứ nhất là hậu quả cuối cùng. Không nguồn nào kể được một hậu quả quan sát được, chẳng hạn làm sai bài tập, phải học lại buổi, hay điểm bị ảnh hưởng. Toàn bộ phần consequence hiện đang đứng trên lời tự thuật về hành vi, chứ không đứng trên kết quả.

Thứ hai là tần suất. Nhóm chưa biết chuyện này xảy ra mấy lần mỗi buổi hay mỗi tuần, nên chưa định lượng được quy mô của vấn đề.

Thứ ba là việc buộc phải tin có gây thiệt hại thật hay không. Chưa ai kể được một lần AI trả lời sai mà họ phát hiện ra sau đó.

Thứ tư là nhóm learner im lặng. Cả hai người được phỏng vấn đều là người có hành động khi kẹt, còn người chọn không làm gì cả thì vẫn nằm ngoài dữ liệu.

Thứ năm là quan hệ giữa lỗi setup môi trường và khái niệm bài học. LC-01 nói setup bị hỏi nhiều nhất, trong khi cả hai learner đều kể về khái niệm. Nhóm chưa rõ đây là hai loại pain khác nhau hay chỉ là một loại nhìn từ hai phía.

Thứ sáu là mức độ phổ biến của việc coach cố ý ít can thiệp, vì hiện mới chỉ có một nguồn.

#### 2.4. Ràng buộc nhóm mang sang phần solution

Một AI đọc nội dung bài rồi giải thích lại thì đã tồn tại trong luồng và đã được learner sử dụng, nhưng Đức vẫn phải đi ra ngoài vì thấy không thỏa đáng. Vì vậy bất kỳ hướng giải quyết nào chỉ lặp lại năng lực đó đều khó tạo ra thay đổi. Phần chưa ai phục vụ là khâu xác minh, tức là cho learner biết câu trả lời đáng tin đến đâu, và mở một đường hỏi người thật đủ ít ma sát để họ chịu dùng khi câu trả lời chưa đủ chắc.

Nhóm không tuyên bố bất kỳ giả thuyết nào đã được validated.

## Chặng 2: Mở lại kho phương án và chọn ba cách giải

### Phần 1. Mở lại Solution Parking Lot

#### 1.1. Rà soát lại pool cũ từ Day 17

Trước khi nghĩ thêm bất kỳ hướng nào mới, nhóm quay lại đọc kỹ sáu hướng đã park ở Day 17 và đối chiếu từng hướng với những gì đã thu được từ ba cuộc phỏng vấn. Kết quả rà soát như sau:

| Số thứ tự | Hướng đã park | Cơ chế cốt lõi | Còn dùng được sau khi có evidence hay không |
|---|---|---|---|
| 1 | Nút "Tôi chưa hiểu" kèm AI chẩn đoán rồi cho ôn lại khái niệm nền | AI sinh ra lời giải thích | Nhóm quyết định loại hướng này. Đức đã dùng AI tutor tích hợp sẵn, thấy không thỏa đáng nên mới chụp slide đưa ra ChatGPT. Cả hai learner được phỏng vấn đều biết rất rõ mình đang kẹt ở đâu, nên phần chẩn đoán không phải là chỗ đang thiếu. |
| 2 | Gắn link tới bài học nền cho từng khái niệm, do đội nội dung khai báo thủ công | Điều hướng người học tới tài liệu vốn đã có sẵn | Nhóm giữ lại nhưng đánh giá là yếu. Đạt cho biết việc đọc lại tài liệu ngoài giờ học vốn đã rất ít, nên thêm một đường dẫn cũng khó thay đổi được hành vi. |
| 3 | Một câu kiểm tra nhanh ở cuối mỗi phần, trả lời sai thì mở lại phần nền tương ứng | Hệ thống tự phát hiện lỗ hổng | Giá trị giảm đi đáng kể, vì việc phát hiện không phải chỗ đang thiếu. Learner tự biết mình hổng ở đâu từ trước rồi. |
| 4 | Thư viện câu hỏi gắn theo từng slide, coach trả lời một lần cho tất cả | Tái sử dụng lại câu trả lời của người thật | Nhóm giữ lại và đánh giá mạnh, vì nó chạm đúng vào rào cản xác minh mà cả hai learner đều gặp phải. |
| 5 | Cho phép đánh dấu điểm kẹt ẩn danh rồi gom thành Support Queue cho coach | Chuyển tiếp sang người thật, có bảo vệ danh tính | Nhóm giữ lại và đánh giá mạnh. Cơ chế ẩn danh chạm đúng vào rào cản tâm lý mà Đức nói ra rất rõ. |
| 6 | AI tổng hợp các điểm kẹt lại thành báo cáo cho đội nội dung viết lại tài liệu | Cải thiện chất lượng nội dung về sau | Nhóm giữ lại nhưng thấy lệch mục tiêu, vì nó không phục vụ learner ngay tại khoảnh khắc họ đang kẹt. |

#### 1.2. Pool cũ đang thiếu điều gì

Nhìn lại cả sáu hướng, nhóm nhận ra chúng đều đang trả lời cho cùng một câu hỏi: làm thế nào để đưa được một lời giải thích tới tay learner. Không có hướng nào trả lời câu hỏi mà evidence thực sự đặt ra, đó là làm thế nào để learner biết được câu trả lời đang nằm trước mặt mình đáng tin đến mức nào. Vì lý do đó, và chỉ vì lý do đó, nhóm bổ sung thêm hai hướng mới. Nhóm không bổ sung để cho đủ số lượng ý tưởng.

Hướng bổ sung thứ bảy là neo nguồn cho câu trả lời và đánh dấu rõ những phần không có trong tài liệu khóa học. Mỗi câu trả lời sẽ đi kèm phần trích dẫn về đúng đoạn trong tài liệu của khóa, đồng thời nói thẳng ra phần nào nằm ngoài phạm vi tài liệu đó.

Hướng bổ sung thứ tám là cho phép hỏi ẩn danh chỉ bằng một thao tác ngay trong bài học, coach trả lời theo lô vào thời điểm thuận tiện, và câu trả lời sau khi được duyệt sẽ vào thư viện để những người sau dùng lại. Đây là cách hợp nhất hướng 4 và hướng 5 thành một cơ chế có vòng lặp khép kín.

#### 1.3. Dùng Day 16 như một câu hỏi gợi mở

Nhóm không lấy buổi teardown ở Day 16 làm sản phẩm nộp, mà chỉ dùng nó như một câu hỏi để mở rộng hướng suy nghĩ. Nguyên lý mà nhóm mượn lại là: sản phẩm do AI tạo ra nên tồn tại ở trạng thái một bản nháp có thể lần lại được và sửa được, chứ không phải một kết quả cuối đã đóng lại. Ở công cụ thiết kế mà nhóm đã teardown, nguyên lý này thể hiện qua việc thứ AI tạo ra vẫn nằm nguyên trên canvas cho người dùng chỉnh sửa, và vẫn còn nguyên lịch sử các phiên bản trước đó.

Điều quan trọng cần nói rõ: nhóm không sao chép tính năng lịch sử phiên bản. Nhóm mượn nguyên lý phía sau nó rồi dịch sang bối cảnh học tập, thành ra một yêu cầu khác hẳn về hình thức, đó là mỗi câu trả lời phải mang theo dấu vết về nguồn gốc của nó và về trạng thái đã được xác nhận hay chưa. Chính nguyên lý này đã sinh ra hướng bổ sung thứ bảy, và về sau trở thành xương sống của Option A.

#### 1.4. Ghi chú về chi phí khi sai

Theo khung thiết kế mức độ tự chủ của Day 18, nhóm xác định trường hợp này thuộc nhóm sai thì đắt và lại khó phát hiện. Khi learner tin nhầm một câu trả lời sai, lỗ hổng kiến thức chỉ lộ ra rất muộn, thường là tới lúc làm bài tập hoặc thi, và tới lúc đó thì không còn cách nào hoàn tác. Vì vậy nhóm thống nhất rằng không option nào được đặt ở vùng để hệ thống tự làm hoàn toàn. Cả ba phương án đều phải nằm ở vùng hỏi lại người dùng, hoặc ở vùng không tự quyết thay người dùng.

### Phần 2. Chọn ba cách giải

Ba option dưới đây cùng xuất phát từ một Hypothesis Problem, nhưng đại diện cho ba giả thuyết giải pháp khác nhau. Điểm khác biệt nằm ở chỗ: ai là người chịu trách nhiệm làm cho câu trả lời trở nên đáng tin, và việc đó diễn ra vào lúc nào.

Option A đặt việc kiểm chứng vào tay chính learner, ngay tại thời điểm họ đang kẹt. Option B để hệ thống tự khai ra mức độ chắc chắn của mình rồi mở đường sang người thật, cũng ngay tại thời điểm kẹt. Option C thì đưa việc kiểm chứng về trước, do người thật làm từ những lần trước đó, và learner chỉ việc nhận lại kết quả.

#### 2.1. Những thứ phải giữ nguyên

| Thành phần | Quyết định chung cho cả A, B và C |
|---|---|
| Target user | Learner đang theo học lab, đã từng bị kẹt và phải tự xoay xở trong bảy ngày gần đây |
| Situation | Đang làm bài trong buổi lab, ở khoảng giữa buổi, gặp một điểm kẹt, trong khi coach đang bận hỗ trợ người khác |
| Task | Có được một câu trả lời đủ tin cậy để đi tiếp bước đang làm dở |
| Desired outcome | Đi tiếp được bước tiếp theo mà không phải chấp nhận một câu trả lời mình không chắc, và cũng không phải bỏ qua phần kiến thức đó |
| Content và data fixture | Cùng một điểm kẹt là lỗi khi cài đặt môi trường ở bước 3 của bài lab, cùng một câu trả lời gốc do AI sinh ra, và cùng một bộ tài liệu khóa học |

Cả ba option đều dùng chung đúng một fixture này. Nhóm giữ nguyên fixture để chắc chắn rằng phản ứng của learner là phản ứng với cơ chế, chứ không phải phản ứng với nội dung khác nhau giữa các bản.

#### 2.2. Những thứ được phép khác nhau

| Thành phần | Option A: Neo nguồn | Option B: Tự khai mức chắc và chuyển tiếp | Option C: Đã được người thật duyệt |
|---|---|---|---|
| Solution mechanism | Mọi câu trả lời đều đi kèm phần trích dẫn về đúng đoạn trong tài liệu khóa học, đồng thời đánh dấu rõ phần nào không tìm thấy trong tài liệu | AI tự phân loại mức độ chắc chắn của chính câu trả lời vừa đưa ra. Khi mức này thấp, hệ thống đề nghị chuyển câu hỏi sang coach dưới dạng ẩn danh, và learner có thể đi tiếp trong lúc chờ | Hệ thống khớp bước mà learner đang làm với những câu trả lời đã được coach duyệt từ các lần trước rồi đưa lên trước. Chỉ khi chưa có câu nào phù hợp thì mới sinh câu trả lời mới và tự động xếp vào hàng chờ coach |
| User làm gì | Đọc phần neo nguồn rồi tự quyết định là tin hay không tin | Quyết định có gửi câu hỏi đi hay không, và tiếp tục làm việc khác trong lúc chờ phản hồi | Đọc câu trả lời đã có nhãn xác nhận, sau đó đánh dấu là có giải quyết được vấn đề hay không |
| AI làm gì | Sinh câu trả lời và neo từng ý về nguồn tương ứng. AI không phán đoán độ tin cậy và không chủ động làm gì thêm | Sinh câu trả lời, tự đánh giá mức độ chắc chắn, và soạn sẵn nội dung câu hỏi để gửi cho coach | Không sinh nội dung mới ở lượt đầu tiên, chỉ làm nhiệm vụ khớp câu hỏi với thư viện đã được duyệt |
| Trigger | Learner tự mở, giống như cách đang làm hiện nay | Hệ thống phát ra ngay trong lượt trả lời, vào lúc AI tự thấy mức chắc chắn của mình thấp | Hệ thống chủ động đưa lên khi thấy learner dừng lại lâu bất thường ở một bước vốn đã có sẵn câu trả lời |
| Trade-off chính | Đẩy toàn bộ công việc kiểm chứng lên vai learner đúng vào lúc họ đang vội. Ngoài ra phương án này gần như vô dụng khi câu trả lời vốn không nằm trong tài liệu khóa học, mà đó lại đúng là trường hợp lỗi cài đặt môi trường | Phụ thuộc hoàn toàn vào việc AI tự đánh giá đúng mức chắc chắn của mình. Nếu hệ thống báo không chắc quá thường xuyên thì tín hiệu thành nhiễu và learner sẽ bỏ qua hết. Ngoài ra vẫn phát sinh thêm một vòng chờ coach | Gặp vấn đề cold start, tức là giai đoạn đầu thư viện còn trống nên chưa giúp được gì. Phương án cũng phụ thuộc vào việc coach có chịu duyệt hay không, và kém linh hoạt với những câu hỏi lạ. Thêm nữa, việc hệ thống can thiệp chủ động đi ngược lại thói quen để learner tự xoay xở của coach |

#### 2.3. Distance check

Nhóm hoàn thành ba câu dưới đây mà không nhắc tới màu sắc, bố cục hay câu chữ, để chắc chắn rằng ba option khác nhau ở cơ chế chứ không phải khác nhau ở lớp vỏ.

A khác B ở chỗ, với A thì quyền phán đoán độ tin cậy nằm hoàn toàn trong tay learner, còn với B thì hệ thống tự tuyên bố mức chắc chắn của mình và chủ động mở một đường sang người thật. Trách nhiệm đánh giá đã chuyển từ phía con người sang phía hệ thống.

B khác C ở chỗ, B sinh ra một câu trả lời mới rồi mới đi tìm cách kiểm chứng sau đó, còn C chỉ phát lại thứ đã được người thật duyệt từ trước. Nói cách khác, việc kiểm chứng ở B diễn ra sau khi learner đã đọc, còn ở C nó diễn ra trước khi learner kịp gặp câu trả lời.

A khác C ở chỗ, A đặt toàn bộ công việc kiểm chứng lên learner ngay tại thời điểm họ đang kẹt, còn C dời công việc đó sang cho coach và sang một thời điểm khác, nên learner không phải làm gì mà vẫn có được sự đảm bảo.

#### 2.4. Vị trí của ba option trên spectrum

Nhóm dùng spectrum về quyền khởi tạo và quyền quyết định để định vị ba phương án:

| Vị trí trên spectrum | Option tương ứng | Diễn giải ngắn |
|---|---|---|
| User tự khởi tạo và tự quyết | Option A | Learner tự kiểm chứng dựa trên phần neo nguồn |
| User và AI cùng làm | Option B | Hệ thống khai mức chắc chắn, learner quyết định có leo thang lên người thật hay không |
| Hệ thống và người thật khởi tạo, user xem lại | Option C | Câu trả lời đã được duyệt từ trước, hệ thống chủ động đưa lên |

Nhóm xin lưu ý rằng không option nào bị làm yếu đi một cách cố ý để hai option còn lại trông tốt hơn. Option A là hướng gần với mặc định nhất, nhưng đồng thời cũng là hướng rẻ nhất và có thể triển khai được ngay. Option C có tiềm năng cao nhất, nhưng lại gánh rủi ro cold start nặng nhất trong ba phương án.

#### 2.5. Tự kiểm theo Gate 2

| Tiêu chí | Kết quả | Căn cứ |
|---|---|---|
| Ba option cùng target user | Đạt | Cùng là learner đã từng bị kẹt trong bảy ngày gần đây |
| Cùng situation | Đạt | Cùng bối cảnh giữa buổi lab, coach đang bận với người khác |
| Cùng task | Đạt | Cùng nhắm tới việc có được câu trả lời đủ tin cậy để đi tiếp |
| Cùng desired outcome | Đạt | Cùng mong muốn đi tiếp mà không phải tin liều và cũng không bỏ qua |
| Cùng content và data fixture | Đạt | Cùng lỗi cài đặt ở bước 3, cùng câu trả lời gốc, cùng bộ tài liệu |
| Khác nhau có ý nghĩa ở mechanism | Đạt | Ba cơ chế lần lượt là neo nguồn, tự khai mức chắc kèm leo thang, và thư viện đã được duyệt |
| Khác nhau ở cách chia việc và quyền quyết định | Đạt | Lần lượt là learner tự quyết, hệ thống khai rồi learner quyết, và người thật đã quyết từ trước |
| Mô tả được ba cơ chế mà không cần tới hình ảnh | Đạt | Ba câu trong phần distance check không nhắc tới màu sắc, bố cục hay câu chữ |
| Không có option nào bị làm yếu có chủ ý | Đạt | Mỗi option đều có một điều kiện riêng để thắng: A thắng khi tài liệu khóa học đầy đủ, B thắng khi gặp câu hỏi lạ cần tới người thật, C thắng khi câu hỏi lặp lại nhiều lần |

#### 2.6. Điều nhóm muốn học được từ ba option này

Câu hỏi nhóm mang vào buổi thử nghiệm là: khi learner đang kẹt và cần một câu trả lời đáng tin, họ muốn tự mình cầm quyền phán đoán, muốn hệ thống tự thú nhận giới hạn rồi mở đường sang người thật, hay muốn nhận sẵn một câu trả lời đã có người bảo chứng.

Kết quả mà nhóm mong đợi là một quyết định thiết kế cho bước tiếp theo, không phải một tuyên bố rằng phương án nào đó đã được validated.