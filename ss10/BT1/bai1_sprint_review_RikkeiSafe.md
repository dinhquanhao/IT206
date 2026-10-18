# BÀI THỰC HÀNH 1 – Chuẩn bị Sprint Review cho RikkeiSafe

## Nhiệm vụ 1 – Phiếu chuẩn bị Sprint Review

| Bước | Việc cụ thể cho buổi Review này |
|---|---|
| 1. Chốt mục tiêu và người tham gia | Mục tiêu: xem người dùng có tự kiểm tra được số, link và hiểu cảnh báo không. Mời đủ 3 Stakeholders. *(đã điền sẵn)* |
| 2. Kiểm tra Increment | **PBI được trình diễn là Done:** PBI-01 (Kiểm tra số điện thoại), PBI-02 (Kiểm tra đường link), PBI-03 (Gửi báo cáo số hoặc link đáng ngờ) – cả 3 đạt đủ 5 điều kiện DoD.<br><br>**PBI phải nói rõ là chưa Done, kèm điều kiện DoD chưa đạt:**<br>- **PBI-04 (Lưu lịch sử kiểm tra):** chưa đạt điều kiện (1) "làm đủ các chức năng đã thống nhất" – còn thiếu chức năng xóa lịch sử và lọc theo loại.<br>- **PBI-05 (Hướng dẫn khi đã lỡ chuyển tiền):** chưa đạt điều kiện (2) "review chéo" (chưa được thành viên khác kiểm tra lại) và điều kiện (3) "kiểm thử trên máy tính và điện thoại" (mới kiểm thử trên máy tính, chưa kiểm thử trên điện thoại).<br><br>PBI-04 và PBI-05 không được trình bày là hoàn thành và không tính vào Increment của Sprint này. |
| 3. Chọn User Journey và người demo | **User Journey:** Nhận cuộc gọi từ số lạ và tin nhắn có kèm link → Mở RikkeiSafe → Nhập số điện thoại → Bấm "Kiểm tra" → Xem cảnh báo kèm lý do → Dán đường link trong tin nhắn → Bấm "Kiểm tra" → Xem cảnh báo kèm lý do → Bấm "Gửi báo cáo" cho số/link đáng ngờ → Nhận thông báo đã gửi báo cáo.<br>(Hành trình này đi qua PBI-01, PBI-02, PBI-03 – đều là PBI đã Done.)<br><br>**Người demo:** Thu An (Developer) thao tác trên bản chạy được, đọc to từng bước. Sau phần demo, mời cô Mai và chị Vy tự thao tác lại để xem họ có tự dùng được không. |
| 4. Chuẩn bị kỹ thuật | Kiểm tra bản chạy được, tài khoản dùng thử, đường truyền họp trực tuyến. *(đã điền sẵn)* |
| 5. Chuẩn bị trao đổi | 2 câu hỏi mở dành cho Stakeholders:<br>1. "Khi thấy cảnh báo và lý do này, cô/anh/chị sẽ làm gì tiếp theo? Chỗ nào cô/anh/chị chưa hiểu hoặc thấy khó hiểu?"<br>2. "Điều gì khiến cô/anh/chị còn ngần ngại khi dùng ứng dụng này trước lúc chuyển tiền cho một người lạ?" |
| 6. Chia thời gian | Xem lịch trình ở Nhiệm vụ 2. |

---

## Nhiệm vụ 2 – Sửa lịch trình Sprint Review (35 phút)

| Thời gian | Hoạt động | Nhận xét và cách sửa |
|---|---|---|
| 0–5' | Product Owner nhắc Sprint Goal. | Phù hợp, giữ nguyên. |
| 5–20' | Product Owner trình diễn cả 5 PBI, giới thiệu PBI-05 là đã hoàn thành. | **Sai:** (1) Product Owner không phải người demo mà Developers là người làm ra sản phẩm nên trình diễn; (2) PBI-05 chưa Done (chưa review chéo, mới kiểm thử trên máy tính) nhưng bị giới thiệu là hoàn thành; PBI-04 cũng chưa Done; (3) demo rời từng PBI thay vì theo hành trình người dùng thật.<br>**Sửa:** Thu An (Developer) demo PBI-01, 02, 03 theo User Journey đã chọn. Product Owner nói rõ PBI-04 và PBI-05 chưa Done kèm điều kiện DoD chưa đạt (như Nhiệm vụ 1, bước 2) và không tính vào Increment. |
| 20–32' | Từng Developer lần lượt báo cáo việc cá nhân mình đã làm. | **Sai:** Báo cáo việc cá nhân biến buổi Review thành buổi báo cáo tiến độ; Sprint Review là để Stakeholders xem sản phẩm thật và cho phản hồi, không phải để nghe ai làm gì.<br>**Sửa:** Dành 12 phút cho Stakeholders (cô Mai, anh Phúc, chị Vy) tự thao tác trên sản phẩm và trao đổi qua 2 câu hỏi mở. Developers lắng nghe, trả lời thắc mắc. Product Owner và Scrum Master ghi lại Feedback. |
| 32–35' | Stakeholders được nói trong 3 phút cuối; Scrum Master chốt góp ý nào sẽ làm ở Sprint sau. | **Sai:** (1) Stakeholders bị dồn vào 3 phút cuối, không đủ thời gian góp ý; (2) Scrum Master không có quyền quyết định góp ý nào được làm – thứ tự ưu tiên Product Backlog thuộc về Product Owner; (3) chốt "sẽ làm ở Sprint sau" là hứa trước khi đã cân nhắc.<br>**Sửa:** Stakeholders đã góp ý ở 20–32'. Trong 3 phút cuối, Product Owner tóm tắt các Feedback đã ghi, nói sẽ đưa vào Product Backlog để xem xét và sắp xếp thứ tự ưu tiên, **không hứa làm ngay**. Scrum Master giữ thời gian và cảm ơn mọi người. |

---

## Nhiệm vụ 3 – Ghi nhận Feedback

| Mã | Góp ý | Cách xử lý |
|---|---|---|
| FB-01 | Anh Phúc: nên có nút hướng dẫn gọi ngân hàng khi người dùng báo đã chuyển tiền. | Ghi vào Product Backlog để Product Owner xem xét cùng PBI-05; chưa hứa làm ngay. *(mẫu)* |
| FB-02 | Chị Vy: muốn thêm chức năng chia sẻ cảnh báo cho người thân. Việc này nằm ngoài Sprint Goal. | Cảm ơn chị Vy. Scrum Team ghi lại thành một PBI mới trong Product Backlog (Product Owner Ngọc Hương chịu trách nhiệm). Product Owner xem xét giá trị và xếp thứ tự ưu tiên so với các PBI khác. Nếu thấy phù hợp, PBI này sẽ được đưa ra bàn ở buổi Sprint Planning sau. Không hứa làm ngay và không thêm vào Sprint hiện tại hay thay đổi Sprint Goal. |
| FB-03 | Cô Mai: dán đường link rất dài thì nút "Kiểm tra" bị đẩy ra ngoài màn hình điện thoại (PBI-02). | Ghi vào Product Backlog dưới dạng lỗi giao diện trên điện thoại liên quan PBI-02, kèm mô tả cách tái hiện (dán link dài trên điện thoại). Developers xác nhận lại lỗi trên điện thoại và cho biết mức độ ảnh hưởng. Product Owner quyết định mức ưu tiên – nên cân nhắc cao vì lỗi ảnh hưởng chức năng chính và người dùng lớn tuổi như cô Mai; nếu đánh giá là lỗi nghiêm trọng thì phải xem lại điều kiện DoD (4) của PBI-02. Không hứa ngày sửa trong buổi Review. |
