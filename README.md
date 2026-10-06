# BÀI TẬP: CHỌN CÁCH LÀM PHÙ HỢP CHO HAI ĐỘI RIKKEIGO

## Phần 1 - Đề xuất 2 giải pháp

* **Giải pháp 1: Mô hình tuần tự (Waterfall)**  
  Tiếp nhận toàn bộ yêu cầu cố định ngay từ đầu, sau đó triển khai qua các giai đoạn tuần tự từ phân tích, thiết kế, lập trình đến kiểm thử trước khi bàn giao một lần duy nhất.
* **Giải pháp 2: Mô hình lặp phát triển theo Sprint (Scrum)**  
  Tiếp nhận yêu cầu liên tục qua Product Backlog và chia nhỏ thành các chu kỳ ngắn (Sprint 1–2 tuần) để liên tục phân tích, phát triển và chuyển giao từng phần sản phẩm gia tăng.

---

## Phần 2 - So sánh hai giải pháp

| Tiêu chí | Giải pháp 1: Waterfall | Giải pháp 2: Scrum |
| :--- | :--- | :--- |
| **Khả năng thích nghi khi yêu cầu thay đổi** | **(–) Nhược điểm:** Kém linh hoạt; việc đổi phạm vi giữa chừng đòi hỏi quy trình Change Request phức tạp, gây trễ tiến độ và đội chi phí. | **(+) Ưu điểm:** Thích nghi rất cao; Product Backlog cho phép tinh chỉnh, tái ưu tiên hoặc thêm/bớt tính năng sau mỗi Sprint. |
| **Thời điểm khách thấy sản phẩm / phát hiện sai lệch** | **(–) Nhược điểm:** Rất muộn, chỉ thấy ở giai đoạn nghiệm thu cuối cùng nên nếu sai lệch sẽ tốn rất nhiều nguồn lực để sửa chữa. | **(+) Ưu điểm:** Rất sớm, khách hàng và stakeholder kiểm tra bản chạy thực tế (Increment) ngay tại buổi Sprint Review cuối mỗi chu kỳ. |
| **Mức phù hợp khi yêu cầu rõ ràng, ổn định** | **(+) Ưu điểm:** Rất cao; giúp lập kế hoạch chi tiết, kiểm soát ngân sách, nguồn lực và đảm bảo tính chặt chẽ, tài liệu hóa đầy đủ. | **(–) Nhược điểm:** Không tối ưu; gây lãng phí nguồn lực tổ chức các sự kiện điều chỉnh (planning, retro, refinement) khi phạm vi hầu như không đổi. |

---

## Phần 3 - Lựa chọn & phản biện

1. **Đội Tính năng** nên chọn **Scrum** vì tính chất thị trường biến động liên tục đòi hỏi việc phát hành tính năng nhỏ nhanh chóng để đo lường và thích ứng.
2. **Đội Đối soát** nên chọn **Waterfall** vì quy định thuế có tính chuẩn hóa cao, yêu cầu độ chính xác tuyệt đối và tài liệu hóa chặt chẽ để tránh bị xử phạt.
3. Khi luật thuế thay đổi gấp, Đội Đối soát sẽ kích hoạt quy trình **Change Request khẩn cấp** để đóng băng mã nguồn, đánh giá lại tác động pháp lý và cập nhật tài liệu kỹ thuật trước khi làm tiếp.
4. Rủi ro lớn nhất của phương án này là phát sinh chi phí làm lại (rework) và thời gian thẩm định có thể làm chậm hạn chót áp dụng luật mới.
5. Đề xuất của trưởng phòng là sai lầm mang tính giáo điều vì mô hình phát triển phần mềm được chọn dựa trên mức độ ổn định của yêu cầu (Requirements Volatility) chứ không phải dựa trên tính chất "hiện đại" hay xu hướng.