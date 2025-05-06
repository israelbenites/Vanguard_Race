<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vanguard Race</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background: #000;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
        }
        header img {
            height: 50px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            margin: 0;
            padding: 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #f00;
        }
        .hero {
            padding: 100px 20px;
            text-align: center;
            background-color: #000;
        }
        .hero h1 {
            color: #f00;
            font-size: 36px;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        h2 {
            color: #f00;
        }
        .servicos, .oficina, .galeria, .prova-social {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background: #111;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            box-sizing: border-box;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            font-size: 14px;
        }
        button {
            background-color: #25D366;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            animation: pulse 1.5s infinite;
        }
        button:hover {
            background-color: #128C7E;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        .img-oficina, .img-galeria {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .img-oficina:hover, .img-galeria:hover {
            transform: scale(1.05);
        }
        .galeria {
            display: flex;
            flex-wrap: nowrap;
            justify-content: center;
        }
        .galeria .card {
            width: 250px;
        }

        /* Ajustes para dispositivos móveis */
        @media (max-width: 768px) {
            .servicos, .oficina, .galeria, .prova-social {
                flex-direction: column;
                align-items: center;
            }

            .card {
                width: 90%; /* Ajuste da largura dos cards */
                margin-bottom: 20px; /* Adicionando espaçamento entre os cards */
            }

            .hero h1 {
                font-size: 28px; /* Ajuste do tamanho da fonte para telas menores */
            }

            header img {
                height: 40px; /* Menor logo para telas pequenas */
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0; /* Espaçamento maior entre os links */
            }
        }
    </style>
</head>
<body>

<header>
    <img src="https://i.postimg.cc/RZmL72YT/IMG-8541.jpg" alt="Vanguard Race">
    <nav>
        <ul>
            <li><a href="#sobre">Sobre Nós</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#oficina">Nossa Oficina</a></li>
            <li><a href="#galeria">Galeria</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h1>Serviços especializados em mecânica automotiva em Nova Iguaçu</h1>
</section>

<section id="sobre">
    <h2>Sobre Nós</h2>
    <p>A Vanguard Race é especializada em Mecânica automotiva, com serviços como revisão, suspensão, freios e diagnóstico eletrônico. Estamos há 5 anos atuando em oficina mecânica, garantindo qualidade, segurança e performance para o seu carro. Nossa equipe é formada por profissionais apaixonados por automobilismo.</p>
</section>

<section id="servicos">
    <h2>Alguns de nossos Serviços</h2>
    <div class="servicos">
        <div class="card">Revisão Completa</div>
        <div class="card">Troca de Óleo</div>
        <div class="card">Suspensão</div>
        <div class="card">Freios</div>
        <div class="card">Diagnóstico Eletrônico</div>
        <div class="card">Preparação Esportiva</div>
    </div>
</section>

<section id="oficina">
    <h2>Nossa Oficina</h2>
    <div class="oficina">
        <div class="card">
            <img src="https://i.postimg.cc/Dw7KxYc8/IMG-8280.jpg" alt="Oficina Vanguard Race" class="img-oficina">
            <p>Nosso espaço conta com equipamentos modernos para garantir máxima eficiência, qualidade e segurança nos serviços realizados.</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/1tsCQLfq/IMG-8637.jpg" alt="Oficina Vanguard Race" class="img-oficina">
            <p>Equipe especializada pronta para atender você com excelência e paixão pelo automobilismo.</p>
        </div>
    </div>
</section>

<section id="galeria">
    <h2>Galeria</h2>
    <div class="galeria">
        <div class="card">
            <img src="https://i.postimg.cc/T1pYtNjz/IMG-8634.jpg" alt="Carro 1" class="img-galeria">
            <p>PORSHE GT3 RS - Detalhes de performance</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/k5zWx56C/IMG-8636.jpg" alt="Carro 2" class="img-galeria">
            <p>JAGUAR XKR - Customização esportiva</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/h4rfnjDG/IMG-8635.jpg" alt="Carro 3" class="img-galeria">
            <p>BMW M3 - Suspensão personalizada</p>
        </div>
    </div>
</section>

<section id="provas">
    <h2>O que nossos clientes dizem</h2>
    <div class="prova-social">
        <div class="card">
            "Serviço rápido e de qualidade! Recomendo muito."<br><br>
            <strong>Isaque Freitas</strong>
        </div>
        <div class="card">
            "Equipe maravilhosa e atendimento impecável. Muito satisfeita!"<br><br>
            <strong>Nathalia Lourenço</strong>
        </div>
        <div class="card">
            "Meu carro ficou perfeito depois da revisão. Vale cada centavo!"<br><br>
            <strong>Victor Miguel</strong>
        </div>
        <div class="card">
            "Profissionais que realmente entendem de carro. Recomendo demais!"<br><br>
            <strong>Shtefany Rocha</strong>
        </div>
    </div>
</section>

<section id="contato">
    <h2>Fale com a gente e marque sua revisão</h2>
    <a href="https://wa.me/seuNumeroDeTelefone" target="_blank">
        <button>Nos chame no WhatsApp</button>
    </a>
</section>

<section id="endereco">
    <h2>Endereço</h2>
    <p>Visite a gente: Rua Maria Macedo, 83, Nova Iguaçu - RJ</p>
    <p>CEP: 26215-490</p>
    <a href="https://www.google.com/maps/search/Vanguard+Race" target="_blank">
        Ver no Google Maps
    </a>
</section>

<footer>
    &copy; 2025 Vanguard Race. Todos os direitos reservados.
</footer>

</body>
</html>
