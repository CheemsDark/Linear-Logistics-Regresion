# Linear-Logistics-Regresion

#  Cài đặt cơ bản các thuật toán Machine Learning: Linear & Logistic Regression

Dự án này bao gồm các bản triển khai (implementation) từ con số không (from scratch) của hai thuật toán nền tảng trong Học máy (Machine Learning) bằng Python và thư viện `numpy`. Trọng tâm của dự án là hiểu rõ cơ sở toán học đằng sau các mô hình dự đoán và phân loại.

## 📂 Cấu trúc thư mục

```text
.
├── data1.csv       # Dataset 30 mẫu cho bài toán Linear Regression
├── data2.csv           # Dataset 40 mẫu cho bài toán Logistic Regression
├── data3.csv          # Dataset mở rộng 50 mẫu (Augmented Data)
├── data4.csv          # Dataset mở rộng 50 mẫu (Augmented Data)
├── LinearRegression1.ipynb     # Notebook: Dự đoán cân nặng
├── LogisticRegression1.ipynb   # Notebook: Phân loại đỗ/trượt
├── LinearRegression2.ipynb     # Notebook: Dự đoán giá nhà
├── Logistic2Regression2.ipynb   # Notebook: Phân loại hồ sơ cho vay
└── README.md
```

Nội dung chi tiết các bài toán1. Linear Regression (Hồi quy tuyến tính)Bài toán: Dự đoán cân nặng (kg) của một người dựa trên chiều cao (cm).Loại bài toán: Regression (Hồi quy giá trị liên tục).Thuật toán sử dụng: Nghiệm chính xác (Exact solution) sử dụng Đại số tuyến tính với công thức Giả nghịch đảo (Pseudo-inverse matrix).Công thức nghiệm: $\mathbf{w} = (\mathbf{\bar{X}}^T \mathbf{\bar{X}})^{-1} \mathbf{\bar{X}}^T \mathbf{y}$Tính năng:Tự động tách tập dữ liệu thành tập Huấn luyện (Train set) và tập Kiểm thử (Test set).Vẽ đường thẳng hồi quy (Fitting line) trực quan hóa xu hướng dữ liệu.So sánh đối chiếu kết quả tính tay với thư viện scikit-learn chuẩn công nghiệp.2. Logistic Regression (Hồi quy Logistic)Bài toán: Dự đoán xác suất vượt qua kỳ thi (Pass/Fail) dựa trên số giờ tự học của sinh viên.Loại bài toán: Binary Classification (Phân loại nhị phân).Thuật toán sử dụng: Tối ưu hóa hàm mất mát bằng thuật toán Stochastic Gradient Descent (SGD) kết hợp với hàm kích hoạt Sigmoid.Hàm Sigmoid: $y = \frac{1}{1 + e^{-\mathbf{w}^T\mathbf{x}}}$Tính năng:Khởi tạo trọng số ngẫu nhiên và cập nhật liên tục qua từng vòng lặp.Sử dụng kỹ thuật xáo trộn dữ liệu (mix data) để tránh tối ưu cục bộ.Trực quan hóa đường cong Sigmoid và chỉ ra Ngưỡng quyết định (Decision Boundary) rõ ràng trên đồ thị.


Hướng dẫn cài đặt và sử dụng
1. Yêu cầu môi trường (Dependencies)
Đảm bảo bạn đã cài đặt Python 3.x và các thư viện hỗ trợ xử lý dữ liệu, vẽ đồ thị:

##pip install numpy pandas matplotlib scikit-learn

2. Cách chạy code

Mở terminal/command prompt tại thư mục chứa dự án.

Khởi động Jupyter Notebook bằng lệnh:
## jupyter notebook
