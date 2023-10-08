
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>自我介紹網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
        }

        .left-image, .right-content {
            flex: 1;
            padding: 10px;
        }

        .left-image img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
        }

        .right-content p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>歡迎來到我的自我介紹網站</h1>
    </header>

    <div class="container">
        <div class="left-image">
            <img src="left-image.jpg" alt="左側圖片">
        </div>
        <div class="right-content">
            <h2>關於我</h2>
            <p>你的自我介紹文字在這裡。你可以講述你的背景、技能、興趣和目標。</p>

            <h2>我的作品</h2>
            <p>這裡可以展示你的作品、專案或經驗。你可以使用圖片和文字來描述它們。</p>

            <h2>聯絡我</h2>
            <p>如果你想與我聯絡，請使用以下方式：</p>
            <ul>
                <li>Email: your.email@example.com</li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile">LinkedIn Profile</a></li>
                <li>Twitter: <a href="https://twitter.com/yourusername">Twitter Profile</a></li>
            </ul>
        </div>
    </div>
</body>
</html>
