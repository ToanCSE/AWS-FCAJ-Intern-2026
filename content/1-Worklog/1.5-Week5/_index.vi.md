---
title: "Worklog Tuần 5"
date: 2026-07-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Tích hợp hệ thống ghi log và giám sát ứng dụng bằng dịch vụ **AWS CloudWatch**.
* Theo dõi trạng thái hoạt động của Backend sau khi triển khai trên AWS.
* Thiết lập cảnh báo để hỗ trợ phát hiện sớm các sự cố trong quá trình vận hành.

### Các công việc triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| --- | --- | --- | --- |
| 2 | - Tìm hiểu các tính năng của AWS CloudWatch Logs và CloudWatch Metrics <br> - Nghiên cứu cách giám sát ứng dụng trên AWS | 06/07/2026 | 06/07/2026 |
| 3 | - Tích hợp thư viện `watchtower` vào Backend <br> - Cấu hình hệ thống logging để gửi log lên CloudWatch | 07/07/2026 | 07/07/2026 |
| 4 | - Thiết lập ghi log cho các sự kiện quan trọng như đăng nhập, nhận diện khuôn mặt và lỗi hệ thống <br> - Kiểm tra Log Group trên CloudWatch | 08/07/2026 | 08/07/2026 |
| 5 | - Tạo CloudWatch Alarm theo dõi CPU Utilization của EC2 <br> - Thiết lập ngưỡng cảnh báo phục vụ việc giám sát hệ thống | 09/07/2026 | 09/07/2026 |
| 6 | - Kiểm tra hoạt động của hệ thống Logging và Monitoring <br> - Đánh giá khả năng theo dõi và xử lý sự cố thông qua CloudWatch | 10/07/2026 | 10/07/2026 |

### Kết quả đạt được tuần 5:
* Tích hợp thành công AWS CloudWatch vào hệ thống **Fav Web Portal**.
* Nhật ký hoạt động của ứng dụng được đồng bộ lên CloudWatch Logs.
* Thiết lập được cơ chế giám sát và cảnh báo cho tài nguyên EC2.
* Nâng cao khả năng theo dõi và vận hành hệ thống sau khi triển khai trên AWS.

![AWS CloudWatch Logging & Monitoring](/images/cloudwatch.png)
