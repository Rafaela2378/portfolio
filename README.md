<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jogadora237 - Portfólio</title>

  <!-- Fontes -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />

  <!-- Font Awesome para ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #0e0e10;
      color: #ffffff;
      line-height: 1.6;
    }

    h1, h2, nav a, button {
      font-family: 'Orbitron', sans-serif;
      letter-spacing: 1px;
    }

    header {
      background-color: #1f1f23;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      color: #00ffcc;
      font-size: 2.5rem;
    }

    nav {
      background-color: #131316;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00ffcc;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      font-size: 1.8rem;
      color: #00ffcc;
      margin-bottom: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: #1f1f23;
    }

    th, td {
      padding: 12px;
      text-align: center;
      border: 1px solid #333;
    }

    th {
      background-color: #2a2a2e;
      color: #00ffcc;
    }

    td {
      color: #fff;
    }

    .social {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
      flex-wrap: wrap;
    }

    .social a {
      color: #00ffcc;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 1rem;
    }

    .social a:hover {
      color: #ffffff;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: 0 auto;
    }

    input, textarea {
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-family: 'Poppins', sans-serif;
      font-size: 1rem;
    }

    button {
      background-color: #00ffcc;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      padding: 10px;
      cursor: pointer;
      transition: background 0.3s;
      font-family: 'Orbitron', sans-serif;
      letter-spacing: 1px;
    }

    button:hover {
      background-color: #00ccaa;
    }

    footer {
      background-color: #1f1f23;
      text-align: center;
      padding: 20px;
      color: #aaa;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }

      .social {
        justify-content: center;
        gap: 15px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Jogadora237</h1>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#stats">Último status na GC</a>
    <a href="#horarios">Horários de Live</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre Mim</h2>
    <p>Uma carioca que não sabe o que esperar da vida, mas esperando uma vida inteira para viver!</p>
    <p>Não vivo só de CS, jogo alguns outros jogos como Valorant, Minecraft e alguns RPG da vida!</p>
  </section>

  <section id="stats">
    <h2>Último status na GC</h2>
    <table>
      <thead>
        <tr>
          <th>K/D</th>
          <th>HS%</th>
          <th>Winrate</th>
          <th>Ranking mais alto</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1.25</td>
          <td>47%</td>
          <td>58%</td>
          <td>GC 15</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section id="horarios">
    <h2>Horários de Live</h2>
    <p>Segunda a Sexta - das 20h às 23h (podendo variar em dias de campeonato ou gravações).</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <form action="https://formsubmit.co/jogadora2378@gmail.com" method="POST">
      <input type="text" name="name" placeholder="Seu nome" required />
      <input type="email" name="email" placeholder="Seu email" required />
      <textarea name="message" rows="5" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>

    <div class="social">
      <a href="https://www.twitch.tv/jogadora237" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-twitch"></i> Twitch
      </a>
      <a href="https://www.youtube.com/@jogadora2376" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-youtube"></i> YouTube
      </a>
      <a href="https://www.tiktok.com/@jogadora2378" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-tiktok"></i> TikTok
      </a>
    </div>
  </section>

  <footer>
    <p>© 2025 Jogadora237 - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
