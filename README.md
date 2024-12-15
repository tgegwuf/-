<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黑貓代打 - 第五人格段位代練</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
            transition: background-color 0.3s, color 0.3s;
        }
        .white-mode {
            background-color: #ffffff;
            color: #000000;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #333;
        }
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: #00bcd4;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
        }
        .container {
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #444;
        }
        .price-section h2 {
            margin-top: 40px;
        }
        .discount {
            color: #f39c12;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .toggle-mode {
            background-color: #00bcd4;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>黑貓代打 - 第五人格段位代練</h1>
        <nav>
            <a href="#prices">價格表</a>
            <a href="#discount">優惠活動</a>
            <a href="#contact">聯絡我們</a>
        </nav>
        <button class="toggle-mode" onclick="toggleMode()">切換黑/白模式</button>
    </header>
    
    <div class="container">
        <section id="discount">
            <h2>🛒 優惠活動</h2>
            <p>單筆訂單滿 <span class="discount">500元</span>，立減 <span class="discount">50元</span></p>
            <p>單筆訂單滿 <span class="discount">1000元</span>，立減 <span class="discount">120元</span></p>
            <p>單筆訂單滿 <span class="discount">1500元</span>，立減 <span class="discount">200元</span></p>
            <p>單筆訂單滿 <span class="discount">2000元</span>，立減 <span class="discount">300元</span></p>
        </section>

        <section id="prices" class="price-section">
            <h2>⭐ 蜜蜂段位代練套餐</h2>
            <table>
                <tr><th>段位進階</th><th>價格</th></tr>
                <tr><td>小蜜蜂 ➡ 獵犬</td><td>150元</td></tr>
                <tr><td>小蜜蜂 ➡ 雄鹿</td><td>400元</td></tr>
                <tr><td>小蜜蜂 ➡ 猛瑪象</td><td>800元</td></tr>
                <tr><td>小蜜蜂 ➡ 獅鳩獸</td><td>1300元</td></tr>
                <tr><td>小蜜蜂 ➡ 獨角獸</td><td>1550元</td></tr>
            </table>
            
            <h2>🕷️ 小蜘蛛段位代練套餐</h2>
            <table>
                <tr><th>段位進階</th><th>價格</th></tr>
                <tr><td>小蜘蛛 ➡ 眼鏡蛇</td><td>150元</td></tr>
                <tr><td>小蜘蛛 ➡ 鱷魚</td><td>400元</td></tr>
                <tr><td>小蜘蛛 ➡ 劍齒虎</td><td>800元</td></tr>
                <tr><td>小蜘蛛 ➡ 奇美拉</td><td>1300元</td></tr>
                <tr><td>小蜘蛛 ➡ 獨眼巨人</td><td>1550元</td></tr>
            </table>
        </section>
    </div>

    <footer>
        <p>© 2024 黑貓代打 | 聯絡我們：service@blackcat.com</p>
    </footer>

    <script>
        function toggleMode() {
            document.body.classList.toggle('white-mode');
        }
    </script>
</body>
</html>
