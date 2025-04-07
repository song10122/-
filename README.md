<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>랜덤 숫자</title>
    <style>
        body {
            text-align: center;
            font-size: 2rem;
            margin-top: 20%;
        }
    </style>
</head>

<body>
    <p id="message">🥵모 아니면 도☠️</p>
    <button onclick="showRandomNumber()">눌러서 확인하기</button>

    <script>
        function showRandomNumber() {
            const randomNumber = Math.floor(Math.random() * 100) + 1;
            document.getElementById("message").innerText = "랜덤 숫자: " + randomNumber;
        }
    </script>
</body>

</html>
