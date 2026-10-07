# BT1 – Bắt lỗi Backlog của thực tập sinh
**Chuẩn hóa Product Backlog "Đặt xe ghép" trên Trello – Đội RikkeiGo**

## Phần 1 – Phân tích

| Hạng mục | Đúng/Sai | Vi phạm tiêu chí/quy tắc | Lý do |
|---|---|---|---|
| H1. Thẻ trên cùng "Làm tính năng đi ghép" chỉ có tiêu đề, không mô tả | **Sai** | D.E.E.P – **D**etailed appropriately (chi tiết vừa đủ theo vị trí ưu tiên) | Thẻ đứng đầu sẽ được làm sớm nhất nên phải chi tiết nhất, nhưng thẻ này mơ hồ nên Developers phải hỏi lại yêu cầu. |
| H2. "Đổi màu giao diện theo mùa lễ hội" nằm trên "Tự động chia tiền cho các khách đi ghép" | **Sai** | D.E.E.P – **P**rioritized/Ordered by value (sắp xếp theo giá trị) | Chia tiền là chức năng cốt lõi của đi ghép, giá trị cao hơn hẳn việc đổi màu giao diện, nên không thể xếp sau. |
| H3. Thẻ cuối cột "Khách đánh giá bạn đi ghép" chỉ có tiêu đề ngắn, ước lượng sơ bộ "lớn" | **Đúng** | — | Thẻ ưu tiên thấp nằm cuối chỉ cần mô tả thô và ước lượng sơ bộ (Detailed appropriately + Estimated), chưa cần chi tiết hay ước lượng chính xác. |
| H4. Tú tự thêm thẻ "Tối ưu tốc độ tải bản đồ" và kéo lên đầu cột vì thấy cần làm gấp | **Sai** | Quy tắc quyền sở hữu: chỉ Product Owner được thêm, bớt, sắp xếp Product Backlog | Dù lý do "cần gấp" nghe hợp lý, Tú là Developer nên không có quyền thêm thẻ hay đổi thứ tự; quyết định độ ưu tiên thuộc về PO (Đức). |
| H5. Bảng chỉ 4 cột (Product Backlog → Sprint Backlog → In Progress → Done), code xong kéo thẳng sang Done | **Sai** | Quy tắc luồng cột: chỉ thẻ đạt tiêu chuẩn "xong" mới vào Done | Thiếu cột kiểm tra (Review/Testing) nên thẻ code xong nhưng chưa được kiểm tra vẫn vào Done, làm Done không phản ánh thật sự hoàn thành. |

## Phần 2 – Sửa lỗi

- **H1:** Bổ sung cho thẻ "Làm tính năng đi ghép" mô tả đầy đủ (user story, tiêu chí chấp nhận, ước lượng) – nếu quá lớn thì tách thành các thẻ nhỏ – để Developers làm ngay mà không phải hỏi lại.
- **H2:** Đức (PO) đưa thẻ "Tự động chia tiền cho các khách đi ghép" lên trên thẻ "Đổi màu giao diện theo mùa lễ hội" để thứ tự phản ánh đúng giá trị.
- **H3:** *Giữ nguyên* (đã đúng).
- **H4:** Tú đưa thẻ "Tối ưu tốc độ tải bản đồ" ra khỏi đầu cột và chỉ đề xuất với Đức; Đức đánh giá giá trị rồi tự quyết định có thêm vào Product Backlog hay không và đặt ở vị trí nào.
- **H5:** Bảng Trello gồm 5 cột theo đúng thứ tự, di chuyển một chiều từ trái sang phải:
  1. **Product Backlog**
  2. **Sprint Backlog**
  3. **In Progress**
  4. **Review/Testing** (kiểm tra theo Definition of Done)
  5. **Done** (chỉ nhận thẻ đã qua Review/Testing và đạt tiêu chuẩn "xong")

## Kết luận
Sau khi sửa: thẻ đứng đầu đủ chi tiết và đúng giá trị nên Developers biết ngay làm thẻ nào trước; chỉ PO điều chỉnh backlog; cột Done chỉ chứa thẻ đã thật sự hoàn thành.
