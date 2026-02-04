# Biểu diễn ảnh màu và lọc tín hiệu

## Mục tiêu
Thực hành các kỹ thuật xử lý ảnh cơ bản, bao gồm biểu diễn ảnh màu – ảnh xám, xử lý kênh màu và áp dụng các phép lọc không gian.

## Phần 1: Biểu diễn ảnh màu và ảnh xám
- Load một hoặc nhiều ảnh màu (RGB).
- Chuyển đổi ảnh màu sang ảnh xám và ngược lại.
- Tách các kênh màu R, G, B và hiển thị từng kênh dưới dạng ảnh xám.
- Kết hợp các kênh màu để:
  - Tái tạo ảnh màu ban đầu.
  - Tạo ảnh màu mới bằng cách hoán đổi hoặc thay thế kênh màu.
- Nhận xét sự khác biệt trực quan khi thay đổi hoặc thiếu thông tin kênh màu.

## Phần 2: Lọc ảnh với Low-pass và High-pass Filter
- Load ảnh đầu vào (ảnh màu hoặc ảnh xám).
- Áp dụng low-pass filtering (Gaussian, Median) để làm trơn ảnh và giảm nhiễu.
- Áp dụng high-pass filtering (Sobel, Laplacian) để làm nổi biên và chi tiết ảnh.
- Các phép lọc được áp dụng trên nhiều ảnh khác nhau (ít nhất 2–3 ảnh).
- Trình bày kernel sử dụng và ý nghĩa của từng phép lọc.

## Công cụ sử dụng
- Python
- OpenCV
- NumPy
- Jupyter Notebook

## Ghi chú
- Ảnh đầu vào được lưu trong thư mục `images/`.
- Kết quả được so sánh trực quan giữa ảnh gốc và ảnh sau khi xử lý.
- Phần phân tích và đánh giá chi tiết được trình bày trong báo cáo.
