---
layout: post
title:  "Miniconda và Opencv Python"
date:   2022-08-24
categories: Learning
---
<html>
<body>
<h2>Cài đặt Miniconda cho việc học Python, AI</h2>
Tải Miniconda tại website: 
<a href = "https://docs.conda.io/en/latest/miniconda.html">https://docs.conda.io/en/latest/miniconda.html</a>
Tùy vào hệ điều hành máy tính bạn đang dùng mà tải bản cho phù hợp, ở đây tôi sử dụng
hệ điều hành Window 10 nên tôi sẽ tải bản Python 3.9, Miniconda3 Windows 64-bit
Việc cài đặt rất dễ dàng, các bạn chỉ việc Next trong các thao tác.
Sau khi cài đặt xong, chúng ta sẽ tiến hành các bước cài đặt thêm cho môi trường.
Mở Miniconda3 terminal lên, cài đặt các package sau:
opencv
Đầu tiên các bạn tạo 1 folder trong ổ cứng. VD: D:\sample_project
Sau đó terminal trong miniconda3 tới thư mục đó

cd D:\sample_project
mkdir env
conda --prefix ./env pandas numpy matplotlip scikit-learn jupyter
hoặc muốn cài package nào thì xài câu lệnh
conda install opencv

Sau đó active lên:
conda activate D:\sample_project\env

bật Jupyter Note book lên 
jupyter notebook


Để thoát: ấn Ctrl + C 

Để deactive: 
conda deactive


</body>
</html>

