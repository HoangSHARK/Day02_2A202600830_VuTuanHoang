# Day 02 Lab — Bài Làm Học Viên 

## Học viên thực hiện
- **Họ và tên:** Vũ Tuấn Hoàng
- **Mã học viên:** 2A202600830

---

# Phase 1 — Individual Scan: tìm 5+ problems

## Bảng scan

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Lượng kiến thức lý thuyết của môn học quá lớn, khó tiếp thu và dễ bị ngợp khi tự học. | Sinh viên ngành Công nghệ / Data | Mất 2-3 tiếng đọc tài liệu nhưng không đọng lại được bao nhiêu, khó áp dụng vào thực hành. |
| 2 | Pain từ người khác | Thông báo, tài liệu môn học bị phân tán rải rác ở quá nhiều kênh (Zalo, LMS, Facebook Group, Email...). | Thành viên trong lớp / Nhóm dự án | Thường xuyên sót deadline, mất 10-15 phút lục tìm lại link file hoặc thông báo cũ mỗi khi cần. |
| 3 | Lặp lại | Thời gian mở cổng hoặc gọi tên điểm danh trực tuyến quá ngắn và diễn ra chớp nhoáng. | Sinh viên | Chỉ cần mạng lag hoặc vào muộn 1-2 phút là bị tính vắng, mất điểm chuyên cần dù có đi học. |
| 4 | Tốn thời gian | Bị kẹt dữ dội và mất phương hướng khi hệ thống báo lỗi code (bug) trong quá trình làm bài tập lớn. | Sinh viên Code / Dự án | Bị stuck ở một lỗi duy nhất suốt nhiều giờ, loay hoay sửa mò làm chậm tiến độ toàn bộ đồ án. |
| 5 | AI có thể tốt hơn | Mất quá nhiều thời gian và dễ gặp lỗi khi thiết lập môi trường, cài đặt thư viện và kết nối dữ liệu hệ thống. | Sinh viên làm Lab / Dự án | Mất nguyên cả buổi học (2-3 tiếng) chỉ để cài đặt, cấu hình môi trường chạy code mà vẫn lỗi, không kịp làm bài Lab. |
| 6 | Lặp lại | Phải viết báo cáo tiến độ tuần (Weekly Status) cho bài tập lớn của nhóm theo cùng một format. | Trưởng nhóm / Thành viên nhóm | Mất 30 phút mỗi cuối tuần để nhắn tin giục giã, thu thập thông tin từ từng người rồi tổng hợp lại. |
| 7 | AI có thể tốt hơn | Đọc các tài liệu nghiên cứu (Research paper) hoặc slide bài giảng tiếng Anh chuyên ngành dài dòng, nhiều thuật ngữ khó. | Sinh viên | Mất cả tiếng tra từ điển, dịch từng câu nhưng vẫn khó hiểu được ý tưởng cốt lõi của tác giả. |
| 8 | Pain từ người khác | Không nhớ hoặc bỏ lỡ các feedback, góp ý của thầy cô sau mỗi buổi review bài tập lớn trực tiếp trên lớp. | Nhóm làm bài tập lớn | Các thành viên nghe không kịp hoặc ghi chép thiếu, dẫn đến việc sửa bài không đúng ý thầy cô, bị trừ điểm. |
| 9 | | | | |
| 10 | | | | |

---

# Phase 2 — Top 3 Problem Cards + draft workflow

## Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Lượng kiến thức lý thuyết quá lớn, dễ bị ngợp và khó áp dụng vào bài tập thực hành. | Gặp phải liên tục ở các môn chuyên ngành nặng, ảnh hưởng trực tiếp đến kết quả đồ án. | Cách định lượng chính xác mức độ "hiểu" và "nhớ" kiến thức sau khi đổi workflow. |
| 2 | "Cơn ác mộng" cấu hình môi trường, cài đặt thư viện và lỗi kết nối dữ liệu hệ thống. | Cản trở ngay từ bước đầu tiên của mọi bài Lab, gây ức chế và lãng phí thời gian vô ích. | Khả năng AI bắt được các lỗi dị do xung đột phần cứng hoặc hệ điều hành đặc thù. |
| 3 | Thông báo, tài liệu học tập bị phân tán rải rác ở quá nhiều kênh (Zalo, LMS, Teams...). | Gây mất thời gian tìm kiếm lặp đi lặp lại và dễ làm sót các deadline quan trọng. | Cách tự động hóa việc cào (crawl) hoặc đồng bộ dữ liệu từ các nền tảng đóng như Zalo. |

## Problem Card #1 — Lượng kiến thức lý thuyết quá lớn (Learning Overwhelm)

```text
Problem 1:
Sinh viên ngành Công nghệ / Data bị ngợp bởi lượng kiến thức lý thuyết quá đồ sộ, tốn nhiều thời gian đọc tài liệu nhưng khó nhớ và khó áp dụng vào làm bài tập thực hành.

Actor:
Sinh viên ngành Công nghệ / Data.

Thời điểm / bối cảnh:
Khi tự học, chuẩn bị bài trước khi lên lớp hoặc ôn thi học kỳ các môn chuyên ngành nặng lý thuyết (như Cơ sở dữ liệu, Kiến trúc máy tính, Học máy, Mạng máy tính).

Current workflow 3-7 bước:
1. Mở slide bài giảng, sách giáo trình hoặc tài liệu PDF dài (thường từ 50-100 trang).
2. Đọc lần lượt từ đầu đến cuối một cách thụ động (Passive Reading).
3. Cố gắng ghi chép (take notes) các định nghĩa chính vào vở hoặc Notion.
4. Đọc đề bài tập thực hành hoặc bài Lab.
5. Loay hoay tìm kiếm lại slide hoặc Google phần lý thuyết tương ứng để làm bài do không nhớ kiến thức đã đọc.

Bottleneck:
Bước 2 và 3: Việc đọc thụ động lượng thông tin lớn và take note cơ học tốn rất nhiều thời gian (2-3 tiếng) nhưng không đọng lại được bao nhiêu, dẫn đến mau quên và bị ngợp khi bắt tay vào thực hành.

Impact:
Học trước quên sau, tốn nhiều thời gian tự học lý thuyết nhưng vẫn bị stuck hoặc làm sai bài thực hành; điểm số thấp và kết quả đồ án kém.

Success metric:
Giảm thời gian đọc hiểu và tổng hợp lý thuyết môn học của một chương xuống dưới 30 phút; tăng tỷ lệ làm đúng bài thực hành ngay từ lần đầu lên trên 80%.

Non-AI alternative:
Tự vẽ sơ đồ tư duy (mindmap) thủ công hoặc thiết lập bộ câu hỏi Flashcard giấy để ôn tập chủ động (Active Recall), nhưng vẽ tay rất tốn thời gian.

AI hypothesis:
Sử dụng AI đọc tài liệu học thô, tự động tạo sơ đồ tư duy (bằng Mermaid code) và trích xuất bộ câu hỏi Flashcard tương tác (Q&A) dựa trên nội dung tài liệu để sinh viên tự học chủ động.

Quick gut:
[x] Workflow
```

### Draft workflow
*Vẽ workflow hiện tại và tương lai dưới dạng ASCII*
```text
CURRENT STATE — 180 phút (Học thụ động)
[Nhận tài liệu/Slide 50-100 trang]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 2: Đọc thụ động (Passive Reading) từ đầu đến cuối  │  <── BOTTLENECK (90-120 phút)
 └────────────────────────────────────────────────────────┘      Tốn thời gian, dễ nản, ngợp
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 3: Take notes cơ học các định nghĩa vào tập/Notion │  <── BOTTLENECK (30-45 phút)
 └────────────────────────────────────────────────────────┘      Chép xuôi, chưa có tư duy sâu
       │
       ▼
 [Đọc đề bài tập thực hành/bài Lab]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 5: Loay hoay lật lại slide/Google tra cứu để code │  <── PAIN POINT (30-60 phút)
 └────────────────────────────────────────────────────────┘      Do quên sạch lý thuyết nền
       │
       ▼
 [Kết quả: Tốn nhiều thời gian, code lỗi, học trước quên sau]

FUTURE STATE — 40 phút (Học chủ động với AI)
[Nhận tài liệu/Slide 50-100 trang]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ [AI] Quét tài liệu thô -> Xuất Sơ đồ tư duy (Mermaid)  │  <── AI WORKFLOW (1-2 phút)
 │ [AI] Trích xuất nhanh bộ Flashcard Q&A (Active Recall)  │      Xử lý cấu trúc dữ liệu thô
 └────────────────────────────────────────────────────────┘
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Sinh viên xem sơ đồ tư duy để nắm tổng quan bức tranh  │  <── HUMAN BOUNDARY (5-10 phút)
 └────────────────────────────────────────────────────────┘      Định vị nhanh vùng kiến thức
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Sinh viên tự trả lời bộ câu hỏi Flashcard từ AI        │  <── HUMAN BOUNDARY (15 phút)
 └────────────────────────────────────────────────────────┘      Kích hoạt tư duy chủ động
       │
       ▼
 [Đọc đề bài tập thực hành/bài Lab]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Sinh viên code và làm bài thực hành dựa trên bộ khung  │  <── HOÀN THANH (Tỷ lệ đúng > 80%)
 │ tư duy sẵn có (Nếu quên, tra nhanh ngay trên Flashcard)│      Ít bị stuck, nhớ lâu hơn
 └────────────────────────────────────────────────────────┘

 💡 Fallback: AI trích xuất sai/thiếu ý -> Sinh viên dùng chức năng Search để tra lại file tài liệu gốc.
```

## Problem Card #2 — "Cơn ác mộng" cấu hình môi trường (Environment Setup)

```text
Problem 2:
Sinh viên mất quá nhiều thời gian loay hoay cài đặt thư viện, cấu hình môi trường chạy code và kết nối dữ liệu khi bắt đầu môn thực hành hoặc bài Lab mới.

Actor:
Sinh viên ngành Công nghệ thông tin / Lập trình viên bắt đầu môn thực hành mới.

Thời điểm / bối cảnh:
Buổi học thực hành đầu tiên của môn học hoặc khi bắt đầu triển khai một dự án/bài tập lớn mới.

Current workflow 3-7 bước:
1. Đọc file hướng dẫn setup chung (Readme hoặc slide bài giảng của giảng viên).
2. Thực hiện chạy các câu lệnh cài đặt trên terminal/cmd của máy cá nhân.
3. Gặp lỗi do xung đột phiên bản phần mềm (Python, Java, Node.js...) hoặc sự khác biệt về hệ điều hành (Windows, macOS, Linux).
4. Tra cứu mã lỗi trên Google để tìm cách sửa cấu hình biến môi trường hoặc thư viện hệ thống.
5. Cài đặt lại và chạy thử cho đến khi thành công.

Bottleneck:
Bước 3 và 4: Gặp các lỗi cấu hình hệ thống rất đặc thù của từng dòng máy cá nhân mà không được ghi trong hướng dẫn cài đặt chung.

Impact:
Mất nguyên cả buổi học thực hành (2-3 tiếng) chỉ để cài đặt môi trường chạy code mà không kịp làm bài Lab; tạo tâm lý chán nản, mệt mỏi ngay từ đầu môn học.

Success metric:
Hoàn thành thiết lập môi trường chạy code thành công trong vòng dưới 30 phút thay vì mất cả buổi học (120-180 phút).

Non-AI alternative:
Sử dụng các môi trường phát triển trên Cloud (như GitHub Codespaces, Replit) hoặc chạy máy ảo pre-configured sẵn (VirtualBox) nhưng yêu cầu máy cá nhân cấu hình mạnh và có mạng ổn định.

AI hypothesis:
Sinh viên cung cấp thông tin cấu hình máy cá nhân + thông báo lỗi setup, AI tự động phân tích lỗi cấu hình hệ thống và sinh ra file setup script hoặc hướng dẫn từng bước khắc phục lỗi cụ thể cho máy đó.

Quick gut:
[x] Rule
```

### Draft workflow
```text
CURRENT STATE — 120 phút
[Nhận file hướng dẫn setup chung]
       │
       ▼
 [Chạy các câu lệnh cài đặt trên Terminal/CMD]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 3: Gặp lỗi xung đột phiên bản/hệ điều hành (OS)   │  <── BOTTLENECK (Khởi đầu chuỗi thử-sai)
 └────────────────────────────────────────────────────────┘      Lỗi đặc thù theo cấu hình máy
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 4: Tra cứu mã lỗi trên Google / Stack Overflow    │  <── BOTTLENECK (90-120 phút)
 └────────────────────────────────────────────────────────┘      Bơi trong đống giải pháp chắp vá
       │
       ▼
 [Cài đặt lại, sửa biến môi trường (Environment Variables)]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ LỖI CHỒNG LỖI: Hệ thống rối loạn, xóa đi cài lại mò mẫm│  <── PAIN POINT (Tốn tài nguyên tâm lý)
 └────────────────────────────────────────────────────────┘      Mất nguyên buổi thực hành
       │
       ▼
 [Kết quả: Trễ tiến độ làm bài Lab, mệt mỏi, chán nản]

FUTURE STATE — 25 phút
[Nhận file hướng dẫn setup chung]
       │
       ▼
 [Chạy các câu lệnh cài đặt trên Terminal/CMD]
       │
       ▼
 [Gặp lỗi cấu hình / Thư viện hệ thống]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ [AI] Cung cấp: Thông số máy + Lỗi -> AI phân tích lỗi   │  <── AI INTERVENTION (1-2 phút)
 │ [AI] Xuất: Script sửa lỗi tự động hoặc hướng dẫn Fix   │      Áp dụng quy tắc (Rule) chuẩn bệnh
 └────────────────────────────────────────────────────────┘
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Sinh viên chạy Script sửa lỗi hoặc làm theo hướng dẫn  │  <── HUMAN BOUNDARY (5-10 phút)
 └────────────────────────────────────────────────────────┘      Kiểm soát quyền thực thi trên máy
       │
       ▼
 [Môi trường chạy code thông suốt]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Bắt tay vào code bài Lab ngay trong 20 phút đầu giờ     │  <── HOÀN THÀNH (Tiết kiệm >80% thời gian)
 └────────────────────────────────────────────────────────┘      Đảm bảo tiến độ môn học

 💡 Fallback: Script lỗi/AI chẩn đoán sai -> Chuyển sang phương án Non-AI (Codespaces/Replit) hoặc nhờ Mentor.
```

## Problem Card #3 — Thông báo, tài liệu học tập bị phân tán (Info Fragmentation)

```text
Problem 3 :
Thành viên trong nhóm/lớp dễ bỏ sót deadline và tốn nhiều thời gian tìm kiếm thông báo, tài liệu học tập do bị phân tán trên quá nhiều kênh truyền thông khác nhau.

Actor:
Sinh viên, thành viên trong nhóm làm bài tập lớn hoặc ban cán sự lớp.

Thời điểm / bối cảnh:
Hằng ngày khi kiểm tra cập nhật môn học hoặc khi cần tìm tài liệu chuẩn bị làm bài tập lớn.

Current workflow 3-7 bước:
1. Giảng viên đăng thông báo hoặc tài liệu môn học trên một kênh bất kỳ (Zalo, Teams, LMS, Email...).
2. Sinh viên đọc thông báo tại thời điểm đăng (hoặc bỏ lỡ do trôi tin nhắn).
3. Khi cần làm bài, sinh viên mở từng ứng dụng để tìm lại thông báo hoặc link tài liệu cũ liên quan.
4. Tải file về máy hoặc sao chép link tài liệu để lưu trữ.
5. Tự ghi chú deadline vào lịch cá nhân nếu có.

Bottleneck:
Bước 3: Lục tìm lại tin nhắn cũ bị trôi trên các group chat hoặc link tài liệu trên nhiều nền tảng khác nhau (mất 10-15 phút/lần và rất dễ bỏ sót).

Impact:
Sinh viên bị trễ hạn nộp bài tập lớn, thiếu tài liệu tham khảo chính thống từ thầy cô, tạo sự ức chế và mất đoàn kết khi làm việc nhóm.

Success metric:
Tìm thấy bất kỳ tài liệu/thông báo môn học nào dưới 1 phút; tỷ lệ sót deadline quan trọng giảm về 0%.

Non-AI alternative:
Ban cán sự lớp tạo một file Google Sheet chung để cập nhật thủ công toàn bộ link tài liệu và lịch deadline của các môn học hàng tuần.

AI hypothesis:
AI tự động đọc dữ liệu thô (quét qua API hoặc từ thông tin do người dùng paste vào), trích xuất deadline, file tài liệu và tự động phân loại, đưa vào một dashboard quản lý tập trung.

Quick gut:
[x] Workflow
```

### Draft workflow
```text
CURRENT STATE — 15 phút/lần tìm kiếm
[Giảng viên đăng thông báo/tài liệu lên Zalo, Teams, LMS, Email...]
       │
       ▼
 [Sinh viên đọc lướt qua -> Tin nhắn nhanh chóng bị trôi]
       │
       ▼
 [Đến hạn làm bài tập lớn / Cần ôn tập]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ BƯỚC 3: Mở từng app, cuộn chat, lục lọi tìm lại link   │  <── BOTTLENECK (10-15 phút/lần)
 └────────────────────────────────────────────────────────┘      Ức chế, dễ bỏ sót thông tin ngầm
       │
       ▼
 [Tải file thủ công + Tự gõ lịch deadline vào điện thoại]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ RỦI RO: Nhớ sai hạn nộp, sót file đính kèm quan trọng   │  <── PAIN POINT (Hậu quả thực tế)
 └────────────────────────────────────────────────────────┘      Trễ deadline, mất điểm chuyên cần
       │
       ▼
 [Kết quả: Làm việc nhóm rời rạc, trễ hạn nộp bài]

FUTURE STATE — 2 phút/lần
[Giảng viên đăng thông báo/tài liệu lên các kênh khác nhau]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ [AI/Automation] Quét dữ liệu thô (API hoặc User paste) │  <── AI WORKFLOW (Tự động hóa)
 │ [AI] Trích xuất: Tên tài liệu, Link, Hạn nộp (Deadline) │      Phân loại thông tin thông minh
 └────────────────────────────────────────────────────────┘
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Dữ liệu tự động đổ về Dashboard tập trung (Notion/Sheet)│  <── TRẠM TRUNG TÂM (Lưu trữ tự động)
 └────────────────────────────────────────────────────────┘
       │
       ▼
 [Đến hạn làm bài tập lớn / Cần ôn tập]
       │
       ▼
 ┌────────────────────────────────────────────────────────┐
 │ Sinh viên mở 1 Dashboard duy nhất để lấy tài liệu      │  <── HUMAN BOUNDARY (< 1 phút)
 └────────────────────────────────────────────────────────┘      Theo dõi trực quan, chủ động lịch trình
       │
       ▼
 [Kết quả: Tỷ lệ sót deadline về 0%, quản lý tài nguyên học tập khoa học]

 💡 Fallback: Hệ thống tự động lỗi/Sót tin -> Thành viên nhóm dùng tính năng tìm kiếm (Search) trên app gốc.
```

## Card tôi muốn pitch nhất
```text
Problem Card #1 — Lượng kiến thức lý thuyết quá lớn (Learning Overwhelm)
```

Vì sao:
```text
Vì đây là vấn đề cốt lõi mà mọi sinh viên ngành Công nghệ / Data đều phải đối mặt thường xuyên trong các kỳ học. Tác động của nó rất nặng nề (mất hàng giờ tự học nhưng vẫn không hiểu, làm bài tập thực hành bị stuck). Hơn nữa, việc tóm tắt thông tin học thuật, sinh mã sơ đồ tư duy (Mermaid) và tạo câu hỏi tương tác (Flashcard) là thế mạnh vượt trội của AI, giúp sinh viên chuyển đổi từ việc học thụ động sang học chủ động một cách dễ dàng.
```

Câu hỏi tôi muốn nhóm challenge:
```text
Làm thế nào để AI có thể trích xuất chính xác các khái niệm cốt lõi trong slide mà không bị bỏ sót các chi tiết nhỏ nhưng quan trọng khi sinh viên làm bài thực hành, đồng thời làm sao để đo lường được mức độ "hiểu sâu" của sinh viên thay vì chỉ là học thuộc lòng (vẹt)?
```

---

