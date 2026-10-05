# Track 1 — Day 17: Finding and Validating Pain Points

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202602612
- **Họ tên:** Hoàng Anh Tài
- **Tên nhóm:** Tomorrow
- **Thành viên:** Đinh Trường An · Trần Phạm Thái Vũ · Hoàng Anh Tài
- **Case đã chọn:** Case A — AI Tutor: Diagnostic Refresher
- **Lý do chọn case:** Cả 3 thành viên đều có thể tiếp cận ngay các học viên đang tự học công nghệ/AI trong 7 ngày gần nhất từng gặp tình huống bài giảng khó hiểu và phải tự xoay xở giải quyết.

---

## 2. Chặng 1 — Đặt giả thuyết & Evidence Map (Checkpoint 1)

### 2.1. Solution — Gỡ solution khỏi hình thức cụ thể

- **Solution directive nguyên văn:**
  > *"Thêm nút “Tôi vẫn chưa hiểu” vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để đặt 2–3 câu hỏi chẩn đoán ngắn, chọn một khái niệm nền để học viên ôn lại, tạo phần giải thích ngắn rồi đưa học viên trở về bài đang học. Học viên chủ động yêu cầu trợ giúp."*
- **Capability trung tính (bỏ tên nút, màn hình và AI):**
  > Khả năng giúp người học nhanh chóng nhận diện chính xác lỗ hổng kiến thức nền tảng (prerequisite gaps) đang cản trở việc hiểu bài hiện tại, và ôn lại nhanh trọng tâm ngay tại chỗ để duy trì mạch học liên tục.

### 2.2. Change — Chuỗi thay đổi được kỳ vọng

- **Chuỗi thay đổi:**
  `Gặp đoạn khó hiểu & yêu cầu trợ giúp tại chỗ` → `Nhận biết chính xác khái niệm nền bị hổng` → `Ôn lại nhanh tại chỗ mà không phải thoát bài` → `Hiểu bài hiện tại và tiếp tục tiến trình học liền mạch (Outcome)`
- **Các thay đổi cụ thể được kỳ vọng:**
  1. Học viên không mất thời gian đoán mò xem mình đang thiếu kiến thức gì.
  2. Học viên thay đổi hành vi: thay vì chuyển tab/mở công cụ ngoài tra cứu lan man, học viên xử lý dứt điểm điểm nghẽn ngay trong luồng học.
  3. Giảm tỷ lệ đứt mạch, bế tắc và bỏ dở buổi học giữa chừng.
- **Output vs Outcome:**
  - *Output sản phẩm tạo ra:* Câu hỏi chẩn đoán ngắn và tóm tắt giải thích khái niệm nền liên quan.
  - *Outcome sản phẩm chỉ có thể ảnh hưởng:* Thời gian thông suốt bài học, mức độ duy trì trạng thái tập trung (flow state) và tỷ lệ hoàn thành bài học.

### 2.3. Actor — Xác định các nhóm người có liên quan

| Actor | Họ đang làm gì? | Pain hoặc hậu quả có thể có | Họ hưởng lợi thế nào? |
|---|---|---|---|
| **Học viên tự học (Learner)** | Đang tự đọc bài, xem video bài giảng hoặc làm bài tập | Gặp khái niệm lạ/khó hiểu; mất nhiều thời gian tra cứu ngoài luồng; dễ mất tập trung, nản lòng và bỏ dở | Nhanh chóng gỡ rối, tiết kiệm thời gian, hiểu sâu kiến thức và giữ vững mạch học |
| **Giảng viên / Course Author** | Soạn giáo trình, thiết kế bài giảng và bài tập | Không thể lường hết nền tảng kiến thức ban đầu của mọi học viên; tốn công giải đáp các câu hỏi nền tảng lặp lại | Nắm được các điểm nghẽn phổ biến để cải tiến giáo trình; giảm tải hỗ trợ cơ bản |
| **Trợ giảng / Mentor** | Hỗ trợ học viên trong quá trình học và làm bài tập | Quá tải khi nhiều học viên hỏi những câu hỏi kiến thức nền rải rác | Tập trung thời gian vào các vấn đề chuyên sâu, phức tạp |

- **Actor nhóm chọn điều tra trước:** **Học viên tự học (Learner)**.
- **Vì sao chọn nhánh này:** Học viên là người trực tiếp trải nghiệm sự đứt mạch, trực tiếp chịu hậu quả nản lòng hoặc bỏ học, và là người trực tiếp tương tác với giải pháp.

### 2.4. Situation & Job — User đang cố làm gì trong tình huống nào?

- **Mô tả Situation & Job:**
  > Khi đang tự học một bài mới (đọc tài liệu hoặc xem video bài giảng), học viên đang cố hiểu nội dung bài học để hoàn thành bài tập bằng cách tự ghi chú lại các chỗ khó hiểu và chuyển sang Google / ChatGPT tra cứu ngoài luồng.
- **JTBD Hypothesis:**
  > *"Khi gặp một phần kiến thức chưa hiểu trong lúc tự học, tôi muốn nhanh chóng tìm ra mình đang vướng ở lỗ hổng nào và lấp ngay chỗ đó, để có thể tiếp tục hoàn thành bài học mà không bị đứt mạch."*

### 2.5. Pain — Hai cách giải thích cạnh tranh

- **Pain Hypothesis A (Vấn đề định vị lỗ hổng kiến thức):**
  > Khi đang tự học một bài mới, học viên gặp khó khăn trong việc hiểu bài tiếp theo vì **không tự nhận biết được mình đang thiếu khái niệm nền tảng nào**, dẫn đến **hoang mang, tra cứu chung chung và mất nhiều thời gian nhưng vẫn không hiểu bản chất**.
- **Pain Hypothesis B (Vấn đề chi phí chuyển ngữ cảnh / tìm trợ giúp):**
  > Khi đang tự học một bài mới, học viên biết mình vướng chỗ nào nhưng gặp khó khăn vì **quy trình tra cứu/hỏi đáp hiện tại đòi hỏi phải rời khỏi bài học (mở tab khác, chụp màn hình, copy paste prompt sang AI ngoài)**, dẫn đến **mất tập trung, đứt mạch tư duy và tốn nhiều công sức tổng hợp lại**.
- **Giả thuyết nhóm chọn để điều tra trước:** **Nhánh A**.
- **Lý do chọn:** Nếu học viên căn bản không biết mình đang bị hổng ở đâu (unknown unknowns) thì dù có công cụ hỗ trợ nhanh, họ vẫn không biết phải hỏi gì hoặc hỏi sai trọng tâm.

### 2.6. Evidence Map — Xác định điều cần tìm trước khi viết câu hỏi

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ hoặc bác bỏ |
|---|---|---|
| **Situation có thật** | Kể lại được sự kiện cụ thể trong 7 ngày qua: học môn gì, bài nào, gặp khái niệm gì lạ, trình tự các bước xử lý. | Không nhớ được lần nào gần đây, hoặc chỉ trả lời chung chung mang tính lý thuyết ("mình hay xem youtube..."). |
| **Pain có ý nghĩa** | Barrier khiến học viên bực bội, tốn hơn 30–45 phút loay hoay, làm sai bài tập hoặc dừng hẳn buổi học. | Chỗ không hiểu là chi tiết phụ, bỏ qua vẫn làm được bài tập bình thường, không gây ảnh hưởng. |
| **Workaround tồn tại** | Đã bỏ công sức thực tế: chụp màn hình lưu Notion, mở nhiều tab Google, tra cứu video bài cũ, hỏi ChatGPT. | Không cần làm gì hoặc chỉ cần đọc lại 1 lần là hiểu ngay; không tốn công sức tìm giải pháp. |
| **Consequence tồn tại** | Đứt mạch học, mất tập trung vì chuyển nhiều tab, ChatGPT trả lời ngoài ngữ cảnh bài khiến hiểu sai. | Cách tự tra cứu hiện tại (Google/ChatGPT) diễn ra cực kỳ nhanh và mượt mà (< 2 phút), hài lòng 100%. |
| **Pattern có lặp** | Tình trạng bị nghẽn do hổng kiến thức nền lặp lại ở nhiều bài học mới khác nhau. | Chỉ là tình huống cá biệt, hiếm khi xảy ra. |

- **Problem Hypothesis nhóm mang sang Chặng 2:**
  > *Khi học viên gặp một phần bài chưa hiểu trong lúc tự học, họ bị chậm hoặc đứt mạch học vì chưa xác định được khái niệm nền nào đang vướng (Pain A) và quy trình rời bài để tìm trợ giúp bên ngoài tốn nhiều công sức chuyển ngữ cảnh (Pain B).*
- **Điều gì phải đúng để giả thuyết đứng vững:** Học viên gặp trở ngại thật sự trong việc định nghĩa mình đang không hiểu điều gì, và việc chuyển đổi công cụ tra cứu gây gián đoạn rõ rệt đến việc học.
- **Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:** Học viên chỉ cần 1-2 phút tra cứu nhanh là hiểu ngay mà không đứt mạch, hoặc học viên chủ động thích tự mày mò đào sâu đa nguồn thay vì cần hỗ trợ tại chỗ.

### 2.7. Solution Parking Lot

Brainstorm ít nhất 5 hướng giải quyết sơ bộ (trong đó có các hướng không sử dụng AI):

| Hướng giải quyết có thể có | AI / Không sử dụng AI |
|---|---|
| **1. Diagnostic Quiz:** AI phân tích và đưa ra 2–3 câu hỏi trắc nghiệm ngắn chẩn đoán đúng lỗ hổng | Sử dụng AI |
| **2. Bản đồ kiến thức tiên quyết (Prerequisite Tree):** Mục lục hiển thị cây kiến thức nền tảng đi kèm link ôn lại từng mục | **Không sử dụng AI** |
| **3. Thuật ngữ chú giải tại chỗ (Glossary Tooltip/Pop-up):** Di chuột/click vào thuật ngữ chuyên ngành để xem tóm tắt và ví dụ | **Không sử dụng AI** |
| **4. AI In-context Explainer:** AI giải thích lại đoạn bài học hiện tại bằng ngôn ngữ đơn giản dựa trên ngữ cảnh khóa học | Sử dụng AI |
| **5. Nút gửi thắc mắc kèm vị trí bài học lên diễn đàn/cộng đồng trợ giúp:** Kết nối trợ giảng và bạn học cùng khóa | **Không sử dụng AI** |

---

## 3. Chặng 2 — Chuẩn bị phỏng vấn (Checkpoint 2: Interview-ready)

### 3.1. Chốt Big 3 — Ba điều quan trọng nhất cần học

Quay lại Evidence Map ở Chặng 1, nhóm chọn ra 3 điều quan trọng nhất cần kiểm chứng (trong đó Điều 3 là câu hỏi "đáng sợ" có thể làm lung lay giả thuyết):

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| **1. Hành vi và Workaround thật khi gặp bế tắc** | Khi gặp đoạn bài học/video không hiểu, học viên đã làm gì theo thứ tự? Có thực sự chụp màn hình, ghi chú Notion, tra cứu ngoài luồng không? Mất bao nhiêu thời gian? | Học viên chỉ lướt qua rồi bỏ mặc không tìm hiểu; hoặc các tài liệu/video hiện tại đã có chú thích sẵn cực kỳ dễ hiểu, không cần workaround. |
| **2. Bản chất của Barrier (Pain A hay Pain B)** | Điểm khó khăn lớn nhất là do **không biết mình hổng kiến thức tiên quyết nào** (Pain A) hay do **việc chuyển đổi qua lại giữa các công cụ tra cứu gây mất tập trung** (Pain B)? | Học viên biết rất rõ mình thiếu gì và việc mở tab ChatGPT hỏi mất chưa đầy 30 giây, không hề gây đứt mạch hay phiền toái. |
| **3. Mức độ nghiêm trọng của hậu quả (Câu hỏi "đáng sợ")** | Việc không hiểu bài đó có dẫn đến hậu quả thực tế không (bỏ học, làm sai bài tập, trễ tiến độ)? Hay đây chỉ là bất tiện nhỏ mà học viên sẵn sàng chấp nhận? | **Nếu câu trả lời là:** Chỗ không hiểu đó không ảnh hưởng gì đến việc hoàn thành bài tập/mục tiêu, học viên vẫn đạt kết quả tốt mà không cần giải quyết triệt để chỗ nghẽn → *Pain không đủ lớn để làm sản phẩm.* |

### 3.2. Thiết kế Conversation Guide (The Mom Test)

#### A. Tiêu chí tuyển người & Recruitment check
- **Tiêu chí tuyển người:** Chúng tôi cần nói chuyện với học viên đã **tự học trực tuyến (đọc tài liệu, xem video bài giảng hoặc làm bài tập công nghệ/lập trình) và từng gặp một phần bài chưa hiểu** trong vòng **7 ngày** gần đây.
- **Recruitment check (câu hỏi sàng lọc nhanh):**
  > *“Trong 7 ngày vừa qua, bạn có buổi tự học hoặc làm bài tập nào mà gặp một khái niệm/đoạn code chưa hiểu và phải dừng lại tìm cách xử lý không?”* (Nếu có mới tiến hành phỏng vấn).

#### B. Lời mở đầu (Briefing)
> *“Chào bạn, cảm ơn bạn đã dành thời gian. Nhóm mình đang tìm hiểu về trải nghiệm tự học và những thói quen thực tế của mọi người khi gặp nội dung chưa rõ trong quá trình học tập. Cuộc trò chuyện này hoàn toàn nhằm mục đích học hỏi từ câu chuyện thực tế của bạn, không có câu trả lời đúng hay sai, và mình không bán hay giới thiệu bất kỳ tính năng/sản phẩm nào. Bạn có thể bỏ qua bất kỳ câu hỏi nào hoặc dừng lại bất cứ lúc nào. Mình xin phép được ghi âm lại buổi nói chuyện để tiện ghi chép nội bộ và cam kết không chia sẻ công khai bản ghi này nhé.”*

#### C. Story Opener
> **“Kể mình nghe về lần gần nhất trong 7 ngày qua bạn tự học một bài mới hoặc làm bài tập. Hôm đó câu chuyện bắt đầu như thế nào và bạn định hoàn thành điều gì?”**

#### D. Big 3 Questions (Ánh xạ trực tiếp với Big 3)

| Điều cần học | Câu hỏi sẽ dùng (Quá khứ & Thực tế) |
|---|---|
| **1. Hành vi & Workaround** | *“Từ lúc bắt đầu gặp đoạn chưa hiểu đó cho đến lúc dừng lại, bạn đã làm những gì theo thứ tự? Đoạn nào chiếm nhiều thời gian hoặc sự chú ý nhất?”* |
| **2. Bản chất Barrier (Pain A vs B)** | *“Khi dừng lại ở đoạn đó, điều gì cản trở bạn tiếp tục nhất: là do không rõ phần kiến thức nào trước đó chưa nắm chắc, hay do việc tìm kiếm tài liệu giải thích bên ngoài bị phân mảnh?”* |
| **3. Hậu quả thực tế (Đáng sợ)** | *“Cuối cùng buổi học đó kết thúc thế nào so với dự định ban đầu của bạn? Việc vướng mắc đó có làm thay đổi kết quả làm bài tập hay tiến độ học hôm đó không?”* |

#### E. Probe Bank (Đào sâu Hành vi — Workaround — Hậu quả)
- *Đào sâu trình tự:* “Lúc đó chuyện gì xảy ra tiếp theo?” / “Sau khi chụp màn hình/mở tab mới, bạn làm gì tiếp?”
- *Đào sâu chi phí/thời gian:* “Đoạn tra cứu đó mất khoảng bao nhiêu phút?” / “Bạn có phải xem đi xem lại video nhiều lần không?”
- *Đào sâu workaround:* “Bạn đã thử cách nào khác ngoài ChatGPT/Notion chưa?” / “Vì sao bạn lại chọn cách đó mà không hỏi giảng viên/bạn học?”
- *Đào sâu hậu quả:* “Sau khi làm theo cách đó, bạn có quay lại làm tiếp bài được ngay không, hay phải dừng buổi học?”

#### F. Ba phản xạ khi dữ liệu bị lệch
1. **Khi nhận được lời khen / đồng tình:** (VD: *"Mình thấy có công cụ giải thích tại chỗ thì hay quá"*)  
   → **Phản xạ Deflect:** Cảm ơn ngắn gọn, không xác nhận tính năng, kéo về quá khứ: *“Cảm ơn bạn. Thế ở lần gần nhất tự học hôm qua/hôm kia, bạn đã xử lý chỗ khó hiểu đó như thế nào?”*
2. **Khi nhận câu trả lời chung chung / giả định tương lai:** (VD: *"Thường thì mình hay tìm trên mạng..."*)  
   → **Phản xạ Anchor:** Kéo về sự kiện cụ thể gần nhất: *“Lần gần nhất bạn tìm trên mạng là khi nào? Bạn có thể kể cụ thể lần đó bạn gõ từ khóa gì không?”*
3. **Khi nhận ý tưởng hoặc feature request:** (VD: *"Ứng dụng nên có phần tóm tắt video ở dưới..."*)  
   → **Phản xạ Dig:** Đào sâu vào pain hiện tại thay vì ghi nhận tính năng: *“Điều đó sẽ giúp bạn giải quyết được việc gì mà hiện tại các cách bạn đang làm chưa đáp ứng được?”*

### 3.3. Tự rà soát và Phân công nhóm

#### Checklist tự rà soát (7 câu hỏi kiểm tra):
- [x] Không có câu hỏi nào để lộ giải pháp nút bấm hay AI Tutor.
- [x] Không hỏi ý kiến phỏng đoán tương lai hay hỏi người dùng "có muốn một tính năng như vậy không".
- [x] Story opener đã neo chính xác vào "lần gần nhất trong 7 ngày qua".
- [x] Ba câu hỏi chính khớp 1-1 với 3 điều cần học (Big 3).
- [x] Đã có câu hỏi kiểm chứng mức độ nghiêm trọng của hậu quả (có thể làm yếu giả thuyết).
- [x] Người tham gia phỏng vấn đáp ứng đúng tiêu chí tự học có gặp khó khăn gần đây.
- [x] Phân chia vai trò rõ ràng, mỗi thành viên phỏng vấn một người ngoài nhóm.

#### Bảng phân công phỏng vấn nhóm Tomorrow:
| Thành viên | Người được phỏng vấn | Tiêu chí phù hợp | Thời gian thực hiện | Bản ghi / Ghi chú |
|---|---|---|---|---|
| **Hoàng Anh Tài** | Học viên VinUniversity (nghiên cứu AI) | Đang tự học video YouTube về AI, gặp khó khăn về thuật ngữ trong 7 ngày qua | 04/10/2026 (09:38) | Đã lưu `Interview/Note.docx` và `Interview/VinUniversity.m4a` |
| **Đinh Trường An** | Học viên khóa Data / Python | Tự học lập trình, gặp lỗi bài tập và thuật toán trong tuần qua | 04/10/2026 | Lưu trong hồ sơ nhóm |
| **Trần Phạm Thái Vũ** | Học viên tự học trực tuyến | Tự học tài liệu chuyên ngành, thường xuyên tra cứu ngoài | 04/10/2026 | Lưu trong hồ sơ nhóm |

### 3.4. Bảng tổng hợp thay đổi của Guide sau buổi luyện tập (Bản 1.1)

| Câu hỏi / Probe ban đầu | Vấn đề nhận ra khi thực hành | Câu hỏi / Probe đã sửa đổi (Bản 1.1) |
|---|---|---|
| *“Khi không hiểu bài bạn làm thế nào?”* | Quá chung chung, dễ gợi ý câu trả lời lý thuyết hoặc theo thói quen giả định. | Đổi thành Story Opener: *“Kể mình nghe về lần gần đây bạn tự học hoặc làm một bài tập. Bạn định hoàn thành điều gì?”* |
| *“So với các buổi học khác thì buổi này thế nào?”* | Mơ hồ, khiến người được phỏng vấn bối rối không biết so sánh khía cạnh nào. | Đổi thành: *“Cuối cùng chuyện diễn ra thế nào so với điều bạn định làm?”* |
| *“ChatGPT giải thích xong bạn thấy có clear hơn không?”* | Câu hỏi đóng, mang tính dẫn dắt và gợi ý đánh giá. | Thay bằng probe trung tính: *“Bạn vừa nhắc đến [cách làm]. Bạn kể rõ hơn đoạn đó được không? Mất khoảng bao lâu?”* |

---

## 4. Practice Reflection (Hoàng Anh Tài)

1. **Câu hỏi nào giúp người được phỏng vấn kể chuyện cụ thể?**
   - Câu hỏi *“Trong buổi đó, đoạn nào chiếm nhiều thời gian hoặc sự chú ý của bạn nhất?”* khiến người được phỏng vấn kể chi tiết về việc gặp thuật ngữ chưa quen, cách chụp màn hình note sang Notion, và cách gửi ảnh sang ChatGPT để hỏi đáp.
2. **Tôi cần làm tốt hơn điều gì?**
   - Cần tránh các câu hỏi đóng hoặc câu hỏi dẫn dắt (như hỏi xem ChatGPT trả lời có làm clear hơn không).
   - Cần đào sâu hơn vào một tình huống duy nhất cụ thể: lần đó diễn ra khi nào, mất bao nhiêu phút, chi phí thời gian bỏ ra thế nào và cuối cùng có hoàn thành được bài học đó không.
3. **Nhóm đã sửa guide thế nào sau buổi luyện?**
   - Nhóm chuyển câu mở đầu sang một buổi học hoặc bài tập gần đây nói chung.
   - Thay câu so sánh khó hiểu bằng câu hỏi về kết quả so với dự định.
   - Thêm probe trung tính dựa trên chính lời kể của interviewee để đào sâu hành động thực tế.

---

## 5. AI Support Log

AI đã hỗ trợ:
- Tái cấu trúc và rà soát logic của Chặng 1 theo chuỗi: Solution → Change → Actor → Situation & Job → Pain → Evidence.
- Thiết kế Chặng 2 theo chuẩn The Mom Test: chốt Big 3, viết script mở đầu trung tính, thiết kế probe bank và 3 phản xạ lệch data.
- Rà soát độ trung tính của các câu hỏi trong Conversation Guide, loại bỏ các câu hỏi có tính định hướng hoặc hỏi tương lai.
- Hỗ trợ định dạng và sắp xếp dữ liệu transcript phỏng vấn cá nhân thành Interview Record chuẩn.
- *Cam kết:* AI không tạo dữ liệu phỏng vấn giả lập, không bịa đặt quote hay nội dung reflection của người phỏng vấn.

---

## 6. Tình trạng trước khi nộp

- [x] Tên nhóm: Tomorrow.
- [x] Danh sách nhóm: Đinh Trường An, Trần Phạm Thái Vũ, Hoàng Anh Tài.
- [x] Hoàn thành Checkpoint 1: Đủ chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence.
- [x] Hoàn thành Checkpoint 2: Interview-ready (Big 3, Recruitment check, Mom Test Guide, Probe bank, 3 phản xạ, Phân công).
- [x] Có 2 pain hypothesis cạnh tranh và điều kiện bác bỏ giả thuyết.
- [x] Có Solution Parking Lot với 5 hướng (gồm các hướng không dùng AI).
- [x] Có Conversation Guide chuẩn The Mom Test sau buổi practice.
- [x] Có Interview Record transcript và file ghi âm thực tế trong thư mục `Interview/`.
- [x] Bản Practice Reflection chân thực từ buổi phỏng vấn.
- [x] Khai báo minh bạch AI Support Log.
- [x] Đã đồng bộ và đẩy lên GitHub cá nhân.
