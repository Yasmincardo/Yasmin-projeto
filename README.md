# Yasmin-projeto
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Responsivo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Site Responsivo</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home</h2>
        <p>Este é um exemplo de site com design responsivo.</p>
    </section>

    <section id="sobre">
        <h2>Sobre</h2>
        <p>Este site se adapta a diferentes tamanhos de tela.</p>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato conosco!</p>
    </section>

    <footer>
        <p>&copy; 2024 - Site Responsivo</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
}

header {
    background-color: #333;
    color: #fff;
    width: 100%;
    padding: 1rem;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
    gap: 1rem;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    width: 100%;
    max-width: 800px;
    padding: 1rem;
    margin: 1rem 0;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
    width: 100%;
}

/* Estilos responsivos */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        gap: 0.5rem;
    }

    section {
        padding: 0.5rem;
    }
}
