# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Thái Anh | 2A202602810 | **Research Lead** (Khảo sát công cụ thị trường, thiết kế validation, thẩm định tính đúng đắn toán học) |
| 2   | Đoàn Quang Minh | 2A202602711 | **Problem Owner / Facilitator** (Cung cấp bài toán gốc từ đồ án tốt nghiệp, điều phối thảo luận nhóm) |
| 3   | Ngọ Doãn Ngọc | 2A202602825 | **Workflow Lead** (Mô hình hóa Current/Future workflow, xác định điểm nghẽn và Human boundary) |
| 4   | Hoàng Ngọc Đăng Khoa | 2A202602840 | **Writer / Documentation** (Chuẩn hóa Problem Statement v0/v1, biên tập nhật ký hội tụ và bảng rubric) |

**Candidate problem nhóm chọn (1 câu):**

Sinh viên năm cuối ngành CNTT (chuyên ngành AI) mất trung bình 2–3 tiếng trong tổng số 8–10 tiếng nghiên cứu mỗi bài báo kỹ thuật để giải mã các công thức toán và thuật toán phức tạp (ký hiệu ma trận, hàm mất mát tùy biến, đạo hàm tensor), trong đó việc thiếu ngữ cảnh trực quan và phải lật tìm định nghĩa ký hiệu tản mát xuyên suốt bài báo là điểm nghẽn lớn nhất làm chậm tiến độ nghiên cứu đồ án.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Thái Anh | Mất phương hướng khi mở code template lab sáng (không rõ input/output và data contract) | Học viên làm lab (bootcamp K4A) | Mất 20' trace code mẫu đoán format dữ liệu (list, dict, tensor) | Rất thực tế trong 6 tuần học, phạm vi gọn gàng |
| 2 | Thái Anh | Đọc hiểu slide lý thuyết 40+ trang bị văn phong AI dịch thuật gượng gạo và lệch ngữ cảnh | Sinh viên học lý thuyết | Mất 55' nhảy qua lại giữa slide và tài liệu gốc | Pain lớn về nhận thức, nhưng khó chuẩn hóa format slide đầu vào |
| 3 | Thái Anh | Thao tác ghép file báo cáo nhóm và đồng bộ bài nộp về repo cá nhân cuối giờ lab | 4 thành viên trong nhóm | Mất 20-30' sửa lỗi bảng Markdown và copy thủ công | Bài toán thuần Rule/Automation, không cần đến AI |
| 4 | Quang Minh | Đọc paper kỹ thuật dài: Tốn 2-3h giải mã công thức toán/thuật toán cho đồ án tốt nghiệp | Sinh viên làm đồ án AI | Mất 2-3h lật tìm định nghĩa ký hiệu và suy luận chiều không gian ma trận | Pain cực lớn, đo được bằng số giờ cụ thể, ai làm AI cũng gặp |
| 5 | Quang Minh | Tra nghĩa lời bài hát đa quốc gia khi nghe nhạc giải trí hàng ngày | Người nghe nhạc cá nhân | Tra cứu từ ngữ rời rạc mất 15'/bài | Nhu cầu giải trí cá nhân, impact thấp, không liên quan chuyên môn |
| 6 | Quang Minh | Sinh hoạt không điều độ do không cố định lịch làm việc đồ án ở nhà | Sinh viên tự học ở nhà | Thức khuya đến 3h sáng, ngày làm việc thất thường | Vấn đề kỷ luật bản thân, không phải quy trình xử lý thông tin |
| 7 | Doãn Ngọc | Giáo viên mất nhiều thời gian tạo bài tập theo các trình độ khác nhau
của học sinh, đặc biệt khi cần nhiều phiên bản cho cùng một chủ đề. | Giáo viên dạy tiếng Anh | Tự soạn và điều chỉnh nhiều câu hỏi cho các trình độ khác nhau. | Pain phổ biến nhưng đa số đã được giải quyết  |
| 8 | Doãn Ngọc | Học sinh gặp khó khăn khi tự phát hiện và sửa lỗi phát âm tiếng Anh
vì không có phản hồi cụ thể về âm tiết, âm sai và cách đọc đúng. | Học sinh học tiếng Anh | Học sinh khó xác định chính xác mình phát âm sai âm nào và phải sửa như thế nào. | Có thể giải quyết tốt bằng các công cụ AI chuyên dạy tiếng Anh |
| 9 | Doãn Ngọc | Giáo viên mất nhiều thời gian đọc bài tự luận, chấm điểm và viết feedback cá nhân cho từng học sinh, đặc biệt khi phải chấm nhiều bài trong thời gian ngắn. | Giáo viên dạy tiếng Anh | Bước 2-5 — Đọc, phân tích lỗi, chấm điểm và viết feedback cho từng bài. | đã có dự án khác giải quyết vấn đề này |
| 10 | Đăng Khoa | Soạn slide báo cáo tiến độ đồ án hằng tuần cho GVHD từ ghi chú rời rạc | Sinh viên làm đồ án | Mất 90-120' cấu trúc lại nội dung thành slide thuyết trình | Thường xuyên lặp lại, nhưng template slide có thể giải quyết 70% |
| 11 | Đăng Khoa | Chuyển đổi công thức toán từ file PDF của paper sang mã nguồn LaTeX để đưa vào báo cáo | Sinh viên viết báo cáo/đồ án | Gõ lại công thức phức tạp mất 20-30'/trang | Đã có công cụ Mathpix giải quyết rất triệt để ở tầng OCR |
| 12 | Đăng Khoa | Quản lý và trích dẫn tài liệu tham khảo BibTeX bị sai format hoặc thiếu trường | Sinh viên làm đồ án | Mất 20' sửa dấu câu và format trích dẫn thủ công | Zotero/Mendeley đã giải quyết tốt bằng rule quản lý trích dẫn |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A: Đọc hiểu & Giải mã tài liệu học thuật AI** | #2, #4, #11 | Xử lý tài liệu học thuật chuyên sâu (slide, paper, công thức toán), gặp rào cản về thuật ngữ, ký hiệu toán học ma trận và ngữ cảnh lý thuyết rời rạc. | Đây là cụm có giá trị trí tuệ cao nhất, gắn liền trực tiếp với năng lực của kỹ sư/sinh viên chuyên ngành AI. |
| **B: Lập trình, Môi trường & Thực nghiệm AI** | #1, #3, #7, #8, #9 | Thao tác kỹ thuật xoay quanh code: Môi trường, data contract bài lab, log benchmark, git repository. | Phần lớn đã có tool chuyên dụng (Docker, Wandb) hoặc có thể xử lý bằng Rule/Script tự động hóa. |
| **C: Soạn thảo Báo cáo & Thuyết trình cho GVHD** | #10, #12 | Công việc hành chính học thuật: Viết slide báo cáo tuần, định dạng trích dẫn BibTeX. | Lặp lại thường xuyên nhưng giá trị cải tiến không mang tính đột phá về mặt tư duy AI. |
| **D: Kỷ luật & Thói quen Cá nhân** | #5, #6 | Quản lý thời gian, giải trí, nhịp sinh hoạt cá nhân. | Không có workflow nghiệp vụ rõ ràng, ranh giới giải pháp phụ thuộc ý chí cá nhân, loại bỏ. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Candidate #4: Giải mã công thức toán trong paper kỹ thuật dài** | - Actor rõ nét (sinh viên làm đồ án/nghiên cứu AI).<br>- Điểm nghẽn định lượng cực lớn (2–3 tiếng/paper cho phần toán).<br>- Có ranh giới rõ ràng giữa việc hiểu toán và kiểm chứng code. | AI có nguy cơ hallucinate giải thích sai bản chất thuật toán hoặc gán nhầm ý nghĩa các biến ký hiệu. |
| **Candidate #1: Làm rõ Data contract & Input/Output khi mở bài lab** | - Diễn ra hàng ngày trong 6 tuần học bootcamp.<br>- Bottleneck định lượng rõ (40-50' đầu giờ).<br>- Dễ thử nghiệm và kiểm chứng ngay trong lớp. | Phạm vi hẹp trong nội bộ lớp học; nếu đề bài lab viết chuẩn docstring thì vấn đề tự biến mất. |
| **Candidate #10: Tự động hóa soạn slide báo cáo tiến độ cho GVHD** | - Lặp lại đều đặn mỗi tuần cho toàn bộ sinh viên tốt nghiệp.<br>- Đầu vào là log thí nghiệm và note tuần tương đối rõ. | Một template slide mẫu (Non-AI) kết hợp checklist chuẩn có thể giải quyết được 70% vấn đề mà không cần LLM. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Candidate #4 (Paper Math)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| **Candidate #1 (Lab Dataflow)** | 5 | 4 | 4 | 4 | 5 | 4 | 5 | **31** |
| **Candidate #10 (Weekly Slide)** | 4 | 4 | 4 | 3 | 4 | 3 | 4 | **26** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Candidate #4: Giải mã công thức toán học và thuật toán phức tạp trong paper kỹ thuật dài phục vụ nghiên cứu & đồ án tốt nghiệp AI.
```

**Vì sao chọn (4-5 câu):**

```text
Cả 4 thành viên trong nhóm đều là sinh viên CNTT chuyên ngành AI và đang trong giai đoạn làm đồ án tốt nghiệp, nơi việc đọc hiểu paper hội nghị (NeurIPS, CVPR, ICLR) là nhiệm vụ bắt buộc mỗi tuần. Đây là bài toán có thời gian lãng phí lớn nhất (chiếm 2–3 tiếng trong tổng 10 tiếng đọc mỗi bài báo), gây tắc nghẽn toàn bộ tiến trình triển khai code mô hình phía sau. Bài toán có ranh giới cấu trúc văn bản học thuật rất rõ ràng (Section Methodology, Equation blocks, Symbol definitions), cho phép phân định rành mạch giữa bước máy trích xuất ký hiệu và bước người kiểm chứng tính đúng đắn toán học. Quan trọng nhất, việc giải quyết bài toán này mang lại giá trị học thuật và kỹ năng thực chiến lâu dài cho cả nhóm khi làm việc tại các phòng lab nghiên cứu hoặc doanh nghiệp công nghệ cao như Vin.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Không chọn Candidate #1 (Lab Dataflow): Mặc dù bài toán này rất gần gũi với 6 tuần bootcamp hiện tại, nhưng phạm vi bài toán bị phụ thuộc lớn vào chất lượng đề bài của ban đào tạo; nếu giảng viên cập nhật type hints đầy đủ thì pain point sẽ biến mất, tính bền vững không cao bằng việc đọc paper học thuật quốc tế.
- Không chọn Candidate #10 (Weekly Slide): Việc soạn slide báo cáo đồ án phần lớn có thể giải quyết bằng giải pháp phi AI (sử dụng 1 slide master template cố định và đặt lịch tổng hợp vào chiều thứ Sáu); việc đưa AI vào soạn slide dễ tạo ra nội dung sáo rỗng, GVHD vẫn yêu cầu số liệu benchmark thực tế.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Thái Anh (Research Lead) ban đầu bày tỏ lo ngại sâu sắc: 'Toán học trong các paper AI đỉnh cao thường dùng các biến ký hiệu rất dị biệt hoặc ước lệ riêng của tác giả. Nếu LLM hallucinate giải thích sai một chỉ số tensor hay một phép nhân chập ma trận thì người học sẽ hiểu sai toàn bộ thuật toán, hậu quả còn tai hại hơn việc tự đọc chậm'. Nhóm đã thảo luận kỹ và chốt giải pháp: Thiết lập Human Boundary nghiêm ngặt, trong đó AI không được phép tự do suy diễn mà bắt buộc phải trích xuất bảng ánh xạ ký hiệu (Symbol Table) có số trang và trích đoạn gốc, đồng thời mô hình hóa kích thước chiều vector/tensor (Dimension check) để con người tự đối chiếu tính tương thích toán học.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| **Interview** | 3 sinh viên năm cuối CNTT AI (PTIT, VinUni, HUST) | - *"Đọc abstract và intro thì 15' là hiểu, nhưng cứ đụng vào phần Math với các công thức gộp 3-4 hàm Loss là kẹt cả buổi chiều."*<br>- *"Khổ nhất là tác giả dùng 1 ký hiệu ở trang 3 nhưng mãi trang 7 mới nhắc lại, phải lật ngược lật xuôi tìm xem biến đó là scalar hay matrix."* | *"Một số paper lý thuyết thuần (Statistical Learning) toán quá sâu, AI hiện nay giải thích chỉ toàn dịch chữ chứ không nắm được bản chất tiên đề."* | Thu hẹp phạm vi: Tập trung vào paper ứng dụng thực nghiệm (Deep Learning / Computer Vision / NLP), không nhận paper toán thuần túy lý thuyết. |
| **Survey / poll** | 12 sinh viên đang làm đồ án AI | 10/12 (83.3%) bạn khẳng định khâu đọc hiểu công thức và thuật toán trong Methodology là bước tốn nhiều thời gian nhất, trung bình mất **2.3 giờ/paper** chỉ cho các khối phương trình. | 2/12 bạn cho rằng khâu chạy code thực nghiệm (setup GPU, tái lập benchmark) mới là khâu lâu nhất. | Nhóm xác định rõ: Khâu chạy code lâu là do hiểu sai logic toán từ trước; giải quyết khâu hiểu toán là điều kiện tiên quyết giúp rút ngắn thời gian debug code sau này. |
| **Log ghi chép cá nhân** | 1 tuần đọc 2 paper của bạn Minh | Paper 1 (Diffusion model): mất 2h45' cho phần công thức chuyển đổi nhiễu; Paper 2 (Transformer variant): mất 2h10' cho phần Attention scaling. | Không có tín hiệu phản bác, số liệu bấm giờ thực tế hoàn toàn trùng khớp với giả định. | Giữ nguyên con số baseline là 2–3 tiếng cho khâu giải mã công thức toán. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật sự không nằm ở việc dịch tiếng Anh sang tiếng Việt, mà nằm ở việc mất dấu định nghĩa ký hiệu (Symbol Disconnection) xuyên suốt bài báo và thiếu trực quan hóa về chiều không gian biến đổi của các tensor trong các phương trình toán học phức tạp.
```

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **SciSpace (Typeset.io)** | [scispace.com](https://scispace.com) | Cho phép bôi đen khối công thức toán trên file PDF và hỏi Copilot *"Explain this math formula"*. | Trích xuất OCR công thức nhanh, giao diện đọc PDF trực quan, có giải thích sơ bộ từng ký hiệu. | Giải thích mang tính ngữ cảnh cục bộ; thường xuyên bịa nghĩa nếu ký hiệu toán học đó phụ thuộc vào định nghĩa ở Section trước; không phân tích được chiều tensor. | Bắt buộc phải có bước phân tích toàn văn bài báo để lập bảng tra cứu ký hiệu toàn cục (Global Symbol Table) trước khi giải thích công thức cục bộ. |
| **Mathpix Snip** | [mathpix.com](https://mathpix.com) | Chụp ảnh màn hình / bôi chọn công thức toán trong PDF và chuyển đổi sang mã LaTeX / MathML chuẩn. | Độ chính xác OCR toán học đạt >98%, nhận diện hoàn hảo các chỉ số trên/dưới, ma trận lồng nhau. | Thuần túy là công cụ Rule/OCR trích xuất cú pháp; hoàn toàn không có khả năng phân tích ngữ nghĩa hay giải thích thuật toán. | Sử dụng tầng OCR/Rule của Mathpix hoặc parser LaTeX tương đương để làm sạch đầu vào cho AI, tránh việc AI đọc nhầm ký hiệu toán học. |
| **Papers with Code** | [paperswithcode.com](https://paperswithcode.com) | Liên kết bài báo arXiv với repository GitHub chính thức và các bản tái lập mã nguồn cộng đồng. | Cung cấp mã nguồn thực tế để đối chiếu xem công thức toán được implement thành các dòng code PyTorch nào. | Người đọc vẫn phải tự mò mẫm hàng nghìn dòng code để tìm xem đoạn code nào tương ứng với phương trình nào trong paper; không có giải thích lý thuyết. | Cần tạo cầu nối trực quan: Công thức toán → Kích thước Tensor (Tensor Shapes) → Mã giả (Pseudocode) tương đương trong PyTorch. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm KHÔNG NÊN xây dựng một chatbot tổng quát tự động đọc toàn bộ bài báo vì chi phí context token cao và sinh ra nhiều câu trả lời lan man. Nhóm NÊN xây dựng một Workflow chuyên biệt hóa 2 giai đoạn: Giai đoạn 1 dùng Rule để lập Bảng ký hiệu toàn cục (Symbol Table) từ toàn văn bài báo; Giai đoạn 2 cho phép người dùng kích hoạt giải mã từng công thức cụ thể, kết hợp công thức LaTeX sạch với Symbol Table để sinh ra bản giải thích trực quan kèm chiều biến đổi Tensor và mã giả logic.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
CURRENT STATE — 165 phút (~2.75 giờ) cho khâu đọc hiểu lý thuyết & toán học của 1 paper

[1 Đọc Abstract & Intro: 20'] 
  → [2 Đọc lướt Methodology & đánh dấu phương trình: 15'] 
  → [3 Đọc chi tiết công thức toán: 40']  <-- bottleneck 1: bế tắc trước ký hiệu lạ
  → [4 Lật tìm định nghĩa ký hiệu ở các trang trước: 35']  <-- bottleneck 2: mất dấu biến số
  → [5 Nháp tay & vẽ chiều ma trận để hiểu luồng: 35'] 
  → [6 Tự tóm tắt ghi chú vào Notion: 20']
```

```mermaid
flowchart LR
    A["1. Đọc Abstract & Intro (20')"] --> B["2. Khoanh vùng công thức Method (15')"]
    B --> C["3. Đọc chi tiết công thức toán (40') - BOTTLENECK 1"]
    C --> D["4. Lật tìm định nghĩa ký hiệu ở các trang trước (35') - BOTTLENECK 2"]
    D --> E["5. Nháp tay tính thử & vẽ chiều tensor (35')"]
    E --> F["6. Tự gõ ghi chú tóm tắt vào Notion (20')"]

    style C fill:#ffebee,stroke:#c62828,stroke-width:2px
    style D fill:#ffebee,stroke:#c62828,stroke-width:2px
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Sinh viên nghiên cứu | File PDF bài báo khoa học (10–15 trang) | Hiểu được bài toán tổng thể và kết quả chính | 20' / 1 paper/tuần | Đọc nhanh, ít khi bị tắc nghẽn |
| 2 | Sinh viên nghiên cứu | Section Methodology của paper | Danh sách các phương trình toán cốt lõi | 15' / 1 paper/tuần | Xác định trọng tâm cần đọc |
| 3 | Sinh viên nghiên cứu | Các khối phương trình toán phức tạp | Sự mơ hồ về mặt ký hiệu và phép toán | 40' / 1 paper/tuần | **Bottleneck 1:** Bế tắc trước các ký hiệu ước lệ mới hoặc phép toán ma trận phức tạp |
| 4 | Sinh viên nghiên cứu | Toàn văn các section trước đó của bài báo | Tìm thấy đoạn văn định nghĩa ký hiệu | 35' / 1 paper/tuần | **Bottleneck 2:** Lật qua lật lại giữa các trang PDF để tìm định nghĩa biến số, rất dễ mất tập trung |
| 5 | Sinh viên nghiên cứu | Giấy nháp, bút, tài liệu phụ | Sơ đồ biến đổi chiều không gian tensor | 35' / 1 paper/tuần | Tính toán thủ công để hiểu xem ma trận nhân với vector ra shape gì |
| 6 | Sinh viên nghiên cứu | Sự hiểu biết sau khi nháp | Bản ghi chép trên Notion / Obsidian | 20' / 1 paper/tuần | Gõ lại tốn công, dễ chán nản |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nghiêm trọng nhất là bước 3 và bước 4 (ngốn 75 phút): Người đọc bị ngắt quãng dòng tư duy liên tục vì phải lật ngược lại các trang trước để truy tìm định nghĩa ký hiệu (Symbol Hunting). Việc thiếu một cơ chế hiển thị định nghĩa tức thời khiến sinh viên phải tốn thêm nhiều thời gian nháp tay kiểm tra lại từng chiều không gian của các ma trận trong công thức.
```

---

### 5.2. Future workflow bản nhóm

```text
FUTURE STATE — 35 phút (tiết kiệm 130 phút, giảm 78% thời gian)

[1 Nạp PDF: 2'] 
  → [2 Máy trích xuất Symbol Table toàn cục: 3' - Máy (Rule)] 
  → [3 Người chọn công thức cần đọc: 1' - Human Trigger] 
  → [4 AI giải mã: Phân rã biến + Trực quan hóa Tensor + Mã giả: 4' - AI Workflow] 
  → [5 Người kiểm chứng chiều tensor & đối chiếu trích đoạn gốc: 15' - Human Boundary] 
  → [6 Tự động kết xuất note Markdown: 10']
```

```mermaid
flowchart LR
    subgraph Ingestion["1. Nạp & Tiền xử lý (5')"]
        M1["1. Nạp file PDF bài báo (2')"] --> M2["2. Parser trích xuất Global Symbol Table (3' - Rule)"]
    end

    subgraph Trigger["2. Kích hoạt (1')"]
        H1["3. Sinh viên bôi chọn công thức cần giải mã (1')"]
    end

    subgraph AIProcessing["3. Phân tích AI theo cấu trúc (4')"]
        A1["4. LLM Workflow: Phân rã biến + Tensor shape + Mã giả (4')"]
    end

    subgraph Verification["4. Human Boundary & Kiểm chứng (15')"]
        H2["5. Sinh viên đối chiếu số chiều tensor & trích đoạn gốc (15')"]
    end

    subgraph Export["5. Lưu trữ (10')"]
        E1["6. Tự động kết xuất ghi chú Markdown có cấu trúc (10')"]
    end

    M2 --> H1
    H1 --> A1
    A1 --> H2
    H2 --> E1
    H2 -.->|"Nếu AI suy diễn mâu thuẫn"| FB["Fallback: Nhấp vào Symbol để nhảy thẳng đến trang gốc của tác giả"]

    style H2 fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
    style FB fill:#fff9c4,stroke:#fbc02d,stroke-width:1px
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| **Tổng thời gian giải mã toán** | 165 phút | 35 phút | Bấm giờ thực tế khi đọc phần Methodology của 1 paper mới |
| **Thời gian truy tìm định nghĩa biến** | 35 phút | < 1 phút | Thời gian từ lúc thấy ký hiệu lạ đến khi biết ý nghĩa và trang gốc |
| **Số thao tác lật trang thủ công** | 15–20 lần/paper | 0 lần | Đếm số lần phải cuộn chuột ngược về các trang trước để tìm biến |
| **Độ tự tin hiểu đúng thuật toán** | 60% (vẫn mơ hồ khi code) | > 90% (nắm rõ tensor shape) | Khảo sát tự đánh giá sau khi viết được mã giả tương ứng |
| **Risk mới phát sinh** | Không có (chỉ tốn công) | Nguy cơ tin tưởng mù quáng vào chiều tensor do AI gợi ý | Bắt buộc có Human Boundary: Sinh viên phải xác nhận phép nhân ma trận hợp lệ trước khi chốt note |

---

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối ngành CNTT (chuyên ngành AI), đang thực hiện đồ án tốt nghiệp hoặc nghiên cứu các mô hình Deep Learning mới. Họ có nền tảng toán cơ bản nhưng không quen với các hệ thống ký hiệu toán học đặc thù của từng nhóm tác giả quốc tế. |
| **Workflow** | Quy trình đọc tài liệu kỹ thuật hàng tuần: Đọc tổng quan bài báo → Đánh dấu các khối phương trình trong Methodology → Truy tìm định nghĩa ký hiệu ở các trang trước → Nháp tay chiều không gian vector/tensor → Viết lại ghi chú để áp dụng vào mô hình đồ án. |
| **Bottleneck** | Mất dấu định nghĩa ký hiệu toán học và thiếu công cụ trực quan hóa chiều không gian tensor ngay tại vị trí đọc phương trình. Việc phải liên tục lật trang tìm biến làm đứt gãy luồng tư duy logic và gây kiệt quệ nhận thức. |
| **Impact** | Tốn 2.5–3 tiếng mỗi tuần chỉ cho vài khối phương trình toán học; làm chậm tiến độ thử nghiệm mã nguồn của đồ án tốt nghiệp từ 2–3 ngày. Dễ dẫn đến việc hiểu sai công thức và triển khai thuật toán sai trong code PyTorch. |
| **Success Metric** | Giảm tổng thời gian đọc hiểu và giải mã công thức toán trong 1 paper từ 165 phút xuống dưới 40 phút. 100% các ký hiệu toán học trong công thức trọng tâm được định danh chính xác nguồn gốc và kích thước tensor. |
| **Boundary** | **Phạm vi làm:** Trích xuất bảng ký hiệu toán học toàn cục từ file PDF, giải mã phương trình được người dùng chỉ định, phân tích chiều tensor và xuất mã giả logic. **Không làm:** Không thay thế con người đọc toàn bộ bài báo; không tự động viết mã nguồn hoàn chỉnh thay sinh viên; không giải quyết các paper toán lý thuyết thuần túy không có ứng dụng mã nguồn. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: AI phản biện rằng field *Success Metric* "hiểu đúng thuật toán" là định tính, khó đo đếm khách quan.
- Tôi sửa gì: Chuẩn hóa lại metric định lượng rõ ràng: Đo bằng **thời gian giải mã thực tế (từ 165' xuống dưới 40')** và **tỷ lệ trích xuất đúng kích thước chiều Tensor (Tensor Dimensions)** được kiểm chứng qua mã giả.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) — Toán học và kích thước tensor có tính đúng/sai logic tuyệt đối, một phép nhân ma trận hoặc là hợp lệ hoặc là sai số chiều; ý nghĩa thuật toán có chân lý tham chiếu trong bài báo.
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Quy trình đòi hỏi đọc hiểu tài liệu PDF nhiều trang, liên kết chéo giữa các section, phân tích cú pháp LaTeX, ánh xạ với bảng ký hiệu và sinh mã giả.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: Phức tạp cao — Mơ hồ thấp (Deterministic High-Complexity).
```

**Vì sao (2-3 câu):**

```text
Bài toán xử lý công thức toán trong paper có tính logic và cấu trúc rất chặt chẽ (độ mơ hồ thấp), nhưng lại đòi hỏi quy trình xử lý dữ liệu nhiều tầng từ trích xuất tài liệu đến truy vấn ngữ cảnh (độ phức tạp cao). Dạng bài toán này không phù hợp cho chatbot tự do (dễ hallucinate) mà đòi hỏi một quy trình pipeline có kiểm soát chặt chẽ từng bước.
```

---

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng regex / OCR parser (Mathpix API) để bóc tách công thức LaTeX và lập bảng index ký hiệu dựa trên từ khóa *"where $x$ denotes..."*. | Đủ cho bước trích xuất cú pháp LaTeX sạch và quét tìm vị trí xuất hiện của ký hiệu trong bài báo. | Không giải thích được ý nghĩa trực quan, không suy luận được bản chất toán học nếu tác giả diễn đạt bằng câu văn phức tạp. | **Có chọn một phần** — Dùng cho Bước 2 (Lập Symbol Table cơ sở) và Bước 6 (Format Markdown). |
| **Workflow** | Pipeline tuần tự: Rule trích xuất PDF/LaTeX → RAG ghép cặp công thức với ngữ cảnh định nghĩa → LLM phân rã biến & sinh Tensor Shape → Con người kiểm chứng. | Hoàn toàn đủ để giải mã triệt để phương trình toán học với độ chính xác cao và kiểm soát được hallucination. | Cần prompt cấu trúc tốt để LLM luôn trả lời theo đúng schema (JSON/Markdown) quy định. | **CHỌN CHÍNH** — Áp dụng cho toàn bộ luồng xử lý cốt lõi từ trích xuất ngữ cảnh đến giải mã công thức. |
| **Agent** | Agent tự động đọc toàn bộ paper, tự quyết định gọi tool tìm kiếm repo GitHub, tự clone code về máy và chạy thử nghiệm để kiểm chứng toán. | Chỉ cần thiết khi muốn tự động hóa hoàn toàn từ nghiên cứu lý thuyết đến benchmark thực nghiệm mà không cần người can thiệp. | Rủi ro vòng lặp vô tận (infinite loop), chi phí API cực kỳ đắt đỏ, dễ mất kiểm soát lỗi môi trường khi chạy code lạ. | **KHÔNG CHỌN** — Quá phức tạp, rủi ro cao, không cần thiết cho mục tiêu giúp sinh viên hiểu toán. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?**  
   *Không, Rule chỉ giải được khâu trích xuất cú pháp LaTeX (~30% công việc), không thể giải thích được trực giác thuật toán và ý nghĩa của các hàm mục tiêu phức tạp.*
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**  
   *Các bước đi thẳng theo một pipeline tuyến tính rõ ràng: Nạp PDF → Lập Symbol Index → Nhận công thức được chọn → Truy vấn context liên quan → Sinh giải thích có cấu trúc → Con người nghiệm thu.*
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**  
   *Hoàn toàn không cần thiết; việc giải mã một phương trình toán học không đòi hỏi hệ thống phải tự đưa ra quyết định đa bước hay tự sửa sai hành động ngoài đời thực.*
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**  
   *Sinh viên (người đọc) sẽ phát hiện đầu tiên ở bước Human Boundary thông qua việc kiểm tra tính tương thích số chiều tensor; sửa lại mất khoảng 2–3 phút bằng cách bấm vào link dẫn về trang gốc của tác giả.*
5. **Có hạ được từ Agent → Workflow → Rule không?**  
   *Nhóm đã chủ động hạ từ Agent xuống **Workflow kết hợp Rule**, loại bỏ hoàn toàn các rủi ro không kiểm soát được của Autonomous Agent.*

**Mức chọn:**

```text
Workflow (kết hợp tầng tiền xử lý bằng Rule).
```

**Vì sao chọn (3-4 câu):**

```text
Quy trình giải mã công thức toán học có đầu vào và đầu ra xác định, các bước trung gian diễn ra theo một trình tự cố định nên mô hình Workflow là tối ưu nhất. Workflow cho phép tận dụng sức mạnh trích xuất chuẩn xác của Rule (OCR, Regex index) kết hợp với năng lực suy luận ngữ nghĩa của LLM trong một khung prompt có cấu trúc chặt chẽ. Cách tiếp cận này loại bỏ hoàn toàn nguy cơ chạy lạc đề hay tốn kém tài nguyên của Agent, đồng thời đảm bảo con người luôn giữ vai trò chốt chặn kiểm duyệt cuối cùng.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Mức thuần Rule không thể giải quyết được bài toán vì ngôn ngữ học thuật toán học rất đa dạng; các tác giả có vô số cách diễn đạt gián tiếp để định nghĩa biến số mà các mẫu Regex đơn giản không thể bao quát hết. Cần có năng lực đọc hiểu ngữ cảnh của LLM để liên kết được mối quan hệ nhân quả giữa biểu thức toán học và bài toán thực tế mà mô hình đang giải quyết.
```

---

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối ngành CNTT (chuyên ngành AI), đang làm đồ án tốt nghiệp hoặc nghiên cứu paper mô hình Deep Learning. Họ cần hiểu cặn kẽ bản chất toán học để tái lập (reproduce) hoặc tùy biến kiến trúc mạng. |
| **Workflow** | Đọc tổng quan bài báo → Chọn công thức toán trọng tâm trong phần Methodology → Hệ thống tự động tra cứu Symbol Table và phân tích kích thước tensor → Người đọc kiểm chứng tính đúng đắn số chiều → Xuất ghi chú có cấu trúc để phục vụ lập trình mô hình. |
| **Bottleneck** | Hiện tượng "mất dấu ký hiệu" (Symbol Disconnection) và thiếu góc nhìn trực quan về không gian tensor; người đọc mất 75 phút lật tìm trang cũ và nháp tay thủ công cho mỗi khối phương trình. |
| **Impact** | Tốn 2.5–3 tiếng/paper; làm chậm tiến độ triển khai đồ án 2–3 ngày; sinh viên dễ nản lòng hoặc bỏ qua phần toán dẫn đến việc code sai thuật toán mà không biết nguyên nhân. |
| **Success Metric** | Giảm thời gian giải mã công thức toán từ **165 phút xuống dưới 35 phút/paper**; 100% các ký hiệu trong công thức được liên kết chính xác với trang định nghĩa gốc; sinh viên viết được mã giả với số chiều tensor chuẩn xác ngay sau khi đọc. |
| **Boundary** (làm / không làm) | **Làm:** Phân tích công thức toán của các bài báo Deep Learning/AI thực nghiệm có mã nguồn; trích xuất ký hiệu cục bộ & toàn cục; mô tả tensor dimension; xuất mã giả logic. **Không làm:** Không đọc thay toàn bộ bài báo; không tự động viết mã nguồn hoàn chỉnh; không nhận paper toán thuần túy lý thuyết phi thực nghiệm. |
| **AI intervention point** | Can thiệp ngay sau khi người dùng bôi chọn một khối phương trình toán học trên giao diện PDF và trước khi người dùng bắt tay vào nháp tay chiều tensor hoặc viết code mô hình. |
| **Mức chọn** | **Workflow** (kết hợp Rule parser). Vì bài toán có luồng xử lý tuần tự cố định, đòi hỏi độ chuẩn xác cao và có sự kiểm soát của con người tại các điểm chốt, không cần sự tự trị của Agent. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro lớn nhất:** AI suy luận sai chiều của tensor hoặc diễn giải nhầm ý nghĩa của siêu tham số tùy biến. **Người thật kiểm tra:** Sinh viên đối chiếu trực tiếp kích thước ma trận/tensor đầu vào và đầu ra dựa trên bảng Dimension Breakdown mà AI cung cấp; nếu có mâu thuẫn, nhấp vào ký hiệu để mở trực tiếp trang tài liệu gốc để xác thực. |

---

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Sinh viên làm đồ án AI với quy trình 6 bước được lượng hóa thời gian chi tiết. |
| Baseline + metric đo được chưa? | **Yes** | Baseline 165 phút giảm xuống 35 phút; đo đếm bằng đồng hồ bấm giờ khi đọc paper thật. |
| Data/input đủ dùng chưa? | **Yes** | File PDF bài báo khoa học chuẩn (arXiv / IEEE / CVPR) có cấu trúc văn bản rõ ràng. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Sai sót chỉ nằm ở tầng gợi ý giải thích; người học phát hiện ngay qua kiểm tra chiều tensor và có link xem trang gốc. |
| Có người review/owner không? | **Yes** | Sinh viên đọc bài là người chịu trách nhiệm trực tiếp về đồ án của mình. |
| Có cách non-AI đơn giản hơn không? | **Yes (nhưng không đủ)** | Non-AI (Rule/Mathpix) chỉ lấy được cú pháp LaTeX, không giải quyết được khâu hiểu ngữ nghĩa và tensor shape. |

**Decision:**

```text
[Go] — Quyết định triển khai thử nghiệm (Pilot) với phạm vi có kiểm soát.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Cả 6 câu hỏi thẩm định đều đạt trạng thái sẵn sàng với bằng chứng thực tế từ quá trình làm đồ án của các thành viên trong nhóm. Giá trị tiết kiệm thời gian là rất lớn (giảm hơn 2 tiếng cho mỗi bài báo kỹ thuật), giải quyết đúng điểm nghẽn gây kiệt quệ nhận thức nhất của sinh viên chuyên ngành AI. Phương án Workflow kết hợp Rule giữ cho hệ thống an toàn, chi phí thấp, tránh được hoàn toàn rủi ro hallucination mất kiểm soát của Agent.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data thử nghiệm: 3 paper Deep Learning kinh điển đang được sử dụng trực tiếp trong đồ án của nhóm (1 paper về Transformer, 1 paper về Diffusion, 1 paper về Object Detection).
- Cách chạy pilot: Chạy bán tự động (Human-in-the-loop): Dùng script bóc tách bảng ký hiệu thủ công, đưa công thức LaTeX vào LLM với prompt template chuẩn hóa của nhóm, kết xuất bản giải thích ra Markdown.
- Đo lường 3 chỉ số then chốt:
  1. Thời gian đọc hiểu và giải mã công thức (mục tiêu: < 35 phút/paper).
  2. Tỷ lệ trích xuất đúng ý nghĩa biến số so với nguyên bản tác giả (mục tiêu: > 95%).
  3. Mức độ tự tin khi viết mã giả PyTorch của sinh viên sau khi đọc bản giải thích (thang điểm 1-5, mục tiêu: >= 4/5).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn GO).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì nhóm đã chọn GO).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu trong quá trình pilot trên 3 paper đầu tiên mà tỷ lệ AI giải thích sai lệch ký hiệu toán học vượt quá 15%, hoặc sinh viên nhận thấy việc kiểm tra lại lỗi của AI mất nhiều thời gian hơn việc tự đọc giấy nháp truyền thống (> 45 phút), nhóm sẽ lập tức dừng giải pháp AI và quay về quy trình truyền thống: Sử dụng Mathpix để lấy nhanh LaTeX và tự lập bảng chú giải thủ công trên Notion.
```

---

### Self-check nộp phần 02 (nhóm)

- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
