<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário de Namoro</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: 'Arial', sans-serif;
        }
        .container {
            text-align: center;
        }
        .brasao {
            width: 150px;
            margin-bottom: 20px;
        }
        .heart {
            font-size: 100px;
            color: red;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .heart:hover {
            transform: scale(1.1);
        }
        .message {
            display: none;
            font-size: 24px;
            color: #333;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="brasao.png" alt="Brasão G & í" class="brasao">
        <h1>Feliz Aniversário de Namoro!</h1>
        <p>22/05/2024</p>
        <div class="heart" onclick="showMessage()">❤️</div>
        <div class="message" id="message">Te amo! Quase 5 anos, né?</div>
    </div>

    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
