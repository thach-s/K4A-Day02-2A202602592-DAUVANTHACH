# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đậu Văn Thạch
- Mã học viên: 2A202602592
- Nhóm: Lê Thanh Tùng, Đinh Quốc Bảo, Nguyễn Hồ Nam, Nguyễn Thu Hằng, Đậu Văn Thạch (vai trò của tôi: Validation — interview/survey, thu thập evidence)
- Candidate problem nhóm chọn: Nhân viên nhập liệu phải đọc và gõ lại thủ công dữ liệu từ báo cáo/biểu mẫu viết tay vào Excel, khiến bước nhập liệu chiếm phần lớn thời gian xử lý và dễ phát sinh sai sót khi số lượng phiếu nhiều hoặc chữ viết khó đọc.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 10 problem từ công việc intern chatbot AI (test tốc độ phản hồi, đọc tài liệu API, tổng hợp báo cáo cuối tuần), dùng ít nhất 3/4 lăng kính (Lặp lại / Tốn thời gian / Pain từ người khác / AI có thể tốt hơn), sau đó dùng AI để phản biện và mở rộng danh sách. | Có 3 Problem Card cụ thể (kiểm tra tốc độ phản hồi ~90'/tuần, tổng hợp báo cáo ~60'/tuần, đọc tài liệu API ~2-3h/tuần) để mang vào buổi convergence — 3 candidate này trở thành #13, #14, #15 trong bảng trình bày top-3 của cả nhóm. |
| Pitch Problem Card | Pitch Card #1 "Kiểm tra tốc độ phản hồi của chatbot": nêu workflow 6 bước, bottleneck ở khâu đo/ghi thủ công, và đặt câu hỏi challenge cho chính mình (phần nào trong 90' là bottleneck thật, có cần AI hay chỉ cần script). | Candidate của tôi được nhóm ghi nhận là "workflow rõ, có khả năng tự động hóa bằng Rule/Workflow" (cluster B) nhưng không lọt vào shortlist 3 candidate cuối vì thời gian phụ thuộc từng task và ít đo được impact bằng số liệu chắc chắn như candidate #1. |
| Challenge bài của bạn khác | Trong lúc gom cluster, tôi đối chiếu candidate #1 và #3 (nhập liệu viết tay, đọc ảnh/PDF) với chính candidate #14/#15 của mình để chỉ ra điểm chung: bottleneck đều nằm ở bước "chuyển thông tin thô sang dữ liệu có cấu trúc", giúp nhóm gộp đúng cluster A và B thay vì tách rời từng người. | Góp phần vào bảng 3.2 (Gom trùng/cluster) có 4 cluster rõ ràng thay vì 15 candidate rời rạc, làm nền cho bước shortlist ở 3.3. |
| Gom trùng / cluster | Đóng góp góc nhìn "đo lường được impact bằng thời gian/tỷ lệ sai sót" khi nhóm so sánh candidate #1 (nhập liệu viết tay) với #10 (Daily Operation Report) và #4 (đọc task trước khi code) ở bảng score 3.4. | Candidate #1 đạt điểm tổng cao nhất (34/35) một phần nhờ tiêu chí "Pain có evidence" và "Impact đo được" được nhóm thống nhất áp cho tất cả ứng viên như nhau. |
| Chọn candidate problem | Đồng thuận chọn #1 "Nhập liệu thủ công từ báo cáo viết tay" thay vì giữ candidate của chính mình, vì #1 có bottleneck đơn-điểm và dễ đo hơn ba candidate tôi tự đưa ra. | Nhóm chốt 1 candidate duy nhất để đi tiếp Phase 4-6 thay vì phân vân giữa nhiều hướng. |
| Validation / research | Là người phụ trách Validation: thực hiện interview 3 người và survey 8 người (bảng 4.1) để kiểm tra pain "nhập liệu từ báo cáo viết tay" có thật không, ghi nhận cả tín hiệu xác nhận lẫn tín hiệu phản bác (một số người cho rằng nếu ít biểu mẫu/chữ rõ thì không đáng kể). | Giúp nhóm thu hẹp problem đúng chỗ: pain không nằm ở "có báo cáo viết tay" mà ở "số lượng phiếu nhiều hoặc chữ khó đọc" — insight này được ghi thẳng vào phần Insight sau validation và ảnh hưởng tới cách viết Impact/Boundary ở Problem Statement. |
| Workflow nhóm | Không trực tiếp vẽ workflow (bạn Nguyễn Hồ Nam phụ trách phần này), nhưng cung cấp số liệu validation để đối chiếu workflow 7 bước (~125'/lô 20 phiếu) với thực tế những người được phỏng vấn mô tả. | Giúp workflow "Current state" không chỉ là ước lượng của một người mà có đối chiếu chéo với người ngoài nhóm. |
| Problem Statement | Đóng góp phần "Impact" và "Boundary" bằng dữ liệu validation (tần suất, mức độ nghiêm trọng khi chữ khó đọc), để bạn Nguyễn Thu Hằng (writer) viết PS v0 → v1. | PS v1 quy được Impact ra ~125'/ngày ≈ 10,4 giờ/tháng và khóa Boundary về đúng 1 loại biểu mẫu + 8 trường — tránh việc PS bị chung chung như bản v0. |
| Rule / Workflow / Agent | Đóng góp góc nhìn từ validation vào phần "Rủi ro & người thật kiểm tra" (6.2): nhấn mạnh rủi ro AI đọc sai số liệu mà confidence cao vẫn lọt qua, dựa trên phản ánh thực tế của người được phỏng vấn về việc chữ viết tay dễ nhầm số. | Góp phần vào quyết định ép review 100% với hai trường số lượng/đơn giá trong giai đoạn pilot, thay vì chỉ dựa vào ngưỡng confidence chung. |
| Decision | Tham gia trả lời câu hỏi "Có người review/owner không?" trong bảng Final decision dựa trên vai trò validation — xác nhận nhân viên nhập liệu là người review trực tiếp mỗi lô. | Góp phần vào quyết định "Go (có điều kiện)" thay vì Go toàn phần, vì hai điểm chưa chắc (baseline một lần, chưa đủ ảnh thật) do chính phần validation của tôi chỉ ra. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là dòng insight "pain không nằm ở việc có báo cáo viết tay mà nằm ở số lượng phiếu nhiều/chữ khó đọc" trong mục 4.1 — chính tín hiệu phản bác tôi thu được từ interview và survey đã ngăn nhóm phát biểu problem quá rộng, và buộc Problem Statement phải khóa Boundary rõ ràng hơn ở v1.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Prompt AI để phản biện và mở rộng danh sách problem từ 4 công việc hằng tuần của intern chatbot AI, tập trung vào lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ mentor. | Giúp tách một công việc gộp ("test chatbot") thành các problem nhỏ hơn có thể đo riêng: đo tốc độ, ghi số liệu, tổng hợp báo cáo, tìm tài liệu API, đối chiếu kết quả. | AI đề xuất một số ý quá rộng và không có bằng chứng, kiểu "AI có thể thay thế intern" hoặc "chatbot chưa thông minh" — không gắn với số liệu hay workflow cụ thể nào. | Tôi loại bỏ các ý quá rộng đó, chỉ giữ lại problem nào tôi tự chấm được số phút/tuần và actor cụ thể. |
| Problem Card | Dùng AI để phản biện Problem Card #1 tôi định pitch, xem field nào còn yếu trước khi mang ra nhóm. | AI chỉ đúng điểm yếu: con số 90 phút/tuần mới là tổng, chưa breakdown theo từng bước bằng bấm giờ thật, và giải pháp có thể chỉ cần automation/rule chứ chưa chắc cần AI. | AI không tự đề xuất được cách chia nhỏ 90 phút thành các bước hợp lý — phần này tôi phải tự ước lượng dựa trên trải nghiệm thật khi test chatbot. | Tôi tách lại current workflow thành 4 bước có ước lượng thời gian riêng (chuẩn bị test case, gửi request, ghi response time, tổng hợp) và thêm câu hỏi challenge "có cần AI/Agent hay chỉ cần script" vào phần pitch. |
| Workflow | Không dùng AI trực tiếp ở phase này — vai trò vẽ current/future workflow của nhóm do bạn Nguyễn Hồ Nam phụ trách; tôi chỉ đối chiếu số liệu validation với bản vẽ đó. | — | — | Tôi tự kiểm tra bằng cách so sánh mô tả workflow 7 bước của nhóm với những gì người được tôi phỏng vấn kể lại, để chắc bước 4 (gõ tay) đúng là bước họ than phiền nhiều nhất. |
| Research | Không dùng AI để lấy số liệu tool OCR (phần này do bạn Đinh Quốc Bảo phụ trách Research); riêng phần validation của tôi tôi có tham khảo AI để gợi ý cách đặt câu hỏi phỏng vấn/khảo sát trung lập, tránh dẫn dắt câu trả lời. | Gợi ý giúp câu hỏi không mớm câu trả lời (VD: hỏi "bạn mất bao lâu để nhập một phiếu" thay vì "bạn có thấy việc này chậm không"). | AI không nhắc tôi phải lấy quote nguyên văn — nhóm bị thiếu sót này và phải tự ghi chú cảnh báo "còn thiếu quote nguyên văn của 3 người interview, không được để placeholder". | Tôi tự bổ sung yêu cầu ghi quote nguyên văn thay vì diễn giải lại lời người được phỏng vấn, để tín hiệu xác nhận/phản bác không bị tôi "làm mềm" đi. |
| Problem Statement | Không dùng AI trực tiếp để viết PS (bạn Nguyễn Thu Hằng là writer); tôi chỉ dùng AI để tự kiểm tra xem dữ liệu validation tôi đưa có đủ cụ thể để quy ra Impact theo giờ/tháng hay chưa. | AI nhắc đúng chỗ PS v0 còn mơ hồ: "Impact" ban đầu chỉ nói "mất nhiều thời gian" chứ chưa quy ra số, "Success Metric" chưa có mốc và cách đo. | AI không tự biết ngưỡng accuracy 95%/98% nào là hợp lý cho bài toán kho vận — đây là quyết định nghiệp vụ, không phải thứ AI đoán đúng được. | Tôi và nhóm tự chọn mốc dựa trên mức độ rủi ro chấp nhận được (lệch tồn kho), không lấy nguyên số AI gợi ý. |
| Rule / Workflow / Agent | Không dùng AI để ra quyết định mức Rule/Workflow/Agent — đây là phần nhóm tự lý luận qua 5 câu hỏi chốt dựa trên đặc điểm bài toán (độ mơ hồ thấp, độ phức tạp cao). | — | — | Tôi đóng góp lập luận từ góc độ validation: rủi ro lớn nhất không phải "AI có làm được không" mà là "nếu AI sai mà confidence cao thì ai phát hiện" — nên nhóm thêm cơ chế ép review 100% cho hai trường nhạy cảm thay vì chỉ dựa ngưỡng confidence. |
| Decision | Không dùng — quyết định Go/Not Yet/No-Go được nhóm thảo luận trực tiếp dựa trên bảng 6 câu hỏi và bằng chứng validation/research đã có, không cần AI gợi ý thêm. | — | — | Tôi giữ quan điểm "Not Yet" cho 2/6 câu hỏi (baseline mới đo một lần, chưa đủ ảnh thật) dù có thể dễ dàng chấm "Yes" cho gọn, vì đó là đúng thực trạng dữ liệu nhóm đang có. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problem của các bạn khác, tôi nhận ra candidate của mình (kiểm tra tốc độ phản hồi chatbot) tuy có số đo rõ nhưng lại yếu hơn candidate #1 của Lê Thanh Tùng ở một điểm quan trọng: bottleneck của tôi trải đều trên nhiều bước nhỏ, còn bottleneck của #1 dồn hết vào đúng một bước (gõ tay 70 phút), nên dễ chứng minh AI có tạo khác biệt hay không. Ban đầu tôi vẫn nghiêng về giữ candidate của mình vì đã đầu tư công sức viết Problem Card khá kỹ, nhưng khi nhóm so điểm ở bảng 3.4, tôi bị thuyết phục bởi chính tiêu chí "Pain có evidence" và "Impact đo được" mà cả nhóm thống nhất áp dụng công bằng cho mọi người — tôi đổi ý vì nhìn thấy rõ candidate #1 hơn mình ở đúng những tiêu chí đó, không phải vì nể bạn. Đóng góp thật sự của tôi vào artifact cuối nằm ở phần Validation: tôi phỏng vấn 3 người và khảo sát 8 người, và chính từ đó phát hiện tín hiệu phản bác — có người nói nếu ít phiếu hoặc chữ rõ thì việc này không đáng gọi là pain. Nếu nhóm bỏ qua tín hiệu phản bác này, Problem Statement có thể đã viết chung chung kiểu "mọi báo cáo viết tay đều là vấn đề", trong khi thực tế pain chỉ nặng khi số lượng phiếu nhiều hoặc chữ khó đọc. Điều khó nhất với tôi không phải là đặt ra metric, mà là boundary — vì "không làm gì" (loại phiếu khác, phần ghi chú tự do, không tự động ghi thẳng vào hệ thống kho) là những giới hạn dễ bị bỏ qua khi ai cũng muốn giải pháp nghe "hoành tráng" hơn. Có một khoảnh khắc gần với solution-first: khi research của Đinh Quốc Bảo mang về ba nền tảng OCR doanh nghiệp, có ý kiến muốn nhảy thẳng sang bàn "dùng Agent để tự tra danh mục hàng và tự sửa lỗi", nhưng khi áp 5 câu hỏi chốt ở Phase 6, nhóm nhận ra không có bước nào thật sự cần hệ thống tự lập kế hoạch, nên hạ xuống đúng mức Workflow. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần baseline: nhóm mới bấm giờ một lần (~125 phút/lô) rồi coi đó gần như con số chính thức, trong khi chính phần validation của tôi cho thấy mức độ khó đọc chữ viết tay khác nhau khá nhiều giữa các phiếu, nên một lần đo là chưa đủ để tin tưởng đặt mục tiêu giảm xuống 50 phút.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI