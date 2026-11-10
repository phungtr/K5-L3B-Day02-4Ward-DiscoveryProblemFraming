# Báo cáo cá nhân — 2A202604089_NguyenTuanAnh

## 1. Thông tin học viên

- Họ tên: Nguyễn Tuấn Anh
- MSSV: 2A202604089
- Email trường (không bắt buộc, repo có thể để public): 26ai.anhnt14@vinuni.edu.vn
- Tên nhóm: 4Ward
- Link repo nhóm: https://github.com/phungtr/K5-L3B-Day02-4Ward-DiscoveryProblemFraming.git

## 2. CP1 — Scan problems

| # | Lăng kính | Job Story | Dấu hiệu thật |
|---|---|---|---|
| 1 | Lặp lại | Khi cần tìm lại một thông báo hoặc quyết định cũ trong nhóm chat, tôi muốn thấy đúng tin đó ngay, để khỏi phải cuộn hàng trăm tin nhắn. | ~10 phút/lần, 3–4 lần/tuần, cả nhóm 5 người đều gặp |
| 2 | Tốn thời gian | Khi chuẩn bị nộp bài lúc 22h, tôi muốn biết bài còn thiếu mục nào, để không bị trừ điểm vì sai cấu trúc. | ~20 phút đối chiếu đề, 1–2 lần/tuần; từng bị trừ điểm 1 lần |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn thi từ slide, ghi chú và tài liệu tiếng Anh rời rạc, tôi muốn gom ý chính của từng chương vào một chỗ, để ôn xong trong một buổi. | ~3 giờ/môn, mỗi kỳ 5–6 môn, 4/5 bạn trong lớp làm như vậy |
| 4 | Pain từ người khác | Khi làm bài nhóm, tôi muốn biết ai đang làm phần nào và hạn bao giờ, để khỏi phải nhắn hỏi lại. | Nhóm chat có ≥5 tin hỏi lại mỗi tuần, từng có 1 lần trùng phần việc |
| 5 | Tốn thời gian | Khi theo dõi chi tiêu trong tháng, tôi muốn thấy tổng theo từng loại, để biết mình vượt ngân sách ở đâu. | ~30 phút/tháng, dữ liệu ở 3 nơi (ngân hàng, ví điện tử, ghi chú) |
| 6 | Lặp lại | Khi ghi chép buổi học, tôi muốn có ghi chú đã gọn theo ý chính, để khỏi mất thời gian sắp xếp lại sau buổi học. | ~25 phút/buổi, 4 buổi/tuần |

## 3. CP2 — Top 3 Problem Card + quy trình nháp

### Bảng xếp hạng top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tìm lại thông tin cũ trong chat nhóm (#1) | Pain thật, cả nhóm đều gặp, impact rộng (~200 phút/tuần) | Thời gian tìm thật sự là bao nhiêu, mình có đang ước lượng quá cao? |
| 2 | Kiểm tra bài nộp trước deadline (#2) | Quy trình rõ, bottleneck cụ thể, có baseline đo thật (~12 phút, từng mất điểm) | Checklist đã đủ hay cần thêm công cụ khác? |
| 3 | Theo dõi phân công bài nhóm (#4) | Có dấu hiệu thật (≥5 tin hỏi lại/tuần), dễ đo | Nhóm có chịu cập nhật bảng chung không? |

### Problem Card #1 — Tìm lại thông tin cũ trong chat nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần tìm lại một thông báo hoặc quyết định cũ trong nhóm chat, tôi muốn thấy đúng tin đó ngay, để khỏi phải cuộn hàng trăm tin nhắn |
| Actor | Sinh viên trong nhóm 5 người |
| Thời điểm / bối cảnh | Khi làm bài nhóm, cần nhớ lại hạn nộp hoặc quyết định đã chốt trước đó |
| Quy trình hiện tại | 1. Nhớ mang máng (1') · 2. Cuộn chat (6') · 3. Hỏi lại người khác (3') · 4. Chờ trả lời (5') · 5. Xác nhận (1') |
| Bottleneck | Bước 2, cuộn chat tìm thủ công: khoảng 6 phút/lần |
| Impact | ~10 phút/lần × 4 lần/tuần × 5 người = ~200 phút/tuần cả nhóm |
| Success metric | Thời gian tìm từ ~10 phút xuống dưới 2 phút/lần, tự bấm giờ trong 1 tuần |
| Phương án không dùng AI | Ghim tin quan trọng + file "Quyết định chung" cập nhật sau mỗi buổi họp |
| Giả thuyết về AI | Nếu ghim và file chung vẫn không đủ, AI tìm và tóm tắt tin cũ trong chat; người dùng tự kiểm tra lại tin gốc |
| Cảm nhận nhanh | No AI |

```text
HIỆN TẠI — ~16 phút/lần

[Nhớ mang máng: 1'] → [Cuộn chat: 6'] ← BOTTLENECK
→ [Hỏi lại người khác: 3'] → [Chờ trả lời: 5'] → [Xác nhận: 1']
```

### Problem Card #2 — Kiểm tra bài nộp trước deadline

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp bài lúc 22h, tôi muốn biết bài còn thiếu mục nào, để không bị trừ điểm vì sai cấu trúc |
| Actor | Sinh viên làm bài lab |
| Thời điểm / bối cảnh | Tối ngày deadline, ngay trước khi nộp bài |
| Quy trình hiện tại | 1. Mở đề (2') · 2. Mở bài làm (1') · 3. Đối chiếu từng mục (12') · 4. Sửa chỗ thiếu (5') · 5. Nộp (1') |
| Bottleneck | Bước 3, tự đối chiếu từng mục bằng mắt: khoảng 12 phút/lần |
| Impact | ~20 phút/lần, 1–2 lần/tuần; từng bị trừ điểm vì thiếu mục |
| Success metric | Thời gian đối chiếu từ ~12 phút xuống dưới 3 phút; 0 lần thiếu mục trong 4 bài liên tiếp |
| Phương án không dùng AI | Checklist các mục bắt buộc của từng bài, tick trước khi nộp |
| Giả thuyết về AI | Nếu checklist vẫn bỏ sót lỗi, AI đối chiếu bài với đề và liệt kê mục thiếu; sinh viên kiểm tra lại trước khi nộp |
| Cảm nhận nhanh | No AI |

```text
HIỆN TẠI — ~21 phút/lần

[Mở đề: 2'] → [Mở bài làm: 1'] → [Đối chiếu từng mục: 12'] ← BOTTLENECK
→ [Sửa chỗ thiếu: 5'] → [Nộp: 1']
```

### Problem Card #3 — Theo dõi phân công bài nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài nhóm, tôi muốn biết ai đang làm phần nào và hạn bao giờ, để khỏi phải nhắn hỏi lại |
| Actor | Nhóm trưởng và 4 thành viên |
| Thời điểm / bối cảnh | Trong tuần làm bài nhóm, sau buổi họp chia việc |
| Quy trình hiện tại | 1. Chia việc khi họp (10') · 2. Mỗi người tự nhớ phần mình (0') · 3. Quên hoặc nhầm hạn (0') · 4. Nhóm trưởng nhắn hỏi từng người (8') · 5. Cập nhật lại (4') |
| Bottleneck | Bước 4, nhắn hỏi từng người vì không có nơi ghi chung: khoảng 8 phút/lần |
| Impact | ≥5 tin hỏi lại/tuần; từng có 1 lần trùng phần việc |
| Success metric | Số tin hỏi lại từ ≥5 xuống ≤1 tin/tuần, đếm trong nhóm chat 3 tuần |
| Phương án không dùng AI | Bảng Google Sheets: người, việc, hạn, trạng thái |
| Giả thuyết về AI | Chưa thấy cần AI; chỉ xem xét nếu bảng chung vẫn không ai cập nhật |
| Cảm nhận nhanh | No AI |

```text
HIỆN TẠI — ~22 phút/lần

[Chia việc khi họp: 10'] → [Mỗi người tự nhớ: 0'] → [Quên/nhầm hạn: 0']
→ [Nhóm trưởng nhắn hỏi từng người: 8'] ← BOTTLENECK → [Cập nhật lại: 4']
```


### Card chọn để pitch

- **Card:** #2
- **Câu hỏi muốn nhóm phản biện:** Checklist đã đủ giải quyết chưa, hay thật sự cần thêm gì nữa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #2: Actor "sinh viên làm bài lab" quá rộng, chưa rõ ai và nộp theo quy định nào | Đồng ý | Thu hẹp Actor thành sinh viên lớp này nộp bài lab theo cấu trúc giảng viên yêu cầu |
| Card #2: 12 phút đối chiếu có thể chỉ là cảm giác, chưa có baseline đo thật | Đồng ý | Ghi baseline là tự bấm giờ 3 bài lab gần nhất, thay vì ước lượng |
| Card #1: 10 phút/lần có thể bị thổi phồng; ghim tin hoặc file chung có thể đã đủ | Đồng ý một phần | Ghi rõ impact là ước lượng cần bấm giờ 1 tuần; giữ phương án không dùng AI là lựa chọn đầu tiên |
| Card #2: Đang nhảy sang AI quá sớm, checklist đã có thể đủ | Không | Giữ nguyên: giả thuyết AI chỉ xét sau khi checklist thử và vẫn bỏ sót lỗi, cảm nhận nhanh vẫn là No AI |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 candidate, mỗi cái khoảng 1–2 phút: #4 tìm lại thông báo/quyết định cũ trong nhóm chat (~6 phút/lần), #5 tự đối chiếu cấu trúc bài lab trước khi nộp (~12 phút/lần), #6 không biết ai đang làm phần nào và hạn bao giờ trong bài nhóm (~8 phút/lần nhắn hỏi) | #6 được gộp vào cluster A cùng #7 (action items sau họp) vì cùng pain "không rõ ai làm gì, hạn bao giờ"; #4 vào top 3 shortlist (27 điểm); #5 được xếp vào cluster D |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: với #8 (viết docs API) của Nam Khánh: "Phần nào trong việc viết docs thật sự cần AI, phần nào Swagger/OpenAPI đã tự sinh được từ code?"; với #7: "Lần gần nhất họp xong bạn mất bao lâu để tổng hợp, có bấm giờ không?" | #8 bị loại vì nhóm thấy khoảng 80% công việc giải được bằng Rule/Script; #7 được yêu cầu ghi rõ baseline thời gian và tần suất họp (30 phút, 2–3 buổi/tuần) |
| Nhận phản biện | Câu hỏi tôi nhận được: với #4: "Muốn tìm được quyết định cũ thì cần quyền truy cập toàn bộ dữ liệu chat của nhóm/công ty, có được phép không? Phạm vi có quá rộng cho bài lab không?" | Tôi đã sửa gì: thừa nhận #4 vướng rủi ro Feasibility và Viability (quyền riêng tư dữ liệu chat), nên tôi chuyển sang ủng hộ #7. Pain của #7 gần với #6 của tôi, đo được rõ hơn và có ranh giới AI dễ kiểm soát |
| Gom cluster / cây OST | Đề xuất gộp #6 của tôi với #7, #3, #9 vào cluster A "Quản lý & theo dõi công việc trong team"; góp ý gạch bỏ nhánh "Tự động gửi danh sách công việc vào kênh chat ngay sau họp" vì đó là tính năng, không phải opportunity | Cluster A trở thành cluster lớn nhất (5 candidate), là cơ sở để chọn #7; OST giữ được 3 opportunity đúng dạng nhu cầu (note lẫn lộn, owner/deadline không chốt, định dạng thủ công) |
| Chọn candidate problem | Chấm điểm shortlist và bỏ phiếu cho #7 thay vì #4 của chính mình | Nhóm chọn #7 (35 điểm) với lý do actor, quy trình và baseline rõ, phù hợp mức Workflow có người kiểm tra |
| Kiểm chứng / research | Phỏng vấn 3 người (trưởng nhóm BTL năm 3 nhóm 5 người là người chính), làm Interview snapshot; lập bảng tổng hợp tín hiệu xác nhận/phản bác cho giả định #1–#4, #6; research 3 giải pháp đã có (Otter.ai My Action Items, Zoom AI Companion Next steps, pattern AI trích xuất + người kiểm tra) | Phát hiện bước trích xuất đã được công cụ có sẵn làm khá tốt với cam kết nói rõ (~70–80%), khoảng trống nằm ở mục mơ hồ (thiếu owner/deadline) → nhóm **thu hẹp problem** và chốt hướng "không tự xây agent". Cũng chỉ ra giả định #6 (được phép đưa transcript vào AI) vẫn chưa có bằng chứng |
| Quy trình nhóm | Cung cấp chi tiết quy trình As-is từ phỏng vấn và góp ý cho bản To-be: đề xuất ghi rõ boundary "AI không tự gửi tin nhắn" và phương án quay về khi AI sai | Interview snapshot cung cấp chi tiết quy trình hiện tại: gõ lại việc từ tin nhắn/ghi chú vào nhóm chat, 15–20 phút/lần, 1–2 lần/tuần; quy trình tương lai có boundary và phương án quay về rõ ràng |
| Problem Statement | Góp ý cho bản v1: đề xuất thêm metric về độ chính xác của người phụ trách, không chỉ đo thời gian, vì phỏng vấn cho thấy hậu quả thật là làm trùng hoặc bỏ việc | Số liệu "15–20 phút", "họp lại 20 phút vì làm trùng việc" từ phỏng vấn được dùng làm bằng chứng; v1 thêm metric "100% action items gửi đi có đúng tên người làm" |
| Mức can thiệp AI | Đưa bằng chứng từ research vào phần so sánh 4 mức: AI sai tên, sót ~20–30% mục mơ hồ, nên không thể chọn mức Agent tự gửi | Bài review độc lập là cơ sở để nhóm chọn mức Workflow: "AI soạn nháp, người xác nhận trước khi gửi"; câu trả lời PAIR chọn augment thay vì automate |
| Quyết định | Viết mục 9–10: chỉ ra 7 hạn chế (mẫu nhỏ, baseline chưa bấm giờ, giả định #5 và #6 chưa kiểm chứng, mục 4–8 chưa khớp với research ở mục 3) và đề xuất hướng pilot | Kết luận research: dùng công cụ có sẵn + rule đánh dấu mục thiếu owner/deadline + người xác nhận trong 15 phút, không xây agent; bổ sung kế hoạch đo baseline và kiểm chứng giả định #6 trước khi pilot |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Liệt kê các vấn đề hay gặp khi làm việc nhóm/đi họp | Gợi ý nhanh nhiều mảng để quét | Danh sách chung chung, đúng với "ai cũng thế", không gắn với tình huống của mình | Chỉ giữ những vấn đề mình hoặc người quen đã thật sự gặp gần đây |
| CP2 Problem Card | Gợi ý cách viết Problem Card cho rõ ràng | Giúp sắp xếp các trường (ai, khi nào, mất gì) | Viết problem dưới dạng giải pháp ("thiếu công cụ AI tóm tắt cuộc họp") | Viết lại theo hành vi + chi phí: "mất 15–20 phút gõ lại việc và gán người sau mỗi buổi họp" |
| CP4 Research | Gợi ý câu hỏi phỏng vấn; tìm và tóm tắt công cụ đã có (Otter, Zoom AI Companion) | Gợi ý câu hỏi "lần gần nhất xảy ra là khi nào" để tránh câu hỏi dẫn dắt; tìm nhanh được danh sách công cụ | **AI tóm tắt rằng Otter "nhận diện action item chính xác"**, nhưng khi mở link thì đó chỉ là thông cáo báo chí của hãng, không có số liệu độ chính xác. AI cũng đưa số liệu % mà không chỉ rõ nguồn | Tự mở từng link để đối chiếu; ghi rõ trong bảng là "thông cáo của chính hãng, không nói về độ chính xác"; đánh dấu blog convertaudiototext là "công ty bán dịch vụ, cần đối chiếu thêm"; chỉ dùng số liệu có nguồn đọc được |
| CP5 Quy trình | Gợi ý các bước của quy trình sau họp | Giúp không bỏ sót bước (ghi chú → lọc → gán người → gửi → theo dõi) | Vẽ quy trình "lý tưởng", không giống cách nhóm thật đang làm (thật ra là gõ tay vào nhóm chat) | Sửa As-is theo đúng lời người được phỏng vấn |
| CP5–6 Problem Statement | Rút gọn, sửa câu chữ cho Problem Statement | Câu văn gọn hơn | Tự thêm số liệu không có trong kiểm chứng; giữ phạm vi rộng "tổng hợp action items" | Bỏ số liệu không có nguồn; thu hẹp vào bước xác nhận owner/deadline mục mơ hồ theo kết quả research |
| CP6 Mức can thiệp / quyết định | Hỏi nên dùng AI ở mức nào | Nêu được các mức (gợi ý, soạn nháp, tự động) | Đề xuất "xây agent tự gán owner và tự gửi task" — đi ngược bằng chứng (AI sai ~20–30% mục mơ hồ, tên sai) | Chọn mức AI soạn nháp + người xác nhận; quy tắc "không rõ owner thì để trống, không đoán"; không tự xây agent |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Problem em nhớ nhất là [Gợi ý chỗ ăn và chơi], em học được là problem phải bắt đầu từ chuyện đã xảy ra, nên khi phỏng vấn em luôn hỏi "lần gần nhất là khi nào".

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có. Ban đầu nhóm định xây công cụ AI tự trích action item và gán người. Khi em research thấy Otter, Zoom đã làm tốt bước này, nhóm thu hẹp sang bước xác nhận owner/deadline cho mục amơ hồ.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Em pitch #4, bị hỏi có được truy cập toàn bộ dữ liệu chat không. Em thấy rủi ro quyền riêng tư quá lớn nên chuyển sang ủng hộ #7.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có. Em tưởng mọi người quên ghi, nhưng thật ra ai cũng nghĩ mình nhớ rồi mỗi người nhớ một kiểu, dẫn tới 2 bạn làm trùng slide và phải họp lại 20 phút.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là metric có số thật: nhóm ghi baseline 30 phút, phỏng vấn chỉ ra 15–20 phút, và chưa ai bấm giờ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Em sẽ phỏng vấn thêm người đi làm, và nói ngay khi thấy mục 4–8 vẫn viết theo hướng "AI lọc task" dù research đã chỉ ra khoảng trống ở bước xác nhận owner.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Sau mỗi buổi họp, các việc chưa rõ người làm và hạn chót không được xác nhận, nên team làm trùng, bỏ sót và phải họp lại. Hiện note-taker tự đọc lại ghi chú, lọc việc, gán người rồi gửi vào nhóm chat, mất 15–30 phút mỗi buổi. Metric là thời gian từ lúc họp xong đến lúc gửi danh sách đã xác nhận dưới 15 phút và mọi việc gửi đi đều đúng người làm. Boundary là AI chỉ soạn nháp, không đoán người làm khi không rõ, không bịa việc và không tự gửi. Nhóm chọn mức Workflow vì AI vẫn sót hoặc sai khoảng 20–30% mục mơ hồ nên cần người kiểm tra. Quyết định là Go với pilot 2 tuần dùng công cụ có sẵn; nếu phải sửa tay hơn một nửa bản nháp thì dừng.

## 7. Tài liệu tham khảo

- Otter.ai, "My Action Items" (thông cáo báo chí): https://www.silicon.co.uk/press-release/streamline-workflows-with-my-action-items-otter-ai-can-now-keep-track-of-all-your-action-items-across-all-your-meetings
- Zoom Community, "How to improve Next Steps in Meeting summary": https://community.zoom.com/t5/Zoom-AI-Companion/How-to-improve-Next-Steps-in-Meeting-summary/m-p/154490
- ConvertAudioToText, bài phân tích trích xuất action item từ bản ghi họp: https://convertaudiototext.com/blog/action-items-from-meeting-recordings
- Phỏng vấn nhanh 3 người (Interview snapshot, mục 3 `report/team/group_report.md`)