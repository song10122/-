# -
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

            const messages = 

import random

random_number = random.randint(1, 100)

print(random_number)

            ];

            document.getElementById("message").innerText = messages[Math.floor(Math.random() * messages.length)];

        }

    </script>

</body>

</html>

