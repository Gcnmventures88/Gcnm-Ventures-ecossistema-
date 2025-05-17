<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GCNM Wallet - Makubungo</title>
  <meta name="description" content="GCNM Wallet: carteira digital Makubungo com integração internacional, IA e inclusão financeira para África.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body { font-family: 'Segoe UI', sans-serif; scroll-behavior: smooth; }
    header, section { padding: 60px 20px; }
    header { background-color: #00563f; color: #fff; text-align: center; }
    nav { background-color: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 10px 20px; }
    .lang-icons img { width: 28px; margin-left: 8px; cursor: pointer; border-radius: 50%; }
    footer { background-color: #111; color: #ccc; text-align: center; padding: 20px; }
    #whatsapp { position: fixed; bottom: 20px; right: 20px; z-index: 999; }
  </style>
</head>
<body>

<!-- Menu topo -->
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
  <h1 id="mainTitle">GCNM Wallet</h1>
  <p id="mainDesc">Sua carteira digital Makubungo, rápida, segura e global.</p>
</header>

<!-- Conteúdo -->
<section>
  <div class="container">
    <h2 id="sectionTitle">Sobre a GCNM Wallet</h2>
    <p id="sectionText">
      A GCNM Wallet é a carteira digital oficial do ecossistema GCNM Ventures. Usando a moeda Makubungo (1 Makubungo = 100 Kz), ela permite transferências, pagamentos, saques e recompensas entre artistas, ouvintes e parceiros. Integrada com inteligência artificial, multilíngue e acessível em qualquer país.
    </p>
    <p id="sectionText2">
      Disponível para qualquer pessoa — mesmo fora da plataforma GCNM MUSIC. Integra-se com IBAN, telefone, carteiras móveis e bancos locais. Totalmente segura e controlada por IA com 95% de automação.
    </p>
  </div>
</section>

<!-- Rodapé -->
<footer>
  <p>&copy; 2025 GCNM Ventures – Makubungo Wallet. Todos os direitos reservados.</p>
</footer>

<!-- Botão WhatsApp -->
<a href="https://wa.me/244938248388?text=Olá!%20Gostaria%20de%20saber%20mais%20sobre%20a%20GCNM%20Wallet" target="_blank" id="whatsapp">
  <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" width="60" alt="WhatsApp">
</a>

<!-- Tradução -->
<script>
  const translations = {
    pt: {
      mainTitle: "GCNM Wallet",
      mainDesc: "Sua carteira digital Makubungo, rápida, segura e global.",
      sectionTitle: "Sobre a GCNM Wallet",
      sectionText: "A GCNM Wallet é a carteira digital oficial do ecossistema GCNM Ventures. Usando a moeda Makubungo (1 Makubungo = 100 Kz), ela permite transferências, pagamentos, saques e recompensas entre artistas, ouvintes e parceiros. Integrada com inteligência artificial, multilíngue e acessível em qualquer país.",
      sectionText2: "Disponível para qualquer pessoa — mesmo fora da plataforma GCNM MUSIC. Integra-se com IBAN, telefone, carteiras móveis e bancos locais. Totalmente segura e controlada por IA com 95% de automação."
    },
    en: {
      mainTitle: "GCNM Wallet",
      mainDesc: "Your Makubungo digital wallet: fast, secure, and global.",
      sectionTitle: "About GCNM Wallet",
      sectionText: "GCNM Wallet is the official digital wallet of GCNM Ventures. Using the Makubungo currency (1 Makubungo = 100 Kz), it allows transfers, payments, withdrawals, and rewards for artists, listeners, and partners. AI-powered, multilingual, and globally accessible.",
      sectionText2: "Available to anyone — even outside the GCNM MUSIC platform. Integrated with IBAN, phone numbers, mobile wallets, and local banks. Fully secure and 95% managed by AI."
    },
    fr: {
      mainTitle: "GCNM Wallet",
      mainDesc: "Votre portefeuille Makubungo, rapide, sécurisé et mondial.",
      sectionTitle: "À propos de GCNM Wallet",
      sectionText: "GCNM Wallet est le portefeuille numérique officiel de GCNM Ventures. Utilisant la monnaie Makubungo (1 Makubungo = 100 Kz), il permet les transferts, paiements, retraits et récompenses entre artistes, auditeurs et partenaires. Alimenté par l'IA, multilingue et accessible partout dans le monde.",
      sectionText2: "Disponible pour tous, même hors de la plateforme GCNM MUSIC. Intégré avec IBAN, numéro de téléphone, portefeuilles mobiles et banques locales. Sécurisé et contrôlé par l'IA à 95%."
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
