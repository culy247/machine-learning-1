# Cài đặt
Trong khóa học này, chúng ta sẽ lập trình bằng ngôn ngữ lập trình Python, sử dụng Jupyter Notebook.

Làm theo hướng dẫn để có môi trường thực hành đúng theo yêu cầu của khóa học.

## Cài đặt Python 3.6

Có 2 cách cài đặt Python 3.6 trên máy tính: sử dụng bản cài đặt của Python hoặc sử dụng bản phân phối Anaconda.

Anaconda là bản phân phối có chứa nhiều package Python thông dụng cho khoa học, toán học, kỹ thuật và phân tích dữ liệu. Đây là lựa chọn được ưu tiên hơn khi cài đặt các phụ thuộc khi làm bài tập trong khóa học này. 

Download và cài đặt Anaconda tại [đây](https://anaconda.org/).

* Lưu ý: Khi cài đặt Anaconda, để chạy Python trong môi trường dòng lệnh (command line), lựa chọn option ```Add Anaconda to the system PATH enviroment variable``` trong quá trình cài đặt.

## Cài đặt các package (nếu cần)
Để thêm mới một package trong quá trình làm bài tập, các bạn sử dụng lệnh ```$ pip install <package_name>```.

Ví dụ, để cài đặt gói ```numpy```, chạy lệnh ```$ pip install numpy```.

## Bắt đầu IPython
Bài tập từng tuần đều được tạo bằng file IPython.

Sử dụng lệnh ```$ jupyter notebook``` để khởi động IPython, sau đó chọn file bài tập tương ứng và bắt đầu làm bài.

## Hướng dẫn làm bài
Trong từng tuần, cần cài đặt các gói (package) cần thiết để hoàn thành bài tập. Các gói phụ thuộc sẽ được ghi trong file requirement.txt (nếu có).

Chạy lệnh ```$ pip install -r requirement.txt``` để cài đặt các ràng buộc cần thiết. 

Đọc file ```README.txt``` trong từng tuần (nếu có) để xem hướng dẫn làm bài.

## Nộp bài
Bài tập được update hàng tuần tại [đây](https://github.com/hiendt58/machine-learning).

Các bạn cần tải bài tập và cài đặt môi trường cần thiết cho từng tuần trước khi đến lớp.

Mỗi sinh viên được yêu cầu tạo tài khoản trên Github, tạo repository với tên ```Machine Learning```.

Deadline: 23h59' ngày thứ 3 mỗi tuần.

Điểm thực hành được chấm ngẫu nhiên một trong số các bài tập từng tuần. Yêu cầu nộp bài đúng hạn và CẤM SAO CHÉP.


# Bài tập lớn
Xử lý bài toán nhận dạng chữ số viết tay với dữ liệu ```digits``` trong gói ```Scikit-learn```.

## Yêu cầu
- Tự xây dựng một mô hình phân lớp đa nhãn từ đầu (Class và các phương thức đi kèm).
- Viết notebook demo cho mô hình đã xây dựng và giải thích các cách tối ưu mô hình.

## Khóa học tham khảo
- CS231n (Standford University): [Khóa học](http://cs231n.stanford.edu/), [Bài giảng](https://www.youtube.com/playlist?list=PLlJy-eBtNFt6EuMxFYRiNRS07MCWN5UIA), [Bài tập](http://cs231n.github.io/).
- Machine Learning (Coursera): [Khóa học](https://www.coursera.org/learn/machine-learning).