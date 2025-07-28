<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Teresiona Decorações</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: auto;
      scroll-behavior: smooth;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }
    header {
      background: #25D366;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .intro {
      text-align: center;
      margin: 20px 0;
      color: #555;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding-bottom: 60px; /* espaço para o botão flutuante */
    }
    .item {
      background: white;
      border-radius: 8px;
      overflow: hidden;
      width: 280px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .item img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .item img:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
    }
    .item a {
      display: block;
      margin: 15px;
      padding: 10px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .item a:hover {
      background: #128C7E;
    }
    .contact-info {
      text-align: center;
      margin-top: 50px;
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #777;
      padding-bottom: 30px;
    }
    .instagram-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #E4405F;
      border: none;
      padding: 15px;
      border-radius: 50%;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
      cursor: pointer;
      z-index: 999;
    }
    .instagram-btn img {
      width: 30px;
      height: 30px;
    }
    /* Botão voltar ao topo */
    #backToTop {
      position: fixed;
      bottom: 80px;
      right: 20px;
      display: none;
      background-color: #25D366;
      border: none;
      padding: 12px;
      border-radius: 50%;
      cursor: pointer;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
      z-index: 999;
      font-size: 20px;
      color: white;
      line-height: 1;
    }
  </style>
</head>
<body>

  <header>
    <h1>Teresina Decorações</h1>
    <p>Cadeiras em fibra e corda náutica – novas ou reformadas</p>
  </header>

  <div class="intro">
    <p>Escolha a sua favorita e clique para falar conosco pelo WhatsApp!</p>
  </div>

  <div class="gallery">

    <div class="item">
      <img src="img/cadeira1.jpg" alt="Cadeira 1">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%201.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira2.jpg" alt="Cadeira 2">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%202.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira3.jpg" alt="Cadeira 3">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%203.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira4.jpg" alt="Cadeira 4">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%204.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira5.jpg" alt="Cadeira 5">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%205.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira6.jpg" alt="Cadeira 6">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%206.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira7.jpg" alt="Cadeira 7">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%207.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira8.jpg" alt="Cadeira 8">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%208.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira9.jpg" alt="Cadeira 9">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%209.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira10.jpg" alt="Cadeira 10">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2010.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira11.jpg" alt="Cadeira 11">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2011.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira12.jpg" alt="Cadeira 12">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2012.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira13.jpg" alt="Cadeira 13">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2013.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira14.jpg" alt="Cadeira 14">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2014.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira15.jpg" alt="Cadeira 15">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2015.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira16.jpg" alt="Cadeira 16">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2016.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira17.jpg" alt="Cadeira 17">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2017.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira18.jpg" alt="Cadeira 18">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2018.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira19.jpg" alt="Cadeira 19">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2019.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>
    <div class="item">
      <img src="img/cadeira20.jpg" alt="Cadeira 20">
      <a href="https://wa.me/5586994624299?text=Olá,%20gostei%20da%20cadeira%2020.%20Pode%20me%20dar%20mais%20detalhes?">Quero esta cadeira</a>
    </div>

  </div>

  <div class="contact-info">
    <h2>Contato</h2>
    <p><strong>Endereço:</strong> Rua rui barbosa 930-Centro, por trás do verdão, Teresina </p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/5586994624299">(86) 99462-4299</a></p>
    <p><strong>Instagram:</strong> <a href="https://www.instagram.com/teresionadecoracoes" target="_blank">@teresinadecoracoes</a></p>
  </div>

  <footer>
    <p>&copy; 2025 Teresina Decorações - Todos os direitos reservados.</p>
  </footer>

  <!-- Botão flutuante Instagram -->
  <a href="https://www.instagram.com/teresinadecoracoes/" target="_blank">
    <button class="instagram-btn" aria-label="Instagram Teresiona Decorações">
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/Instagram_logo_2022.svg" alt="Instagram">
    </button>
  </a>

  <!-- Botão Voltar ao Topo -->
  <button id="backToTop" title="Voltar ao topo">↑</button>

  <script>
    const backToTopBtn = document.getElementById('backToTop');

    window.onscroll = function() {
      if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
        backToTopBtn.style.display = "block";
      } else {
        backToTopBtn.style.display = "none";
      }
    };

    backToTopBtn.onclick = function() {
      window.scrollTo({top: 0, behavior: 'smooth'});
    };
  </script>

</body>
</html>
