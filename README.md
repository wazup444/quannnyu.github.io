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

        #flavors {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .flavor-card {
            width: 300px;
            margin: 10px;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
        }

        .flavor-card img {
            width: 100%;
            border-radius: 5px;
        }

        .flavor-card h3 {
            margin-top: 15px;
        }

        .flavor-card p {
            margin-top: 10px;
        }

        .flavor-card .rating {
            margin-top: 10px;
        }

        .flavor-card .price {
            margin-top: 10px;
            font-weight: bold;
            color: #333;
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
            <a href="(https://24h.pchome.com.tw/prod/DBAY12-A9007ZA2W?gclid=Cj0KCQiA67CrBhC1ARIsACKAa8RqSTVT5JMrFF0Ow4MQ0Hk_f_JgroixbftAZccXEbgrw6_EfgAjkOwaAoj1EALw_wcB)"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTgIcBcxDAcdcWHK4np-VAdrL7tuFwDMo--Thaiw23LHXKAuvk1U3hvRnLV3ZPByCK-es&usqp=CAU" width="200" height="100"></a>
            <h3>豚骨拉麵</h3>
            <p>濃郁的豚骨湯頭，配上彈牙的拉麵，是日本最受歡迎的泡麵之一。</p>
            <div class="rating">評分: 4.5/5</div>
            <div class="price">價格: 85元</div>
        </div>
        <div class="flavor-card">
            <img src="ramen2.jpg" alt="泰式冬陰麵圖片">
            <h3>泰式冬陰麵</h3>
            <p>帶有酸辣風味的湯頭，搭配著香料和肉片，是泰國風味的泡麵選擇。</p>
            <div class="rating">評分: 4.2/5</div>
            <div class="price">價格: 60元</div>
        </div>
        <div class="flavor-card">
            <img src="ramen3.jpg" alt="味增拉麵圖片">
            <h3>味增拉麵</h3>
            <p>富有深厚風味的味增湯頭，搭配著麵條和各種配料，是日本傳統風味的泡麵。</p>
            <div class="rating">評分: 4.7/5</div>
            <div class="price">價格: 33元</div>
        </div>
        <div class="flavor-card">
            <img src="ramen4.jpg" alt="海鮮湯麵圖片">
            <h3>海鮮湯麵</h3>
            <p>新鮮海鮮的鮮味融入湯頭，清爽可口，是喜愛海鮮的人士的最愛。</p>
            <div class="rating">評分: 4.4/5</div>
            <div class="price">價格: 31元</div>
        </div>
        <div class="flavor-card">
            <img src="ramen5.jpg" alt="辛拉麵圖片">
            <h3>辛拉麵</h3>
            <p>帶有辣味的湯頭，搭配韓式泡菜和嫩滑的拉麵，是喜愛辣味的人士的不二之選。</p>
            <div class="rating">評分: 4.8/5</div>
            <div class="price">價格: 35元</div>
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
