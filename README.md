<!DOCTYPE html>
<html>
<head>
    <title>邹丽的个人主页</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-image: url('flowers.jpg'); /* 背景鲜花图片 */
            background-size: cover;
            transition: background-color 0.5s;
        }
        .header {
            text-align: center;
            border-bottom: 2px solid #eee;
            padding-bottom: 20px;
            margin-bottom: 20px;
        }
        .section {
            margin: 40px 0;
        }
        img {
            width: 150px;
            border-radius: 50%;
            animation: float 2s infinite ease-in-out;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #0056b3;
        }

       .bubble {
            position: absolute;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.7);
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
            animation: rise 5s infinite;
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }
        @keyframes rise {
            0% { transform: translateY(0); opacity: 1; }
            100% { transform: translateY(-100vh); opacity: 0; }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>邹丽</h1>
        <p>“代码改变世界，梦想点亮人生。”
           “在数字的世界里，寻找生活的真谛</p>
    </div>

    <div class="section">
        <h2>🌹 关于我</h2>
        <ul>
            <li>热爱运动、热爱大自然！！！</li>
            <li>现在正好樱花季，阳光那么好，是时候出去逛一逛了！</li>
            <li>有活力、有爱心、有毅力、有耐心。</li>
        </ul>
    </div>

    <div class="section">
        <h2>🎓 教育背景</h2>
        <p>武汉工程大学 · 环境工程 · 2020-2024</p>
        <p>华中农业大学 · 资源与环境 · 2024-至今</p>
    </div>

 <div class="section">
        <h2>💻 技能</h2>
        <ul>
            <li>编程语言：Python, JavaScript都还没学会</li>
            <li>框架：React, Django正准备了解一下</li>
            <li>工具：Git, Docker刚刚认识没多久</li>
            <li>运动：徒步、乒乓、羽毛球；</li>
    </div>

  <div class="section">
        <h2>😊 愿望</h2>
        <ul>
            <li>第一个愿望：全世界和平</li>
            <li>第二个愿望：每天都有好天气，每天都是好心情</li>
            <li>第三个愿望：不说出来</li>
     </div>
            
    <div class="section">
        <h2>📞 联系我</h2>
        <ul>
            <li>邮箱：1394630998@qq.com</li>
            <li>微信：猜一猜</li>
            <li>LinkedIn：here~~~<a href="#">个人主页链接</a></li>
        </ul>
    </div>

<!-- 添加彩色气泡 -->
    <div class="bubble" style="left: 10%; top: 20%; background-color: #ff69b4;"></div>
    <div class="bubble" style="left: 30%; top: 40%; background-color: #90ee90;"></div>
    <div class="bubble" style="left: 50%; top: 10%; background-color: #add8e6;"></div>
    <div class="bubble" style="left: 70%; top: 50%; background-color: #ffa500;"></div>
    <div class="bubble" style="left: 90%; top: 30%; background-color: #f0e68c;"></div>

    <script>
        // 简单的JavaScript功能，比如改变背景颜色
        function changeBackgroundColor() {
            var colors = ['red', 'blue', 'green', 'yellow'];
            var randomColor = colors[Math.floor(Math.random() * colors.length)];
            document.body.style.backgroundColor = randomColor;
        }
    </script>
</body>
</html>
