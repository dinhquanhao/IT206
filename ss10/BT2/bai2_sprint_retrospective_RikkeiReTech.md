# BÀI THỰC HÀNH 2 – Tổ chức Sprint Retrospective cho RikkeiReTech

## Nhiệm vụ 1 – Chọn kỹ thuật và xếp thẻ ý kiến

**(a) Kỹ thuật chọn và lý do:** Start–Stop–Continue, vì vấn đề đã khá rõ qua nhật ký, buổi họp chỉ 45 phút và cả nhóm muốn có ngay hành động; kỹ thuật này cho ra thẳng việc nên bắt đầu, nên dừng, nên giữ, còn 4Ls thiên về chia sẻ cảm nhận và cần nhiều thời gian hơn.

**(b) Xếp thẻ:**

| Thẻ | Nội dung thẻ | Xếp vào cột nào, lý do ngắn |
|---|---|---|
| T1 | Review chéo giúp sửa lỗi trước khi kiểm thử. | Continue. Cách làm này hiệu quả, nên giữ. *(mẫu)* |
| T2 | Kiểm thử dồn đến ngày 9 mới bắt đầu. | **Stop** – dừng việc dồn kiểm thử về cuối Sprint (đây là nguyên nhân khiến lỗi phát hiện muộn, DT-01). |
| T3 | Hải báo lỗi muộn khiến cả nhóm phải sửa gấp. | Đây là thẻ đổ lỗi cá nhân, nên **viết lại** thành: *"Lỗi được báo muộn khiến cả nhóm phải sửa gấp"*, rồi xếp vào **Start** – bắt đầu báo lỗi ngay trong ngày phát hiện. Lý do: vấn đề nằm ở cách làm việc của cả nhóm, không phải ở một người. |
| T4 | Bộ lọc giá chưa hợp nhu cầu của người mua. | **Không thuộc Sprint Retrospective** (đây là góp ý về sản phẩm, không phải về cách làm việc của nhóm). **Chuyển cho Product Owner Thảo** để đưa vào Product Backlog và xem xét, hoặc nêu ở Sprint Review với Stakeholders. |
| T5 | Definition of Done (DoD) chưa ghi việc kiểm thử trên điện thoại. | **Start** – bắt đầu bổ sung "kiểm thử trên điện thoại" vào DoD. Lý do: DoD là quy ước làm việc của chính Scrum Team nên thuộc phạm vi Retrospective. |

---

## Nhiệm vụ 2 – Từ Data đến Improvement

**Data đã chọn: DT-01** – Ngày 9 mới bắt đầu kiểm thử chức năng đặt giữ máy; lỗi phát hiện quá muộn nên chức năng chưa Done.

| Data đã chọn | Khía cạnh | Insight (vì sao xảy ra) |
|---|---|---|
| DT-01: Ngày 9 mới bắt đầu kiểm thử chức năng đặt giữ máy, lỗi phát hiện muộn nên chưa Done. | **Quy trình** | Quy trình làm việc của nhóm chưa có bước kiểm thử sớm: chức năng đặt giữ máy được làm trọn vẹn rồi mới đưa đi kiểm thử, và PBI lớn chưa được chia nhỏ để kiểm thử từng phần. Vì vậy lỗi chỉ lộ ra sát cuối Sprint, khi không còn đủ thời gian sửa và kiểm thử lại. |

| Hành động cụ thể | Người/nhóm theo dõi | Khi kiểm tra lại | Bằng chứng |
|---|---|---|---|
| Từ Sprint sau, mỗi PBI được kiểm thử ngay sau khi review chéo xong từng phần, chậm nhất ngày thứ 6 của Sprint phải bắt đầu kiểm thử; PBI lớn được chia nhỏ ngay ở buổi Sprint Planning để có phần kiểm thử được sớm. | Developers cùng thực hiện (Linh làm đầu mối cập nhật bảng Sprint); Scrum Master Duy nhắc và theo dõi ở Daily Scrum. | Mỗi ngày ở Daily Scrum; kiểm tra giữa Sprint (ngày 5) và đánh giá kết quả ở Sprint Retrospective Sprint sau. | Trên bảng Sprint: mọi PBI có ngày bắt đầu kiểm thử không muộn hơn ngày 6; số lỗi phát hiện sau ngày 8 bằng 0 hoặc rất ít; PBI dự kiến đều đạt Done vào cuối Sprint. |

---

## Nhiệm vụ 3 – Sắp xếp và mở đầu buổi Retrospective

**(a) Thứ tự 5 bước:** H3 → H2 → H5 → H1 → H6

| Bước | Hoạt động |
|---|---|
| 1. Mở đầu (Set the stage) | H3 – Nhắc mục tiêu, thống nhất cách trao đổi không đổ lỗi, xem lại hành động Sprint trước. |
| 2. Thu thập dữ liệu (Gather data) | H2 – Mỗi người tự viết thẻ, dựng lại các sự việc chính của Sprint. |
| 3. Tìm nguyên nhân (Generate insights) | H5 – Gom thẻ theo chủ đề, tìm nguyên nhân của 1–2 vấn đề lớn. |
| 4. Quyết định hành động (Decide what to do) | H1 – Cả nhóm chọn 1 Improvement và thống nhất lúc kiểm tra lại. |
| 5. Kết thúc (Close) | H6 – Tóm tắt kết quả, cảm ơn mọi người, hẹn kiểm tra lại Improvement ở buổi sau. |

**Hoạt động bị loại: H4** – vì Scrum Master chọn sẵn giải pháp rồi giao cho nhóm làm theo thì nhóm không còn tự phân tích và tự cam kết; Improvement phải do chính cả nhóm quyết định.

**(b) Lời mở đầu của Duy:**

> "Chào cả nhóm, hôm nay chúng ta có 45 phút để nhìn lại Sprint vừa rồi và chọn ra một việc cải tiến cụ thể cho Sprint sau. Mình cùng thống nhất: chúng ta nói về cách làm việc và quy trình, không nói về lỗi của một ai; ai cũng được nói thật và nói hết ý. Trước khi bắt đầu, mình xem nhanh hành động cải tiến của Sprint trước đã làm được đến đâu nhé."
