# Giới thiệu

Một bài toán cổ điển trong lĩnh vực nhận dạng đó là nhận dạng chữ viết tay. Giả sử ta có những hình ảnh của các chữ số viết tay từ 0-9, được viết bởi nhiều người trong khung hình có kích thước chỉ định. Đối với bài toán này, ta dùng bộ dữ liệu MNIST, một CSDL lớn về chữ số viết tay. Với bài toán phân loại 10 lớp này, ta sử dụng SVM để xây dựng một mô hình phân loại chính xác các chữ số viết tay.

## Mô tả dữ liệu

Các nhãn là các chữ số từ 0-9 và các đặc trưng là những giá trị pixel trên một ảnh. Vì mỗi ảnh là một ma trận pixel 28 x 28 nên có 784 đặc trưng. Nhận dạng chữ số MNIST là một bài toán tốt để học tập trong cộng đồng Học máy, và nhiều người đã huấn luyện những mô hình khác nhau (Mạng nơ-ron, SVMs, CNN...) đạt tỉ lệ lỗi thấp như 0.23% (vd: độ chính xác accuracy = 99.77%, với mạng nơ-ron tích chập).

## Thực hiện

Dự án này sẽ thử nghiệm với các siêu tham số khác nhau trong SVM. Với bộ dữ liệu con chiếm 10-20% cửa dữ liệu huấn luyện train.csv, và mong đợi sẽ đạt được độ chính xác accuracy nhiều hơn 90%.
