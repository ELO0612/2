<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capa de Jornal com Menu Cascata</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            position: relative;
            display: inline-block;
        }
        nav ul li a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            display: block;
        }
        nav ul li a:hover {
            background-color: #575757;
        }
        nav ul li ul {
            display: none;
            position: absolute;
            background-color: #333;
            min-width: 160px;
            z-index: 1;
        }
        nav ul li:hover ul {
            display: block;
        }
        nav ul li ul li {
            display: block;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .data {
            text-align: center;
            font-size: 1em;
            margin-bottom: 20px;
        }
        .headline {
            font-size: 1.8em;
            margin: 15px 0;
        }
        .article {
            margin-bottom: 20px;
        }
        .article img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jornal do Dia</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Notícias</a>
                <ul>
                    <li><a href="#">Nacionais</a></li>
                    <li><a href="#">Internacionais</a></li>
                </ul>
            </li>
            <li><a href="#">Esportes</a></li>
            <li><a href="#">Entretenimento</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>

    <div class="container">
        <div class="data">24 de Outubro de 2024</div>
        
        <div class="headline">Título Principal da Notícia</div>
        <div class="article">
            <img src="https://via.placeholder.com/800x400" alt="Imagem da notícia">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>

        <div class="headline">Outra Notícia Importante</div>
        <div class="article">
            <img src="https://via.placeholder.com/800x400" alt="Imagem da notícia">
            <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
    </div>

    <footer>
        <p>© 2024 Jornal do Dia. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

