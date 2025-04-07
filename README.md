<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>랜덤 문구</title>
    <style>
        body {
            text-align: center;
            font-size: 2rem;
            margin-top: 20%;
        }
    </style>
</head>

<body>
    <p id="message">🔮 모아니면 도 🔮</p>
    <button onclick="showRandomMessage()">눌러서 확인하기</button>

    <script>
        function showRandomMessage() {
            const messages = [
                "오늘 하루도 화이팅!",
                "행운이 함께하길!",
                "당신은 할 수 있어!",
                "긍정적인 마인드로!",
                "무엇이든 가능하다!",
                "모든 것은 마음먹기 나름이다!"
            ];

            // 랜덤 메시지 선택
            const randomIndex = Math.floor(Math.random() * messages.length);
            document.getElementById("message").innerText = messages[randomIndex];
        }
    </script>
</body>

</html>
