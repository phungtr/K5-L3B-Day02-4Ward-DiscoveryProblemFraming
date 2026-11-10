# Báo cáo cá nhân — 2A202604089_NguyenTuanAnh

## 1. Thông tin học viên

- Họ tên: Nguyễn Tuấn Anh
- MSSV: 2A202604089
- Email trường (không bắt buộc, repo có thể để public):26ai.anhnt14@vinuni.edu.vn
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
| Pitch Problem Card | [Bạn có pitch không? Nếu có: pitch problem gì, trong bao lâu] | [Problem của bạn có được giữ lại/gộp vào cluster "action items sau họp" không] |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: [ví dụ: "Bạn đã gặp vấn đề này lần gần nhất khi nào, mất bao lâu?" / "Đây là vấn đề hay là giải pháp?"] | [Nhóm/bạn đó đã sửa gì sau câu hỏi] |
| Nhận phản biện | Câu hỏi tôi nhận được: [ví dụ: "Bước trích xuất action item đã có công cụ làm rồi, vậy khoảng trống thật nằm ở đâu?"] | Tôi đã sửa gì: thu hẹp problem từ "mất >20 phút lọc và tổng hợp action items" xuống **bước xác nhận owner/deadline cho các mục mơ hồ trong 15 phút sau họp** |
| Gom cluster / cây OST | [Bạn có góp ý khi gom cluster không] | [...] |
| Chọn candidate problem | [Bạn bỏ phiếu/ủng hộ problem nào, lý do] | [...] |
| Kiểm chứng / research | Phỏng vấn 3 người (trưởng nhóm BTL năm 3 nhóm 5 người là người chính), làm Interview snapshot; lập bảng tổng hợp tín hiệu xác nhận/phản bác cho giả định #1–#4, #6; research 3 giải pháp đã có (Otter.ai My Action Items, Zoom AI Companion Next steps, pattern AI trích xuất + người kiểm tra) | Phát hiện bước trích xuất đã được công cụ có sẵn làm khá tốt với cam kết nói rõ (~70–80%), khoảng trống nằm ở mục mơ hồ (thiếu owner/deadline) → nhóm **thu hẹp problem** và chốt hướng "không tự xây agent". Cũng chỉ ra giả định #6 (được phép đưa transcript vào AI) vẫn chưa có bằng chứng |
| Quy trình nhóm | [Bạn có góp vào bản vẽ quy trình As-is/To-be không] | Interview snapshot cung cấp chi tiết quy trình hiện tại: gõ lại việc từ tin nhắn/ghi chú vào nhóm chat, 15–20 phút/lần, 1–2 lần/tuần |
| Problem Statement | [Bạn có viết/sửa câu nào không] | Số liệu "15–20 phút", "họp lại 20 phút vì làm trùng việc" từ phỏng vấn được dùng làm bằng chứng cho Problem Statement |
| Mức can thiệp AI | [...] | Bài review độc lập (AI sót/sai ~20–30% mục mơ hồ) là cơ sở để nhóm chọn mức "AI soạn nháp, người xác nhận trước khi gửi" |
| Quyết định | [...] | Kết luận research: dùng công cụ có sẵn + rule đánh dấu mục thiếu owner/deadline + người xác nhận trong 15 phút, không xây agent |

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

## 6. Reflection (CP7): GỢI Ý Ý TƯỞNG, BẠN TỰ VIẾT

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Nhớ lại 1 problem của nhóm khác làm bạn ấn tượng: vì sao (cụ thể, có số liệu, hay vì nó giống vấn đề của mình?).
- Có problem nào bạn thấy là "giải pháp đội lốt vấn đề" không?
- Bạn rút ra gì để áp vào problem của nhóm mình (ví dụ: phải có "lần gần nhất xảy ra").

**6.2. Nhóm có lúc nào bị "solution-first" không?**
- Gợi ý từ bài nhóm: ban đầu có ai nghĩ tới "làm agent/bot AI tự tổng hợp và giao việc" trước khi kiểm chứng không?
- Thời điểm nhận ra: khi research thấy Otter/Zoom đã làm bước trích xuất → làm lại thì vô ích.
- Nhóm xử lý: quay lại hỏi "bước nào thật sự tốn thời gian/gây lỗi?" → ra bước xác nhận owner.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.** *(bắt buộc có ví dụ)*
- Gợi ý từ bài: bạn từng nghĩ vấn đề là "lọc và tổng hợp mất >20 phút"; sau khi bị hỏi / sau research, bạn đổi sang "xác nhận owner/deadline mục mơ hồ".
- Hoặc chiều ngược lại: bạn mang kết quả research về và **phản biện làm nhóm đổi ý** (thu hẹp problem, bỏ ý xây agent). Kể ai nói gì, bạn đưa bằng chứng gì.
- Hoặc: 1 người phỏng vấn (nhóm 3 người) nói không thấy khó → bạn nhận ra vấn đề có thể chỉ rõ ở nhóm ≥5 người.

**6.4. Kết quả kiểm chứng có làm tôi bất ngờ không?**
- Câu nói "Họp xong ai cũng bảo mình nhớ rồi, đến thứ Tư hỏi lại thì mỗi người nhớ một kiểu."
- Bất ngờ vì vấn đề không phải "quên ghi" mà là 2 bạn làm trùng slide, không ai làm số liệu → mất thêm 20 phút họp lại.
- Bất ngờ vì công cụ AI có sẵn đã khá tốt (~70–80%), cái khó nằm ở mục mơ hồ.
- Hoặc: không ai trả lời được chuyện có được đưa transcript vào AI không.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
- Gợi ý: khó thu hẹp mà không mất ý nghĩa; khó tách "vấn đề" khỏi "giải pháp"; khó có số liệu thật khi chỉ phỏng vấn 3 người; khó viết metric đo được (ví dụ "% action item có owner rõ trong 15 phút sau họp").

**6.6. Nếu làm lại, tôi sẽ đổi gì? Phản biện nhóm mạnh hơn ở điểm nào?**
- Phỏng vấn nhiều người hơn, đặc biệt nhóm ≥5 người và người làm việc ở công ty (không chỉ sinh viên).
- Kiểm chứng giả định #6 (quyền đưa transcript vào AI) sớm hơn, vì nó quan trọng 5/5 mà bằng chứng 1/5.
- Kiểm chứng giả định #5 (sửa nháp < 3 phút) bằng thử thật trên 1 buổi họp.
- Tránh tin số liệu từ blog của công ty bán dịch vụ.

**6.7. Hiểu bài (5–8 câu, không nhìn tài liệu)**

- **Problem:** sau mỗi buổi họp nhóm (≥5 người), các mục việc mơ hồ không được xác nhận owner/deadline → làm trùng, bỏ sót, phải họp lại.
- **Quy trình:** họp → có note/transcript → công cụ có sẵn soạn nháp action items → rule đánh dấu mục thiếu owner/deadline → người ghi chú xác nhận với team trong 15 phút → gửi lên nhóm chat.
- **Metric:** thời gian từ lúc kết thúc họp tới lúc gửi danh sách đã xác nhận (≤15 phút); % mục có owner rõ; số lần làm trùng/họp lại.
- **Boundary:** AI không tự đoán owner, không tự gửi; chỉ dùng khi nhóm cho phép đưa nội dung họp vào AI.
- **Mức can thiệp AI:** AI soạn nháp, người xác nhận trước khi gửi (human-in-the-loop).
- **Quyết định:** không tự xây agent; dùng công cụ có sẵn + rule + bước xác nhận của người.

---

## 7. Tài liệu tham khảo

- Otter.ai, "My Action Items" (thông cáo báo chí): https://www.silicon.co.uk/press-release/streamline-workflows-with-my-action-items-otter-ai-can-now-keep-track-of-all-your-action-items-across-all-your-meetings
- Zoom Community, "How to improve Next Steps in Meeting summary": https://community.zoom.com/t5/Zoom-AI-Companion/How-to-improve-Next-Steps-in-Meeting-summary/m-p/154490
- ConvertAudioToText, bài phân tích trích xuất action item từ bản ghi họp: https://convertaudiototext.com/blog/action-items-from-meeting-recordings
- Phỏng vấn nhanh 3 người (Interview snapshot, mục 3 `report/team/group_report.md`)
