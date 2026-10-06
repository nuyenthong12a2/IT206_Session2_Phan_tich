# BÀI LÀM: PHÂN TÍCH LỰA CHỌN MÔ HÌNH VẬN HÀNH CHO HAI ĐỘI RIKKEIGO

## Phần 1 - Đề xuất 2 giải pháp
* **Giải pháp 1: Phát triển Lặp và Tăng trưởng theo Sprint (Scrum Framework)**
  * *Mô tả:* Yêu cầu được tiếp nhận, làm mịn và đưa vào thực thi theo từng khoảng thời gian cố định (Sprint 1–2 tuần). Khách hàng/thị trường đánh giá sản phẩm sau mỗi Sprint để đội phản hồi và điều chỉnh thích ứng liên tục.
* **Giải pháp 2: Phát triển Tuần tự theo Thác nước (Waterfall Model)**
  * *Mô tả:* Yêu cầu được thu thập, phân tích và chốt cứng toàn bộ ngay từ đầu; sản phẩm đi qua lần lượt các giai đoạn Thiết kế -> Lập trình -> Kiểm thử -> Bàn giao. Khách hàng chỉ nghiệm thu sản phẩm hoàn chỉnh ở cuối chu kỳ phát triển.

---

## Phần 2 - So sánh hai giải pháp

| Tiêu chí | Giải pháp 1: Scrum (Thích ứng theo Sprint) | Giải pháp 2: Waterfall (Tuần tự) |
| :--- | :--- | :--- |
| **Khả năng thích nghi khi yêu cầu thay đổi** | **(+) Ưu điểm:** Cực kỳ cao, thay đổi được tiếp nhận và ưu tiên lại theo từng Sprint mà không gây vỡ kế hoạch tổng thể. | **(–) Nhược điểm:** Rất kém, chi phí và rủi ro sửa đổi cực kỳ lớn do kế hoạch và đặc tả đã bị chốt cứng từ đầu. |
| **Thời điểm khách thấy sản phẩm / phát hiện sai lệch** | **(+) Ưu điểm:** Rất sớm, khách hàng thấy Increment và phát hiện sai lệch ở buổi Sprint Review sau mỗi 1–2 tuần. | **(–) Nhược điểm:** Rất muộn, khách hàng chỉ thấy sản phẩm khi hoàn thành toàn bộ dự án, dễ dẫn đến sai lệch lớn so với thực tế. |
| **Mức phù hợp khi yêu cầu rõ ràng, ổn định** | **(–) Nhược điểm:** Tạo ra chi phí họp hành (overhead) không cần thiết và dễ lãng phí nguồn lực khi cố thích ứng với thứ không đổi. | **(+) Ưu điểm:** Tối ưu hiệu quả và chi phí triển khai nhờ kế hoạch tuyến tính rõ ràng, kiểm soát chặt chẽ tính tuân thủ. |

---

## Phần 3 - Lựa chọn & phản biện

**1. Chốt giải pháp cho từng đội:**
* **Đội Tính năng:** Chọn **Scrum** vì thị trường biến động liên tục, cần phát hành sớm để đo lường và thích ứng nhanh.
* **Đội Đối soát:** Chọn **Waterfall** vì nghiệp vụ hóa đơn thuế có tính chuẩn hóa cao, yêu cầu cố định và cần sự chính xác tuyệt đối.

**2. Ứng phó & Rủi ro cho Đội Đối soát khi Luật thuế đổi gấp:**
* **Ứng phó:** Đội Đối soát xử lý theo quy trình **Change Control Procedure (Kiểm soát thay đổi)**: dừng công việc hiện tại để đánh giá tác động, cập nhật tài liệu đặc tả và lập lại kế hoạch (re-baseline).
* **Rủi ro:** Chi phí làm lại (rework) cao, nguy cơ trễ hạn bàn giao và tăng áp lực kiểm thử toàn bộ hệ thống trong thời gian ngắn.

**3. Phản biện đề xuất của Trưởng phòng:**
Đề xuất *"áp Scrum cho cả hai đội vì Scrum hiện đại hơn"* là vi phạm nguyên tắc quản trị do chọn mô hình theo xu hướng chứ không dựa trên đặc thù yêu cầu công việc. Áp dụng Scrum cho Đội Đối soát sẽ gây lãng phí chi phí vận hành và làm tăng rủi ro sai sót nghiệp vụ thuế vốn đòi hỏi tính ổn định và tuân thủ cao.