<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Outer Banks - Mistério, Aventura e Tesouros</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Estilo Global */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-image: url('https://wallpapercave.com/wp/wp7378215.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-repeat: no-repeat;
      color: #fff;
    }

    .overlay {
      background: rgba(0, 0, 0, 0.8);
      padding: 20px;
      min-height: 100vh;
    }

    /* Cabeçalho */
    header {
      text-align: center;
      padding: 50px;
      color: #FFD700;
      text-shadow: 2px 2px #000;
    }

    header h1 {
      font-size: 4em;
      margin: 0;
    }

    header p {
      font-size: 1.5em;
    }

    /* Seção Principal */
    main {
      max-width: 1200px;
      margin: 40px auto;
      padding: 20px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.7);
    }

    /* Imagem Hero */
    .hero-image {
      width: 100%;
      max-width: 1000px;
      border-radius: 10px;
      margin: 20px auto;
      display: block;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    /* Seção de Personagens */
    .personagens {
      margin-top: 50px;
    }

    .personagem {
      display: inline-block;
      width: 22%;
      margin: 10px;
      text-align: center;
      background: rgba(0, 0, 0, 0.7);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .personagem-img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    .personagem h3 {
      margin: 10px 0;
      font-size: 1.5em;
      color: #FFD700;
    }

    .personagem p {
      font-size: 1em;
      line-height: 1.5;
    }

    /* Motivos para Assistir */
    .motivos {
      margin-top: 40px;
    }

    .motivos h2 {
      font-size: 2.5em;
      text-align: center;
      color: #FFD700;
      margin-bottom: 20px;
      text-shadow: 1px 1px #000;
    }

    .motivos ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }

    .motivos li {
      font-size: 1.2em;
      margin: 10px 0;
    }

    .cta-button {
      display: block;
      text-align: center;
      margin: 40px auto;
      padding: 15px 30px;
      font-size: 1.5em;
      color: #000;
      background: #FFD700;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s ease, transform 0.3s ease;
    }

    .cta-button:hover {
      background: #ffc107;
      transform: translateY(-5px);
    }

    /* Rodapé */
    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      background: rgba(0, 0, 0, 0.8);
      color: #FFD700;
    }

    footer a {
      color: #fff;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <!-- Cabeçalho -->
    <header>
      <h1>Outer Banks</h1>
      <p>Embarque na aventura épica com os Pogues em busca do tesouro perdido.</p>
    </header>

    <!-- Seção Principal -->
    <main>
      <section class="intro">
        <h2>A História de Outer Banks</h2>
        <p>Em **Outer Banks**, um grupo de adolescentes conhecidos como **Pogues** se envolvem em uma caça ao tesouro ligada ao desaparecimento do pai de John B., o líder do grupo. Enquanto enfrentam os ricos **Kooks** e se aprofundam em mistérios do passado, cada passo os leva mais perto de um segredo que pode mudar tudo.</p>
        <img class="hero-image" src="https://tm.ibxk.com.br/2023/02/16/16144503290241.jpg" alt="Outer Banks - John B e Sarah Cameron">
      </section>

      <!-- Personagens -->
      <section class="personagens">
        <h2>Os Personagens</h2>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzWIrRX4fazBx0ZEcSmKVhMxz2dw5sEim61Q&s" alt="John B" class="personagem-img">
          <h3>John B</h3>
          <p>O corajoso e determinado líder dos Pogues, que não desiste da missão de encontrar o pai desaparecido e o lendário tesouro.</p>
        </div>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxNvqijuHIHAe7HnhuW9j55SjtQNkHz38Mgg&s" alt="Sarah Cameron" class="personagem-img">
          <h3>Sarah Cameron</h3>
          <p>Uma Kook que se une ao grupo dos Pogues. Sua história de amor com John B é cheia de desafios, mas também de momentos intensos.</p>
        </div>
        <div class="personagem">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSR4Df5ldu26gyBM8afsHk1ZJItTEJjeM2DVw&s" alt="Kiara" class="personagem-img">
          <h3>Kiara</h3>
          <p>A ecologista do grupo, que tem um grande coração e sempre faz o que é certo, mesmo que isso a coloque em risco.</p>
        </div>
        <div class="personagem">
          <img src="https://imgix.bustle.com/uploads/image/2024/10/8/7e11ec46/outerbanks_401_unit_06125rc.jpg?w=414&h=306&fit=crop&crop=focalpoint&dpr=2&fp-x=0.5418&fp-y=0.4182" alt="Pope" class="personagem-img">
          <h3>Pope</h3>
          <p>O cérebro dos Pogues, que sempre vem com uma solução quando as coisas ficam complicadas, seja na escola ou na busca pelo tesouro.</p>
        </div>
      </section>

      <!-- Por que Assistir? -->
      <section class="motivos">
        <h2>recomendo assitir o Outer banks?</h2>
        <ul>
          <li><strong>Aventura emocionante:</strong> A caça ao tesouro é repleta de reviravoltas e momentos de tirar o fôlego.</li>
          <li><strong>Personagens cativantes:</strong> Com personalidades únicas, os Pogues e Kooks têm histórias emocionantes e cheias de sentimentos.</li>
          <li><strong>Cenários deslumbrantes:</strong> A série é filmada nas belas paisagens das Outer Banks, na Carolina do Norte.</li>
          <li><strong>Reviravoltas imprevisíveis:</strong> Cada episódio é cheio de surpresas e segredos que mantém os espectadores presos à tela.</li>
        </ul>
      </section>

      <!-- Botão de Ação -->
      <a href="https://www.netflix.com/br/title/80236318" class="cta-button" target="_blank">Assista Agora na Netflix!</a>
    </main>

    <!-- Rodapé -->
    <footer>
      <p>Para mais informações, visite a página oficial de <a href="https://www.netflix.com/br/title/80236318" target="_blank">Outer Banks</a>.</p>
      <p>&copy; 2024 Fan Page de Outer Banks</p>
    </footer>
  </div>
</body>
</html>
