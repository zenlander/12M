<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hộp Quà Bí Ẩn</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
        }
        .gift-box {
            width: 150px;
            height: 150px;
            background-color: #ffcc00;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            font-weight: bold;
            cursor: pointer;
            margin: 100px auto;
            transition: transform 0.3s;
        }
        .gift-box:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <h1>Nhấn vào hộp quà để nhận bất ngờ!</h1>
    <div class="gift-box" onclick="openGift()">🎁</div>

    <script>
        function openGift() {
            window.location.href = "https://vt.tiktok.com/ZSrjV5oFV/";
        }
    </script>
</body>
</html>
