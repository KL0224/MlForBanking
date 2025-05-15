# 🏦 Banking Machine Learning Projects

## 1. Tổng quan

Dự án tổng hợp một số bài toán trong lĩnh vực ngân hàng, được giải quyết bằng các kỹ thuật Machine Learning. Các bài toán bao gồm:

- **Cross-sell Prediction** – Dự đoán khả năng bán chéo sản phẩm
- **Customer Churn** – Dự đoán khách hàng rời đi
- **Customer Segmentation** – Phân khúc khách hàng
- **Loan Repayment** – Dự đoán khả năng trả nợ

---

## 2. Xử lý và tiền xử lý dữ liệu

Trước khi đưa vào mô hình học máy, dữ liệu cần được xử lý và phân tích cẩn thận. Một số kỹ thuật đã sử dụng:

- **Phân tích dữ liệu**:
  - Kiểm tra hệ số tương quan (`correlation`)
  - Phát hiện và xử lý giá trị ngoại lai (`outliers`)
   ...
- **Tiền xử lý dữ liệu**:
  - Mã hóa biến phân loại bằng `get_dummies`
  - Giải quyết vấn đề mất cân bằng dữ liệu bằng `SMOTE`
  - Chuẩn hóa dữ liệu bằng `MinMaxScaler`
  ...
---

## 3. Mô hình và thuật toán

Sau khi tiền xử lý dữ liệu, các mô hình phổ biến đã được sử dụng để huấn luyện và đánh giá:

- `Logistic Regression`
- `XGBoost`
- `Decision Tree`
- `Random Forest`
...
Mỗi mô hình được đánh giá dựa trên độ chính xác, độ phủ và khả năng tổng quát hóa để chọn ra mô hình tối ưu nhất cho từng bài toán cụ thể.
