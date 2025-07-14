# Promo-o-Dim
Premiação 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Promoção Dim</title>
  <style>
    body {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(to bottom, #f9f9f9, #e0e0e0);
      font-family: Arial, sans-serif;
      margin: 0;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #2c3e50;
    }
    .botao {
      background-color: gold;
      color: black;
      padding: 15px 30px;
      font-size: 18px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
      transition: background-color 0.3s;
      margin-top: 20px;
    }
    .botao:hover {
      background-color: orange;
    }
    iframe {
      display: none; /* esconde o vídeo */
    }
  </style>
</head>
<body>
  <h1>🎉 Parabéns! Você foi premiado pela Dim!</h1>
  <p>Clique no botão abaixo para receber seu prêmio exclusivo.</p>
  <button class="botao" onclick="alert('😆 Pegadinha da Dim! Seu prêmio é um sorriso! 😄')">
    🎁 Receber Prêmio
  </button>

  <!-- Música de fundo (autoplay, sem controles) -->
  <iframe width="0" height="0" src="https://www.youtube.com/embed/pyxLFVidYCo?autoplay=1&loop=1&playlist=pyxLFVidYCo" 
    frameborder="0" allow="autoplay" allowfullscreen></iframe>
</body>
</html>
