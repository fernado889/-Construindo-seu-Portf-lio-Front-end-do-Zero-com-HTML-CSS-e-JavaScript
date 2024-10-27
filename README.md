# -Construindo-seu-Portf-lio-Front-end-do-Zero-com-HTML-CSS-e-JavaScript
portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── styles.css
└── js/
    └── scripts.js
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Meu Portfólio</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">Sobre</a></li>
                <li><a href="projects.html">Projetos</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Meus Projetos</h2>
            <!-- Adicione uma lista de seus projetos aqui -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Meu Nome</p>
    </footer>
    <script src="js/scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

h1, h2 {
    margin: 20px 0;
}
document.addEventListener('DOMContentLoaded', () => {
    console.log('Portfólio carregado!');
    // Adicione interatividade aqui
});
<section>
    <h2>Meus Projetos</h2>
    <article>
        <h3>Projeto 1</h3>
        <p>Descrição do projeto 1. <a href="link-do-projeto.com">Veja mais</a></p>
    </article>
    <article>
        <h3>Projeto 2</h3>
        <p>Descrição do projeto 2. <a href="link-do-projeto.com">Veja mais</a></p>
    </article>
</section>
