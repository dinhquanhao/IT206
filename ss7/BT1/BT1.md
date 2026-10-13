# BT1 – Sửa lỗi buổi Planning Poker cho các chức năng đặt xe (RikkeiGo)

Người rà soát: Lan (Scrum Master)
Reference Story: "Xem lịch sử chuyến đi" = 3 SP. Thang: 1, 2, 3, 5, 8, 13, 21.

## Phần 1 – Phân tích

| Mã | Hợp lý / Chưa hợp lý | Quy tắc bị vi phạm | Hậu quả khi lập kế hoạch Sprint |
|----|----------------------|--------------------|----------------------------------|
| P1 | Chưa hợp lý | (1) Thẻ lệch là tín hiệu để tìm giả định, không phải để lấy trung bình. (2) Kết quả phải là một giá trị trên thang của đội (4 không thuộc thang). | Con số 4 không có mốc so sánh với Reference Story; sự khác biệt 3 và 5 không được giải thích nên giả định ẩn không lộ ra. Velocity và dung lượng Sprint tính trên số không chuẩn, dễ lệch kế hoạch. |
| P2 | Chưa hợp lý | (1) Developers chọn thẻ, Product Owner không quyết định SP. (2) Thẻ lệch lớn (5 đến 13) phải được thảo luận rồi chọn lại, không được bỏ qua. | SP bị ép theo deadline nên đánh giá thấp so với thực tế; rủi ro tích hợp ví RikkeiPay (điều Tú lo) không được nêu ra. Sprint bị nhận quá tải, dễ trễ hoặc không hoàn thành PBI. |
| P3 | Hợp lý | Không vi phạm. | Thẻ lệch vừa (3 đến 8); hai người ở hai đầu giải thích, cả đội chọn lại và hội tụ về 5 – đúng quy trình, giá trị 5 nằm trên thang. |
| P4 | Chưa hợp lý (con số đúng, ghi chú sai) | SP là độ lớn tương đối, không quy đổi cố định sang giờ hoặc ngày. | Ghi chú "13 SP = 52 giờ" khiến người ngoài đội hiểu SP là cam kết giờ; lập kế hoạch theo giờ, so sánh giữa các đội/người sai, và khi thực tế lệch sẽ bị coi là trễ hạn. Đồng thời che mất lý do thật (rủi ro/giả định) của con số 13. |
| P5 | Chưa hợp lý | (1) Thẻ lệch không được chốt theo đa số. (2) PBI chưa đủ rõ thì làm rõ rồi mới ước lượng. | Con số 13 có thể quá cao hoặc quá thấp vì chưa biết mã có dùng chung khuyến mãi khác không; phạm vi mơ hồ đưa vào Sprint dễ phình việc, phát sinh làm lại, đẩy các PBI khác ra khỏi Sprint. |

## Phần 2 – Sửa lỗi

**P1:** Hai Developer chọn 3 và hai Developer chọn 5 lần lượt giải thích giả định của mình (ví dụ: có phải gửi/xác thực OTP, xử lý gửi lại OTP, giới hạn số lần nhập sai). Sau đó cả đội chọn lại bí mật, lật đồng thời cho đến khi hội tụ về một thẻ trên thang (3 hoặc 5), không lấy trung bình.

**P2:** Đức (PO) không chọn thẻ nữa mà làm rõ phạm vi và giá trị (ví nạp tiền, hoàn tiền, xử lý giao dịch lỗi?). Những Developer chọn 13 nêu rủi ro tích hợp RikkeiPay (API, môi trường test, bảo mật), người chọn 5 nói giả định của mình; rồi cả đội chọn lại. Nếu muốn kịp kế hoạch, Đức cắt giảm phạm vi hoặc tách PBI, chứ không ép con số.

**P4:** Giữ nguyên 13 SP nhưng xóa ghi chú "13 SP = 52 giờ". Lan yêu cầu thay bằng ghi chú về giả định và rủi ro (cập nhật vị trí thời gian thực, độ chính xác, dịch vụ bản đồ bên thứ ba), và nhắc đội rằng SP là độ lớn tương đối so với Reference Story 3 SP.

**P5:** Dừng ước lượng; Đức (PO) làm rõ với bên kinh doanh xem mã giới thiệu có dùng cùng khuyến mãi khác không, giới hạn số lần dùng, điều kiện áp dụng. Chỉ khi đã rõ, Developers mới chọn thẻ lại, người chọn 5 và 13 giải thích, rồi chốt kết quả hội tụ trên thang (không theo đa số). Nếu chưa có câu trả lời, để PBI trong backlog, không đưa vào Sprint.
