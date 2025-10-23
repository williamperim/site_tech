<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechStore - Eletrônicos Modernos</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <header class="main-header">
        <div class="container">
            <h1 class="logo">TechStore</h1>

            <nav class="main-nav">
                <ul>
                    <li><a href="#inicio">Início</a></li>
                    <li><a href="#produtos">Produtos</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#contato">Contato</a></li>
                    <li><a href="#avaliacoes">Avaliações</a></li>
                </ul>
            </nav>

            <form class="search-form">
                <input type="search" placeholder="O que você procura?">
                <button type="submit">Buscar</button>
            </form>
        </div>
    </header>

    <main>
        <section id="inicio" class="banner">
            <div class="banner-content">
                <h2>Super Ofertas de Outono!</h2>
                <p>Os melhores gadgets com até 40% OFF.</p>
                <a href="#produtos" class="btn">Compre Agora</a>
            </div>
            </section>

        <section id="produtos" class="container section-padding">
            <h2>Produtos em Destaque</h2>
            <div class="product-grid">
                
                <article class="product-card">
                    <img src="imagens/produto1.jpg" alt="Smartphone XYZ">
                    <h3>Smartphone XYZ</h3>
                    <p class="price">R$ 2.999,00</p>
                    <button class="btn-add-cart">Adicionar ao carrinho</button>
                </article>

                <article class="product-card">
                    <img src="imagens/produto2.jpg" alt="Fone Bluetooth Pro">
                    <h3>Fone Bluetooth Pro</h3>
                    <p class="price">R$ 899,00</p>
                    <button class="btn-add-cart">Adicionar ao carrinho</button>
                </article>

                <article class="product-card">
                    <img src="imagens/produto3.jpg" alt="Smartwatch Tech">
                    <h3>Smartwatch Tech</h3>
                    <p class="price">R$ 1.450,00</p>
                    <button class="btn-add-cart">Adicionar ao carrinho</button>
                </article>

                <article class="product-card">
                    <img src="imagens/produto4.jpg" alt="Notebook UltraSlim">
                    <h3>Notebook UltraSlim</h3>
                    <p class="price">R$ 5.999,00</p>
                    <button class="btn-add-cart">Adicionar ao carrinho</button>
                </article>

            </div>
        </section>

        <section id="sobre" class="about-section section-padding">
            <div class="container about-content">
                <img src="imagens/loja.jpg" alt="Equipe TechStore ou fachada da loja">
                <div class="about-text">
                    <h2>Sobre a TechStore</h2>
                    <p>Fundada em 2020, a TechStore nasceu da paixão por tecnologia e inovação. Nossa missão é conectar pessoas aos melhores e mais modernos dispositivos eletrônicos do mercado, oferecendo um catálogo selecionado, atendimento especializado e preços justos. Acreditamos que a tecnologia existe para facilitar vidas, e queremos ser a sua ponte para o futuro.</p>
                </div>
            </div>
        </section>

        <section id="contato" class="container section-padding">
            <h2>Entre em Contato</h2>
            <form class="contact-form">
                <div class="form-group">
                    <label for="nome">Nome completo</label>
                    <input type="text" id="nome" name="nome" placeholder="Seu nome" required>
                </div>
                <div class="form-group">
                    <label for="email">E-mail</label>
                    <input type="email" id="email" name="email" placeholder="seuemail@dominio.com" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem</label>
                    <textarea id="mensagem" name="mensagem" rows="6" placeholder="O que você gostaria de nos dizer?" required></textarea>
                </div>
                <button type="submit" class="btn">Enviar mensagem</button>
            </form>
        </section>

        <section id="avaliacoes" class="reviews-section section-padding">
            <div class="container">
                <h2>O que nossos clientes dizem</h2>
                <div class="reviews-grid">
                    <article class="review-card">
                        <div class="review-stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p class="review-comment">"Atendimento impecável e entrega super rápida. O smartphone chegou perfeito!"</p>
                        <h4 class="review-author">- Maria S.</h4>
                    </article>
                    <article class="review-card">
                        <div class="review-stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i> </div>
                        <p class="review-comment">"Gostei muito do fone, mas a caixa veio um pouco amassada. O produto funciona bem."</p>
                        <h4 class="review-author">- João P.</h4>
                    </article>
                    <article class="review-card">
                        <div class="review-stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i> </div>
                        <p class="review-comment">"Melhor smartwatch que já tive. A TechStore tem os melhores preços."</p>
                        <h4 class="review-author">- Ana L.</h4>
                    </article>
                </div>
            </div>
        </section>

    </main>

    <footer class="main-footer">
        <div class="container footer-content">
            <div class="footer-info">
                <p>TechStore Comércio de Eletrônicos LTDA</p>
                <p>CNPJ: 12.345.678/0001-99</p>
                <p>Rua da Tecnologia, 123 - Vale do Silício, BR</p>
            </div>
            <div class="footer-social">
                <a href="#">Facebook</a>
                <a href="#">Instagram</a>
                <a href="#">Twitter (X)</a>
            </div>
        </div>
        <div class="footer-copyright">
            <p>© 2025 TechStore – Todos os direitos reservados.</p>
        </div>
    </footer>

</body>
</html>






CSS
/*
 * Arquivo CSS para a Loja Virtual TechStore
 * Atividade Avaliativa II
 */

/* Desafio Extra 3: Variáveis CSS para paleta de cores */
:root {
    --color-primary: #007BFF; /* Azul principal */
    --color-secondary: #0a4f9a; /* Azul mais escuro (hover) */
    --color-dark: #222;       /* Preto/Cinza escuro (textos, header, footer) */
    --color-light: #f4f4f4;   /* Cinza claro (fundo de seções) */
    --color-white: #ffffff;   /* Branco */
    --color-accent: #FFD700;  /* Dourado/Amarelo (estrelas, detalhes) */
    
    --font-main: Arial, sans-serif;
    --container-width: 1100px;
    --shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    --border-radius: 8px;
}

/* --- Reset e Estilos Globais --- */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    /* Habilita rolagem suave para links âncora */
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-main);
    color: var(--color-dark);
    line-height: 1.6;
    /* Adiciona padding no topo para compensar o header fixo */
    padding-top: 80px; 
}

.container {
    max-width: var(--container-width);
    margin: 0 auto;
    padding: 0 20px;
}

img {
    max-width: 100%;
    display: block;
}

a {
    text-decoration: none;
    color: var(--color-primary);
}

h1, h2, h3, h4 {
    margin-bottom: 15px;
}

h2 {
    font-size: 2.2rem;
    text-align: center;
    text-transform: uppercase;
    color: var(--color-dark);
}

/* Padding padrão para seções */
.section-padding {
    padding: 60px 0;
}

/* Estilo padrão para botões */
.btn, .btn-add-cart, .search-form button, .contact-form button {
    display: inline-block;
    background: var(--color-primary);
    color: var(--color-white);
    padding: 12px 25px;
    border: none;
    border-radius: var(--border-radius);
    cursor: pointer;
    font-size: 1rem;
    font-weight: bold;
    text-transform: uppercase;
    transition: background-color 0.3s ease; /* Efeito hover */
}

/* Efeito hover para botões */
.btn:hover, .btn-add-cart:hover, .search-form button:hover, .contact-form button:hover {
    background: var(--color-secondary);
}

/* --- 1. Cabeçalho (Header) --- */

/* Desafio Extra 1: Menu Fixo */
.main-header {
    background: var(--color-white);
    color: var(--color-dark);
    padding: 10px 0;
    position: fixed; /* Fixa o header no topo */
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000; /* Garante que fique acima de outros elementos */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    height: 80px; /* Altura fixa para o body padding-top */
}

.main-header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 2rem;
    color: var(--color-primary);
    margin: 0;
}

.main-nav ul {
    list-style: none;
    display: flex;
}

.main-nav li {
    margin-left: 20px;
}

.main-nav a {
    color: var(--color-dark);
    font-weight: bold;
    padding-bottom: 5px;
    transition: color 0.3s ease, border-bottom 0.3s ease;
}

/* Efeito hover nos links do menu */
.main-nav a:hover {
    color: var(--color-primary);
    border-bottom: 2px solid var(--color-primary);
}

.search-form {
    display: flex;
}

.search-form input {
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: var(--border-radius) 0 0 var(--border-radius);
    outline: none;
}

.search-form button {
    padding: 8px 15px;
    border-radius: 0 var(--border-radius) var(--border-radius) 0;
    margin-left: -1px; /* Junta o botão ao input */
}

/* --- 2. Seção Banner (Início) --- */
.banner {
    background-image: url('imagens/banner.jpg'); /* Imagem de fundo */
    background-size: cover;
    background-position: center;
    background-color: var(--color-dark); /* Fallback */
    background-blend-mode: overlay; /* Efeito sutil */
    height: 60vh; /* Altura (60% da altura da tela) */
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: var(--color-white);
}

.banner-content {
    background: rgba(0, 0, 0, 0.5); /* Fundo escuro semitransparente */
    padding: 40px;
    border-radius: var(--border-radius);
}

.banner h2 {
    font-size: 3rem;
    color: var(--color-white);
    margin-bottom: 10px;
}

.banner p {
    font-size: 1.5rem;
    margin-bottom: 25px;
}

/* --- 3. Produtos em Destaque --- */
.product-grid {
    display: grid;
    /* Cria colunas responsivas: 
       - 1 coluna em telas pequenas
       - 2 colunas em telas médias
       - 4 colunas em telas grandes */
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px; /* Espaço entre os cards */
    margin-top: 30px;
}

.product-card {
    background: var(--color-white);
    border: 1px solid #ddd;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    text-align: center;
    padding: 20px;
    overflow: hidden; /* Para o efeito de hover na imagem */
    
    /* Desafio Extra 2: Efeitos de Transição (Hover) */
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* Efeito de hover no card */
.product-card:hover {
    transform: translateY(-10px); /* Levanta o card */
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.product-card img {
    height: 200px;
    width: 100%;
    object-fit: contain; /* Garante que a imagem caiba sem distorcer */
    margin-bottom: 15px;
    transition: transform 0.3s ease;
}

/* Efeito de zoom na imagem do card */
.product-card:hover img {
    transform: scale(1.05);
}

.product-card h3 {
    font-size: 1.25rem;
    color: var(--color-dark);
}

.product-card .price {
    font-size: 1.4rem;
    font-weight: bold;
    color: var(--color-primary);
    margin-bottom: 15px;
}

.btn-add-cart {
    width: 100%; /* Botão ocupa 100% do card */
}

/* --- 4. Seção Sobre a Loja --- */
.about-section {
    background: var(--color-light); /* Fundo claro para diferenciar */
}

.about-content {
    display: flex;
    align-items: center;
    gap: 40px;
}

.about-content img {
    flex: 1; /* Ocupa 50% */
    max-width: 500px;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
}

.about-text {
    flex: 1; /* Ocupa 50% */
}

.about-text h2 {
    text-align: left;
}

/* --- 5. Seção Contato --- */
.contact-form {
    max-width: 700px;
    margin: 30px auto 0 auto;
    background: var(--color-light);
    padding: 30px;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: var(--border-radius);
    font-family: var(--font-main);
    font-size: 1rem;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--color-primary);
    box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
}

.contact-form button {
    width: 100%;
}

/* --- Desafio Extra 4: Avaliações --- */
.reviews-section {
    background: var(--color-light);
}

.reviews-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin-top: 30px;
}

.review-card {
    background: var(--color-white);
    padding: 25px;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    border-left: 5px solid var(--color-primary);
}

.review-stars {
    color: var(--color-accent); /* Cor das estrelas */
    margin-bottom: 15px;
    font-size: 1.2rem;
}

.review-comment {
    font-style: italic;
    margin-bottom: 15px;
    color: #555;
}

.review-author {
    font-weight: bold;
    color: var(--color-dark);
    text-align: right;
}

/* --- 6. Rodapé (Footer) --- */
.main-footer {
    background: var(--color-dark);
    color: var(--color-light);
    padding: 40px 0 0 0;
    margin-top: 40px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding-bottom: 30px;
    border-bottom: 1px solid #555;
    flex-wrap: wrap; /* Para telas menores */
    gap: 20px;
}

.footer-info p {
    margin-bottom: 5px;
}

.footer-social a {
    color: var(--color-white);
    margin-left: 15px;
    font-weight: bold;
    transition: color 0.3s ease;
}

.footer-social a:hover {
    color: var(--color-primary);
}

.footer-copyright {
    text-align: center;
    padding: 20px 0;
    font-size: 0.9rem;
    color: #aaa;
}



