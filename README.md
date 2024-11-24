<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang web của tôi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background: #4CAF50;
            color: rgb(255, 255, 255);
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>mày thích đấm nhau thì cho xin cái lịch hẹn</h1>
    </header>
    <nav>
        <a href="#gioithieu">QUỲNH SƯ TỬ</a>
    </nav>
    <main>
        <section id="gioithieu">
            <h2>Giới thiệu</h2>
            <p>Quỳnh mỏ hơi hỗn rất láo nháo </p>
        </section>
        <section id="dichvu">
            <h2>Sở Thích</h2>
            <ul>
                <li>thích trai đẹp nhất là Phạm HỒNG ANH</li>
                <li>đây là fb của anh ấy https://www.facebook.com/profile.php?id=100041749986876&sk=about</li>
                <li>Hỗ trợ kỹ thuật Nguyễn Văn Chí nếu đóng góp ý kiến thêm hãy để lại thông tin ở phần liên hệ</li>
            </ul>
        </section>
        <section id="lienhe">
            <h2>Liên hệ</h2>
            <form action="#" method="post">
                <label for="name">Họ Và Tên :</label>
                <input type="text" id="name" name="name" placeholder="Nhập họ và tên" required>
                <br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Nhập email" required>
                <br><br>
                <label for="message">Lời nhắn:</label>
                <textarea id="message" name="message" placeholder="Nhập lời nhắn" rows="5" required></textarea>
                <br><br>
                <button type="submit">Gửi</button>
            </form>
        </section>
    </main>
    <footer>
        &copy; 2024 Trang web của tôi. Mọi quyền được bảo lưu.
    </footer>
</body>
</html>
