# Workflow Dự Án

## Tổng Quan
Dự án này là một ứng dụng cho phép người dùng tạo và phân tích biểu đồ cơ cấu doanh thu thông qua việc nhập prompt tự nhiên.

## Workflow Xử Lý Prompt Vẽ Biểu Đồ Cơ Cấu Doanh Thu

### 1. Nhận Prompt từ Người Dùng
- Người dùng nhập prompt mô tả yêu cầu vẽ biểu đồ cơ cấu doanh thu
- Ví dụ: "Vẽ biểu đồ cơ cấu doanh thu theo ngành hàng năm 2023"

### 2. Xử Lý và Phân Tích Prompt
- Hệ thống phân tích prompt để xác định:
  - Loại biểu đồ cần vẽ (pie chart, bar chart, etc.)
  - Thời gian phân tích (năm, quý, tháng)
  - Các tiêu chí phân loại doanh thu
  - Các yêu cầu đặc biệt về định dạng hoặc hiển thị

### 3. Truy Vấn Dữ Liệu
- Hệ thống truy vấn cơ sở dữ liệu để lấy thông tin doanh thu
- Lọc dữ liệu theo các tiêu chí đã xác định từ prompt
- Tính toán các chỉ số cần thiết (tỷ lệ phần trăm, tổng doanh thu, etc.)

### 4. Tạo Biểu Đồ
- Sử dụng thư viện đồ họa để tạo biểu đồ
- Áp dụng các định dạng và style phù hợp
- Thêm các thành phần như:
  - Tiêu đề biểu đồ
  - Chú thích
  - Đơn vị tính
  - Màu sắc phân biệt

### 5. Lưu Trữ và Xuất
- Lưu biểu đồ dưới dạng file ảnh
- Tạo báo cáo kèm theo biểu đồ
- Lưu thông tin metadata về biểu đồ

### 6. Hiển Thị Kết Quả
- Hiển thị biểu đồ cho người dùng
- Cung cấp các tùy chọn:
  - Tải xuống biểu đồ
  - Chia sẻ biểu đồ
  - Chỉnh sửa biểu đồ
  - Xuất báo cáo

## Các Tính Năng Bổ Sung
- Lưu lịch sử các biểu đồ đã tạo
- Tùy chỉnh giao diện biểu đồ
- Tự động cập nhật dữ liệu
- Hỗ trợ nhiều định dạng xuất file

## Yêu Cầu Hệ Thống
- Python 3.8+
- Các thư viện cần thiết:
  - pandas
  - matplotlib
  - seaborn
  - plotly
  - numpy

## Cài Đặt
```bash
pip install -r requirements.txt
```

## Sử Dụng
1. Chạy ứng dụng
2. Nhập prompt mô tả biểu đồ cần tạo
3. Đợi hệ thống xử lý và hiển thị kết quả
4. Tùy chỉnh và xuất biểu đồ theo nhu cầu 