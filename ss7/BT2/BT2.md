# BT2 – Sửa lỗi báo cáo Velocity và Burndown Chart của Sprint 4 (RikkeiGo)

Người rà soát: Lan (Scrum Master)

## Dữ liệu đối chiếu

- Tổng SP đầu Sprint (ngày 0): 8 + 5 + 5 + 3 + 2 = **23 SP** (khớp Burndown ngày 0).
- Các PBI đạt DoD: Hủy chuyến (5) + Đánh giá tài xế (5) + Lưu địa chỉ yêu thích (3) + Đổi ảnh đại diện (2) = **15 SP**.
- PBI không đạt DoD: Thanh toán ví RikkeiPay (8 SP, chưa qua Integration Test) và Hiển thị mã khuyến mãi trên hóa đơn (3 SP, chưa làm) = **11 SP**.
- Ngày 3: 21 + 3 (PBI mã khuyến mãi được thêm vào) = **24 SP**, khớp đường tăng trên biểu đồ.

## Phần 1 – Phân tích

| Nhận định | Đúng / Sai | Căn cứ trong dữ liệu | Hậu quả nếu giữ nguyên |
|-----------|-----------|----------------------|------------------------|
| BC1. Velocity = 21 SP (15 SP Done + 6 SP cho PBI ví đã làm 75%) | **Sai** | Velocity chỉ tính SP của PBI đạt DoD, PBI chưa Done tính 0 SP. PBI ví chưa qua Integration Test nên chưa Done; "làm được 75%" không được tính. Velocity đúng là 15 SP. | Velocity bị thổi phồng 40% (21 so với 15). Product Owner và quản lý dự báo Sprint sau, ngày release theo số ảo; Sprint tới nhận quá tải, dễ trượt cam kết. Che mất việc Sprint Goal chưa đạt. |
| BC2. Ngày 1 sang ngày 2 đường nằm ngang (21 sang 21), đội hỏi nhau tại Daily Scrum có Task nào quá lớn hoặc làm dở quá nhiều việc cùng lúc | **Đúng** | Burndown ngày 1 = 21, ngày 2 = 21: đường đi ngang, không có SP nào giảm. Đường ngang là tín hiệu cần tìm nguyên nhân, và việc tìm nguyên nhân tại Daily Scrum là cách xử lý đúng. Giữ nguyên. | Không có (nhận định đúng). |
| BC3. Ngày 3 đường tăng từ 21 lên 24, chứng tỏ Developers làm việc chậm | **Sai** | Nguyên nhân đã nằm sẵn trong dữ liệu: ngày 3 có PBI mã khuyến mãi 3 SP được thêm vào (Đức thương lượng với Developers), và 21 + 3 = 24. Đường tăng do phạm vi tăng, không phải do năng suất. | Kết luận oan cho Developers, làm hỏng niềm tin. Che mất bài học thật: thêm việc giữa Sprint mà không đổi bớt việc làm Sprint quá tải và PBI mới không kịp làm. |
| BC4. Ngày 10 sửa số còn lại từ 11 về 0 cho Actual Line chạm Ideal Line | **Sai** | Ngày 8 đến 10 còn 11 SP (ví 8 SP + mã khuyến mãi 3 SP) đều chưa Done. Actual Line phải phản ánh đúng công việc còn lại, không cần chạm Ideal Line. | Số liệu bị "làm đẹp", báo cáo cho thấy Sprint hoàn thành trong khi thực tế còn 11/23 SP chưa xong. Quản lý ra quyết định sai và đội mất cơ hội cải tiến ở Retrospective. |
| BC5. PBI ví chỉ còn thiếu Integration Test nên tự động chuyển sang Sprint 5 với 2 SP còn lại | **Sai** | Quy tắc: PBI chưa Done quay lại Product Backlog để PO xem xét thứ tự, không tự động chuyển Sprint. PBI chưa Done cũng không được chia theo phần trăm (không có "2 SP còn lại"); nó giữ nguyên 8 SP và chưa tạo giá trị dùng được. | Sprint 5 nhận PBI mà PO chưa cân nhắc ưu tiên; ước lượng 2 SP quá thấp, làm Sprint 5 lệch kế hoạch. Nếu tính lại 2 SP vào Velocity Sprint 5 thì Velocity lại bị sai nữa. |

## Phần 2 – Vá lỗi

**Velocity Sprint 4:**
Velocity = 5 (Hủy chuyến) + 5 (Đánh giá tài xế) + 3 (Lưu địa chỉ yêu thích) + 2 (Đổi ảnh đại diện) = **15 SP**.
Hai PBI chưa Done (ví RikkeiPay 8 SP và mã khuyến mãi 3 SP) tính 0 SP.

**Số SP còn lại đúng của ngày 10:**
8 (ví RikkeiPay) + 3 (mã khuyến mãi) = **11 SP**, giữ nguyên số của ngày 9. (Phép đối chiếu: 23 + 3 − 15 = 11.)

**Cách xử lý PBI ví RikkeiPay:**
PBI không được tự chuyển sang Sprint 5 và không chia lại thành 2 SP: nó trả về Product Backlog với trạng thái chưa Done. Đức (PO) xem xét thứ tự ưu tiên (vì liên quan Sprint Goal chưa đạt), sau đó Developers ước lượng lại phần việc còn thiếu (Integration Test, sửa lỗi phát hiện) nếu cần, rồi đưa vào Sprint 5 khi đã được chọn.
