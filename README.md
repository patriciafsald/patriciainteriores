<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Interiores</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            padding: 2rem;
        }
        .projetos {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .projeto {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: calc(33.333% - 1rem);
        }
        .projeto img {
            width: 100%;
            height: auto;
        }
        .projeto h3 {
            margin: 0;
            padding: 1rem;
            background-color: #333;
            color: #fff;
        }
        .projeto p {
            padding: 1rem;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer .social {
            margin-top: 0.5rem;
        }
        footer .social a {
            color: #fff;
            margin: 0 0.5rem;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portfólio de Interiores</h1>
    </header>
    <div class="container">
        <section>
            <h2>Sobre Mim</h2>
            <p>Sou um designer de interiores especializado em criar espaços modernos e funcionais. Minha paixão pela arquitetura contemporânea brasileira se reflete em cada um dos meus projetos.</p>
        </section>
        <section>
            <h2>Projetos</h2>
            <div class="projetos">
                <div class="projeto">
                    <img src="projeto1.jpg" alt="Projeto 1">
                    <h3>Projeto 1</h3>
                    <p>Descrição do Projeto 1.</p>
                </div>
                <div class="projeto">
                    <img src="projeto2.jpg" alt="Projeto 2">
                    <h3>Projeto 2</h3>
                    <p>Descrição do Projeto 2.</p>
                </div>
                <div class="projeto">
                    <img src="projeto3.jpg" alt="Projeto 3">
                    <h3>Projeto 3</h3>
                    <p>Descrição do Projeto 3.</p>
                </div>
                <!-- Adicione mais projetos conforme necessário -->
            </div>
        </section>
    </div>
    <footer>
        <p>© 2024 Meu Nome</p>
        <div class="social">
            <a href="https://www.facebook.com">Facebook</a>
            <a href="https://www.instagram.com">Instagram</a>
            <a href="https://www.linkedin.com">LinkedIn</a>
        </div>
    </footer>
</body>
</html>
