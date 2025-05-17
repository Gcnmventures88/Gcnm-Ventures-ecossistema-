<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GCNM Vídeos</title>
  <meta name="description" content="Vídeos GCNM MUSIC: destaques de artistas africanos, eventos e campanhas.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body { font-family: 'Segoe UI', sans-serif; scroll-behavior: smooth; }
    header, section { padding: 60px 20px; }
    header { background-color: #880e4f; color: #fff; text-align: center; }
    nav { background-color: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 10px 20px; }
    .lang-icons img { width: 28px; margin-left: 8px; cursor: pointer; border-radius: 50%; }
    footer { background-color: #111; color: #ccc; text-align: center; padding: 20px; }
    .video-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; margin-bottom: 30px; }
    .video-container iframe { position: absolute; top:0; left: 0; width: 100%; height: 100%; }
    #whatsapp { position: fixed; bottom: 20px; right: 20px; z-index: 999; }
  </style>
</head>
<body>

<!-- Menu -->
<nav class="d-flex justify-content-between align-items-center">
  <a class="fw-bold" href="index.html">← Voltar à GCNM</a>
  <div class="lang-icons">
    <img src="https://flagcdn.com/w40/ao.png" onclick="switchLang('pt')" title="Português" />
    <img src="https://flagcdn.com/w40/gb.png" onclick="switchLang('en')" title="English" />
    <img src="https://flagcdn.com/w40/fr.png" onclick="switchLang('fr')" title="Français" />
  </div>
</nav>

<!-- Cabeçalho -->
<header>
  <h1 id="mainTitle">Vídeos em Destaque</h1>
  <p id="mainDesc">Artistas, eventos e campanhas da GCNM Ventures</p>
</header>

<!-- Vídeos -->
<section>
  <div class="container">
    <div id="videoTitle" class="mb-4"><h4>Assista aos nossos destaques:</h4></div>

    <!-- Vídeo 1 -->
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/Z1BCujX3pw8" title="Vídeo 1" frameborder="0" allowfullscreen></iframe>
    </div>

    <!-- Vídeo 2 -->
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/ScMzIvxBSi4" title="Vídeo 2" frameborder="0" allowfullscreen></iframe>
    </div>

    <!-- Vídeo 3 -->
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/FN7ALfpGxiI" title="Vídeo 3" frameborder="0" allowfullscreen></iframe>
    </div>

  </div>
</section>

<!-- Rodapé -->
<footer>
  <p>&copy; 2025 GCNM Ventures – Música e Cultura Africana em Vídeo. Todos os direitos reservados.</p>
</footer>

<!-- WhatsApp -->
<a href="https://wa.me/244938248388?text=Olá!%20Gostaria%20de%20enviar%20um%20vídeo%20para%20a%20GCNM" target="_blank" id="whatsapp">
  <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" width="60" alt="WhatsApp">
</a>

<!-- Script de tradução -->
<script>
const translations = {
  pt: {
    mainTitle: "Vídeos em Destaque",
    mainDesc: "Artistas, eventos e campanhas da GCNM Ventures",
    videoTitle: "<h4>Assista aos nossos destaques:</h4>"
  },
  en: {
    mainTitle: "Featured Videos",
    mainDesc: "Artists, events and GCNM campaigns",
    videoTitle: "<h4>Watch our featured highlights:</h4>"
  },
  fr: {
    mainTitle: "Vidéos en Vedette",
    mainDesc: "Artistes, événements et campagnes de GCNM",
    videoTitle: "<h4>Regardez nos meilleurs moments :</h4>"
  }
};

function switchLang(lang) {
  const d = translations[lang];
  document.getElementById('mainTitle').innerText = d.mainTitle;
  document.getElementById('mainDesc').innerText = d.mainDesc;
  document.getElementById('videoTitle').innerHTML = d.videoTitle;
}
</script>

</body>
</html>
