# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Ngọ Doãn Ngọc
- Mã học viên: 2A202602635
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): giáo viên
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại| Giáo viên chấm bài tự luận và viết nhận xét cho từng học sinh | Giáo viên | Mỗi bài cần đọc, sửa và nhận xét |
| 2 | Tốn thời gian| Giáo viên tạo bài tập theo nhiều trình độ học sinh| Giáo viên | Phải soạn nhiều bài tập và tạo thành một phiên bản |
| 3 | Tốn thời gian / AI có thể tốt hơn | Giáo viên phải giảng lại cho từng học sinh nếu học sinh gặp vấn đề trong việc tiếp thu kiến thức mới (Nhiều học sinh cùng raise vấn đề khiến cho giáo viên không thể hỗ trợ cùng lúc) | Học sinh, Giáo viên | Cần công cụ hỗ trợ |
| 4 | AI có thể tốt hơn | Học sinh học tiếng Anh không biết mình sai phát âm ở đâu | Học sinh | Cần người sửa hoặc công cụ phản hồi |
| 5 | Tốn thời gian | Học sinh muốn tìm và sửa lỗi ngữ pháp trong bài viết | Học sinh| Phải tự tìm lỗi và tra cứu |
| 6 | Pain từ người khác | Phụ huynh khó biết con đang yếu phần nào trong môn học | Phụ huynh | Thông tin tiến độ học không liên tục |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [✅] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [✅] Dùng ít nhất 3/4 lăng kính
- [✅] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Chấm bài và viết feedback| Workflow rõ, có thể đo thời gian, AI có khả năng hỗ trợ ngôn ngữ | AI feedback có chính xác và hữu ích không? |
| 2 | Tạo bài tập theo trình độ học sinh | Lặp lại, dễ thử nghiệm, có thể tạo prototype | Giáo viên có cần nhiều phiên bản không? |
| 3 | Sửa lỗi phát âm tiếng Anh | Lặp lại, AI có khả năng hỗ trợ ngôn ngữ | AI sửa lại nhưng học sinh không thể đọc theo cho đúng|

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

Problem 1 câu:
Giáo viên mất nhiều thời gian đọc bài tự luận, chấm điểm và viết
feedback cá nhân cho từng học sinh, đặc biệt khi phải chấm nhiều bài
trong thời gian ngắn.

Actor:
Giáo viên tiếng Anh hoặc giáo viên tiểu học/trung học.

Thời điểm / bối cảnh:
Sau mỗi bài kiểm tra hoặc bài tập về nhà, trước khi trả bài cho học sinh.

Current workflow 3-7 bước:
1. Nhận bài làm của học sinh.
2. Đọc từng bài.
3. Tìm lỗi và đối chiếu rubric.
4. Chấm điểm.
5. Viết feedback cá nhân.
6. Review và trả bài.

Bottleneck:
Bước 2-5 — Đọc, phân tích lỗi, chấm điểm và viết feedback cho từng bài.

Impact:
Giả định giáo viên chấm 30 bài, mỗi bài mất 5 phút,
tổng cộng khoảng 150 phút cho một lần chấm. Giáo viên phải dành nhiều thời gian cho công việc lặp lại.

Success metric:
Giảm thời gian chấm và viết feedback từ 150 phút xuống dưới 75 phút cho 30 bài, đồng thời giữ chất lượng feedback ở mức giáo viên chấp nhận được.

Non-AI alternative:
Rubric chấm điểm, checklist lỗi và template feedback theo nhóm lỗi.

AI hypothesis:
AI phân tích bài làm dựa trên rubric, đề xuất điểm, chỉ ra lỗi và draft feedback cá nhân. Giáo viên review trước khi phê duyệt.

Quick gut:
Workflow.

[ ] No AI / process fix

[ ] Rule

[x] Workflow

[ ] Agent

[ ] Chưa biết

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

CURRENT STATE — 150 phút (giả định, 30 bài)

[1 Nhận bài: 5']
→ [2 Đọc từng bài: 60']
→ [3 Tìm lỗi + đối chiếu rubric: 30']
→ [4 Chấm điểm + viết feedback: 45']  <-- bottleneck

FUTURE STATE — 75 phút (mục tiêu giả định)

[1 Upload bài + rubric: 5']
→ [2 AI phân tích + draft feedback: 10']
→ [3 Giáo viên review + sửa: 55']  <-- human boundary
→ [4 Phê duyệt + trả bài: 5']

Fallback: Nếu AI chấm sai hoặc feedback không phù hợp,
giáo viên bỏ draft và tự chấm/viết lại.

---

#### Problem Card #2 — [Tên problem]

Problem 1 câu:
Giáo viên mất nhiều thời gian tạo bài tập theo các trình độ khác nhau của học sinh, đặc biệt khi cần nhiều phiên bản cho cùng một chủ đề.

Actor:
Giáo viên tiếng Anh hoặc giáo viên tiểu học/trung học.

Thời điểm / bối cảnh:
Trước mỗi buổi học hoặc khi giao bài tập về nhà, giáo viên cần chuẩn bị bài tập phù hợp với trình độ học sinh.

Current workflow 3-7 bước:
1. Xác định chủ đề và mục tiêu bài học.
2. Xác định trình độ học sinh.
3. Tìm hoặc tự soạn câu hỏi.
4. Điều chỉnh độ khó và nội dung.
5. Tạo đáp án.
6. Review và giao bài.

Bottleneck:
Bước 3-4 — Tự soạn và điều chỉnh nhiều câu hỏi cho các trình độ khác nhau.

Impact:
Giả định giáo viên cần chuẩn bị 3 phiên bản bài tập, mỗi phiên bản mất 30 phút, tổng cộng khoảng 90 phút
cho một lần soạn bài.

Success metric:
Giảm thời gian soạn 3 phiên bản từ 90 phút xuống dưới 30 phút, đồng thời giáo viên đánh giá bài tập phù hợp với trình độ và mục tiêu học tập.

Non-AI alternative:
Dùng ngân hàng câu hỏi có sẵn, template bài tập
và phân loại câu hỏi theo độ khó.

AI hypothesis:
AI tạo nhiều phiên bản bài tập dựa trên chủ đề,
trình độ, số lượng câu hỏi và mục tiêu học tập.
Giáo viên review, chỉnh sửa và phê duyệt trước khi giao.

Quick gut:
Workflow.

[ ] No AI / process fix

[ ] Rule

[x] Workflow

[ ] Agent

[ ] Chưa biết

**Draft workflow Card #2:**

CURRENT STATE — 90 phút (giả định, 3 phiên bản)

[1 Xác định chủ đề + mục tiêu: 10']
→ [2 Tìm/soạn câu hỏi: 35']
→ [3 Điều chỉnh 3 trình độ: 30']  <-- bottleneck
→ [4 Tạo đáp án + review: 15']

FUTURE STATE — 28 phút (mục tiêu giả định)

[1 Nhập chủ đề + trình độ + mục tiêu: 3']
→ [2 AI tạo 3 phiên bản + đáp án: 5']
→ [3 Giáo viên review + sửa: 18']  <-- human boundary
→ [4 Phê duyệt + giao bài: 2']

Fallback: Nếu bài tập không phù hợp trình độ,
giáo viên chỉnh prompt hoặc sửa trực tiếp,
không sử dụng bài tập chưa được review.

---

#### Problem Card #3 — [Tên problem]

Problem 1 câu:
Học sinh gặp khó khăn khi tự phát hiện và sửa lỗi phát âm tiếng Anh vì không có phản hồi cụ thể về âm tiết, âm sai và cách đọc đúng.

Actor:
Học sinh tiểu học hoặc người học tiếng Anh ở trình độ cơ bản.

Thời điểm / bối cảnh:
Khi học từ vựng, luyện đọc câu hoặc tự luyện nói tiếng Anh
ở nhà mà không có giáo viên hướng dẫn trực tiếp.

Current workflow 3-7 bước:
1. Học từ vựng hoặc câu tiếng Anh.
2. Nghe mẫu phát âm.
3. Tự đọc và ghi âm.
4. So sánh với phát âm mẫu.
5. Tìm lỗi hoặc hỏi giáo viên.
6. Đọc lại để sửa lỗi.

Bottleneck:
Bước 4-5 — Học sinh khó xác định chính xác mình phát âm sai âm nào và phải sửa như thế nào.

Impact:
Giả định học sinh luyện 10 từ mỗi buổi,
mỗi từ mất khoảng 2 phút để nghe, đọc và tự sửa,
tổng cộng khoảng 20 phút.
Tuy nhiên, học sinh vẫn có thể lặp lại lỗi nếu không nhận được feedback chính xác.

Success metric:
AI xác định đúng lỗi phát âm trong phần lớn các trường hợp đã kiểm thử; học sinh có thể đọc lại đúng hơn sau feedback. Giảm thời gian tìm hiểu cách sửa lỗi từ 20 phút xuống dưới 10 phút cho 10 từ (mục tiêu giả định).

Non-AI alternative:
Giáo viên sửa trực tiếp, nghe audio mẫu, dùng từ điển có phát âm và luyện theo cặp.

AI hypothesis:
AI nhận audio của học sinh, phát hiện các lỗi phát âm,
chỉ ra âm cần sửa và cung cấp mẫu đọc để học sinh luyện lại. Học sinh có thể ghi âm lần nữa để nhận feedback.

Quick gut:
Workflow.

[ ] No AI / process fix

[ ] Rule

[x] Workflow

[ ] Agent

[ ] Chưa biết

**Draft workflow Card #3:**

CURRENT STATE — 20 phút (giả định, 10 từ)

[1 Học từ/câu: 3']
→ [2 Nghe mẫu: 3']
→ [3 Tự đọc + ghi âm: 5']
→ [4 So sánh + tìm lỗi: 9']  <-- bottleneck

FUTURE STATE — 9 phút (mục tiêu giả định)

[1 Chọn từ/câu + nghe mẫu: 2']
→ [2 AI phân tích audio + chỉ ra lỗi: 2']
→ [3 Học sinh đọc lại + nhận feedback: 5']  <-- human boundary

Fallback: Nếu AI nhận diện sai hoặc học sinh không tiến bộ, học sinh nghe mẫu chuẩn và nhờ giáo viên sửa trực tiếp.

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

Problem 2 – Giáo viên mất nhiều thời gian soạn bài tập phù hợp với trình độ khác nhau của học sinh

Actor: Giáo viên tiếng Anh

Workflow hiện tại:
1. Xác định chủ đề và mục tiêu bài học.
2. Xác định trình độ của học sinh.
3. Tìm hoặc tự soạn câu hỏi.
4. Điều chỉnh độ khó và số lượng bài tập.
5. Soạn đáp án/hướng dẫn giải.
6. Kiểm tra lại nội dung trước khi giao cho học sinh.

Bottleneck:
Giáo viên phải tự tạo nhiều phiên bản bài tập với độ khó khác nhau, đồng thời kiểm tra xem bài tập có phù hợp với trình độ học sinh hay không.

Impact ước tính:
Nếu cần chuẩn bị 3 phiên bản bài tập cho 3 trình độ khác nhau, giáo viên có thể mất khoảng 90 phút cho một lần soạn bài.

Success metric:
Giảm thời gian soạn bài từ khoảng 90 phút xuống dưới 30 phút, trong khi bài tập vẫn đúng chủ đề, đúng mục tiêu và phù hợp với từng trình độ.

AI hypothesis:
AI tạo nhiều phiên bản bài tập theo chủ đề, trình độ, số lượng câu hỏi và mục tiêu học tập. AI đồng thời tạo đáp án và giải thích.
Giáo viên kiểm tra, chỉnh sửa và phê duyệt trước khi sử dụng.

Loại giải pháp:
AI Workflow có human-in-the-loop.

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

Tôi muốn pitch Card 2 vì đây là workflow lặp lại thường xuyên của giáo viên, có bottleneck rõ ràng ở việc tạo và điều chỉnh bài tập cho nhiều trình độ học sinh.
Với giả định giáo viên cần soạn 3 phiên bản bài tập, thời gian có thể lên tới 90 phút cho một lần chuẩn bị. Nếu AI giúp giảm thời gian xuống dưới 30 phút, giáo viên có thể tiết kiệm khoảng 60 phút, tương đương gần 67% thời gian,
đồng thời có thêm thời gian tập trung vào việc giảng dạy và hỗ trợ học sinh.

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

1. Làm thế nào để xác định chính xác độ khó của bài tập và bảo đảm bài tập thực sự phù hợp với trình độ của từng nhóm học sinh?

2. Nếu AI tạo bài tập nhanh nhưng câu hỏi bị sai, trùng lặp hoặc không đúng mục tiêu bài học, giáo viên sẽ phải mất bao nhiêu thời gian để kiểm tra và sửa?

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [✅] Có 5+ problems + top 3 Cards đủ field
- [✅] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [✅] Đã chọn 1 card pitch + câu hỏi challenge
