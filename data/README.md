**📂 Mô tả dữ liệu (Data Description)**

**1. Nguồn dữ liệu**

Bộ dữ liệu được sử dụng trong đề tài này là Stroke Prediction Dataset từ nền tảng Kaggle.
Dữ liệu được công khai phục vụ mục đích học tập và nghiên cứu.

**2. Cấu trúc thư mục**

<pre>
data/
├── raw/
│   └── healthcare-dataset-stroke-data.csv
├── processed/
│   └── stroke_clean.csv
└── README.md
</pre>

**3. Mô tả các biến dữ liệu**

| Tên biến | Ý nghĩa |
|----------|--------|
| id | Mã định danh bệnh nhân |
| gender | Giới tính |
| age | Tuổi |
| hypertension | Tăng huyết áp (0: Không, 1: Có) |
| heart_disease | Bệnh tim mạch (0/1) |
| ever_married | Tình trạng hôn nhân |
| work_type | Loại hình công việc |
| Residence_type | Khu vực sinh sống |
| avg_glucose_level | Mức đường huyết trung bình |
| bmi | Chỉ số khối cơ thể |
| smoking_status | Tình trạng hút thuốc |
| stroke | Nhãn mục tiêu (0: Không đột quỵ, 1: Có đột quỵ) |


**4. Tiền xử lý dữ liệu**

    - Các bước tiền xử lý đã thực hiện:

    - Loại bỏ hoặc điền giá trị thiếu (missing values)

    - Chuẩn hóa tên cột

    - Mã hóa các biến phân loại

    - Chuẩn hóa dữ liệu số

    - File sau xử lý được lưu tại: data/processed/stroke_clean.csv