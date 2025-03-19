<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Meu Portfólio</h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#projetos">Projetos</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Seção Sobre -->
    <section id="sobre">
        <div class="container">
            <h2>Sobre Mim</h2>
            <p>Sou desenvolvedor web com experiência em front-end e design. Apaixonado por criar soluções criativas para problemas complexos.</p>
        </div>
    </section>

    <!-- Seção Projetos -->
    <section id="projetos">
        <div class="container">
            <h2>Meus Projetos</h2>
            <div class="projeto">
                <img src="projeto1.jpg" alt="Projeto 1">
                <p>Projeto 1 - Descrição do projeto.</p>
            </div>
            <div class="projeto">
                <img src="projeto2.jpg" alt="Projeto 2">
                <p>Projeto 2 - Descrição do projeto.</p>
            </div>
        </div>
    </section>

    <!-- Seção Contato -->
    <section id="contato">
        <div class="container">
            <h2>Entre em Contato</h2>
            <form>
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Meu Portfólio. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>

