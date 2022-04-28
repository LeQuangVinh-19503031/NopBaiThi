<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documen</title>
    <link rel="stylesheet" href="./CSS/Index.css">
    <link rel="stylesheet" href="./BS4/css/bootstrap.min.css">
    <script src="../jquery/jquery-3.6.0.min.js"></script>
    <script src="./BS4/js/bootstrap.bundle.min.js"></script>
    <script src="./BS4/js/bootstrap.min.js"></script>
</head>

<body>
    <header class="row col-sm-12">

        <div class="row col-sm-12 d-flex justify-content-between align-items-center">
            <img src="./Images/logo.PNG" alt="" class="w-25    ">
            <div class="col col-sm-8">
                <h2 class="text-center">ĐOÀN THANH NIÊN THÀNH PHỐ HỒ CHÍ MINH</h2>
                <h6 class="text-center text-danger">ĐOÀN THANH NIÊN TRƯỜNG ĐẠI HỌC CÔNG NGHIỆP THÀNH PHỐ HỒ CHÍ MINH
                </h6>
            </div>
        </div>
        <nav class="col-sm-12 navbar navbar-expand-lg alert-success">
            <div class="row col-sm-12 collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">TRANG CHỦ</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">ĐOÀN THỂ</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">SỰ KIỆN</a>
                      </li>
                    <li class=" dropdown alert m-0 p-0">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-toggle="dropdown" aria-expanded="false">
                            HOẠT ĐỘNG
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#">ĐĂNG KÝ</a>
                            <a class="dropdown-item" href="#">THAM GIA</a>
                        </div>
                    </li>
                    
            </div>
        </nav>
    </header>
    <section class="row col-sm-12 mt-0 pt-1">
        <img src="./Images/ngayhoithanhnien.JPG" alt="" class="col rounded-circle">
        <div class="col">
            <h4 class="alert d-flex justify-content-start text-warning">TIN NỔI BẬT</h4>
            <div class="row alert alert-success">
                <ol type="I" style="padding-left: 10px;">
                    <a href="#">
                        <li>Mùa hè xanh</li>
                    </a>
                    <a href="#">
                        <li>Thanh niên tình nguyện</li>
                    </a>
                    <a href="#">
                        <li>Tấm lòng vàng</li>
                    </a>
                    <a href="#">
                        <li>Hiến máu nhân đạo</li>
                    </a>
                    <a href="#">
                        <li>Bảo vệ môi trường sạch</li>
                    </a>
                    <a href="#">
                        <li>Thi đua lập thành tích chào mừng 26/03</li>
                    </a>

                </ol>
            </div>

        </div>
        <div class="col-sm-12 mt-3">
            <h5 class="d-flex justify-content-center text-warning">DANH SÁCH ĐANG KÝ HOẠT ĐỘNG MÙA HÈ XANH</h5>
            <table class="table">
                <thead>
                    <tr>
                        <th scope="col">Mã SV</th>
                        <th scope="col">Tên SV</th>
                        <th scope="col">Ngày tham gia</th>
                        <th scope="col">Email</th>
                        <th scope="col">Số điện thoại</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th scope="row">12345</th>
                        <td>LE VAN A</td>
                        <td>2021-06-25</td>
                        <td>thu@iuh.edu.vn</td>
                        <td>0121-234-214</td>
                    </tr>

                </tbody>
            </table>
        </div>
    </section>
    <footer class="col-sm-12 w-100 alert alert-success text-right bg-info" style="padding: 10px 30px; color: white;">@
        2020-2021 Đoàn thanh niên - Trường đại học Công nghiệp TP. Hồ Chí Minh</footer>
</body>

</html>
