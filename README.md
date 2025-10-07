# HỆ THỐNG QUẢN LÝ PHÒNG KHÁM ĐƠN GIẢN  

\*(Clinic Management System – CMS)\*



---



\## 📘 Giới thiệu



\*\*Hệ thống Quản lý Phòng khám Đơn giản\*\* là một ứng dụng phần mềm giúp số hóa quy trình quản lý của một phòng khám tư nhân hoặc phòng y tế nhỏ.  

Dự án được xây dựng nhằm hỗ trợ các hoạt động cơ bản như:

\- Quản lý thông tin bệnh nhân, bác sĩ và nhân viên.  

\- Quản lý lịch hẹn, hồ sơ bệnh án và đơn thuốc.  

\- Quản lý thanh toán và thống kê doanh thu.  



Dự án được thực hiện theo \*\*mô hình tiến trình phần mềm Incremental Model\*\*, cho phép phát triển hệ thống theo từng phần (module) và mở rộng dần.



---



\## 🎯 Mục tiêu



\- Giảm thao tác giấy tờ trong phòng khám.  

\- Quản lý dữ liệu bệnh nhân, bác sĩ và lịch khám tập trung.  

\- Hỗ trợ bác sĩ lưu trữ hồ sơ khám và đơn thuốc điện tử.  

\- Tăng hiệu quả làm việc của nhân viên lễ tân và quản lý.  



---



\## ⚙️ Phạm vi hệ thống



| Vai trò | Quyền hạn |

|----------|-----------|

| \*\*Quản trị viên\*\* | Quản lý tài khoản người dùng, cấu hình hệ thống |

| \*\*Bác sĩ\*\* | Quản lý lịch khám, hồ sơ bệnh án, kê đơn thuốc |

| \*\*Lễ tân\*\* | Đặt lịch hẹn, tiếp nhận bệnh nhân, in hóa đơn |

| \*\*Bệnh nhân\*\* | Đặt lịch online, xem lịch sử khám và đơn thuốc |



---



\## 🧩 Các chức năng chính



| Mã | Chức năng | Mô tả ngắn gọn |

|----|------------|----------------|

| F1 | Quản lý tài khoản | Thêm, sửa, xóa và phân quyền người dùng |

| F2 | Quản lý bệnh nhân | Lưu trữ thông tin, lịch sử khám, liên hệ |

| F3 | Quản lý lịch hẹn | Tạo, chỉnh sửa, hủy lịch khám |

| F4 | Hồ sơ bệnh án | Ghi nhận triệu chứng, chẩn đoán, đơn thuốc |

| F5 | Quản lý thuốc | Danh mục thuốc, tồn kho, đơn giá |

| F6 | Thanh toán | Tạo hóa đơn, theo dõi doanh thu |

| F7 | Báo cáo thống kê | Doanh thu, số bệnh nhân, lượt khám |



---



\## 🧠 Mô hình tiến trình phần mềm



\*\*Incremental Model\*\* được chọn làm mô hình phát triển cho dự án này.  

Hệ thống sẽ được xây dựng qua các giai đoạn tăng dần, mỗi lần thêm một module mới (ví dụ: Quản lý Bệnh nhân → Quản lý Lịch hẹn → Quản lý Đơn thuốc...).



\### Ưu điểm:

\- Dễ kiểm thử và bảo trì.  

\- Người dùng sớm thấy sản phẩm mẫu.  

\- Giảm rủi ro trong giai đoạn đầu.



---



## 🧱 Kiến trúc \& Công nghệ



| Thành phần | Công nghệ sử dụng |

|-------------|-------------------|

| \*\*Frontend\*\* | HTML, CSS, JavaScript (hoặc ReactJS) |

| \*\*Backend\*\* | PHP / Python / Java |

| \*\*Database\*\* | MySQL hoặc PostgreSQL |

| \*\*Web Server\*\* | Apache / Nginx |

| \*\*IDE\*\* | Visual Studio Code / IntelliJ / NetBeans |



---



