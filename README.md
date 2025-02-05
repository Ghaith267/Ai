<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مساعد الذكاء الاصطناعي</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="chat-container">
        <h2>مساعد الذكاء الاصطناعي</h2>
        <div id="chat-box"></div>
        <input type="text" id="user-input" placeholder="اكتب سؤالك هنا..." onkeypress="handleKeyPress(event)">
        <button onclick="sendMessage()">إرسال</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
