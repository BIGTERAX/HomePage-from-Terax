<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Über Mich - Moritz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .about {
      max-width: 800px;
      width: 90%;
      background: white;
      border-radius: 15px;
      padding: 20px;
      margin-top: 40px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      text-align: center;
    }

    .about-text h2 {
      margin-bottom: 10px;
      font-size: 2em;
      color: #333;
    }

    .about-text p {
      font-size: 1.1em;
      line-height: 1.6;
      color: #555;
    }

    .social-banners {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin: 40px 0;
      width: 90%;
      max-width: 800px;
    }

    .banner {
      display: block;
      text-align: center;
      padding: 20px;
      border-radius: 10px;
      font-size: clamp(1.2em, 2vw, 1.4em);
      font-weight: bold;
      color: white;
      text-decoration: none;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .banner:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    }

    .discord { background: #7289da; }
    .tiktok { background: #000; }
    .instagram {
      background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%);
    }

    @media (min-width: 768px) {
      .social-banners {
        flex-direction: row;
        justify-content: center;
      }
    }
  </style>
</head>
<body>

  <!-- Über mich -->
  <div class="about">
    <div class="about-text">
      <h2>Über Mich</h2>
      <p>
        Hey! 👋 Ich bin <strong>Moritz</strong>, 14 Jahre alt und Rollstuhlfahrer.<br>
        Ich bin Gamer 🎮 und Content Creator, und teile gerne meine Leidenschaft für Games.<br>
        Besonders gerne spiele ich <strong>Valorant</strong>, <strong>Fortnite</strong> und <strong>GTA</strong>.<br>
        Komm gerne vorbei und sei Teil meiner Community!
      </p>
    </div>
  </div>

  <!-- Social Media Links -->
  <div class="social-banners">
    <a href="https://discord.gg/rvbYdQEzVz" target="_blank" class="banner discord">Discord</a>
    <a href="https://www.tiktok.com/@big_terax" target="_blank" class="banner tiktok">TikTok</a>
    <a href="https://www.instagram.com/fst_moritz" target="_blank" class="banner instagram">Instagram</a>
  </div>

</body>
</html>
