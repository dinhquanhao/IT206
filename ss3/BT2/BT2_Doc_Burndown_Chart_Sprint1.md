# BT2 – Đọc lại Burndown Chart Sprint 1 (Đặt xe ghép)

Sprint 10 ngày, cam kết 40 SP → đường lý tưởng giảm 40 / 10 = **4 SP/ngày**.

## Bảng số liệu đối chiếu

| Ngày | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Lý tưởng | 40 | 36 | 32 | 28 | 24 | 20 | 16 | 12 | 8 | 4 | 0 |
| Thực tế | 40 | 38 | 36 | 36 | 36 | 36 | 32 | 29 | 26 | 23 | 20 |
| Chênh lệch (thực tế − lý tưởng) | 0 | +2 | +4 | +8 | +12 | +16 | +16 | +17 | +18 | +19 | +20 |

Chênh lệch luôn dương: đường thực tế **luôn nằm trên** đường lý tưởng.

## Phần 1 – Phân tích

| Nhận định | Đúng/Sai | Dẫn chứng số liệu | Cách hiểu đúng |
|---|---|---|---|
| N1. Trục dọc là số giờ làm việc đã dùng | **Sai** | Các giá trị trục dọc (40, 38, … 20) là Story Points còn lại, giảm dần theo thời gian; số giờ đã dùng chỉ có thể tăng. | Trục Y là khối lượng công việc **còn lại** (SP), trục X là các ngày làm việc trong Sprint. |
| N2. Đường lý tưởng giảm đều 4 điểm/ngày, chạm 0 vào ngày 10 | **Đúng** (giữ nguyên) | 40 ÷ 10 = 4 SP/ngày; ngày 5 còn 20, ngày 10 còn 0. | Đường lý tưởng giảm đều từ tổng khối lượng về 0 vào ngày cuối Sprint. |
| N3. Ngày 2→5 đường thực tế đi ngang = đội làm việc rất ổn định | **Sai** | Ngày 2, 3, 4, 5 đều còn 36 SP: không có SP nào hoàn thành trong 3 ngày (3→5). Cuối ngày 5 lý tưởng 20, thực tế 36 → trễ 16 SP (4 ngày công). | Đường đi ngang nghĩa là không có tiến độ, dấu hiệu công việc **bị chặn** (hoặc task quá lớn, chưa Done), không phải sự ổn định. |
| N4. Đường thực tế luôn dưới đường lý tưởng nên nhanh hơn kế hoạch | **Sai** | Mọi ngày từ 1 đến 10 thực tế đều cao hơn lý tưởng (ngày 1: 38 > 36; ngày 5: 36 > 20; ngày 10: 20 > 0). | Đường thực tế **trên** đường lý tưởng nghĩa là **trễ lịch trình**; cuối Sprint còn 20/40 SP (50%) chưa xong. |

Bổ sung: sau ngày 6 đội chỉ đốt 3 SP/ngày (32→29→26→23→20), thấp hơn mức 4 SP/ngày cần có, nên khoảng cách tăng dần từ +16 lên +20 chứ không thu hẹp.

## Phần 2 – Vá lỗi (hiện tượng mà các nhận định sai đã bỏ qua)

**1. Bị chặn (ngày 3–5, đường đi ngang ở mức 36 SP).**
- Hành động: nhận ra ở Daily Scrum đầu ngày 4 (sau 1 ngày không giảm), xác định và gỡ vật cản, Developers nêu rõ họ đang kẹt ở đâu.
- Trách nhiệm: Developers báo vật cản; **Scrum Master (Lan)** gỡ chặn; nếu cần quyết định về yêu cầu thì có Product Owner (Đức).
- Thời điểm: Daily Scrum ngày 4, không để kéo đến hết ngày 5.

**2. Trễ lịch trình (đường thực tế luôn trên đường lý tưởng, lệch +16 SP từ ngày 5).**
- Hành động: thương lượng lại phạm vi Sprint Backlog, giữ các User Story giá trị cao nhất, đưa phần ưu tiên thấp về Product Backlog.
- Trách nhiệm: **Product Owner (Đức)** quyết định cắt/giữ scope cùng Developers; Scrum Master (Lan) điều phối buổi trao đổi.
- Thời điểm: giữa Sprint (ngày 5–6, ngay khi chênh lệch đã đạt +16), không đợi đến Sprint Review.

**Lưu ý:** trường hợp "trước lịch trình" **không xảy ra** trong Sprint này vì đường thực tế không lần nào dưới đường lý tưởng.
