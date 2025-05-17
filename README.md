<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GCNM Privado</title>
  <meta name="robots" content="noindex, nofollow" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body { font-family: 'Segoe UI', sans-serif; background: #f4f4f4; padding: 40px; }
    h1, h2 { color: #b71c1c; }
    .section { background: #fff; padding: 25px; margin-bottom: 20px; border-radius: 6px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
    code { background: #eee; padding: 2px 6px; border-radius: 4px; }
  </style>
  <script>
    const senha = "gibertocumbo";
    const acesso = prompt("Área restrita GCNM\nDigite a senha para continuar:");
    if (acesso !== senha) {
      document.write("<h2 style='color:red;'>Acesso negado.</h2><p>Você não tem permissão para visualizar esta página.</p>");
      throw new Error("Senha incorreta");
    }
  </script>
</head>
<body>

<h1>Área Privada – GCNM Internal</h1>
<p><strong>Aviso:</strong> Esta é uma área interna protegida. Não compartilhe este link nem a senha.</p>

<div class="section">
  <h2>Links de Vídeos Futuros</h2>
  <ul>
    <li><code>https://www.youtube.com/embed/SEU_VIDEO_1</code> — Campanha Makubungo</li>
    <li><code>https://www.youtube.com/embed/SEU_VIDEO_2</code> — Artista em Destaque</li>
  </ul>
</div>

<div class="section">
  <h2>Anotações ou Textos Rascunho</h2>
  <p>“GCNM Wallet será relançada com novo design e suporte para pagamentos por QR.”</p>
  <p>“Notificação automática para talentos em crescimento.”</p>
</div>

<div class="section">
  <h2>Ideias para Implementar</h2>
  <ul>
    <li>Perfil verificável para artistas</li>
    <li>Integração com canais de TV e rádio</li>
    <li>Eventos mensais com votação por usuários</li>
  </ul>
</div>

<footer class="mt-5 text-muted">
  <p>© 2025 GCNM Ventures – Uso interno. Documento confidencial.</p>
</footer>

</body>
</html>
