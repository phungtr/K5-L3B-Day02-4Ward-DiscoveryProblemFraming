# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: 4Ward
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi vừa kết thúc cuộc họp dài 1 tiếng, tôi muốn tổng hợp lại danh sách công việc (action items) kèm người phụ trách, để gửi cho từng người trong team xác nhận ngay.
- Quyết định cuối: Go (Pilot phạm vi nhỏ)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phùng Quang Trà | Khi có bộ hồ sơ giải ngân online mới, CRO muốn kiểm tra đủ giấy tờ và nhập lên hệ thống nhanh, để khách không phải chờ và phàn nàn vì xử lý chậm. | CRO nhập liệu; khách hàng chờ giải ngân bị ảnh hưởng gián tiếp. | Bước 3–4: đọc, trích thông tin và nhập hệ thống, ước tính ~45/80 phút mỗi bộ (~10 bộ/tháng); ~3/10 bộ bị trả về vì thiếu/sai; chưa bấm giờ thực tế. | |
| 2 | Phùng Quang Trà | Khi đến ngày đầu tháng, tôi muốn biết tháng trước đã chi bao nhiêu và phát sinh vào đâu, để điều chỉnh chi tiêu tháng sau. | Người dùng cá nhân quản lý chi tiêu từ nhiều app ngân hàng / ví. | Bước 3–4: chép và phân loại giao dịch từ nhiều app, ước tính ~10/23 phút mỗi tháng; chỉ tổng kết xong 1/3 tháng gần đây. | |
| 3 | Phùng Quang Trà | Khi kết thúc ngày làm việc, tôi muốn biết task nào đã xong, chưa xong và sắp tới, để sáng hôm sau bắt đầu ngay mà không bỏ sót việc. | Nhân viên văn phòng nhận việc qua email / chat. | Bước 1: lục lại email/chat tìm việc phát sinh, ước tính ~15/33 phút mỗi ngày; bỏ sót ~2 việc/tuần. | |
| 4 | Nguyễn Tuấn Anh |Khi cần tìm lại một thông báo hoặc quyết định cũ trong nhóm chat, tôi muốn thấy đúng tin đó ngay, để khỏi phải cuộn hàng trăm tin nhắn |Sinh viên trong nhóm 5 người |Bước 2, cuộn chat tìm thủ công: khoảng 6 phút/lần | |
| 5 | Nguyễn Tuấn Anh |Khi chuẩn bị nộp bài lúc 22h, tôi muốn biết bài còn thiếu mục nào, để không bị trừ điểm vì sai cấu trúc |Sinh viên làm bài lab |Bước 3, tự đối chiếu từng mục bằng mắt: khoảng 12 phút/lần | |
| 6 | Nguyễn Tuấn Anh |Khi làm bài nhóm, tôi muốn biết ai đang làm phần nào và hạn bao giờ, để khỏi phải nhắn hỏi lại |Nhóm trưởng và 4 thành viên |Bước 4, nhắn hỏi từng người vì không có nơi ghi chung: khoảng 8 phút/lần | |
| 7 | Vũ Nam Khánh | Khi vừa kết thúc cuộc họp dài 1 tiếng, tôi muốn tổng hợp lại danh sách công việc (action items) kèm người phụ trách, để gửi cho từng người trong team xác nhận ngay | Bản thân, Team | Trích xuất Task + Assignee | |
| 8 | Vũ Nam Khánh | Khi cần viết tài liệu cho một API/service mới, tôi muốn có cấu trúc tài liệu nhất quán từ source/config, để không phải viết thủ công từ đầu | Backend Developer | Viết mô tả param + response mẫu | |
| 9 | Vũ Nam Khánh | Khi mentor cần theo dõi tiến độ công việc, họ muốn thấy báo cáo dạng hình ảnh/bảng tổng quan ngắn gọn, để nắm tình hình mà không phải nhắn hỏi từng người | Mentor, Team | Lọc task xong & blocker | |
| 10 | Phạm Duy Thành| Gom nhanh yêu cầu và deadline từ các nguồn (LMS, chat) để làm bài không sót việc.| Sinh viên làm bài cá nhân; bạn cùng lớp có thể bị ảnh hưởng nếu thông tin được chia sẻ không thống nhất.| Bước 2–4: tìm và đối chiếu thông tin giữa các nguồn, ước tính 10–15 phút/lần; chưa bấm giờ, cần đo ở lần làm bài tiếp theo. Thời gian chờ câu trả lời chưa tính.| |
| 11 | Phạm Duy Thành| Tổng hợp tài liệu ôn tập (slide, ghi chú) để khoanh vùng phần chưa hiểu và học đúng trọng tâm.| Sinh viên đang tự ôn tập một chủ đề có nhiều tài liệu.| Bước 3–4: ghi chú rồi đối chiếu nội dung giữa các nguồn, ước tính 20–30 phút cho một chủ đề; chưa bấm giờ, số nguồn và độ dài tài liệu có thể làm thời gian thay đổi nhiều.| |
| 12 | Phạm Duy Thành| Phân loại và xếp ưu tiên các feedback để chỉnh sửa bài hiệu quả, không bị sót lỗi.| Sinh viên viết/chỉnh sửa bài; người góp ý có thể cần biết phản hồi đã được tiếp nhận.| Bước 3–5: phân loại, gắn góp ý vào phần bài và xác định thứ tự, ước tính 15–25 phút/bộ góp ý; chưa đo trên một bộ phản hồi thật.| |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A - Quản lý & Theo dõi công việc trong team/dự án | 3, 6, 7, 8, 9 | Gom thông tin, ghi chú rải rác sau cuộc họp hoặc quá trình làm việc để tạo danh sách action items, viết docs API hoặc báo cáo tiến độ cho lead/mentor/team |
| B - Thu thập & Theo dõi thông tin cá nhân (Học tập & Chi tiêu) | 2, 10, 11 | Gom và đối chiếu thông tin từ nhiều nguồn rời rác (lịch sử ngân hàng, bài tập LMS, slide/ghi chú ôn tập) để quản lý công việc và kế hoạch cá nhân |
| C - Tìm kiếm & Tra cứu thông tin rải rác | 4, 12 | Tìm kiếm, truy xuất đúng đoạn tin nhắn/quyết định cũ trong kênh chat hoặc gom/phân loại feedback để chỉnh sửa bài |
| D - Kiểm tra cấu trúc & Nhập liệu quy trình | 1, 5 | Đọc, đối chiếu và rà soát thủ công các thông tin/hồ sơ (hồ sơ giải ngân online, checklist cấu trúc bài lab) theo đúng mẫu tiêu chuẩn |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm 75% thời gian tổng hợp Action Items sau cuộc họp (từ 30 phút xuống <8 phút) mà không bị sót việc hoặc gán nhầm người phụ trách.
├── Opportunity A: Note họp dạng văn bản thô bị lan man, lẫn lộn giữa thảo luận chung và task thực sự cần làm.
├── Opportunity B: Tên người phụ trách (Assignee) và thời hạn (Deadline) không được chốt rõ ràng trong hội thoại họp.
└── Opportunity C: Việc định dạng lại danh sách việc ra dạng bảng để gửi cho team xác nhận tốn thời gian thủ công.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Xây bot AI tự động tham gia cuộc họp để ghi chép": Đây là giải pháp công nghệ, không phải nỗi đau người dùng; bỏ để tập trung vào nhu cầu xử lý nội dung thô.
- "Tự động gửi danh sách công việc vào kênh chat ngay sau họp": Đây là tính năng/hành động giải pháp, vi phạm nguyên tắc chỉ ghi nhu cầu ở tầng Opportunity.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Candidate #7: Action items sau họp (Nam Khánh) | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 35 |
| Candidate #8: Viết tài liệu API từ source (Nam Khánh) | 5 | 5 | 4 | 4 | 5 | 3 | 4 | 30 |
| Candidate #4: Tìm tin nhắn/quyết định cũ (Tuấn Anh) | 4 | 4 | 4 | 4 | 3 | 4 | 4 | 27 |

**Candidate được chọn:** Candidate #7 — Khi vừa kết thúc cuộc họp dài 1 tiếng, tôi muốn tổng hợp lại danh sách công việc (action items) kèm người phụ trách, để gửi cho từng người trong team xác nhận ngay.

**Vì sao chọn:**

- Actor và quy trình cực kỳ cụ thể: Đối tượng chịu ảnh hưởng rõ ràng (note-taker, PM, thành viên dự án); quy trình 5 bước đo được chính xác bằng phút.
- Có baseline đo lường được: Mất 30 phút/buổi họp, tần suất 2–3 buổi/tuần, tác động trực tiếp đến tiến độ chung của team.
- Phân định rõ ranh giới AI (HITL): Bài toán phù hợp hoàn hảo để triển khai mức Workflow, trong đó AI xử lý bước trích xuất nháp và con người (Note-taker/PM) kiểm tra lại trước khi gửi, đảm bảo không bị rủi ro gán sai người/sai việc.

**Vì sao loại các candidate còn lại:**

- Candidate #8 (Viết Docs API): Mặc dù quy trình rất chuẩn hóa, nhưng nhóm phân tích thấy có đến 80% công việc có thể xử lý hoàn toàn bằng Rule/Script (ví dụ: các thư viện Swagger/OpenAPI spec tự sinh docs từ code annotation), không thực sự cần tới sự can thiệp của AI.
- Candidate #4 (Tìm quyết định cũ trong chat): Bài toán đòi hỏi quyền truy cập dữ liệu chat toàn công ty/nhóm, phạm vi quá rộng và chạm trần rủi ro về mặt Feasibility & Viability (quyền riêng tư và bảo mật dữ liệu).

**Xử lý bất đồng (nếu có):** Không

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Note-taker/PM khác cũng mất hơn 20 phút sau mỗi buổi họp 1h để lọc và tổng hợp lại action items | Value | 5 | 2 | Có |
| 2 | Bước tốn thời gian nhất là đọc lại note thô để trích xuất task và gán Assignee, không phải bước gửi tin nhắn | Value | 5 | 2 | Có |
| 3 | Thành viên trong team sẵn sàng xác nhận action items nếu nhận được dạng bảng ngắn gọn trong vòng 15 phút sau họp | Value | 4 | 3 | Có |
| 4 | Nội dung transcript/note cuộc họp cung cấp đủ ngữ cảnh để AI phân biệt được đâu là "thảo luận" và đâu là "giao việc" | Feasibility | 5 | 2 | Có |
| 5 | Người dùng dễ dàng kiểm tra, chỉnh sửa bản nháp của AI trong dưới 3 phút trước khi gửi cho team | Usability | 4 | 2 | - |
| 6 | Công ty/Nhóm cho phép đưa transcript hoặc nội dung ghi chép họp nội bộ vào công cụ AI xử lý | Viability | 5 | 1 | Có |

Giả định nhóm kiểm chứng trong buổi này: Giả định #1, #2, #4 và #6 (đây là các giả định có mức độ quan trọng cao từ 5 và bằng chứng hiện có thấp từ 1–2).

### Kiểm chứng

Cách đã dùng: Phỏng vấn 2–3 người + đối chiếu bằng chứng công khai

Interview snapshot:

| Trường | Nội dung |
|---|---|
| Người được hỏi | Trưởng nhóm bài tập lớn, năm 3, nhóm 5 người_ |
| Câu nói đáng nhớ nhất  | “Họp xong ai cũng bảo mình nhớ rồi, đến thứ Tư hỏi lại thì mỗi người nhớ một kiểu.”|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Họp nhóm tối thứ Hai, chia 6 đầu việc. Thứ Tư phát hiện 2 bạn cùng làm phần slide, không ai làm phần số liệu. Phải họp lại 20 phút để chia lại. |
| Hiện đang xử lý bằng cách nào | Tự gõ lại các đầu việc từ tin nhắn và ghi chú vào nhóm chat sau họp, không dùng công cụ nào. |
| Mất bao lâu, bao lần? | Khoảng 15–20 phút mỗi lần họp, họp 1–2 lần/tuần. Tuần trước mất thêm 20 phút vì phải họp lại. |
| Insight / opportunity rút ra | Phần tốn thời gian là gõ lại và gán người cho từng việc, không phải gửi tin. Khi owner không rõ trong buổi họp thì việc bị trùng hoặc bị bỏ. Người này đồng ý thử xác nhận qua bảng ngắn trong 15 phút sau họp (cam kết cho giả định #3). |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn nhanh | 3 người (2 gặp vấn đề) | 2/3 người mất 15–20 phút sau mỗi buổi họp để gõ lại việc và gán người; 1 người từng phải họp lại 20 phút vì 2 bạn làm trùng phần việc (giả định #1, #2). 2/3 người đồng ý thử xác nhận qua bảng ngắn trong 15 phút sau họp (giả định #3) | 1/3 người chỉ họp nhóm 3 người, nhớ hết việc nên không thấy khó; vấn đề có thể chỉ rõ khi nhóm từ 5 người trở lên (giả định #1). Chưa ai trả lời được câu hỏi về việc đưa transcript vào AI (giả định #6 chưa có bằng chứng) |
| Thảo luận của người dùng trên cộng đồng Zoom (research) | 1 bài | Một người dùng cho biết phần "next steps" của bản tóm tắt AI sai tên, thiếu nhiều action item và khó chuyển thành task (giả định #2, #4) | Người này vẫn đánh giá phần tóm tắt tổng thể khá tốt, nên pain tập trung ở bước owner/action item, không phải toàn bộ ghi chú |
| Bài đánh giá độc lập về trích xuất action item (research) | 1 bài | Công cụ bỏ sót hoặc làm sai lệch khoảng 20–30% trường hợp mơ hồ (không rõ owner, không rõ hạn), nên vẫn cần người xem lại 2–3 phút (giả định #4, #5) | Với cam kết nói rõ ("A làm B trước thứ Sáu") công cụ bắt gần như chính xác (~70–80% tổng thể), nên bước "trích xuất" không phải khoảng trống lớn |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**  Trước đây problem là "mất >20 phút lọc và tổng hợp action items". Sau research, bước trích xuất đã được nhiều công cụ giải khá tốt cho cam kết nói rõ, nên nhóm thu hẹp bottleneck vào **bước xác nhận owner/deadline cho các mục mơ hồ trong 15 phút sau họp** và đánh dấu rõ mục thiếu owner thay vì để hệ thống tự đoán.

### Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Otter.ai — My Action Items | https://www.silicon.co.uk/press-release/streamline-workflows-with-my-action-items-otter-ai-can-now-keep-track-of-all-your-action-items-across-all-your-meetings | Tự nhận diện action item từ nhiều cuộc họp, gom về một chỗ để xem, giao lại, tick hoàn thành | Có link về đúng thời điểm trong cuộc họp, có email nhắc hàng tuần | Là thông cáo của chính hãng nên không nói về độ chính xác; chưa thấy bước xác nhận owner với cả team sau họp | Phần trích xuất đã có công cụ làm; nhóm không nên tự xây lại mà tập trung vào xác nhận owner |
| Zoom AI Companion — mục Next steps | https://community.zoom.com/t5/Zoom-AI-Companion/How-to-improve-Next-Steps-in-Meeting-summary/m-p/154490 | Tạo bản tóm tắt và danh sách next steps ngay trong cuộc họp Zoom | Có sẵn trong Zoom, không cần cài thêm | Người dùng báo sai tên, thiếu action item, copy ra bảng khó dùng; chưa tự biến thành task | Cần bước người kiểm tra và quy tắc "không rõ owner thì để trống, không đoán" |
| Pattern: trích xuất AI + bước kiểm tra của người (bài phân tích) | https://convertaudiototext.com/blog/action-items-from-meeting-recordings | Cả quy trình: trích xuất, kiểm tra 2–3 phút, đưa vào công cụ team đang dùng | Có số liệu về độ bắt cam kết, gợi ý triển khai theo giai đoạn (chạy song song trước, tin dần sau) | Là blog của một công ty bán dịch vụ phiên âm nên cần đối chiếu thêm; nêu rủi ro AI gán việc cho người không dự họp | Dùng làm cơ sở cho Boundary và HITL: AI chỉ soạn nháp, người xác nhận trước khi gửi |

**Kết luận research:**

```text
Phần lớn bước trích xuất action item đã có công cụ làm được (Otter, Zoom AI Companion). Không có lý do tự xây agent.
Hướng hợp lý: Công cụ có sẵn soạn nháp action items → Rule đánh dấu mục thiếu owner/deadline → người xác nhận trong 15 phút → gửi team.
```

Đây là điểm khác lớn nhất so với bản nháp ban đầu của nhóm: ban đầu nhóm định "xây một công cụ AI tự trích action item và gán assignee", nhưng research cho thấy phần trích xuất đã được giải khá tốt, còn khoảng trống nằm ở bước xác nhận owner/deadline cho các mục mơ hồ.

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 5 bước, 30 phút, 5/5 bước thủ công

[1] Mở file note thô: 2'
[2] Đọc lại & phân loại việc: 12'
[3] Lọc Task + Assignee: 8' ← BOTTLENECK
[4] Định dạng dạng bảng: 5'
[5] Gửi lên Slack/Email: 3'
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Note-taker | File ghi chép thô trong cuộc họp | File note thô được mở | 2 phút / 2–3 họp/tuần | Dữ liệu lan man, lộn xộn |
| 2 | Note-taker | File note thô | Các đoạn văn bản có chứa việc | 12 phút / 2–3 họp/tuần | Đọc rà soát lại toàn bộ |
| 3 | Note-taker | Các đoạn văn bản chứa việc | Danh sách Task + tên Assignee | 8 phút / 2–3 họp/tuần | Bottleneck: Dễ sót việc hoặc gán nhầm |
| 4 | Note-taker | Danh sách Task + Assignee | Bảng tổng hợp công việc | 5 phút / 2–3 họp/tuần | Định dạng thủ công |
| 5 | Note-taker | Bảng tổng hợp công việc | Tin nhắn gửi lên kênh chat | 3 phút / 2–3 họp/tuần | Copy-paste và gửi team |

**Bottleneck chính:** Bước 2 và 3 (Đọc lại note thô để trích xuất Task và gán đúng người phụ trách) mất 20/30 phút vì cuộc họp thảo luận lan man, không chốt rõ ràng từ đầu.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — 4 bước, 7 phút, 2/4 bước thủ công

[1] Dán note thô vào công cụ: 1'        ← CON NGƯỜI
[2] AI trích xuất nháp bảng task: 1'    ← AI (Rule / Prompt)
[3] Note-taker kiểm tra & chỉnh sửa: 3' ← CON NGƯỜI (HITL Boundary)
[4] Gửi danh sách lên Slack: 2'         ← CON NGƯỜI

BOUNDARY: AI không tự động gửi tin nhắn, không tự nghĩ ra task không có trong note thô.
PHƯƠNG ÁN QUAY VỀ: AI sai hoặc nháp lộn xộn → Note-taker bỏ nháp, tự lọc tay theo cách cũ.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 4 | Bỏ khâu định dạng và phân loại thủ công |
| Tổng thời gian | 30 phút | khoảng 7 phút | Giảm hơn 70% thời gian sau họp |
| Số bước thủ công | 5/5 | 3/4 | AI làm nháp, con người duyệt và gửi |
| Bottleneck chính | Đọc lại note thô & gán người làm | Note-taker kiểm tra & sửa nháp | Chuyển thành bước kiểm soát chất lượng |
| Rủi ro mới phát sinh | Không có | AI đoán sai người làm hoặc lọc thiếu task | Xử lý bằng kiểm tra người duyệt (HITL) |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Note-taker / Người chủ trì cuộc họp team |
| **Quy trình** | Mở file note thô sau họp → Lọc công việc và người làm thủ công → Định dạng lại bảng → Gửi lên Slack cho team |
| **Bottleneck** | Khâu đọc lại ghi chú thô để lọc công việc và gán tên người phụ trách (Assignee), mất khoảng 20 phút |
| **Impact** | Tốn 30 phút sau mỗi buổi họp (2–3 buổi/tuần); gửi danh sách trễ khiến team dễ quên việc hoặc làm chồng chéo |
| **Success Metric** (baseline → target, cách đo) | Thời gian tổng hợp giảm từ 30 phút xuống <8 phút/buổi họp, đo bằng Note-taker tự bấm giờ 4 buổi pilot |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI chỉ được tạo bản nháp bảng task, không được tự động gửi tin nhắn và bắt buộc có con người (Note-taker) duyệt lại trước khi gửi |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ mơ hồ Cao x Độ phức tạp Trung Bình

Vì sao:
- Độ mơ hồ Cao: Mỗi cuộc họp mọi người nói chuyện một kiểu, note thô viết mỗi lúc một khác. AI phải tự hiểu ngữ cảnh để lọc ra đâu là "việc cần làm" và ai phụ trách, chứ không có công thức đúng/sai cố định.
- Độ phức tạp Trung Bình: Luồng xử lý đi thẳng từ trên xuống dưới (Nhập note thô -> AI lọc task -> Định dạng bảng -> Người duyệt), dữ liệu hoàn toàn là chữ (text) nên không bị rẽ nhánh hay tính toán quá phức tạp.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Dùng template Notion/Docs chuẩn, bắt buộc ghi rõ Task + Người làm ngay trong lúc họp | Họp nhóm nhỏ (2–3 người), mọi người tự giác điền thẳng vào file trong lúc nói chuyện | Mọi người hay quên điền, lúc họp mải thảo luận nên note vẫn bị lộn xộn | Không chọn |
| **Rule** | Viết script tự tạo công việc khi gõ đúng cú pháp cố định (ví dụ: @tên + task) | Mọi người chịu gõ đúng định dạng quy định sẵn trong file note | Rất gượng ép, trong lúc họp nói nhanh nên không ai rảnh gõ đúng cú pháp | Không chọn |
| **Workflow** | Nhập note thô -> AI tự lọc task + người làm -> Hiện bản nháp cho Note-taker sửa -> Gửi Slack | Khi muốn giữ cách nói/ghi chép tự nhiên, nhưng vẫn cần AI lọc nháp và người duyệt lại cho chắc | AI có thể bắt thiếu task hoặc đoán sai người làm nếu note thô quá tắt | Chọn |
| **Agent** | Cho AI tự vào họp ghi âm, tự đoán việc, tự tạo task trên Jira và tự gửi tin nhắn cho từng người | Khi quy trình đã quá chuẩn hóa, không cần con người kiểm tra lại | AI tự gửi linh tinh làm trôi tin nhắn, gán sai việc gây cãi nhau trong team, chi phí cao | Không chọn |

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:**
- No AI (Template) không giải quyết được gốc rễ vấn đề: lúc họp mọi người chỉ tập trung trao đổi chứ không ai rảnh vừa nói vừa format lại chữ cho đẹp.
- Rule (Script) thì quá cứng nhắc: bắt người dùng phải gõ đúng cú pháp @tên + làm việc X thì script mới hiểu, thực tế không ai làm theo được khi họp nhanh.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Bảng danh sách nháp gồm: Tên công việc (Action Item) + Người phụ trách (Assignee) + Hạn chót (Deadline) được lọc ra từ ghi chú thô. |
| **Judgment** — con người cân nhắc, quyết định gì? | Note-taker kiểm tra xem AI có lọc thiếu việc nào không, tên người phụ trách có bị gán nhầm không trước khi bấm gửi. |
| **Action** — hành động cuối cùng là gì, ai làm? | Note-taker bấm xác nhận gửi bảng danh sách công việc đã duyệt lên kênh chat Slack/Discord cho cả team. |
| **Outcome** — đo kết quả bằng gì? | Mất dưới 8 phút để tổng hợp (so với 30 phút cũ) và 100% việc gửi đi đều có đúng người nhận task. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Văn bản ghi chú thô (hoặc transcript) của buổi họp. Có sẵn ngay sau khi họp xong. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Xem Note-taker hay sửa lại/xóa bỏ những dòng nào trên bản nháp để chỉnh lại prompt lọc task chuẩn hơn. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**?
    - Trả lời: Người dùng muốn được hỗ trợ (augment).
    - Bằng chứng: Vì lúc họp mọi người hay nói tắt hoặc đùa vui, Note-taker rất sợ AI đoán sai người làm hoặc gán nhầm việc linh tinh. Bắt buộc phải để Note-taker nhìn qua bản nháp rồi tự tay bấm "Gửi", chứ không ai dám để AI tự động gửi thẳng vào Slack của team.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:
    - Bỏ sót tệ hơn nhiều.
    - Nếu AI báo nhầm (tự bịa ra 1 việc thừa), Note-taker nhìn thấy là bấm xóa cái rẹt trong 2 giây. Nhưng nếu AI bỏ sót (bỏ quên 1 task quan trọng), team sẽ bị trễ tiến độ mà không ai hay biết. Cách thiết kế là viết prompt dặn AI "thà bắt nhầm còn hơn bỏ sót" (cứ gom hết các việc có khả năng làm), sau đó để Note-taker tự tay tích chọn và xóa bớt những ý thừa trên màn hình duyệt.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Note-taker / Người chủ trì cuộc họp team |
| **Quy trình** | Mở note thô sau họp -> Dán vào công cụ AI lọc task -> Kiểm tra & sửa bản nháp -> Gửi danh sách lên Slack |
| **Bottleneck** | Khâu đọc lại ghi chú thô để lọc công việc và gán tên người phụ trách (Assignee) |
| **Impact** | Tốn 30 phút sau mỗi buổi họp (2–3 buổi/tuần); trễ gửi danh sách khiến team quên việc hoặc làm chồng chéo |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian tổng hợp giảm từ 30 phút xuống <8 phút; (2) 100% action items gửi đi có đúng tên người làm |
| **Boundary** | AI chỉ được tạo bản nháp, không tự động gửi tin nhắn và không tự nghĩ ra task không có trong note thô |
| **AI intervention point** | Ngay sau khi họp xong (sau khi Note-taker dán ghi chú thô vào) |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI đoán sai người làm hoặc lọc thiếu việc -> Note-taker phải tự nhìn qua và sửa trước khi bấm gửi |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Chỉ đo thời gian tổng hợp (<8 phút) | Thêm chỉ số: 100% việc gửi đi có đúng người làm | Nhanh hơn mà gửi sai tên người làm thì cũng công cốc, nên cần đo thêm độ chuẩn xác |
| Boundary | AI trợ giúp tóm tắt nội dung cuộc họp | Thêm cấm AI tự động gửi tin nhắn và cấm tự bịa task | Đặt ranh giới rõ ràng để Note-taker không sợ AI làm bậy |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bịa task | Mọi công việc liệt kê ra đều có thông tin trong note thô | AI tự sáng tác thêm công việc không ai nói trong họp |
| 2 | Đúng người phụ trách | Tên Assignee khớp chính xác với người được giao trong note | Gán nhầm việc của người này sang cho người khác |
| 3 | Đúng định dạng bảng | Ra đúng dạng bảng 3 cột: Task, Assignee,  Deadline | Ra chữ lan man thành đoạn văn dài khó nhìn |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Thấp | Note-taker nào họp xong cũng ngán khâu đọc lại note thô để gom việc. Nhu cầu rút ngắn thời gian sau họp là có thật. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Giao diện hiện ra dạng bảng 3 cột (Task, Assignee, Deadline), Note-taker chỉ cần nhìn qua, bấm sửa chữ hoặc xóa dòng rất dễ dàng. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Input chỉ là văn bản note thô dán vào, dùng API của các model phổ biến (như ChatGPT/Claude) viết prompt lọc task là chạy được ngay. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | Một số cuộc họp nội bộ có thông tin nhạy cảm nên công ty ngại dán vào AI bên ngoài; chi phí dùng API thì rất rẻ không đáng lo. |

### 8.2. Kết luận

**Quyết định:** Go (Pilot phạm vi nhỏ)

**Lý do:** Không có rủi ro nào ở mức Cao. Rủi ro duy nhất là Viability (bảo mật thông tin họp) có thể giải quyết bằng cách dặn người dùng xóa bớt các thông tin quá nhạy cảm trước khi dán vào AI.

**Nếu Go — pilot nhỏ nhất:** Nhóm chưa cần viết code/app gì phức tạp. Tạo sẵn 1 khung Prompt chuẩn. Mỗi lần họp nhóm xong, Note-taker dán note thô + Prompt đó vào AI (ChatGPT/Claude) để lấy bản nháp bảng task, dùng thử trong 2 tuần (khoảng 4–6 buổi họp).

**Ngưỡng dừng**: Nếu sau 2 tuần dùng thử mà Note-taker vẫn phải ngồi gõ lại tay hơn 50% nội dung bảng nháp -> Dừng lại, quay về dùng template Google Docs thủ công như cũ.

---

## 9. Hạn chế và hướng tiếp theo

### 9.1. Hạn chế

| # | Hạn chế | Ảnh hưởng tới kết luận |
|---:|---|---|
| 1 | **Mẫu kiểm chứng nhỏ:** chỉ phỏng vấn 3 người, đều là sinh viên làm bài nhóm; chưa phỏng vấn note-taker/PM trong môi trường công ty | Số liệu baseline (15–20 phút, 30 phút) và mức độ pain chưa đại diện cho team đi làm; vấn đề có thể chỉ rõ ở nhóm từ 5 người trở lên |
| 2 | **Baseline chưa bấm giờ thực tế:** quy trình hiện tại 30 phút là ước tính, trong khi phỏng vấn cho thấy 15–20 phút | Mục tiêu "giảm từ 30 xuống <8 phút" có thể đang phóng đại mức cải thiện; cần đo lại baseline trước pilot |
| 3 | **Giả định #6 (được phép đưa nội dung họp vào AI) chưa có bằng chứng:** mức quan trọng 5/5 nhưng bằng chứng 1/5, chưa ai trả lời được trong phỏng vấn | Rủi ro Viability có thể cao hơn mức "Trung bình" đã đánh giá; cách "dặn người dùng tự xoá thông tin nhạy cảm" phụ thuộc vào ý thức từng người |
| 4 | **Giả định #5 (sửa nháp dưới 3 phút) chưa kiểm chứng:** thời gian 7 phút của quy trình tương lai là kỳ vọng | Chưa biết note-taker thực sự mất bao lâu để kiểm tra, đặc biệt với các mục mơ hồ |
| 5 | **Mục 4–8 chưa cập nhật hết theo kết quả research ở mục 3:** research đã thu hẹp bottleneck vào bước xác nhận owner/deadline cho mục mơ hồ, nhưng quy trình tương lai, Problem Statement v1 và pilot vẫn đặt trọng tâm ở bước "AI lọc task" | Phần giải pháp còn lệch so với bằng chứng: trích xuất cam kết rõ ràng đã có công cụ làm khá tốt (~70–80%), khoảng trống thật là mục thiếu owner/deadline |
| 6 | **Nguồn research còn mỏng và có thiên lệch:** 1 thông cáo của chính hãng (Otter), 1 bài thảo luận cộng đồng (Zoom), 1 blog của công ty bán dịch vụ phiên âm | Các con số độ chính xác (~70–80%, sót 20–30% mục mơ hồ) chưa được đối chiếu với nguồn độc lập |
| 7 | **Metric "100% action items có đúng người làm" khó đạt và khó đo:** chưa định nghĩa cách kiểm tra "đúng" (so với ai xác nhận, khi nào) | Pilot có thể không kết luận được nếu không có cách đo rõ ràng |

### 9.2. Hướng tiếp theo

1. **Đo lại baseline trước pilot:** note-taker bấm giờ 2 buổi họp theo cách cũ; ghi lại số action item, số mục thiếu owner/deadline, số lần làm trùng/bỏ sót trong tuần.
2. **Đồng bộ lại mục 4–7 với kết quả research:** đưa bước "Rule đánh dấu mục thiếu owner/deadline" vào quy trình tương lai; quy tắc "không rõ owner thì để trống, không đoán"; thêm metric "% mục mơ hồ được xác nhận owner/deadline trong 15 phút sau họp".
3. **Ưu tiên thử công cụ có sẵn trước khi tự viết prompt:** so sánh Zoom AI Companion / Otter với cách dán note vào ChatGPT/Claude trên cùng 1–2 buổi họp, xem cách nào ít phải sửa hơn.
4. **Kiểm chứng giả định #6 trước khi pilot:** hỏi nhóm/trưởng nhóm (hoặc quy định công ty nếu có) xem có được đưa nội dung họp vào công cụ AI không, dữ liệu nào phải loại ra.
5. **Kiểm chứng giả định #5 trong pilot:** ghi thời gian note-taker kiểm tra và sửa bản nháp, đếm số dòng bị sửa/xoá/thêm mỗi buổi.
6. **Mở rộng phỏng vấn:** thêm 3–5 người, gồm cả người đi làm và nhóm từ 5 người trở lên, để xác nhận pain có tồn tại ngoài bối cảnh bài tập nhóm.
7. **Định nghĩa rõ cách đo độ chính xác:** sau họp 2–3 ngày, hỏi lại từng thành viên xem việc họ nhận có đúng không; đếm số lần làm trùng/bỏ sót so với baseline.

---

## 10. Tài liệu tham khảo

**Nguồn research giải pháp đã có (mục 3):**

- Otter.ai, "My Action Items" (thông cáo báo chí): https://www.silicon.co.uk/press-release/streamline-workflows-with-my-action-items-otter-ai-can-now-keep-track-of-all-your-action-items-across-all-your-meetings
- Zoom Community, "How to improve Next Steps in Meeting summary": https://community.zoom.com/t5/Zoom-AI-Companion/How-to-improve-Next-Steps-in-Meeting-summary/m-p/154490
- ConvertAudioToText, bài phân tích về trích xuất action item từ bản ghi họp: https://convertaudiototext.com/blog/action-items-from-meeting-recordings

**Phương pháp và khung phân tích đã dùng:**

- Teresa Torres, *Continuous Discovery Habits* (2021): Opportunity Solution Tree (mục 2.3). https://www.producttalk.org/opportunity-solution-tree/
- David J. Bland & Alexander Osterwalder, *Testing Business Ideas* (2019): Assumption Mapping (mục 3).
- Marty Cagan (SVPG), "The Four Big Risks": Value, Usability, Feasibility, Viability (mục 8.1). https://www.svpg.com/four-big-risks/
- Ajay Agrawal, Joshua Gans & Avi Goldfarb, "A Simple Tool to Start Making Decisions with the Help of AI", Harvard Business Review (2018): AI Canvas (mục 6.3). https://hbr.org/2018/04/a-simple-tool-to-start-making-decisions-with-the-help-of-ai
- Google PAIR, *People + AI Guidebook*: augment vs automate, các kiểu lỗi của AI (mục 6.4). https://pair.withgoogle.com/guidebook/