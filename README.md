
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>泡麵探索</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 40px;
        }

        #about, #flavors {
            background-color: #f4f4f4;
        }

        .flavor-card {
            margin-bottom: 30px;
        }

        .flavor-card img {
            width: 100%;
            border-radius: 5px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>泡麵探索</h1>
        <p>發現不同的泡麵文化</p>
    </header>

    <section id="about">
        <h2>關於我們</h2>
        <p>歡迎來到我們的泡麵探索網站。我們將介紹世界各地的美味泡麵，讓您更深入地了解這個美味的快餐。</p>
    </section>

    <section id="flavors">
        <h2>口味介紹</h2>
        <div class="flavor-card">
            <img src="ramen1.jpg" alt="拉麵圖片">
            <h3>豚骨拉麵</h3>
            <p>濃郁的豚骨湯頭，配上彈牙的拉麵，是日本最受歡迎的泡麵之一。</p>
        </div>
        <div class="flavor-card">
            <img src="ramen2.jpg" alt="泰式冬陰麵圖片">
            <h3>泰式冬陰麵</h3>
            <p>帶有酸辣風味的湯頭，搭配著香料和肉片，是泰國風味的泡麵選擇。</p>
        </div>
        <!-- 可以繼續添加其他口味的卡片 -->
    </section>

    <footer>
        <p>© 2023 泡麵探索網站</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
    <script>
        // 如果需要添加一些動態效果，可以在這裡使用 jQuery
        // 例如: $(".flavor-card").hover(function() { $(this).toggleClass("hover"); });
    </script>
</body>
</html>

