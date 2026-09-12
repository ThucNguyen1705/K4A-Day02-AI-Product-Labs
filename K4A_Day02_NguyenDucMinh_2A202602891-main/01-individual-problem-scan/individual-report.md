# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Minh
- Mã học viên: 2A202602891
- Vai trò / bối cảnh: Sinh viên năm 3 ngành Công nghệ Thông tin, kiêm Trưởng nhóm đồ án môn học
- Công việc hằng tuần:
  * Theo dõi thông báo bài tập, lịch nộp lab và deadline từ giảng viên qua Canvas, Discord, Email trường và Zalo nhóm.
  * Họp nhóm đồ án 1–2 lần/tuần, phân chia task và theo dõi tiến độ thực hiện bài tập lớn.
  * Lập trình backend, chạy thử nghiệm kiểm thử (testing), đọc log và debug lỗi kỹ thuật khi phát sinh.
  * Soạn thảo và chuẩn hóa định dạng báo cáo tiến độ, slide thuyết trình và tài liệu kỹ thuật môn học.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | **Lặp lại** | Thu thập, trích xuất hạn chót (deadline) và yêu cầu nộp bài từ nhiều kênh phân tán (LMS Canvas, Email trường, Discord môn học, Zalo lớp) | Sinh viên, Trưởng nhóm | Mất **20–30 phút mỗi ngày** check 4 nền tảng; từng có 2 lần suýt nộp muộn bài tập lab do giảng viên đổi hạn trên Discord mà không báo trên LMS. |
| 2 | **Tốn thời gian** | Kiểm tra thủ công checklist cấu trúc, định dạng và chuẩn trích dẫn báo cáo đồ án trước khi nộp | Sinh viên làm đồ án, Giảng viên/TA chấm bài | Mất **60–90 phút mỗi báo cáo** để rà soát font chữ, lề, mục lục, bảng biểu và trích dẫn IEEE; 1 nhóm nộp 3–4 báo cáo/học kỳ. |
| 3 | **Lặp lại** | Phân loại và trả lời các thắc mắc lặp đi lặp lại của sinh viên về quy chế, đề bài, link nộp bài trên kênh thảo luận chung | Trợ giảng (TA), Cán bộ lớp, Sinh viên | TA mất **45–60 phút/ngày** gõ lại cùng câu trả lời; 70% câu hỏi tuần thi cử trùng lặp về cùng 4-5 vấn đề quy chế/format nộp. |
| 4 | **Tốn thời gian** | Đọc và gom cụm hàng chục log lỗi/crash report từ server backend để tìm nguyên nhân gốc (root cause) khi test hệ thống đồ án | Sinh viên dev đồ án, Backend Dev | Mất **30–45 phút mỗi đợt test hệ thống** để lọc qua hàng trăm dòng log rác, tìm stack trace chính; thường hoang mang khi nhiều bug văng ra cùng lúc. |
| 5 | **AI có thể tốt hơn** | Tóm tắt các quyết định quan trọng và danh sách công việc (Action Items) sau buổi họp nhóm đồ án kéo dài 1 tiếng | Trưởng nhóm, thành viên nhóm đồ án | Mất **30 phút sau mỗi buổi họp** để đọc lại ghi chú nháp và gõ lại to-do list gửi vào nhóm; khoảng 20% công việc bị sót người phụ trách. |
| 6 | **AI có thể tốt hơn** | Viết tóm tắt Release Notes / Changelog từ danh sách Git Commit và Pull Request trước khi demo bài tập lớn | Tech Lead nhóm, Giảng viên chấm code | Mất **40 phút mỗi sprint** để đọc qua 25-30 commit messages rời rạc và viết lại thành bản cập nhật tính năng mạch lạc. |
| 7 | **Pain từ người khác** | Giảng viên/TA phàn nàn vì sinh viên nộp bài sai cấu trúc thư mục, thiếu file README và sai tên file quy định | Giảng viên, TA, Sinh viên bị trừ điểm | Mất **3–5 phút cho mỗi bài nộp** chỉ để sửa lại tên file hoặc nhắc nộp lại; có khoảng 15% sinh viên từng bị trừ điểm oan vì lỗi format nộp. |
| 8 | **Tốn thời gian** | Tìm kiếm lại các đoạn code mẫu, giải thích thuật toán hoặc công thức trong slide bài giảng tiếng Anh dài 80–100 trang | Sinh viên ôn thi | Mất **15–20 phút mỗi lần tìm kiếm** do tài liệu dạng PDF scan không search text tốt, phải lướt thủ công qua từng slide. |
| 9 | **Pain từ người khác** | Thành viên trong nhóm đồ án không hiểu rõ mô tả task (User Story/Issue) dẫn đến code sai yêu cầu của bạn khác | Các thành viên trong nhóm đồ án | Mất thêm **1–2 ngày code lại** vì task viết quá sơ sài; nhóm phải họp lại 2 lần/tuần để giải thích lại yêu cầu chéo nhau. |
| 10 | **Lặp lại** | Viết báo cáo cập nhật tiến độ công việc hàng tuần (Weekly Standup/Update) cho môn Project | Sinh viên, Trưởng nhóm, Giảng viên hướng dẫn | Mất **20 phút mỗi sáng thứ Hai** để nhớ lại tuần qua mình đã làm task nào trên GitHub/Jira và gõ vào biểu mẫu báo cáo. |

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: 
  ```text
  Tôi là sinh viên năm 3 ngành CNTT kiêm trưởng nhóm đồ án môn học.
  Công việc hằng tuần gồm: theo dõi deadline bài tập, lập trình backend đồ án, họp nhóm, soạn báo cáo nộp bài.
  Tôi đã tự quan sát và nghĩ ra 3 vấn đề ban đầu:
  1. Mỗi ngày mất 25–30 phút check thủ công 4 kênh (Canvas, Discord, Gmail, Zalo) để lọc deadline bài nộp.
  2. Mất 45–60 phút/ngày gõ lại cùng câu trả lời cho các câu hỏi FAQ lặp lại về quy chế môn học và link nộp.
  3. Mất 30 phút sau mỗi buổi họp nhóm để đọc lại ghi chú nháp và gõ lại to-do list gửi vào nhóm.
  Hãy gợi ý thêm các vấn đề thường gặp theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác (đặc biệt trong khâu kiểm thử/debug code và khâu chuẩn bị nộp bài đồ án). Với mỗi gợi ý, ghi rõ actor, workflow sơ bộ và số liệu đo lường cụ thể.
  ```
- Ý dùng được: 
  + **Đối với bài toán Đồng bộ Deadline đa kênh (Problem #1 - Top 1):** AI gợi ý bóc tách điểm nghẽn thực sự không chỉ là "mở nhiều ứng dụng", mà cốt lõi là bước dùng NLP xử lý ngôn ngữ tự nhiên để trích xuất ngày giờ từ các câu diễn đạt đời thường ("thứ 6 tuần sau nộp", "trước buổi học tới") và chuẩn hóa thành dữ liệu JSON có cấu trúc để tự động đồng bộ vào Google Calendar/Notion.
  + **Gợi ý kiểm tra định dạng báo cáo đồ án:** Sinh viên mất 60–90 phút dò từng trang đối chiếu rubric (đã đưa vào bảng thành **Problem #2** và chọn vào **Top 2**).
  + **Gợi ý phân tích log lỗi backend:** Lập trình viên mất 30–45 phút đọc lọc log rác và gom cụm stack trace lỗi khi test hệ thống (đã đưa vào bảng thành **Problem #4** và chọn vào **Top 3**).
  + **Gợi ý tóm tắt changelog:** Đọc commit history và pull requests để viết bản cập nhật tính năng (đã đưa vào bảng thành **Problem #6**).
- Ý bỏ vì không phải pain thật: 
  + Gợi ý *"AI tự động sinh mã nguồn đồ án từ đề bài"*: Bỏ vì không phải pain quy trình, quá viển vông, phạm vi quá lớn và vi phạm liêm chính học thuật.
  + Gợi ý *"Trợ lý AI nhắc nhở sức khỏe và thói quen học tập"*: Bỏ vì mang tính chung chung, không có quy trình cụ thể và không đo lường được điểm nghẽn bằng số liệu thực tế trong buổi lab.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (đạt 10 dòng)
- [x] Dùng ít nhất 3/4 lăng kính (đủ cả 4 lăng kính)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Thu thập, trích xuất hạn chót (deadline) và yêu cầu nộp bài từ nhiều kênh phân tán (LMS Canvas, Email, Discord, Zalo) | - Diễn ra mỗi ngày, 100% sinh viên gặp phải.<br>- Workflow bóc tách thời gian rõ ràng (25–30 phút/ngày).<br>- Tác động trực tiếp đến việc chống trễ hạn, sót bài tập. | Khả năng thu thập tự động từ các app nhắn tin đóng (Zalo cá nhân) bị giới hạn bởi API/chính sách bảo mật. |
| 2 | Kiểm tra thủ công checklist cấu trúc, định dạng và chuẩn trích dẫn báo cáo đồ án trước khi nộp | - Tốn nhiều thời gian (60–90 phút/báo cáo).<br>- Có rubric quy chuẩn rõ ràng từ giảng viên.<br>- Kết hợp tuyệt vời giữa Rule (kiểm tra font/lề) và AI (kiểm tra nội dung các mục). | Mỗi môn học có rubric và chuẩn trích dẫn khác nhau, hệ thống cần hỗ trợ nạp rubric tùy biến linh hoạt. |
| 3 | Đọc và gom cụm hàng chục log lỗi/crash report từ server backend để tìm nguyên nhân gốc (root cause) khi test hệ thống đồ án | - Nỗi đau lớn của sinh viên làm đồ án kỹ thuật.<br>- Tiết kiệm 30–45 phút mỗi lần debug.<br>- Có ranh giới rõ ràng: Rule lọc rác, AI gom cụm và giải thích ngữ cảnh lỗi. | File log có thể quá dài vượt context window nếu không dùng Rule tiền xử lý lọc bỏ log INFO/DEBUG trước. |

---

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

#### Problem Card #1 — Thu thập & đồng bộ Deadline / Thông báo bài tập đa kênh

```text
Problem 1 câu:
Sinh viên mất 25–30 phút mỗi ngày kiểm tra thủ công 4 kênh thông báo rời rạc (LMS Canvas, Discord môn học, Email trường, Zalo) để lọc deadline, dễ bỏ sót hoặc nhầm hạn chót khi giảng viên cập nhật gấp.

Actor:
Sinh viên đại học đang học 5–6 môn học cùng lúc / Trưởng nhóm bài tập lớn.

Thời điểm / bối cảnh:
Diễn ra hằng ngày, cao điểm vào đầu tuần và các tuần kiểm tra giữa kỳ / cuối kỳ.

Current workflow 3-7 bước:
1. Mở lần lượt 4 ứng dụng (LMS Canvas, Gmail, Discord, Zalo) kiểm tra thông báo mới.
2. Đọc lướt qua hàng chục tin nhắn/thông báo thông thường để lọc ra bài đăng có chứa bài tập hoặc thay đổi hạn nộp.
3. Tìm ngày giờ hạn chót và yêu cầu cụ thể trong nội dung bài đăng/thread.
4. Ghi chép thủ công lại hạn chót vào Google Calendar, Notion hoặc sổ tay.
5. Nhắn tin vào nhóm để thông báo/nhắc nhở các thành viên về deadline mới.

Bottleneck:
Bước 2 và Bước 3: Đọc lọc thông tin phi cấu trúc từ nhiều kênh chat/thread để bóc tách chính xác: Tên môn, Yêu cầu nộp, Thời hạn chót (Date/Time), Nơi nộp (LMS hay Drive link).

Impact:
Mất 25–30 phút/ngày (gần 3 giờ/tuần). Từng bị trễ 2 bài tập hoặc phải thức đêm nộp vội do giảng viên dời hạn trên Discord mà không báo trên LMS.

Success metric:
- Giảm thời gian tổng hợp và ghi nhận deadline từ 25–30 phút/ngày xuống dưới 3 phút/ngày.
- Tỷ lệ bỏ sót deadline: giảm từ 1–2 lần/học kỳ về 0 lần.

Non-AI alternative:
Viết Rule-based bot lọc theo từ khóa (như "deadline", "hạn nộp", "nộp bài trước").
Nhược điểm: Giảng viên dùng ngôn ngữ tự nhiên đa dạng ("thứ 6 tuần sau nộp nhé", "dời sang 23h59 ngày 15/10", "hạn chót là buổi học tới"), rule cố định rất dễ bỏ sót hoặc báo động giả từ tin nhắn thảo luận của sinh viên.

AI hypothesis:
Dùng LLM phân tích ngôn ngữ tự nhiên để đọc hiểu ngữ cảnh tin nhắn/thông báo, phân loại bài đăng có chứa deadline hay không và trích xuất ra định dạng JSON có cấu trúc (Subject, Task, Deadline, Submission_Channel).

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 27 phút

[1 Mở 4 app: 5'] → [2 Đọc lọc tin nhắn: 10'] → [3 Tìm ngày giờ deadline: 7']  <-- bottleneck → [4 Nhập Calendar: 3'] → [5 Nhắn tin nhóm: 2']

FUTURE STATE — 3 phút

[1 Webhook/Email Parser gom tin: 0.2'] → [2 AI trích xuất JSON deadline: 0.5'] → [3 Sinh viên review 1-click: 2']  <-- human boundary → [4 Tự động sync Calendar/Notion: 0.3']

Fallback: nếu AI nghi ngờ độ tin cậy (<80%) hoặc thiếu thông tin thời gian cụ thể, hệ thống sẽ đánh dấu tag "Cần kiểm tra thủ công", giữ nguyên đoạn text gốc và kèm link trực tiếp đến bài đăng để người dùng tự xác nhận.
```

File đính kèm (nếu vẽ riêng): 

---

#### Problem Card #2 — Tiền kiểm tra (Pre-check) checklist & định dạng báo cáo đồ án trước khi nộp

```text
Problem 1 câu:
Sinh viên mất 60–90 phút mỗi báo cáo để kiểm tra thủ công từng mục hình thức và cấu trúc theo rubric của môn học, nhưng vẫn dễ bị trừ 10–15% điểm vì các lỗi format và thiếu sót mục nội dung bắt buộc.

Actor:
Sinh viên làm đồ án môn học, Trưởng nhóm chịu trách nhiệm hoàn thiện bản nộp.

Thời điểm / bối cảnh:
Diễn ra vào các đợt nộp báo cáo tiến độ giữa kỳ, báo cáo đồ án cuối kỳ (3–4 lần/học kỳ).

Current workflow 3-7 bước:
1. Mở file rubric/hướng dẫn của giảng viên và file Word/PDF báo cáo của nhóm.
2. Dò thủ công từng trang kiểm tra font chữ, cỡ chữ, dãn dòng, căn lề, tiêu đề bảng/hình vẽ.
3. Đối chiếu danh mục các chương/mục bắt buộc trong rubric xem báo cáo đã có đủ chưa.
4. Rà soát danh mục tài liệu tham khảo (References) xem có đúng chuẩn IEEE và có trích dẫn trong bài không.
5. Đánh dấu các lỗi cần sửa và nhắc thành viên phụ trách chương đó sửa lại.

Bottleneck:
Bước 3 & 4: Đối chiếu xem nội dung từng phần trong báo cáo đã trả lời đủ câu hỏi trong rubric chưa và rà soát tính nhất quán của tài liệu tham khảo.

Impact:
Mất 60–90 phút cho mỗi báo cáo. Nhóm thường phải thức đêm sát giờ nộp để dò lỗi; tâm lý căng thẳng và vẫn hay bị trừ điểm oan ở phần hình thức.

Success metric:
- Giảm thời gian kiểm tra sơ bộ từ 80 phút xuống 15 phút/báo cáo.
- Tỷ lệ lỗi format/thiếu mục khi nộp cho giảng viên giảm từ 3–5 lỗi/bản xuống 0 lỗi cơ bản.

Non-AI alternative:
Dùng template Word/LaTeX dựng sẵn với script Python-docx để check font, margin, heading.
Nhược điểm: Rule chỉ check được định dạng kỹ thuật bề nổi, không thể kiểm tra được ngữ nghĩa (ví dụ: mục "Phân tích yêu cầu" đã đủ cả yêu cầu chức năng và phi chức năng theo đúng rubric chưa).

AI hypothesis:
Kết hợp Rule (kiểm tra font, margin, table of contents) + LLM (đối chiếu rubric với tóm tắt các section trong bài để chỉ ra mục còn thiếu hoặc viết quá sơ sài).

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 83 phút

[1 Mở file & rubric: 3'] → [2 Dò font/lề/bảng: 25'] → [3 Đối chiếu mục theo rubric: 20']  <-- bottleneck → [4 Check references: 20'] → [5 Tổng hợp lỗi: 15']

FUTURE STATE — 15 phút

[1 Upload file báo cáo & rubric: 1'] → [2 Rule check format cơ bản: 1'] → [3 AI đối chiếu rubric & xuất bảng audit: 3'] → [4 Sinh viên xem gợi ý & sửa bài: 10']  <-- human boundary

Fallback: Nếu AI không phân tích được phần nội dung chuyên sâu, hệ thống hiển thị bảng checklist chuẩn của rubric để sinh viên tự đánh dấu (check-off) thủ công, không chặn quy trình nộp bài.
```

File đính kèm (nếu vẽ riêng): 

---

#### Problem Card #3 — Phân loại & tổng hợp Log lỗi / Crash Reports từ server backend

```text
Problem 1 câu:
Khi test hệ thống hoặc chạy demo đồ án, lập trình viên mất 30–45 phút mỗi lần để đọc hàng trăm dòng log lỗi lộn xộn, lọc bỏ log rác và gom các lỗi trùng lặp để tìm nguyên nhân gốc.

Actor:
Sinh viên lập trình backend trong nhóm đồ án môn học / Intern Developer.

Thời điểm / bối cảnh:
Diễn ra mỗi đợt chạy tích hợp hệ thống (Integration test), stress test hoặc chuẩn bị demo bài tập lớn (2–3 lần/tuần).

Current workflow 3-7 bước:
1. Mở file log server (.txt, .log) hoặc màn hình console terminal.
2. Đọc lướt qua hàng trăm dòng log lẫn lộn giữa INFO, DEBUG, WARN và ERROR.
3. Copy các đoạn Stack Trace lỗi tìm kiếm trên Google/StackOverflow hoặc lần theo file code.
4. Gom các log có cùng nguyên nhân vào một nhóm để tránh sửa trùng lặp.
5. Viết issue ticket trên GitHub/Jira để phân công người sửa.

Bottleneck:
Bước 3: Đọc hiểu Stack trace lỗi dài hàng chục dòng giữa các service để bóc tách đâu là dòng code nội bộ gây lỗi (root cause) thay vì lỗi thư viện bên ngoài.

Impact:
Mất 30–45 phút mỗi lần debug; gây gián đoạn mạch code và dễ bỏ sót lỗi nghiêm trọng bị chìm dưới các warning vô hại.

Success metric:
- Giảm thời gian từ khi nhận log đến khi xác định nguyên nhân gốc từ 35 phút xuống dưới 8 phút.
- Tự động gom cụm các lỗi trùng lặp chính xác >90%.

Non-AI alternative:
Dùng công cụ Regex / Logstash / Grep để lọc dòng chứa từ khóa `ERROR` hoặc `CRITICAL`.
Nhược điểm: Chỉ lọc được từ khóa bề mặt nhưng không hiểu ngữ cảnh lỗi; ví dụ 50 lỗi cùng văng ra do mất kết nối Database sẽ bị tính là 50 sự cố riêng biệt thay vì 1 lỗi gốc.

AI hypothesis:
Dùng Regex (Rule) lọc trước các dòng Error/Traceback -> LLM tóm tắt ngữ cảnh lỗi, gom cụm các lỗi có cùng root cause và gợi ý vị trí file code nghi vấn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 45 phút

[1 Mở file log: 2'] → [2 Lướt tìm dòng lỗi: 10'] → [3 Phân tích Stack trace: 15']  <-- bottleneck → [4 Gom nhóm lỗi trùng: 10'] → [5 Tạo issue: 8']

FUTURE STATE — 8 phút

[1 Script Regex trích xuất khối Error: 0.5'] (máy) → [2 AI gom cụm & phân tích root cause: 1.5'] → [3 Dev review giải thích & định vị code: 5']  <-- human boundary → [4 1-click tạo GitHub Issue: 1']

Fallback: Cung cấp nút xem "Raw Log" kèm số dòng cụ thể và link mở thẳng IDE để Dev tự trace code nếu lời giải thích của AI không chính xác.
```

File đính kèm (nếu vẽ riêng): 

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Thu thập & đồng bộ Deadline / Thông báo bài tập đa kênh (LMS Canvas, Discord môn học, Email trường, Zalo)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Vấn đề này là nỗi đau hàng ngày của 100% sinh viên và nhóm đồ án. Quy trình hiện tại rất tốn thời gian (25–30 phút/ngày) vì phải mở 4 app và đọc lọc thủ công hàng chục tin nhắn rác. Giải pháp giải quyết đúng điểm nghẽn trích xuất thông tin phi cấu trúc sang cấu trúc, tiết kiệm ngay gần 3 giờ/tuần và triệt tiêu hoàn toàn nguy cơ nộp muộn bài tập.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Liệu chúng ta có thực sự cần AI cho toàn bộ quy trình không, hay chỉ cần dùng Rule/Regex bắt các từ khóa như 'deadline', 'hạn nộp'?
2. Với các kênh không có Webhook/API mở như Zalo cá nhân, workflow lấy input vào sẽ như thế nào để người dùng không cảm thấy phiền phức hơn cách cũ?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Nếu cố tự động hóa việc tự động cào tin nhắn từ Zalo/Canvas cá nhân, hệ thống sẽ rất dễ bị khóa tài khoản hoặc lỗi kết nối do chính sách bảo mật/chặn scraping.
- Tôi sửa gì: Tôi đã điều chỉnh ranh giới giải pháp từ "tự động cào 100%" thành một workflow thực tế hơn: Các kênh có API mở (Discord webhook, Gmail forwarding) sẽ tự động đồng bộ; riêng Zalo cho phép sinh viên copy đoạn chat hoặc gửi ảnh chụp màn hình vào bot để AI bóc tách (bán tự động nhưng an toàn và khả thi).

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field (Đã có 10 problems + 3 cards chi tiết)
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
