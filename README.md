<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GCNM Ventures - Plataforma Pan-Africana</title>
  <meta name="description" content="GCNM Ventures - ecossistema pan-africano para música, wallet digital, talentos e IA. Multilíngue, inovador e inclusivo.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body { font-family: 'Segoe UI', sans-serif; scroll-behavior: smooth; }
    header, section { padding: 60px 20px; }
    header { background-color: #000; color: #fff; text-align: center; }
    nav { background-color: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .lang-icons img { width: 28px; margin-left: 8px; cursor: pointer; border-radius: 50%; }
    footer { background-color: #111; color: #ccc; text-align: center; padding: 20px; }
    #whatsapp { position: fixed; bottom: 20px; right: 20px; z-index: 999; }
  </style>
</head>
<body>

<!-- MENU -->
<nav class="navbar navbar-expand-lg sticky-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">GCNM Ventures</a>
    <div class="ms-auto lang-icons">
      <img src="https://flagcdn.com/w40/ao.png" onclick="switchLang('pt')" title="Português" />
      <img src="https://flagcdn.com/w40/gb.png" onclick="switchLang('en')" title="English" />
      <img src="https://flagcdn.com/w40/fr.png" onclick="switchLang('fr')" title="Français" />
      <img src="https://flagcdn.com/w40/eg.png" onclick="switchLang('ar')" title="عربي" />
      <img src="https://flagcdn.com/w40/tz.png" onclick="switchLang('sw')" title="Kiswahili" />
      <img src="https://flagcdn.com/w40/ng.png" onclick="switchLang('ha')" title="Hausa" />
      <img src="https://flagcdn.com/w40/za.png" onclick="switchLang('zu')" title="Zulu" />
      <img src="https://flagcdn.com/w40/za.png" onclick="switchLang('xh')" title="Xhosa" />
      <img src="https://flagcdn.com/w40/ma.png" onclick="switchLang('ber')" title="Tamazight" />
      <img src="https://flagcdn.com/w40/es.png" onclick="switchLang('es')" title="Español" />
      <img src="https://flagcdn.com/w40/de.png" onclick="switchLang('de')" title="Deutsch" />
      <img src="https://flagcdn.com/w40/cn.png" onclick="switchLang('zh')" title="中文" />
      <img src="https://flagcdn.com/w40/in.png" onclick="switchLang('hi')" title="हिंदी" />
    </div>
  </div>
</nav>

<!-- CABEÇALHO -->
<header>
  <h1 id="mainTitle">Bem-vindo ao Ecossistema GCNM</h1>
  <p id="mainDesc">Unindo música africana, tecnologia, IA e inclusão digital global.</p>
</header>

<!-- CONTEÚDO -->
<section>
  <div class="container">
    <h2 id="sectionTitle">Sobre a GCNM Ventures</h2>
    <p id="sectionText">Plataforma pan-africana que conecta talentos, artistas, inovação financeira e cultural com IA, wallet digital, rankings musicais e oportunidades internacionais.</p>
  </div>
</section>

<!-- RODAPÉ -->
<footer>
  <p>&copy; 2025 GCNM Ventures. Todos os direitos reservados.</p>
</footer>

<!-- WHATSAPP -->
<a href="https://wa.me/244938248388?text=Olá!%20Gostaria%20de%20saber%20mais%20sobre%20a%20GCNM%20Ventures" target="_blank" id="whatsapp">
  <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" width="60" alt="WhatsApp">
</a>

<!-- SCRIPT DE IDIOMAS -->
<script>
const translations = {
  pt: {
    mainTitle: "Bem-vindo ao Ecossistema GCNM",
    mainDesc: "Unindo música africana, tecnologia, IA e inclusão digital global.",
    sectionTitle: "Sobre a GCNM Ventures",
    sectionText: "Plataforma pan-africana que conecta talentos, artistas, inovação financeira e cultural com IA, wallet digital, rankings musicais e oportunidades internacionais."
  },
  en: {
    mainTitle: "Welcome to the GCNM Ecosystem",
    mainDesc: "Connecting African music, tech, AI and global digital inclusion.",
    sectionTitle: "About GCNM Ventures",
    sectionText: "Pan-African platform linking talents, artists, financial and cultural innovation with AI, digital wallet, music rankings and international opportunities."
  },
  fr: {
    mainTitle: "Bienvenue dans l'écosystème GCNM",
    mainDesc: "Unissant musique africaine, technologie, IA et inclusion numérique mondiale.",
    sectionTitle: "À propos de GCNM Ventures",
    sectionText: "Plateforme panafricaine connectant talents, artistes, innovation financière et culturelle avec IA, portefeuille numérique, classements musicaux et opportunités internationales."
  },
  ar: {
    mainTitle: "مرحبًا بكم في منظومة GCNM",
    mainDesc: "ربط الموسيقى الأفريقية بالتكنولوجيا والذكاء الاصطناعي والشمول الرقمي العالمي.",
    sectionTitle: "حول GCNM Ventures",
    sectionText: "منصة أفريقية تربط المواهب والفنانين والابتكار المالي والثقافي بالذكاء الاصطناعي والمحفظة الرقمية وتصنيفات الموسيقى والفرص الدولية."
  },
  sw: {
    mainTitle: "Karibu kwenye mfumo wa GCNM",
    mainDesc: "Kuunganisha muziki wa Afrika, teknolojia, AI na ushirikishwaji wa kidigitali duniani.",
    sectionTitle: "Kuhusu GCNM Ventures",
    sectionText: "Jukwaa la Pan-Afrika linalounganisha vipaji, wasanii, ubunifu wa kifedha na kitamaduni na AI, mkoba wa kidijitali, viwango vya muziki na fursa za kimataifa."
  },
  ha: {
    mainTitle: "Barka da zuwa tsarin GCNM",
    mainDesc: "Haɗa waƙar Afirka, fasaha, AI da haɗin dijital na duniya.",
    sectionTitle: "Game da GCNM Ventures",
    sectionText: "Dandalin Afirka da ke haɗa baiwa, mawaka, sabbin hanyoyin kuɗi da al'adu da AI, walat dijital, da damar kasa da kasa."
  },
  zu: {
    mainTitle: "Siyakwamukela kuGCNM Ventures",
    mainDesc: "Ukuhlanganisa umculo wase-Afrika, ubuchwepheshe, AI kanye nokufakwa emhlabeni jikelele.",
    sectionTitle: "Mayelana neGCNM Ventures",
    sectionText: "Ipulatifomu yase-Afrika ehlanganisa amakhono, abaculi, ubuchwepheshe bezezimali namasiko ne-AI, iwallet yedijithali, izinga lomculo namathuba omhlaba wonke."
  },
  xh: {
    mainTitle: "Wamkelekile kwiGCNM Ventures",
    mainDesc: "Udibana nomculo waseAfrika, iteknoloji, AI kunye nokufikelela kwidijithali kwehlabathi.",
    sectionTitle: "Malunga neGCNM Ventures",
    sectionText: "Iqonga lePan-Afrika elidibanisa italente, amagcisa, uqoqosho kunye ne-AI, i-wallet yedijithali, amanqanaba omculo namathuba amazwe ngamazwe."
  },
  ber: {
    mainTitle: "ⵓⵙⵙⴰⵎⴰⵏ ⴰⵙⵙ ⴳⴻ GCNM",
    mainDesc: "ⵓⵍⵍⵓⵎ ⴰⵎⵓⵙⵉⴽⵓ ⴰⴼⵔⵉⴽⴰⵏ ⴰⵏⴰⵎⴻⵔ, ⵜⵉⴽⵏⵍⵉⵍ, ⴰⵢ ⵉⴼⵉⵙ ⴰⴳⴻⴷⴷⴰⴷ.",
    sectionTitle: "ⴰⵏⴰⵎⴻⵔ GCNM Ventures",
    sectionText: "ⵜⴰⵎⵙⵙⵓⵔⵜ ⴰⵏⴰⵎⴻⵔ ⵓⵏⴰⵎⵓⵔⵜ ⵜⴰⵎⴰⵔⴰⵡⴻⵜ, ⵉⵎⴰⵣⵉⵖⵏ, ⵜⵉⴽⵏⵍⵉⵍ ⵓⵏⴰⵎⵎⴻⵔ, AI, ⵡⴰⵍⴻⵜ ⴰⴷⵉⵊⵉⵜⴰⵍ ⴰⴳⵎⴰⵣⵏ ⵓⵏⴰⵎⴻⵔ."
  },
  es: {
    mainTitle: "Bienvenido al Ecosistema GCNM",
    mainDesc: "Unimos música africana, tecnología, IA e inclusión digital global.",
    sectionTitle: "Sobre GCNM Ventures",
    sectionText: "Plataforma panafricana que conecta talentos, artistas, innovación cultural y financiera con IA, wallet digital, rankings musicales y oportunidades globales."
  },
  de: {
    mainTitle: "Willkommen im GCNM-Ökosystem",
    mainDesc: "Afrikanische Musik, Technologie, KI und digitale Integration global verbinden.",
    sectionTitle: "Über GCNM Ventures",
    sectionText: "Panafrikanische Plattform für Talente, Künstler, Innovationen mit KI, digitalem Wallet, Musik-Rankings und internationalen Chancen."
  },
  zh: {
    mainTitle: "欢迎来到 GCNM 生态系统",
    mainDesc: "连接非洲音乐、技术、人工智能与全球数字融合。",
    sectionTitle: "关于 GCNM Ventures",
    sectionText: "泛非平台，将人才、艺术家、金融与文化创新、AI、数字钱包和国际机会连接起来。"
  },
  hi: {
    mainTitle: "GCNM इकोसिस्टम में आपका स्वागत है",
    mainDesc: "अफ्रीकी संगीत, तकनीक, एआई और वैश्विक डिजिटल समावेशन को जोड़ना।",
    sectionTitle: "GCNM Ventures के बारे में",
    sectionText: "पैन-अफ्रीकी मंच जो प्रतिभाओं, कलाकारों, सांस्कृतिक और वित्तीय नवाचारों को AI, डिजिटल वॉलेट और अंतर्राष्ट्रीय अवसरों के साथ जोड़ता है।"
  }
};

function switchLang(lang) {
  const d = translations[lang];
  for (let key in d) {
    const el = document.getElementById(key);
    if (el) el.innerText = d[key];
  }
}
</script>

</body>
</html>
