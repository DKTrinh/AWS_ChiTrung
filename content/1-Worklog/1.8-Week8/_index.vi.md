---
title: "Tuần 8 - Triển khai hạ tầng Dự án & Xây dựng luồng CI/CD"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
url: "/vi/1-worklog/1.8-week8/"
---

### Chủ đề tuần

Cấp phát tài nguyên thực tế (Provisioning) + Tích hợp liên tục và Triển khai liên tục (CI/CD)

### Mục tiêu tuần

* Hiện thực hóa bản vẽ kiến trúc thành hạ tầng vật lý ảo trên nền tảng AWS.
* Tự động hóa quá trình đẩy mã nguồn và cập nhật hệ thống.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 20/07/2026 | Thứ 2 | Bắt đầu triển khai hạ tầng dự án. Khởi tạo VPC, cấu hình Subnet, Route Table và NAT Gateway. | Final Project |
| 21/07/2026 | Thứ 3 | Triển khai phần Backend. Cấu hình máy chủ tính toán (EC2/Lambda) và thiết lập môi trường chạy code. | Final Project |
| 22/07/2026 | Thứ 4 | Khởi tạo Cơ sở dữ liệu (RDS/DynamoDB). Triển khai phần Frontend và kết nối Storage tĩnh qua S3. | Final Project |
| 23/07/2026 | Thứ 5 | Thiết lập luồng CI/CD cơ bản cho dự án (sử dụng AWS CodePipeline hoặc GitHub Actions). | Final Project |
| 24/07/2026 | Thứ 6 | Ghi nhận tiến độ dự án tuần 8. Kiểm tra kết nối chéo giữa các module. | Báo cáo cá nhân |

### Kết quả mong đợi

* Toàn bộ tài nguyên AWS (Network, Compute, Database) hoạt động đúng chức năng, kết nối thông suốt.
* Quy trình CI/CD được thiết lập, mã nguồn thay đổi tự động được phản ánh lên môi trường triển khai.

### Tài liệu tham khảo Tuần 8

* [AWS CodePipeline Documentation](https://aws.amazon.com/codepipeline/)