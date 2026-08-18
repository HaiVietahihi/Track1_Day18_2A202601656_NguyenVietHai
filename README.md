# Evidence Huddle và Chốt Hypothesis Problem

**Case:** A. AI Tutor, Diagnostic Refresher (VLearn)
**Nhóm thực hiện:** Nguyễn Hoàng Minh, Nguyễn Việt Hải, Trịnh Hải Đăng
**Nguồn dữ liệu:** 2 learner và 1 lab coach

Chúng em đọc riêng từng nguồn trước, sau đó mới đối chiếu với nhau. Chúng em không gộp ba cuộc phỏng vấn lại thành một finding chung, vì mỗi người kể một câu chuyện khác nhau và chúng em muốn giữ nguyên sự khác nhau đó.

---

## 1. Evidence Huddle

### 1.1. Bảng ba Practice Note

| Practice Note | User đã thực sự làm hoặc nói gì? | Điều nhóm đang diễn giải |
|---|---|---|
| **1. LC-01, lab coach**<br>Người phỏng vấn: Nguyễn Hoàng Minh<br>*(không đúng tiêu chí tuyển, chúng em xếp chị vào nhóm nhân chứng phía hỗ trợ)* | Chị chỉ cần nhìn vào là **biết learner đang mắc lỗi gì**, nhưng chị **thường ít hỏi để learner tự chủ động hơn**.<br>Câu hỏi của learner dồn vào **giữa buổi và cuối buổi**, phần bị hỏi nhiều nhất là **setup môi trường**.<br>Gặp câu hỏi lạ thì chị **phải hỏi lại**, mất **30 giây đến 1 phút** mới nắm được learner cần gì, và **có nhiều trường hợp chị hiểu sai ý hỏi**.<br>Ngoài giờ chị trả lời tiếp qua **tin nhắn và email**, cách này **chỉ giúp được một phần** nhưng chị **vẫn đang dùng**.<br>Những câu **ngoài lề, không đúng trọng tâm** thì chị **bỏ ra và không trả lời**. Chị cũng nói **có lúc trả lời không kịp**. | Khoảng trống ở đây **không nằm ở chỗ thiếu tín hiệu để phát hiện learner đang kẹt**. Nó đến từ một **lựa chọn sư phạm có chủ đích**, cộng thêm **giới hạn của việc một người chỉ xử lý được một câu hỏi tại một thời điểm**. Kênh hỏi người thật bị nghẽn ngay từ phía người trả lời chứ không chỉ từ phía learner. |
| **2. Nguyễn Đức Đạt, learner**<br>Người phỏng vấn: Nguyễn Việt Hải<br>*(đúng tiêu chí tuyển)* | Kẹt ở **bài học kiến thức chuyên sâu về xây dựng ứng dụng AI**.<br>Việc đầu tiên khi kẹt là **hỏi coach hoặc giảng viên**, nhưng anh **phải giơ tay**, việc đó **có thể làm chậm mạch bài giảng**, và **câu hỏi có thể không được giải đáp**.<br>Khi đó anh chuyển sang **hỏi bạn bè**, hoặc **hỏi model AI bên ngoài như Claude và ChatGPT**.<br>Anh **ít đọc lại slide ngoài buổi học**, phần lớn **chỉ học tập trung trên lớp**.<br>Câu trả lời từ bạn bè **chỉ đáp ứng khoảng 80%, có lúc sai lệch**, khiến anh **phải tốn công học lại**. Hỏi AI bên ngoài thì **tốn thêm token và chi phí**. | Khó khăn **không nằm ở việc thiếu tài liệu để tự ôn**, mà ở chỗ **thiếu một kênh giải đáp tức thời, ít ma sát, có mặt ngay trong hoặc sát buổi học**. Khi kênh chính bị nghẽn, user phải **đánh đổi độ chính xác** (hỏi bạn) hoặc **đánh đổi chi phí** (AI ngoài) để lấp khoảng trống. |
| **3. Đỗ Duy Đức, learner**<br>Người phỏng vấn: Trịnh Hải Đăng<br>*(đúng tiêu chí tuyển)* | **Dùng AI tutor tích hợp trước**, khi thấy **không thỏa đáng** thì **chụp ảnh slide đưa lên ChatGPT ngoài nền tảng**.<br>Có kết quả rồi thì **không kiểm chứng mà buộc phải tin**.<br>Anh **ngại hỏi lab coach** để xác minh, nên **chọn bỏ qua** phần chưa chắc.<br>Nguyên văn: *"Anh chụp slide lên... anh buộc phải tin thôi."* và *"Anh bị vấn đề là ngại hỏi lab coach. Nên anh bỏ qua."* | Vấn đề **không nằm ở việc không biết mình hổng ở đâu**, giả thuyết ban đầu của chúng em sai ở đúng điểm này. Vấn đề nằm ở **thiếu cơ chế kiểm chứng câu trả lời của AI** cộng thêm **rào cản tâm lý khi phải hỏi người thật**, hai thứ đó đẩy anh tới chỗ **chủ động chọn bỏ qua kiến thức thay vì xác minh**. |

### 1.2. Những situation, behavior và workaround lặp lại nhiều hơn một lần

**Điểm lặp lại thứ nhất: kênh hỏi người thật bị nghẽn, xuất hiện ở cả ba nguồn từ ba góc khác nhau.**
Đây là điểm hội tụ mạnh nhất trong dữ liệu của chúng em, vì hai learner mô tả nó từ phía người đi hỏi còn coach xác nhận nó từ phía người trả lời.

| Nguồn | Dạng nghẽn |
|---|---|
| Đạt | Ma sát cấu trúc: phải giơ tay, làm chậm mạch bài, câu hỏi có thể không được giải đáp |
| Đức | Rào cản tâm lý: ngại hỏi lab coach |
| LC-01 | Từ phía coach: cố ý ít hỏi để learner tự chủ, lọc bỏ câu ngoài trọng tâm, có lúc không kịp |

Ba dạng nghẽn này khác nhau về nguyên nhân nhưng dẫn tới cùng một hệ quả, đó là learner không lấy được câu trả lời từ người thật đúng vào lúc họ cần.

**Điểm lặp lại thứ hai: workaround chính là AI ngoài nền tảng, cả hai learner đều làm như vậy.**
Đạt hỏi Claude và ChatGPT, còn Đức chụp ảnh slide rồi đưa lên ChatGPT. Chúng em lưu ý rằng không learner nào coi việc đọc lại slide là workaround chính của mình.

**Điểm lặp lại thứ ba: chi phí của workaround là độ tin cậy chứ không phải thời gian, cả hai learner đều vậy.**
Đạt nói câu trả lời từ bạn bè chỉ đúng khoảng 80%, có lúc sai lệch và anh phải học lại. Đức thì không kiểm chứng được nên buộc phải tin. Cả hai người đều đang đi tiếp trên một câu trả lời mà chính họ không chắc là đúng.

**Điểm lặp lại thứ tư: hành vi bỏ qua, một learner nói thẳng và một nguồn nói gián tiếp.**
Đức chủ động bỏ qua phần mình chưa chắc. LC-01 cho biết có một nhóm câu hỏi bị chị loại ra và không trả lời, nghĩa là tồn tại một phần learner đã đặt câu hỏi nhưng không nhận được gì.

### 1.3. Những evidence mâu thuẫn hoặc làm chúng em bất ngờ

**Bất ngờ thứ nhất, giả thuyết gốc của chúng em bị chính hai learner phủ định.** Pain Hypothesis A của chúng em viết rằng learner không xác định được mình đang thiếu chính xác kiến thức nền nào. Nhưng Đạt chỉ rõ mình kẹt ở mảng kiến thức chuyên sâu nào, còn Đức biết chính xác khái niệm nào mình chưa chắc, cái anh thiếu chỉ là cách xác minh. Như vậy barrier không nằm ở khâu chẩn đoán. Barrier nằm ở khâu xác minh và tiếp cận.

**Bất ngờ thứ hai, directive được giao thì đã tồn tại, đã được dùng và đã thất bại.** Đức dùng AI tutor tích hợp trước, thấy không thỏa đáng rồi mới chụp slide đưa ra ChatGPT. Đây là bằng chứng trực tiếp nhất chống lại directive: một AI có khả năng đọc nội dung bài rồi giải thích lại vốn đã có sẵn trong luồng, learner đã thử và vẫn phải đi ra ngoài. Vì vậy chúng em cho rằng làm thêm một phiên bản cùng loại chưa chắc thay đổi được điều gì.

**Bất ngờ thứ ba, nội dung slide không phải nơi vấn đề tập trung.** Đạt nói anh ít đọc lại slide ngoài buổi học. LC-01 nói phần bị hỏi nhiều nhất là setup môi trường, tức là lỗi kỹ thuật khi thao tác chứ không phải nội dung bài. Điều đáng chú ý là Đức vẫn dùng slide, nhưng anh dùng slide làm vật liệu đầu vào để hỏi AI chứ không phải để đọc lại. Với chúng em, slide đang đóng vai trò nguyên liệu chứ không phải câu trả lời.

**Mâu thuẫn chúng em giữ nguyên, learner biết mình kẹt ở đâu nhưng coach lại thường hiểu sai ý hỏi.** Hai learner đều nói họ biết rõ mình đang vướng gì, trong khi LC-01 nói có nhiều trường hợp chị hiểu sai ý hỏi của learner. Cách hòa giải khả dĩ là learner biết mình kẹt ở đâu nhưng diễn đạt chưa đủ chính xác cho người khác hiểu, tức đây là vấn đề truyền đạt chứ không phải vấn đề chẩn đoán. Chúng em ghi lại cách hòa giải này như một suy đoán và không dùng nó làm evidence.

**Mâu thuẫn thứ hai, Đức ngại hỏi coach còn Đạt lại hỏi coach trước tiên.** Điều này cho thấy rào cản tâm lý không phải là chuyện phổ quát. Với Đạt, cản trở là ma sát cấu trúc chứ không phải tâm lý. Chúng em không gộp hai người này lại thành một mẫu chung.

### 1.4. Những điều vẫn chỉ là suy đoán của chúng em

| Suy đoán | Vì sao chúng em chưa coi đây là evidence |
|---|---|
| Hậu quả thật của việc bỏ qua kiến thức | Cả ba nguồn đều mỏng ở chỗ này. Đức nói mình bỏ qua nhưng không kể hậu quả cụ thể. Đạt nói phải tốn công học lại nhưng chưa nêu được bài tập nào sai, điểm nào kém hay sự cố nào xảy ra. |
| Tần suất | Không nguồn nào cho chúng em con số lần trên tuần. Chúng em chưa biết đây là chuyện diễn ra mỗi buổi hay chỉ vài lần trong cả khóa. |
| Chi phí token của việc hỏi AI ngoài | Đạt có nêu đây là một khoản chi phí, nhưng anh chưa đưa ra con số hay ngưỡng nào khiến anh phải dừng lại. |
| Việc buộc phải tin có dẫn tới hiểu sai thật không | Chưa nguồn nào kể được một lần AI trả lời sai mà sau đó người dùng phát hiện ra. |
| Learner im lặng hoàn toàn nghĩ gì | Cả hai người chúng em phỏng vấn đều là người **có hành động** khi kẹt. Chúng em chưa tiếp cận được ai chọn không làm gì cả. |
| Mức độ phổ biến của việc coach cố ý ít can thiệp | Chúng em mới chỉ có LC-01. Chưa rõ đây là phong cách cá nhân của riêng chị hay là chuẩn mực chung. |

### 1.5. Hypothesis Problem nào đủ cụ thể để chúng em dùng làm điểm xuất phát

Bản nháp của Đăng đã bắt đúng barrier, nhưng chúng em thấy cần chỉnh hai chỗ trước khi đem ra dùng.

**Chỗ cần chỉnh thứ nhất là situation.** Bản nháp mở đầu bằng cụm *"khi đọc slide bài giảng"*, trong khi Đạt nói rõ anh ít đọc slide ngoài buổi học, và cả ba nguồn đều đặt sự kiện vào trong hoặc sát buổi học. Vì vậy chúng em đổi situation cho khớp với nơi sự kiện thật sự diễn ra.

**Chỗ cần chỉnh thứ hai là job.** Bản nháp viết job là *"xác minh độ tin cậy của câu trả lời AI"*. Job này sẽ biến mất nếu bỏ AI ra khỏi bối cảnh, nghĩa là nó đang mang sẵn solution vào bên trong problem. Job đúng phải sống được kể cả khi không có AI, đó là **có được một câu trả lời đủ tin cậy để đi tiếp**. Khi viết lại như vậy, việc xác minh AI trở thành một trong các barrier chứ không còn là job.

---

## 2. Chốt Hypothesis Problem

### 2.1. Hypothesis Problem chúng em tiếp tục

> **Khi** đang học trong hoặc sát buổi lab và gặp một khái niệm hoặc một lỗi thao tác chưa hiểu, **learner** gặp khó khăn trong việc **có được một câu trả lời đủ tin cậy để đi tiếp**, **vì** kênh hỏi người thật bị nghẽn (phải giơ tay giữa buổi, ngại hỏi, hoặc coach chủ động ít can thiệp và loại bỏ những câu ngoài trọng tâm), trong khi các kênh thay thế là bạn bè và AI ngoài nền tảng đều trả về câu trả lời không kiểm chứng được, **dẫn đến** learner hoặc đi tiếp trên một câu trả lời mà chính họ không chắc đúng, hoặc bỏ hẳn phần kiến thức đó.

### 2.2. Evidence ban đầu hỗ trợ giả thuyết

**Về situation.** Đạt kẹt tại bài học chuyên sâu, phần lớn anh học tập trung trên lớp và ít đọc lại slide ngoài giờ. LC-01 cho biết câu hỏi dồn vào giữa buổi và cuối buổi.

**Về việc kênh người thật bị nghẽn.** Chúng em có sự hội tụ của cả ba nguồn. Đạt phải giơ tay, việc hỏi làm chậm mạch bài và câu hỏi có thể không được giải đáp. Đức nói *"anh bị vấn đề là ngại hỏi lab coach"*. LC-01 cố ý ít hỏi để learner tự chủ, loại bỏ câu ngoài trọng tâm và có lúc trả lời không kịp.

**Về workaround.** Cả hai learner đều chuyển sang AI ngoài nền tảng. Riêng Đức còn đi qua AI tutor tích hợp trước khi ra ngoài, nghĩa là workaround của anh được xếp thành nhiều tầng.

**Về barrier xác minh.** Đạt nói câu trả lời từ bạn bè chỉ đáp ứng khoảng 80%, có lúc sai lệch và anh phải tốn công học lại. Đức thì nói *"anh chụp slide lên... anh buộc phải tin thôi."*

**Về hậu quả.** Đức chủ động bỏ qua phần mình chưa chắc, còn Đạt tốn công học lại và tốn thêm token khi hỏi AI ngoài.

### 2.3. Những điều vẫn chưa được chứng minh

1. **Hậu quả cuối cùng.** Không nguồn nào kể được một hậu quả quan sát được, chẳng hạn bài tập sai, phải học lại buổi hay điểm bị ảnh hưởng. Toàn bộ phần consequence hiện đang đứng trên lời tự thuật về hành vi chứ không đứng trên kết quả.
2. **Tần suất.** Chúng em chưa biết chuyện này xảy ra mấy lần mỗi buổi hay mỗi tuần, nên chưa định lượng được quy mô.
3. **Việc buộc phải tin có gây thiệt hại thật hay không.** Chưa ai kể được một lần AI trả lời sai mà sau đó họ phát hiện ra.
4. **Nhóm learner im lặng.** Cả hai người chúng em phỏng vấn đều là người có hành động khi kẹt, còn người chọn không làm gì cả thì vẫn nằm ngoài dữ liệu.
5. **Setup môi trường so với khái niệm bài học.** LC-01 nói setup bị hỏi nhiều nhất, nhưng cả hai learner đều kể về khái niệm. Chúng em chưa rõ đây là hai loại pain khác nhau hay chỉ là một loại nhìn từ hai phía.
6. **Việc coach cố ý ít can thiệp có phổ biến hay không.** Chúng em mới chỉ có một nguồn cho điểm này.

### 2.4. Ràng buộc chúng em mang sang phần solution

Một AI đọc nội dung bài rồi giải thích lại thì **đã tồn tại sẵn trong luồng và đã được learner sử dụng**. Đức vẫn phải đi ra ngoài vì thấy không thỏa đáng. Vì vậy chúng em cho rằng hướng giải quyết nào chỉ lặp lại năng lực đó thì khó tạo ra thay đổi. Phần chưa ai phục vụ là **khâu xác minh**, tức là cho learner biết câu trả lời họ nhận được đáng tin đến đâu, đồng thời mở một đường hỏi người thật đủ ít ma sát để họ dùng khi câu trả lời chưa đủ chắc.

Chúng em không tuyên bố bất kỳ giả thuyết nào đã được validated.
