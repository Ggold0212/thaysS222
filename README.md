<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Namoro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            text-align: center;
            padding: 50px;
        }
        .container {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
        }
        .button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 15px 30px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 20px 0;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #ff1493;
        }
        .message {
            display: none;
            font-size: 18px;
            color: #32cd32;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Você quer namorar comigo psicolinda?</h1>
        <button class="button" onclick="acceptProposal()">Sim, aceito!</button>
        <div class="message" id="acceptMessage">Eu aceito namorar com você! ❤️</div>
    </div>

    <script>
        function acceptProposal() {
            document.getElementById('acceptMessage').style.display = 'block';
        }
    </script>
</body>
</html>
