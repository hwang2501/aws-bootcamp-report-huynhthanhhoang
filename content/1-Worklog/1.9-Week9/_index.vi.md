---
title: "Nhật ký công việc Tuần 9"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b>1.9.</b> "
---

### Mục tiêu tuần

* Xây dựng quy trình xử lý tài liệu bằng AI.
* Tích hợp AWS Lambda và Amazon Textract.
* Sử dụng Amazon Bedrock để phân tích nội dung tài liệu.
* Lưu kết quả xử lý vào Amazon DynamoDB.
* Đồng bộ trạng thái xử lý bằng AWS AppSync.

### Công việc thực hiện trong tuần

| Day | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|-------------------|
| 2 | - Cấu hình Amazon S3 Event Trigger để tự động kích hoạt AWS Lambda khi người dùng tải tài liệu lên. | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 3 | - Xây dựng hàm AWS Lambda xử lý tài liệu.<br>- Tích hợp Amazon Textract để trích xuất nội dung từ tài liệu PDF và hình ảnh. | 17/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/textract/ |
| 4 | - Tích hợp Amazon Bedrock để phân tích nội dung tài liệu.<br>- Xây dựng chức năng tóm tắt và phân loại tài liệu tự động. | 18/06/2026 | 18/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 5 | - Thiết kế và lưu kết quả xử lý AI vào Amazon DynamoDB.<br>- Kiểm thử quy trình xử lý tài liệu. | 19/06/2026 | 19/06/2026 | https://docs.aws.amazon.com/amazondynamodb/ |
| 6 | - Tích hợp AWS AppSync Subscription để cập nhật trạng thái xử lý theo thời gian thực.<br>- Hoàn thiện quy trình AI Pipeline. | 20/06/2026 | 20/06/2026 | https://docs.aws.amazon.com/appsync/ |

### Kết quả đạt được

* Hoàn thành quy trình AI Pipeline từ Amazon S3 đến AWS Lambda.
* Tích hợp thành công Amazon Textract để trích xuất nội dung tài liệu.
* Sử dụng Amazon Bedrock để tự động tóm tắt và phân loại tài liệu.
* Lưu kết quả xử lý vào Amazon DynamoDB.
* Hoàn thiện chức năng cập nhật trạng thái xử lý theo thời gian thực bằng AWS AppSync.