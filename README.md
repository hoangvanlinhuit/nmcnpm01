\# Phần 1: Giới thiệu các Mô hình Tiến trình Phần mềm



Các mô hình tiến trình phần mềm (Software Process Models) là những phương pháp luận giúp cấu trúc, lập kế hoạch và kiểm soát quá trình phát triển một hệ thống thông tin.  

Mỗi mô hình có ưu và nhược điểm riêng, phù hợp với các loại dự án khác nhau.



---



\## Mô hình Thác nước (Waterfall Model)



\### Khái niệm

Đây là mô hình truyền thống và đơn giản nhất, thực hiện các giai đoạn phát triển phần mềm một cách tuần tự, nghiêm ngặt.  

Giai đoạn sau chỉ bắt đầu khi giai đoạn trước đã hoàn thành hoàn toàn.



\*\*Các giai đoạn:\*\*



\### Đặc điểm

\- Tuyến tính, tuần tự.  

\- Yêu cầu phải được xác định rõ ràng và đầy đủ ngay từ đầu.  

\- Ít có sự linh hoạt để thay đổi yêu cầu giữa chừng.  



\### Ví dụ tương tự

Xây một ngôi nhà:  

Bạn phải có bản thiết kế hoàn chỉnh trước khi xây móng,  

xây xong móng mới xây tường, và cứ thế tiếp tục.  

Không thể đang xây tầng 2 lại thay đổi thiết kế móng.



\### Ưu điểm

\- Dễ quản lý, theo dõi tiến độ.  

\- Mỗi giai đoạn có mục tiêu và sản phẩm rõ ràng.



\### Nhược điểm

\- Cứng nhắc, khó thay đổi giữa chừng.  

\- Rủi ro cao nếu yêu cầu ban đầu không chính xác.  

\- Sản phẩm chỉ được thấy ở giai đoạn cuối.



\### Khi nên dùng

\- Dự án nhỏ, yêu cầu rõ ràng ngay từ đầu.  

\- Không có khả năng thay đổi yêu cầu.



---



\## Mô hình Tăng trưởng (Incremental Model)



\### Khái niệm

Mô hình này chia dự án thành nhiều phần nhỏ (increments).  

Mỗi phần đi qua các giai đoạn như trong Waterfall,  

nhưng tạo ra một phiên bản sản phẩm hoạt động được sau mỗi lần lặp.



\### Đặc điểm

\- Kết hợp tính tuần tự của Waterfall và tính lặp của Agile.  

\- Khách hàng có thể thấy sản phẩm sớm và phản hồi.  

\- Phiên bản đầu tiên thường là sản phẩm cốt lõi (core product).



\### Ví dụ tương tự

Xây dựng ứng dụng Microsoft Word:  

\- Lần 1: chỉ có chức năng gõ và lưu văn bản.  

\- Lần 2: thêm định dạng (in đậm, in nghiêng).  

\- Lần 3: thêm kiểm tra lỗi chính tả.



\### Ưu điểm

\- Linh hoạt hơn Waterfall.  

\- Giảm rủi ro, khách hàng sớm nhận được giá trị.  



\### Nhược điểm

\- Cần thiết kế tổng thể tốt để các phần tích hợp trơn tru.



\### Khi nên dùng

\- Dự án lớn, có thể chia thành các module chức năng độc lập.



---



\## Mô hình Linh hoạt (Agile Model)



\### Khái niệm

Agile là một triết lý phát triển phần mềm tập trung vào:

\- Lặp lại liên tục (iterations),

\- Hợp tác chặt chẽ với khách hàng,

\- Và thích ứng với thay đổi.



Hai phương pháp phổ biến nhất: Scrum và Kanban.



\### Đặc điểm

\- Phân chia dự án thành các chu kỳ ngắn (sprints), thường 1–4 tuần.  

\- Mỗi sprint cho ra một phần sản phẩm chạy được.  

\- Nhấn mạnh giao tiếp trực tiếp, tự tổ chức, cải tiến liên tục.  

\- Thay đổi yêu cầu được chào đón.



\### Ví dụ tương tự

Nấu một món ăn mới:  

Bạn sẽ nêm nếm và điều chỉnh liên tục dựa trên phản hồi,  

thay vì tuân thủ cứng nhắc công thức ban đầu —  

để có được món ăn ngon nhất.



\### Ưu điểm

\- Rất linh hoạt, thích ứng nhanh.  

\- Chất lượng cao nhờ phản hồi liên tục.  

\- Khách hàng hài lòng do được tham gia vào quá trình.



\### Nhược điểm

\- Khó ước lượng chính xác thời gian và chi phí toàn dự án.  

\- Cần khách hàng tham gia thường xuyên.  



\### Khi nên dùng

\- Dự án yêu cầu chưa rõ ràng hoặc hay thay đổi.  

\- Dự án cần tốc độ cao, tính sáng tạo lớn.



---



\## Tổng kết so sánh



| Mô hình | Cấu trúc | Linh hoạt | Hiển thị sớm sản phẩm | Phù hợp dự án |

|----------|-----------|------------|------------------------|----------------|

| Waterfall | Tuần tự, tuyến tính | Thấp | Không | Nhỏ, yêu cầu rõ |

| Incremental | Tăng dần theo module | Trung bình | Có | Lớn, chia module được |

| Agile | Lặp nhanh theo sprint | Cao | Sớm và liên tục | Năng động, đổi mới |



---



\*\*Ghi chú:\*\*  

Việc lựa chọn mô hình phụ thuộc vào đặc thù dự án, độ rõ của yêu cầu, nguồn lực, và mức độ thay đổi kỳ vọng của khách hàng.



