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

## 3. Conversation Guide — bản 1.1 sau khi tổng hợp practice

Các câu hỏi được mở rộng theo trải nghiệm học tập nói chung để không tiết lộ case hoặc giả thuyết. Hỏi từng câu theo thứ tự, không gợi ví dụ trước.

1. “Kể mình nghe về lần gần đây bạn tự học hoặc làm một bài tập. Bạn định hoàn thành điều gì?”
2. “Bạn kể lại từng bước từ lúc bắt đầu đến khi dừng nhé. Bạn làm gì trước, rồi làm gì tiếp?”
3. “Trong quá trình đó, đoạn nào chiếm nhiều thời gian hoặc sự chú ý nhất, nếu có?”
4. “Bạn vừa nhắc đến [lặp lại đúng từ/cách làm của người tham gia]. Bạn kể rõ hơn đoạn đó được không?”
5. “Cuối cùng chuyện diễn ra thế nào so với điều bạn định làm?”

**Follow-up trung tính khi cần:** “Rồi chuyện gì xảy ra tiếp theo?” / “Bạn kể cụ thể hơn được không?” / “Mất khoảng bao lâu?” Chỉ hỏi thời gian nếu chưa được kể; không gợi sẵn cách xử lý.

**Thay đổi sau practice và tổng hợp nhóm:** Guide mở đầu bằng một hoạt động học/bài tập cụ thể, không nêu trước “không hiểu” hay nguyên nhân. Câu so sánh mơ hồ được thay bằng câu hỏi về kết quả so với dự định. Bổ sung follow-up nhắc lại chính lời người tham gia để đào sâu hành động; chỉ hỏi cách kiểm tra nguồn nếu người tham gia tự nhắc việc đối chiếu.

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
- Rà soát độ trung tính của các câu hỏi trong Conversation Guide, loại bỏ các câu hỏi có tính định hướng hoặc hỏi tương lai.
- Hỗ trợ định dạng và sắp xếp dữ liệu transcript phỏng vấn cá nhân thành Interview Record chuẩn.
- *Cam kết:* AI không tạo dữ liệu phỏng vấn giả lập, không bịa đặt quote hay nội dung reflection của người phỏng vấn.

---

## 6. Tình trạng trước khi nộp

- [x] Tên nhóm: Tomorrow.
- [x] Danh sách nhóm: Đinh Trường An, Trần Phạm Thái Vũ, Hoàng Anh Tài.
- [x] Hoàn thành Checkpoint 1: Đủ chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence.
- [x] Có 2 pain hypothesis cạnh tranh và điều kiện bác bỏ giả thuyết.
- [x] Có Solution Parking Lot với 5 hướng (gồm các hướng không dùng AI).
- [x] Có Conversation Guide chuẩn The Mom Test sau buổi practice.
- [x] Có Interview Record transcript và file ghi âm thực tế trong thư mục `Interview/`.
- [x] Bản Practice Reflection chân thực từ buổi phỏng vấn.
- [x] Khai báo minh bạch AI Support Log.
- [x] Đã đồng bộ và đẩy lên GitHub cá nhân.
