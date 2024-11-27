<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khám Phá Thế Giới Động Vật</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            color: #333;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: #2980b9;
        }

        h1, h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        /* Header Section */
        header {
            background: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        /* Section Layout */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }

        section {
            margin: 40px 0;
        }

        /* About Section */
        .about {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 20px;
        }

        .about img {
            width: 50%;
            max-width: 500px;
            border-radius: 10px;
        }

        .about-text {
            flex: 1;
        }

        .about-text h2 {
            color: #27ae60;
            margin-bottom: 10px;
        }

        .about-text p {
            text-align: justify;
        }

        /* Table Section */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            text-align: center;
            padding: 10px;
            border: 1px solid #ddd;
        }

        th {
            background: #27ae60;
            color: white;
        }

        tr:nth-child(even) {
            background: #f9f9f9;
        }

        tr:hover {
            background: #f1f1f1;
        }

        /* Card Grid Section */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card-content {
            padding: 15px;
        }

        .card-content h3 {
            color: #34495e;
            margin-bottom: 10px;
        }

        .card-content p {
            color: #7f8c8d;
        }

        .card-content a {
            display: inline-block;
            margin-top: 10px;
            color: #27ae60;
            font-weight: bold;
        }

        /* Footer */
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Khám Phá Thế Giới Động Vật</h1>
        <p>Cùng tìm hiểu sự đa dạng và kỳ thú của các loài động vật trên thế giới</p>
    </header>

    <!-- Main Container -->
    <div class="container">
        <!-- About Section -->
        <section class="about">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Lion_waiting_in_Namibia.jpg" alt="Thế giới động vật">
            <div class="about-text">
                <h2>Về Thế Giới Động Vật</h2>
                <p>Thế giới động vật là một trong những điều kỳ diệu nhất của tự nhiên. Mỗi loài động vật đều có một câu chuyện, tập tính và vai trò riêng trong hệ sinh thái. Hãy cùng khám phá các loài động vật và hiểu thêm về tầm quan trọng của việc bảo vệ môi trường sống tự nhiên.</p>
            </div>
        </section>

        <!-- Table Section -->
        <section>
            <h2>Bảng Thông Tin Các Loài Động Vật</h2>
            <table>
                <thead>
                    <tr>
                        <th>Tên</th>
                        <th>Phân Loại</th>
                        <th>Môi Trường Sống</th>
                        <th>Tuổi Thọ</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Hổ</td>
                        <td>Thú</td>
                        <td>Rừng nhiệt đới</td>
                        <td>20-25 năm</td>
                    </tr>
                    <tr>
                        <td>Đại bàng</td>
                        <td>Chim</td>
                        <td>Trên núi</td>
                        <td>30-40 năm</td>
                    </tr>
                    <tr>
                        <td>Cá heo</td>
                        <td>Động vật biển</td>
                        <td>Đại dương</td>
                        <td>40-60 năm</td>
                    </tr>
                    <tr>
                        <td>Voi</td>
                        <td>Thú</td>
                        <td>Rừng và đồng cỏ</td>
                        <td>60-70 năm</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Card Section -->
        <section>
            <h2>Hình Ảnh Minh Họa</h2>
            <div class="card-grid">
                <div class="card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg" alt="Hổ">
                    <div class="card-content">
                        <h3>Hổ</h3>
                        <p>Hổ là loài thú lớn, được xem như vua của rừng rậm.</p>
                        <a href="#">Xem chi tiết</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://thienduongchim.com/wp-content/uploads/2016/01/g%C3%A0-l%C3%B4i-l%C3%A0m-%C4%91u%C3%B4i-tr%E1%BA%AFng.jpg" alt=""width="200" height="200">
                    <div class="card-content">
                        <h3>Đại Bàng</h3>
                        <p>Loài chim săn mồi mạnh mẽ, được mệnh danh là "Chúa tể bầu trời".</p>
                        <a href="#">Xem chi tiết</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Common_dolphin_noaa.jpg" alt="Cá heo">
                    <div class="card-content">
                        <h3>Cá Heo</h3>
                        <p>Cá heo là động vật thông minh và thân thiện.</p>
                        <a href="#">Xem chi tiết</a>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 - Thế Giới Động Vật | Thiết kế bởi Bạn</p>
    </footer>

</body>
</html>
