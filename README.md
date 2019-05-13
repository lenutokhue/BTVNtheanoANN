# BTVNtheanoANN
Deep Learning Homework using Theano.

[Nhóm 1] [Deep Learning] ANN dùng thư viện Theano.

•	Mục tiêu bài tập: Dùng thư viện Theano kết hợp thuật toán backpropagation huấn luyện model ANN nhận dạng chữ số viết tay.

•	Dữ liệu:

  - Training : ex4data1.mat => 5000 examples. (File này được lưu ở định dạng “.mat” của Octave/Matlab. Để đọc dữ liệu trong python, ta sẽ sử dụng hàm “scipy.io.loadmat”)

  - Testing : 

•	Đầu vào của model là hình ảnh thang màu xám (grayscale image) có shape là 20x20.

•	Đầu ra của model là 10 node tương ứng xác suất dự đoán của 10 số trong hệ thập phân.

•	Model có 1 hidden layer có số node là 25.

•	Accuracy dự đoán cuối cùng là 0.953000.
