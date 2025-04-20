<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fff;
        }
        .container {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
        }
        .left, .right {
            width: 50%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .left:hover {
            background-color: #4a90e2; /* Azul médio */
        }
        .right:hover {
            background-color: #90ee90; /* Verde claro */
        }
        .left a, .right a {
            text-decoration: none;
            color: #333;
            font-size: 2rem;
            font-weight: bold;
        }
        .photo {
            position: absolute;
            top: 10%;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid #ddd;
            background-image: url('sua-foto.jpg'); /* Substitua por sua foto */
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="photo"></div>
        <div class="left">
            <a href="informacoes.html">Informações</a>
        </div>
        <div class="right">
            <a href="visual.html">Visual</a>
        </div>
    </div>
</body>
</html>
