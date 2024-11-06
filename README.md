
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Pacifico&display=swap" rel="stylesheet">

    <title>Surpresa</title>
    <style>
        body {
            background-image: url('https://static.videezy.com/system/resources/thumbnails/000/051/777/original/VZ-HD-CG0010.jpg');
            background-size: cover;
            background-position: center center;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Poppins', sans-serif;  
        }
        .container {
            text-align: center;
            padding: 20px;
            background-color: white;
            color: rgb(16, 28, 192);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(240, 0, 0, 0.1);
        }
        input[type="text"] {
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 80%;
        }
        h1{
            text-align: center;
            font-size: 25px;
            font-weight: bold;
            margin-bottom: 15px;
            color: #8c00ff;  
            font-family: 'Pacifico', cursive;  
        }
        button {
            padding: 10px 20px;
            margin-top: 10px;
            background-color: #990d53;
            color: rgb(0, 0, 0);
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #a222a7;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bem-vindo!</h1>
        <label for="nome">Digite seu nome:</label><br>
        <input type="text" id="nome" name="nome" placeholder="Seu nome..."><br>
        <button onclick="continuar()">Continuar</button>
    </div>

    <script>
        function continuar() {
            const nome = document.getElementById('nome').value;
            if (nome) {
                alert('Olá, ' + nome + '\n Parabens, você foi selecionado e apartir de agora seu nome é Benzinho da Yasmin \n Atenção:Não tem mais volta');
            } else {
                alert('Por favor, digite seu nome.');
            }
        }
    </script>
</body>
</html>
