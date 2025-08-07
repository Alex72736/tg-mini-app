# tg-mini-app
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Моя Mini App</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            background: #f0f8ff;
        }
        button {
            padding: 10px 20px;
            background: #0088cc;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Привет! 👋</h1>
    <p>Это моё приложение в Telegram!</p>
    <button onclick="Telegram.WebApp.sendData('Hello!')">Отправить</button>
</body>
</html>
