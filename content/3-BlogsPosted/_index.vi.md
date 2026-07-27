---
title: "Các bài blogs đã đăng"
date: 2026-07-24
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Dưới đây là danh sách các bài viết chuyên môn (Blog posts) được chia sẻ trên cộng đồng [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj) trong quá trình thực hiện dự án **Fav Web Portal**:

### 1. [Blog 1 - Triển khai FastAPI Backend Containerized trên AWS EC2 & Docker](https://www.facebook.com/groups/awsstudygroupfcj)
Bài viết chi tiết hướng dẫn đóng gói ứng dụng web FastAPI với Dockerfile tối ưu trên `python:3.10-slim`, khởi chạy container trên máy chủ AWS EC2 và cấu hình Nginx Reverse Proxy kết hợp Systemd / Volume mounts để đảm bảo tính sẵn sàng cao.

### 2. [Blog 2 - Tối ưu hóa Lưu trữ Amazon S3 & Giải quyết triệt để sự cố Bảo mật CORS/CSP Header](https://www.facebook.com/groups/awsstudygroupfcj)
Phân tích nguyên nhân và giải pháp xử lý các lỗi trình duyệt chặn stream âm thanh/hình ảnh cross-domain. Bài viết chia sẻ cách cấu hình S3 CORS Rules chuẩn xác và thiết lập chính sách Content Security Policy (`media-src`, `connect-src`) bảo mật tuyệt đối.

### 3. [Blog 3 - Tích hợp AI Nhận diện Khuôn mặt (Face ID) & Cơ chế Xác thực JWT Dual Auth trên Cloud](https://www.facebook.com/groups/awsstudygroupfcj)
Giới thiệu kiến trúc xác thực sinh trắc học thông qua mô hình Deep Learning trích xuất vector đặc trưng khuôn mặt (`.npy`), kết hợp cơ chế xác thực kép (HttpOnly Cookie + Bearer Token Header Fallback) giúp bảo mật an toàn trước các nguy cơ tấn công XSS.