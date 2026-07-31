---
title: "Worklog Tuần 4"
date: 2026-07-29
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Tích hợp cơ sở dữ liệu Cloud bằng dịch vụ **AWS RDS PostgreSQL** vào hệ thống **Fav Web Portal**.
* Thiết lập kết nối giữa Backend triển khai trên EC2 và cơ sở dữ liệu RDS.
* Điều chỉnh cấu hình Backend để hỗ trợ hoạt động với database trên môi trường Cloud.

### Các công việc triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| --- | --- | --- | --- |
| 2 | - Tìm hiểu mô hình quản lý database trên AWS RDS <br> - Khởi tạo PostgreSQL Database Instance trên AWS Console | 29/06/2026 | 29/06/2026 |
| 3 | - Cấu hình Security Group cho RDS <br> - Thiết lập quyền truy cập để Backend EC2 có thể kết nối tới PostgreSQL Database | 30/06/2026 | 30/06/2026 |
| 4 | - Cập nhật Backend để hỗ trợ kết nối với AWS RDS PostgreSQL <br> - Bổ sung thư viện cần thiết cho quá trình kết nối database | 01/07/2026 | 01/07/2026 |
| 5 | - Điều chỉnh cấu hình database connection thông qua biến môi trường `DATABASE_URL` <br> - Kiểm tra khả năng chuyển đổi giữa database local và Cloud database | 02/07/2026 | 03/07/2026 |
| 6 | - Kiểm thử kết nối Backend với RDS PostgreSQL <br> - Kiểm tra dữ liệu ứng dụng sau khi chuyển sang môi trường Cloud | 04/07/2026 | 05/07/2026 |

### Kết quả đạt được tuần 4:
* Kết nối thành công Backend trên EC2 với cơ sở dữ liệu AWS RDS PostgreSQL.
* Hiểu được quy trình chuyển đổi database từ môi trường local sang Cloud.
* Hoàn thiện bước tích hợp cơ sở dữ liệu Cloud cho hệ thống **Fav Web Portal**.
* Đảm bảo dữ liệu của hệ thống có thể được quản lý và lưu trữ trên AWS RDS.
