# BT2 – PHÂN ĐỊNH LẠI 3 VAI TRÒ TRONG ĐỘI RIKKEIGO

**Vai trò:** Agile Coach | **Đội:** RikkeiGo (PO: Đức, SM: Lan, 4 Developers) | Tiếp nối nhịp Sprint đã chuẩn hóa ở BT1

**Hai triệu chứng cần gỡ:** (A) Đức quá tải vì nhiều việc phải chờ anh xử lý; (B) lập trình viên bị bắt làm theo cách kém hiệu quả.

---

## Phần 1 – Phân tích

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng gây ra |
|---|---|---|---|
| **QU1.** Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe | **Sai** | **Developers.** Cách triển khai kỹ thuật (viết code, review code, chọn thư viện) là phần Developers tự quyết vì họ là người có chuyên môn và chịu trách nhiệm về chất lượng Increment. PO chỉ chịu trách nhiệm về *cái gì* và *thứ tự*, không phải *làm thế nào*. | **(A)** Mọi đoạn code và quyết định kỹ thuật đều phải chờ Đức nên anh bị nghẽn; **(B)** một phần: Developers không được chọn công cụ phù hợp nên làm theo cách kém hiệu quả. |
| **QU2.** Lan giao cụ thể ai làm thẻ việc nào trong Daily Scrum "để đội làm nhanh hơn" | **Sai** | **Developers.** Daily Scrum là sự kiện của Developers để đồng bộ tiến độ và phát hiện vướng mắc, và chính họ tự lập kế hoạch cho ngày làm việc. Scrum Master là người phục vụ, chỉ coach, điều phối sự kiện và gỡ rào cản, không ra lệnh phân việc. | **(B)** Developers bị chỉ định việc và cách làm thay vì tự tổ chức, nên làm theo cách kém hiệu quả và mất tính chủ động. |
| **QU3.** Đức sắp xếp thứ tự ưu tiên Product Backlog theo giá trị mang lại cho người đặt xe | **Đúng** | **Product Owner.** PO sở hữu Product Backlog, quyết định thứ tự ưu tiên và là cầu nối giữa business và đội phát triển. Sắp xếp theo giá trị cho người dùng đúng là trách nhiệm này. | — (không gây triệu chứng) |
| **QU4.** Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy tính năng khác dễ làm hơn | **Sai** | **Product Owner.** Thứ tự ưu tiên là quyền của PO, dựa trên giá trị. Developers vẫn được đóng góp (ước lượng độ phức tạp, phụ thuộc kỹ thuật) nhưng người quyết định là Đức. "Dễ làm hơn" là tiêu chí về công sức, không phải về giá trị. | Không phải nguyên nhân của (A) hay (B). Đây là lỗi lệch vai theo chiều ngược lại, tạo rủi ro đội ưu tiên việc dễ thay vì việc có giá trị nhất. |

**Ghi chú về các "lý do nghe hợp lý" (bẫy):**
- QU2 "để đội làm nhanh hơn": tốc độ không biện minh cho việc SM ra lệnh. Đội tự tổ chức mới là cách làm nhanh và bền.
- QU4 "dễ làm hơn": đây là thông tin hữu ích cho PO, nhưng không chuyển quyền quyết định thứ tự sang Developers.
- QU1 nhìn có vẻ "PO kiểm soát chất lượng", nhưng chất lượng kỹ thuật thuộc về Developers (qua Definition of Done), còn PO kiểm tra giá trị ở Sprint Review.

---

## Phần 2 – Vá lỗi (quy ước viết lại, áp dụng ngay)

- **QU1 (mới):** Developers tự quyết định cách triển khai kỹ thuật, gồm review code và chọn thư viện bản đồ cho tính năng đặt xe, còn Đức chỉ làm rõ yêu cầu và kiểm tra giá trị của Increment tại Sprint Review.
- **QU2 (mới):** Trong Daily Scrum, Developers tự bàn nhau ai làm thẻ việc nào để đạt Sprint Goal, còn Lan chỉ đảm bảo buổi họp diễn ra trong 15 phút và hỗ trợ gỡ rào cản đội nêu ra.
- **QU4 (mới):** Developers đưa ra ước lượng và các phụ thuộc kỹ thuật để Đức tham khảo, còn việc đổi thứ tự hạng mục trong Product Backlog do Đức quyết định.

**QU3 giữ nguyên** vì đã đúng vai.

## Kiểm tra: bộ quy ước mới gỡ được cả 2 triệu chứng

| Triệu chứng | Được gỡ bởi | Vì sao |
|---|---|---|
| (A) Đức quá tải | QU1 (mới) | Quyết định kỹ thuật và review code về lại tay Developers, Đức không còn là điểm nghẽn và tập trung vào Product Backlog. |
| (B) Developers bị bắt làm theo cách kém hiệu quả | QU1 (mới) + QU2 (mới) | Developers tự chọn công cụ và tự phân việc, nên chọn được cách làm hiệu quả. |

Lưu ý: QU4 (mới) không làm Đức nặng thêm việc vì Developers chỉ cung cấp thông tin đầu vào, không chờ Đức duyệt từng chi tiết.
