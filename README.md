<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GCNM FAQ</title>
  <meta name="description" content="Perguntas frequentes sobre GCNM MUSIC, Wallet Makubungo, cadastro de artistas e parcerias. Plataforma africana com IA.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body { font-family: 'Segoe UI', sans-serif; scroll-behavior: smooth; }
    header, section { padding: 60px 20px; }
    header { background-color: #222; color: #fff; text-align: center; }
    nav { background-color: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 10px 20px; }
    .lang-icons img { width: 28px; margin-left: 8px; cursor: pointer; border-radius: 50%; }
    footer { background-color: #111; color: #ccc; text-align: center; padding: 20px; }
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
  <h1 id="mainTitle">Perguntas Frequentes (FAQ)</h1>
  <p id="mainDesc">Tudo o que você precisa saber sobre a GCNM Ventures</p>
</header>

<!-- FAQ -->
<section>
  <div class="container">
    <div id="faqContent">
      <h4>O que é a GCNM MUSIC?</h4>
      <p>É uma plataforma de música africana com streaming, rankings, IA e wallet integrada.</p>
      <h4>Como posso me tornar um artista na GCNM?</h4>
      <p>Acesse a página de artistas e inscreva-se como Novo Talento ou Artista Formal.</p>
      <h4>O que é Makubungo?</h4>
      <p>É a moeda digital usada na GCNM Wallet, onde 1 Makubungo = 100 Kz.</p>
      <h4>Posso usar a GCNM Wallet fora da plataforma?</h4>
      <p>Sim, qualquer pessoa pode usar, mesmo sem conta no GCNM MUSIC.</p>
      <h4>Como faço parceria com a GCNM?</h4>
      <p>Vá para a página de parcerias e preencha o formulário de interesse.</p>
    </div>
  </div>
</section>

<!-- Rodapé -->
<footer>
  <p>&copy; 2025 GCNM Ventures – Plataforma Pan-Africana. Todos os direitos reservados.</p>
</footer>

<!-- WhatsApp -->
<a href="https://wa.me/244938248388?text=Tenho%20uma%20dúvida%20sobre%20a%20GCNM" target="_blank" id="whatsapp">
  <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" width="60" alt="WhatsApp">
</a>

<!-- Script de tradução -->
<script>
const translations = {
  pt: {
    mainTitle: "Perguntas Frequentes (FAQ)",
    mainDesc: "Tudo o que você precisa saber sobre a GCNM Ventures",
    faqContent: `
      <h4>O que é a GCNM MUSIC?</h4><p>É uma plataforma de música africana com streaming, rankings, IA e wallet integrada.</p>
      <h4>Como posso me tornar um artista na GCNM?</h4><p>Acesse a página de artistas e inscreva-se como Novo Talento ou Artista Formal.</p>
      <h4>O que é Makubungo?</h4><p>É a moeda digital usada na GCNM Wallet, onde 1 Makubungo = 100 Kz.</p>
      <h4>Posso usar a GCNM Wallet fora da plataforma?</h4><p>Sim, qualquer pessoa pode usar, mesmo sem conta no GCNM MUSIC.</p>
      <h4>Como faço parceria com a GCNM?</h4><p>Vá para a página de parcerias e preencha o formulário de interesse.</p>`
  },
  en: {
    mainTitle: "Frequently Asked Questions (FAQ)",
    mainDesc: "Everything you need to know about GCNM Ventures",
    faqContent: `
      <h4>What is GCNM MUSIC?</h4><p>A platform for African music with streaming, rankings, AI, and wallet integration.</p>
      <h4>How can I become an artist on GCNM?</h4><p>Go to the Artists page and register as a New Talent or Formal Artist.</p>
      <h4>What is Makubungo?</h4><p>The digital currency used in the GCNM Wallet (1 Makubungo = 100 Kz).</p>
      <h4>Can I use GCNM Wallet outside the platform?</h4><p>Yes, anyone can use it, even without a GCNM MUSIC account.</p>
      <h4>How do I partner with GCNM?</h4><p>Visit the Partnerships page and fill in the interest form.</p>`
  },
  fr: {
    mainTitle: "Questions Fréquentes (FAQ)",
    mainDesc: "Tout ce que vous devez savoir sur GCNM Ventures",
    faqContent: `
      <h4>Qu'est-ce que GCNM MUSIC ?</h4><p>Une plateforme de musique africaine avec streaming, IA, wallet intégré et classements.</p>
      <h4>Comment devenir artiste sur GCNM ?</h4><p>Visitez la page Artistes et inscrivez-vous comme Nouveau Talent ou Artiste Officiel.</p>
      <h4>Qu'est-ce que le Makubungo ?</h4><p>La monnaie numérique utilisée dans GCNM Wallet (1 Makubungo = 100 Kz).</p>
      <h4>Puis-je utiliser GCNM Wallet hors plateforme ?</h4><p>Oui, même sans compte sur GCNM MUSIC.</p>
      <h4>Comment devenir partenaire GCNM ?</h4><p>Allez sur la page Partenariats et remplissez le formulaire d'intérêt.</p>`
  }
};

function switchLang(lang) {
  const d = translations[lang];
  document.getElementById('mainTitle').innerText = d.mainTitle;
  document.getElementById('mainDesc').innerText = d.mainDesc;
  document.getElementById('faqContent').innerHTML = d.faqContent;
}
</script>

</body>
</html>
