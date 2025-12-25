# XÂY DỰNG MÔ HÌNH HỌC SÂU CHO BÀI PHÂN LOẠI BỆNH TRÊN LÁ ĐẬU TỪ HÌNH ẢNH 

**Môn học:** KHAI PHÁ DỮ LIỆU

**Lớp:** S26-65TTNT

**Giảng viên:** ThS. Vũ Thị Hạnh

**Nhóm thực hiện:** Nhóm 8

**Thành viên:**
1. Nguyễn Văn Tấn Phát
2. Nguyễn Hoàng Lộc
3. Nguyễn Thanh Hoàng

## Giới thiệu
Dự án này tập trung vào việc xây dựng mô hình học sâu (Deep Learning) để phân loại bệnh trên lá đậu bằng hình ảnh. Chúng tôi thực hiện huấn luyện và đánh giá trên 4 mô hình khác nhau, bao gồm 3 mô hình Transfer Learning phổ biến.

## Dữ liệu (Dataset)
Bộ dữ liệu được sử dụng trong dự án này là **Chicken Disease Image Classification**, có sẵn trên Kaggle.
- **Nguồn:** [Bean Leaf Lesions Classification](https://www.kaggle.com/datasets/marquis03/bean-leaf-lesions-classification)
- **Mô tả:** Bộ dữ liệu bao gồm hình ảnh là đậu phân loại cac loại bệnh khác nhau ().

## Danh sách các Notebooks
Thư mục này chứa 4 notebook tương ứng với quá trình huấn luyện của 4 mô hình:

### 1. MobileNetV3 (`02_mobilenetv3.ipynb`)
- **Mô tả:** Áp dụng kiến trúc MobileNetV3 (Small/Large) đã được huấn luyện trước trên ImageNet.
- **Mục tiêu:** Khai thác ưu điểm của MobileNet về nhẹ, nhanh và ít tham số, phù hợp cho các hệ thống triển khai trên thiết bị di động hoặc môi trường hạn chế tài nguyên, đồng thời đánh giá sự cân bằng giữa tốc độ và độ chính xác trong bài toán phân loại bệnh lá cây.

### 2. ResNet50 (`03_resnet50.ipynb`)
- **Mô tả:** Sử dụng kiến trúc ResNet50 với cơ chế Residual Learning để huấn luyện mô hình phân loại ảnh.
- **Mục tiêu:** Đánh giá khả năng trích xuất đặc trưng sâu và khả năng tổng quát hóa của ResNet trong việc phân biệt các loại bệnh lá cây có đặc trưng hình thái tương đồng.

### 3. EfficientNetB3 (`04_efficientnetb3.ipynb`)
- **Mô tả:** Sử dụng kiến trúc EfficientNetB3, mô hình được tối ưu đồng thời về chiều sâu, chiều rộng và độ phân giải ảnh.
- **Mục tiêu:** Hướng tới việc đạt độ chính xác cao nhất trên tập dữ liệu bệnh lá cây bằng cách sử dụng một kiến trúc học sâu hiện đại và hiệu quả.
- 
### 4 EDA (eda.ipynb)
- **Mô tả:** Khám phá và trực quan hóa dữ liệu

## Yêu cầu cài đặt
## Hướng dẫn sử dụng
## Cách xem nếu lỗi trên github: chuyển github.com thành .dev

