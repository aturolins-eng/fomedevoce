<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FOME | Akin</title>
  <meta name="description" content="Site oficial do single FOME, de Akin. Crônica musical sobre fome emocional, arte e vulnerabilidade." />
  <style>
    :root {
      --bg: #0b0b0b;
      --card: #141414;
      --text: #f5f5f5;
      --muted: #b0b0b0;
      --accent: #c9a24d;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.8;
    }

    header { padding: 3rem 1.5rem; }

    .hero {
      max-width: 1100px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2.5rem;
      align-items: center;
    }

    .hero img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 20px 60px rgba(0,0,0,0.6);
    }

    .hero-text h1 {
      font-size: clamp(2.5rem, 5vw, 4rem);
      letter-spacing: 0.2em;
      margin-bottom: 1.5rem;
    }

    .hero-text p {
      color: var(--muted);
      max-width: 520px;
    }

    section { padding: 4rem 1.5rem; }

    .container { max-width: 900px; margin: 0 auto; }

    h2 { font-size: 2rem; margin-bottom: 1.5rem; color: var(--accent); }

    p { margin-bottom: 1.2rem; }

    .card {
      background: var(--card);
      padding: 2.2rem;
      border-radius: 18px;
      margin-bottom: 2.5rem;
    }

    .embeds {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-top: 1.5rem;
    }

    iframe {
      width: 100%;
      border-radius: 14px;
      border: none;
      min-height: 352px;
    }

    .links {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
    }

    .links a {
      text-decoration: none;
      color: var(--text);
      background: #0f0f0f;
      padding: 1.2rem;
      border-radius: 14px;
      text-align: center;
      transition: transform 0.2s ease, background 0.2s ease;
    }

    .links a:hover { transform: translateY(-4px); background: #1c1c1c; }

    footer { padding: 2rem 1.5rem; text-align: center; color: var(--muted); font-size: 0.9rem; }

    @media (max-width: 900px) {
      .hero { grid-template-columns: 1fr; text-align: center; }
      .hero-text p { margin: 0 auto; }
      .embeds { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <header>
    <div class="hero">
      <img src="capa-fome.JPG" alt="Akin com maquiagem de caveira – capa de FOME" />
      <div class="hero-text">
        <h1>FOME</h1>
        <p>
          Em <strong>“FOME”</strong>, seu novo e visceral single, Akin mergulha nas profundezas da dependência emocional,
          expondo um vazio que a sociedade insiste em ignorar.
        </p>
      </div>
    </div>
  </header>

  <section>
    <div class="container">
      <div class="card">
        <h2>O Artista por Trás da Máscara</h2>
        <p>
          Akin é um nome novo para quem acompanha a vanguarda da música brasileira. Nascido em Niterói, o cantor,
          compositor e produtor musical usou das divergências musicais de 2025 para se lançar no mundo da música e viver seu sonho.
        </p>
        <p>
          O início de sua trajetória, marcada pelo lançamento álbum <em>“Nicotina”</em> (2025), já indicava um artista inquieto,
          pesquisador de ritmos e narrativas. Em <strong>“FOME”</strong>, esse mergulho é mais escuro, solitário e
          universalmente doloroso.
        </p>
      </div>

      <div class="card">
        <h2>A Anatomia de “Fome”</h2>
        <p>
          Musicalmente, “Fome” mantém a pulsação do house, mas de forma contida e fantasmagórica. Baixos profundos,
          apenas a sua voz e seu violão carregado de tons melancólicos e um coro que juntos constroem uma temerosa atmosfera de claustrofobia noturna.
        </p>
        <p>
          A letra é uma confissão direta sobre dependência emocional. Não é a fome do corpo, mas do espírito. A busca
          compulsiva por algo que promete alívio e apenas aprofunda o vazio.
        </p>
      </div>

      <div class="card">
        <h2>Quando a Fome Não é do Estômago</h2>
        <p>
          A canção dialoga com o conceito de fome emocional: súbita, intensa e específica, ligada a gatilhos como
          ansiedade, estresse e solidão. Os desejos oferecem alívio temporário, seguido de culpa e frustração.
        </p>
        <p>
          “FOME” funciona como trilha sonora desse ciclo silencioso, dando voz a uma dor frequentemente invisível.
        </p>
      </div>

      <div class="card">
        <h2>Ouça e Assista “FOME”</h2>
        <div class="embeds">
          <iframe src="https://open.spotify.com/embed/track/6WRHaunYTM9usnCScZCmpQ" allow="encrypted-media"></iframe>
          <iframe src="https://www.youtube.com/embed/TT48MlmE49Q" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </div>

      <div class="card">
        <h2>Acompanhe AKIN</h2>
        <div class="links">
          <a href="https://open.spotify.com/artist/7uoQ0hVZkS6GoqAEBf34Eq" target="_blank">🟢 Spotify</a>
          <a href="https://youtube.com/@akinlume" target="_blank">🔴 YouTube</a>
          <a href="https://www.instagram.com/akinlume" target="_blank">📸 Instagram</a>
          <a href="https://www.tiktok.com/@akinlume" target="_blank">🎵 TikTok</a>
        </div>
      </div>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 — Akin | “FOME”</p>
  </footer>

</body>
</html>
