# Vanguard_Race<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vanguard Race - Nova Iguaçu</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
      color: #fff;
    }

    header {
      background: #000;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
    }

    header img {
      height: 60px;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #f00;
    }

    .banner {
      background: #111;
      height: 150px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .banner h1 {
      padding: 20px;
      font-size: 32px;
    }

    .banner a {
      margin-top: 20px;
      background: #f00;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 30px;
    }

    h2 {
      color: #f00;
      margin-bottom: 20px;
    }

    .servicos, .galeria, .depoimentos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
    }

    .card {
      background: #111;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }

    .card img {
      width: 100%;
      height: 360px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card img:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 15px rgba(255, 0, 0, 0.6);
    }

    .oficina-imagens {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      justify-content: center;
    }

    .oficina-imagens img {
      width: 30%; /* Reduzido ainda mais */
      height: auto;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      opacity: 0;
      transform: translateY(20px);
    }

    .oficina-imagens img.show {
      opacity: 1;
      transform: translateY(0);
    }

    .oficina-imagens img:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 15px rgba(255, 0, 0, 0.6);
    }

    .depoimentos .depoimento {
      background: #111;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .depoimentos .depoimento:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 15px rgba(255, 0, 0, 0.3);
    }

    .depoimento p {
      font-style: italic;
      margin-bottom: 10px;
    }

    .depoimento h4 {
      font-size: 18px;
      font-weight: bold;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }

    #topo-btn {
      position: fixed;
      right: 20px;
      bottom: 20px;
      background: #f00;
      color: #fff;
      border: none;
      padding: 10px 15px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 20px;
      display: none;
    }

    .whatsapp-btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: #25D366;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 30px;
      font-size: 16px;
      cursor: pointer;
      text-decoration: none;
      margin-top: 20px;
    }

    #mapa iframe {
      width: 100%;
      height: 100px;
      border: 0;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<header>
  <img src="https://i.postimg.cc/RZmL72YT/IMG-8541.jpg" alt="Vanguard Race">
  <nav>
    <a href="#sobre">Sobre Nós</a>
    <a href="#servicos">Serviços</a>
    <a href="#projetos">Nossa Oficina</a>
    <a href="#galeria">Galeria</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<div class="banner">
  <h1>Serviços especializados em mecânica automotiva em Nova Iguaçu</h1>
</div>

<section id="sobre">
  <h2>Sobre Nós</h2>
  <p>A Vanguard Race é especializada em mecânica automotiva, com serviços como revisão, suspensão, freios e diagnóstico eletrônico. Estamos há <strong>5 anos atuando em oficina mecânica</strong>, garantindo qualidade, segurança e performance para seu carro. Nossa equipe é formada por profissionais apaixonados por automobilismo.</p>
</section>

<section id="servicos">
  <h2>Alguns de nossos serviços</h2>
  <div class="servicos">
    <div class="card">Revisão Completa</div>
    <div class="card">Troca de Óleo</div>
    <div class="card">Suspensão</div>
    <div class="card">Freios</div>
    <div class="card">Diagnóstico Eletrônico</div>
    <div class="card">Preparação Esportiva</div>
  </div>
</section>

<section id="projetos">
  <h2>Nossa Oficina</h2>
  <div class="oficina-imagens">
    <img src="https://i.postimg.cc/VNLg5Rzg/IMG-8638.jpg" alt="Oficina 1">
    <img src="https://i.postimg.cc/Vvcb0fjw/IMG-8637.jpg" alt="Oficina 2">
  </div>
</section>

<section id="galeria">
  <h2>Galeria</h2>
  <div class="galeria">
    <div class="card">
      <img src="https://i.postimg.cc/q70dZg2S/IMG-8634.jpg" alt="Projeto 1">
      <p>PORSCHE GT3 RS</p>
    </div>
    <div class="card">
      <img src="https://i.postimg.cc/v8W9nN3z/IMG-8636.jpg" alt="Projeto 2">
      <p>JAGUAR XKR</p>
    </div>
    <div class="card">
      <img src="https://i.postimg.cc/x1kLXT7k/IMG-8635.jpg" alt="Projeto 3">
      <p>BMW M3</p>
    </div>
  </div>
</section>

<section id="contato">
  <h2>Fale Conosco</h2>
  <p>Rua Maria Macedo, 83, Nova Iguaçu - RJ</p>
  <p>Siga-nos no Instagram: <a href="https://www.instagram.com/vanguard_race" target="_blank">@Vanguard_Race</a></p>
  <a href="https://wa.me/5521999999999?text=Olá! Gostaria de saber mais sobre os serviços da Vanguard Race." target="_blank" class="whatsapp-btn">
    <span style="font-size:24px;">&#x1F4AC;</span> Fale conosco no WhatsApp
  </a>
  <div id="mapa" style="margin-top: 20px;">
    <iframe src="https://www.google.com/maps?q=Rua+Maria+Macedo,+83,+Nova+Iguaçu+-+RJ&output=embed" allowfullscreen="" loading="lazy"></iframe>
  </div>
</section>

<section id="depoimentos">
  <h2>O que nossos clientes dizem</h2>
  <div class="depoimentos">
    <div class="depoimento">
      <p>"Serviço rápido e de qualidade! Recomendo muito."</p>
      <h4>Isaque Freitas</h4>
    </div>
    <div class="depoimento">
      <p>"Equipe maravilhosa e atendimento impecável. Muito satisfeita!"</p>
      <h4>Nathalia Lourenço</h4>
    </div>
    <div class="depoimento">
      <p>"Meu carro ficou perfeito depois da revisão. Vale cada centavo!"</p>
      <h4>Victor Miguel</h4>
    </div>
    <div class="depoimento">
      <p>"Profissionais que realmente entendem de carro. Recomendo demais!"</p>
      <h4>Sthefany Rocha</h4>
    </div>
  </div>
</section>

<footer>
  &copy; 2025 Vanguard Race. Todos os direitos reservados.
</footer>

<button id="topo-btn" onclick="voltarAoTopo()">↑</button>

<script>
  window.addEventListener('scroll', function() {
    const btn = document.getElementById('topo-btn');
    btn.style.display = window.scrollY > 300 ? 'block' : 'none';
  });

  function voltarAoTopo() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // Efeito de entrada das imagens
  window.addEventListener('load', function() {
    const images = document.querySelectorAll('.oficina-imagens img');
    images.forEach(function(img) {
      img.classList.add('show');
    });
  });
</script>

</body>
</html>
