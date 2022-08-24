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
<p>Tùy vào hệ điều hành máy tính bạn đang dùng mà tải bản cho phù hợp, ở đây tôi sử dụng
hệ điều hành Window 10 nên tôi sẽ tải bản Python 3.9, Miniconda3 Windows 64-bit</p>
<p>Việc cài đặt rất dễ dàng, các bạn chỉ việc Next trong các thao tác.</p>
<p>Sau khi cài đặt xong, chúng ta sẽ tiến hành các bước cài đặt thêm cho môi trường.</p>
<p>Mở Miniconda3 terminal lên, cài đặt các package sau:</p>
<b>opencv</b>
<p>Đầu tiên các bạn tạo 1 folder trong ổ cứng. VD: D:\sample_project</p>
<p>Sau đó terminal trong miniconda3 tới thư mục đó</p>

<code>
<b>cd D:\sample_project</b>
<b>mkdir env</b>
<b>conda --prefix ./env pandas numpy matplotlip scikit-learn jupyter</b>
</code>
<p>hoặc muốn cài package nào thì xài câu lệnh</p>
<p><b>conda install opencv</p>

<p>Sau đó active lên:</p>
<p><b>conda activate D:\sample_project\env</b></p>

<p>bật Jupyter Note book lên </p>
<p><b>jupyter notebook</b></p>

<p>Để thoát: ấn Ctrl + C </p>

<p>Để deactive: </p>
<p><b>conda deactive</b></p>


</body>
</html>

