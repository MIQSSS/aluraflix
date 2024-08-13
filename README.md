<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trailers de Filmes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #fff 3px solid;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        .film {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin: 20px 0;
            padding: 20px;
            text-align: center;
        }
        .film img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .film h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .film iframe {
            width: 100%;
            height: 315px;
            border: none;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Trailers de Filmes</h1>
        </div>
    </header>

    <div class="container">
        <div class="film">
            <h2>Vingadores: Ultimato</h2>
            <iframe src="https://www.youtube.com/embed/TcMBFSGVi1c" allowfullscreen></iframe>
        </div>

        <div class="film">
            <h2>Homem-Aranha: Através do Aranhaverso</h2>
            <iframe src="https://www.youtube.com/embed/0sA8AD0xk80" allowfullscreen></iframe>
        </div>

        <div class="film">
            <h2>Capitão América: Guerra Civil</h2>
            <iframe src="https://www.youtube.com/embed/dKrVegVI0Us" allowfullscreen></iframe>
        </div>
    </div>
</body>
</html>
