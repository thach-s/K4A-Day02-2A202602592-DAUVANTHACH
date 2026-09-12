# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên:Đậu Văn Thạch 
- Mã học viên: 2A202602592
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên vừa tốt nghiệp - intern về phát triển chatbot AI  
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): - Đọc cái tài liệu về  API , - kiểm tra tốc độ phản hồi của chatbot ,- Tổng hợp lại các thông số để viết báo cáo vào cuối tuần ,- review lại với menter về công việc trong tuần 

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Kiểm tra tốc độ phản hồi của chatbot | Mentor, bản thân | Khoảng 90 phút/tuần để thực hiện kiểm tra và tổng hợp kết quả |
| 2 | Tốn thời gian | Đọc và tìm kiếm thông tin trong tài liệu API | Bản thân | Khoảng 2-3 giờ/tuần; phải tìm nhiều endpoint/tham số trước khi có thể sử dụng |
| 3 | Lặp lại | Tổng hợp thông số chatbot thành báo cáo cuối tuần | Bản thân, mentor | Khoảng 60 phút/tuần để tổng hợp số liệu và viết báo cáo |
| 4 | Tốn thời gian | Đối chiếu kết quả test chatbot với yêu cầu/kỳ vọng của mentor | Bản thân, mentor | Khoảng 30-60 phút/tuần; thường phải xem lại kết quả test và tài liệu liên quan |
| 5 | Pain từ người khác | Mentor phải xem lại và hỏi thêm về các thông số test chatbot | Mentor, bản thân | 1 lần review/tuần; cần chuẩn bị và giải thích lại các thông số đã đo |
| 6 | AI có thể tốt hơn | So sánh kết quả tốc độ phản hồi giữa nhiều lần/chế độ test | Bản thân, mentor | Khoảng 30 phút/tuần; phải xem và đối chiếu nhiều kết quả test |
| 7 | Lặp lại | Ghi lại kết quả test chatbot từ các lần kiểm tra | Bản thân | Thực hiện nhiều lần trong tuần; khoảng 15-20 phút/lần khi test và ghi số liệu |
| 8 | Tốn thời gian | Tìm lại thông tin API đã đọc trước đó khi cần triển khai/test | Bản thân | Khoảng 30 phút/tuần; phải tìm lại tài liệu hoặc ghi chú cũ |
| 9 | Pain từ người khác | Báo cáo chưa có cùng một format nên mentor phải đọc và kiểm tra từng phần | Mentor, bản thân | 1 lần/tuần vào buổi review; cần rà lại các thông số và kết luận |
| 10 | AI có thể tốt hơn | Phân tích xu hướng tốc độ phản hồi từ dữ liệu test theo thời gian | Bản thân, mentor | Dữ liệu được thu thập hằng tuần nhưng việc tổng hợp xu hướng hiện chưa được tự động hóa |
> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Phản biện và mở rộng danh sách problem từ các công việc hằng tuần của một intern phát triển chatbot AI, tập trung vào các việc lặp lại, tốn thời gian, có thể dùng AI và pain từ mentor.
- Ý dùng được: Tách công việc thành các problem nhỏ hơn như đo tốc độ, ghi nhận số liệu, tổng hợp báo cáo, tìm kiếm tài liệu API và đối chiếu kết quả.
- Ý bỏ vì không phải pain thật: Các ý quá rộng như "AI có thể thay thế intern", "chatbot chưa thông minh" vì chưa có số liệu hoặc workflow cụ thể chứng minh pain.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Kiểm tra tốc độ phản hồi của chatbot | Lặp lại hằng tuần; đã có số đo khoảng 90 phút/tuần; có thể xây workflow test và tự động hóa khá rõ | Chưa chắc phần nào trong 90 phút là đo thủ công và phần nào là tổng hợp |
| 2 | Tổng hợp thông số chatbot thành báo cáo cuối tuần | Có thời gian cố định hằng tuần; mentor là người sử dụng báo cáo; workflow có thể chuẩn hóa | Chưa rõ báo cáo hiện cần những trường thông số nào và mức độ thay đổi mỗi tuần |
| 3 | Đọc và tìm kiếm thông tin trong tài liệu API | Chiếm khoảng 2-3 giờ/tuần; thường xuyên lặp lại; có khả năng hỗ trợ bằng công cụ tìm kiếm/tóm tắt tài liệu | Chưa rõ phần lớn thời gian mất ở đọc hiểu, tìm endpoint hay thử nghiệm API |


## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Kiểm tra tốc độ phản hồi của chatbot | Lặp lại hằng tuần; đã có số đo khoảng 90 phút/tuần; có thể xây workflow test và tự động hóa khá rõ | Chưa chắc phần nào trong 90 phút là đo thủ công và phần nào là tổng hợp |
| 2 | Tổng hợp thông số chatbot thành báo cáo cuối tuần | Có thời gian cố định hằng tuần; mentor là người sử dụng báo cáo; workflow có thể chuẩn hóa | Chưa rõ báo cáo hiện cần những trường thông số nào và mức độ thay đổi mỗi tuần |
| 3 | Đọc và tìm kiếm thông tin trong tài liệu API | Chiếm khoảng 2-3 giờ/tuần; thường xuyên lặp lại; có khả năng hỗ trợ bằng công cụ tìm kiếm/tóm tắt tài liệu | Chưa rõ phần lớn thời gian mất ở đọc hiểu, tìm endpoint hay thử nghiệm API |

---

## 2.2. Problem Cards chi tiết

### Problem Card #1 — Kiểm tra tốc độ phản hồi của chatbot

```text
Problem 1 câu:
Việc kiểm tra tốc độ phản hồi chatbot đang phải thực hiện thủ công nhiều lần và mất khoảng 90 phút/tuần.

Actor:
Intern phát triển chatbot AI; mentor sử dụng kết quả để review.

Thời điểm / bối cảnh:
Trong quá trình test chatbot và trước buổi review hằng tuần.

Current workflow 3-7 bước:
1. Chuẩn bị các câu hỏi/test case cần kiểm tra.
2. Gửi từng request đến chatbot.
3. Ghi nhận thời gian phản hồi của từng request.
4. Lặp lại test với các case khác nhau.
5. Tổng hợp kết quả.
6. Gửi kết quả cho mentor để review.

Bottleneck:
Đo và ghi nhận kết quả thủ công qua nhiều lần test.

Impact:
Khoảng 90 phút/tuần; tốn thời gian của intern và tạo thêm công việc kiểm tra cho mentor.

Success metric:
Giảm thời gian kiểm tra và tổng hợp từ khoảng 90 phút xuống còn <= 20 phút/tuần, đồng thời vẫn giữ đủ dữ liệu để mentor review.

Non-AI alternative:
Viết script tự động gửi test case và đo response time, lưu kết quả vào CSV/Google Sheets.

AI hypothesis:
AI workflow có thể tự chạy bộ test, tổng hợp response time, phát hiện các request bất thường và tạo summary để mentor review.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #1

```text
CURRENT STATE — ~90 phút/tuần

[1 Chuẩn bị test case: 10'] → [2 Gửi request: 30'] → [3 Ghi response time: 25'] → [4 Tổng hợp + review: 25'] <-- bottleneck

FUTURE STATE — ~20 phút/tuần

[1 Chọn/ cập nhật test case: 5'] → [2 Auto test + đo response time: 5'] → [3 AI tổng hợp + phát hiện bất thường: 5'] → [4 Mentor review: 5'] <-- human boundary

Fallback: nếu AI hoặc script đo sai thì chạy lại test thủ công trên các case quan trọng và giữ log gốc để đối chiếu.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

### Problem Card #2 — Tổng hợp thông số chatbot thành báo cáo cuối tuần

```text
Problem 1 câu:
Việc tổng hợp các thông số chatbot để viết báo cáo cuối tuần đang mất khoảng 60 phút mỗi tuần.

Actor:
Intern phát triển chatbot AI; mentor là người đọc và review báo cáo.

Thời điểm / bối cảnh:
Cuối mỗi tuần trước buổi review với mentor.

Current workflow 3-7 bước:
1. Tập hợp các kết quả test trong tuần.
2. Kiểm tra lại các thông số và log.
3. Chọn các số liệu cần đưa vào báo cáo.
4. Tổng hợp thành bảng/ghi chú.
5. Viết nhận xét và kết luận.
6. Gửi báo cáo cho mentor.
7. Review và chỉnh sửa nếu cần.

Bottleneck:
Tập hợp, kiểm tra và chuyển dữ liệu test rời rạc thành một báo cáo có cấu trúc.

Impact:
Khoảng 60 phút/tuần; mentor mất thêm thời gian đọc và hỏi lại nếu thông tin chưa rõ.

Success metric:
Giảm thời gian tạo báo cáo từ khoảng 60 phút xuống <= 15 phút; báo cáo có đầy đủ số liệu, nhận xét và nguồn dữ liệu.

Non-AI alternative:
Chuẩn hóa template báo cáo và lưu kết quả test vào một bảng dữ liệu thống nhất.

AI hypothesis:
AI có thể lấy dữ liệu test đã chuẩn hóa, tự tạo bảng tổng hợp, nhận xét xu hướng và draft báo cáo để intern kiểm tra trước khi gửi mentor.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #2

```text
CURRENT STATE — ~60 phút/tuần

[1 Tập hợp dữ liệu: 15'] → [2 Kiểm tra số liệu: 15'] → [3 Viết bảng + nhận xét: 20'] → [4 Chỉnh báo cáo: 10'] <-- bottleneck

FUTURE STATE — ~15 phút/tuần

[1 Dữ liệu được lưu chuẩn: 2'] → [2 AI tạo summary + draft report: 5'] → [3 Intern kiểm tra số liệu: 5'] → [4 Mentor review: 3'] <-- human boundary

Fallback: nếu AI tổng hợp sai, sử dụng bảng dữ liệu gốc để kiểm tra và chỉnh báo cáo thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

### Problem Card #3 — Đọc và tìm kiếm thông tin trong tài liệu API

```text
Problem 1 câu:
Intern mất khoảng 2-3 giờ mỗi tuần để đọc và tìm lại thông tin cần thiết trong tài liệu API.

Actor:
Intern phát triển chatbot AI.

Thời điểm / bối cảnh:
Khi cần hiểu API, tìm endpoint, tham số hoặc cách xử lý lỗi trong quá trình phát triển/test.

Current workflow 3-7 bước:
1. Xác định thông tin API cần tìm.
2. Mở tài liệu API.
3. Tìm endpoint hoặc keyword liên quan.
4. Đọc phần mô tả, request/response và parameter.
5. Đối chiếu với code hoặc nhu cầu hiện tại.
6. Thử API nếu thông tin chưa rõ.

Bottleneck:
Tìm đúng thông tin liên quan trong tài liệu dài và phải đọc nhiều phần trước khi có câu trả lời.

Impact:
Khoảng 2-3 giờ/tuần; làm chậm quá trình phát triển và test chatbot.

Success metric:
Giảm thời gian tìm thông tin API xuống còn <= 30 phút/tuần và câu trả lời phải trỏ được đến phần tài liệu nguồn.

Non-AI alternative:
Tạo documentation nội bộ có mục lục, search và các ví dụ API thường dùng.

AI hypothesis:
Xây trợ lý hỏi đáp trên tài liệu API, có khả năng tìm đúng đoạn tài liệu, giải thích parameter và đưa ví dụ request/response có trích nguồn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #3

```text
CURRENT STATE — ~2-3 giờ/tuần

[1 Xác định thông tin cần tìm: 10'] → [2 Search tài liệu: 30-45'] → [3 Đọc nhiều phần liên quan: 60'] → [4 Đối chiếu code/test: 30'] <-- bottleneck

FUTURE STATE — ~30 phút/tuần

[1 Đặt câu hỏi: 2'] → [2 AI tìm + trích nguồn tài liệu: 5'] → [3 Intern kiểm tra câu trả lời: 10'] → [4 Áp dụng/test API: 13'] <-- human boundary

Fallback: nếu AI không tìm thấy hoặc trích nguồn không đúng, quay lại tài liệu API gốc và kiểm tra trực tiếp endpoint/parameter.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

## 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Kiểm tra tốc độ phản hồi của chatbot
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là workflow lặp lại hằng tuần với khoảng 90 phút dành cho việc chuẩn bị test, gửi request, ghi response time và tổng hợp kết quả.
Bottleneck nằm ở việc phải thực hiện và ghi nhận nhiều lần thủ công. Nếu tự động hóa phần chạy test và tổng hợp, mục tiêu là giảm thời gian xuống khoảng 20 phút/tuần trong khi mentor vẫn giữ quyền review kết quả.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Trong 90 phút/tuần, phần nào thực sự là bottleneck lớn nhất: chạy test, ghi số liệu hay tổng hợp kết quả?
Có cần AI/Agent hay chỉ cần một script tự động hóa việc test và ghi response time là đã giải quyết phần lớn pain?
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: Pain hiện mới có số tổng 90 phút/tuần, chưa có breakdown được đo bằng stopwatch cho từng bước. Ngoài ra, giải pháp có thể chỉ cần automation/rule thay vì AI.
- Tôi sửa gì: Tách workflow thành các bước cụ thể, ghi rõ thời gian ước tính cho từng bước và đặt câu hỏi challenge về việc có thực sự cần AI hay không.

---

## Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
