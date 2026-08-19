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
