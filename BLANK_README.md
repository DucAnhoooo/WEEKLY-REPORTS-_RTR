
## `Tên: Hà Đức Anh`
<div align="center">

  ## <strong>Báo cáo tuần 1+2 </strong>
  # <a >Tìm hiểu về xử lý hình ảnh dùng opencv & Pythone</a>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Nội dung </summary>
  <ol>
    <li>
      <a href="#about-the-project"> Đếm các vật thể đơn giản trong bức ảnh</a>
      <ul>
        <li><a href="#built-with">Color Conversion</a></li>
      </ul>
      <ul>
        <li><a href="#built-with">Thresholding</a></li>
      </ul>
      <ul>
        <li><a href="#built-with">Contour Detection</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Noise image</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">...</a></li>
    <li><a href="#roadmap">....</a></li>

  </ol>
</details>





<!-- GETTING STARTED -->
## <a>1.Đếm vật thể trong bức ảnh </a>
<div align="center">
    <img src ='https://github.com/DucAnhoooo/REPORT_RTR/blob/main/images/1.PNG' width="80%" height="80%">
</div>

Để đếm được số hình tròn trong hình trên ta thực hiện một số công đoạn sau:
- 1.Load tấm ảnh 
- 2.Chuyển ảnh màu về ảnh xám
- 3.Chuyển ảnh về dạng binary
- 4.Sử dụng hàm findcontours để tìm tọa độ các điểm viền của vật 
- 5.Show kết quả


## <a>Color Conversion <a>
<div align="center">
    <img src="images/2.png" alt="Logo" width="800" height="300">
    
</div>


## <a>Thresholding </a>
<div align="center">
    <img src="images/3.png" alt="Logo" width="800" height="300">
    <img src="images/4.png" alt="Logo" width="800" height="300">
    Histogram of image: xác định giá trị threshold
    <img src="images/9.png" alt="Logo" width="800" height="300">


 Get a free API Key at [https://https://docs.opencv.org/4.x/d7/d1b/group__imgproc__misc.html#gae8a4a146d1ca78c626a53577199e9c57](https://docs.opencv.org/4.x/d7/d1b/group__imgproc__misc.html#gae8a4a146d1ca78c626a53577199e9c57)
</div


## <a>Contour detection</a>
<div align="center">
    <img src="report/images/5.png" alt="Logo" width="800" height="300">
    <img src="images/6.png" alt="Logo" width="800" height="300">

Get a free API Key at [https://docs.opencv.org/3.4/d3/dc0/group__imgproc__shape.html#ga17ed9f5d79ae97bd4c7cf18403e1689a](hhttps://docs.opencv.org/3.4/d3/dc0/group__imgproc__shape.html#ga17ed9f5d79ae97bd4c7cf18403e1689a)
</div>
## <a>DEMO</a>
<div align="center">
    <img src="images/7.png" alt="Logo" width="800" height="300">
    <strong>Result</strong>
    <img src="images/8.png" alt="Logo" width="800" height="400">

</div>

## <a>2.Noise image </a>
Nguyên tắc chung của các phương pháp lọc là cho ma trận ảnh nhân với một ma trận lọc (Kernel). Ma trận lọc lọc (Kernel) còn có thể được gọi là cửa số chập (trong phép nhân chập), cửa sổ lọc, mặt nạ,…
<div align="center">
    <img src="images/10.png" alt="Logo" width="800" height="300">
    <img src="images/11.png" alt="Logo" width="800" height="300">
    Ảnh minh họa:
    <img src="images/14.png" alt="Logo" width="800" height="300">
    <img src="images/11.png" alt="Logo" width="800" height="300">
    <img src="images/12.png" alt="Logo" width="800" height="300">
    Ảnh minh họa:
     <img src="images/15.png" alt="Logo" width="800" height="300">
    <img src="images/13.png" alt="Logo" width="800" height="300">
    Ảnh minh họa:
     <img src="images/16.png" alt="Logo" width="800" height="300">
    
</div>
## <a>Morphology </a>
<img src="images/17.png" alt="Logo" width="800" height="300">
<img src="images/18.png" alt="Logo" width="800" height="300">
<img src="images/19.png" alt="Logo" width="800" height="300">
<img src="images/20.png" alt="Logo" width="800" height="300">
<img src="images/21.png" alt="Logo" width="800" height="300">
<img src="images/22.png" alt="Logo" width="800" height="300">





