<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Concurso de Histórias – A Hora da Abobrinha</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      --verde: #2e7d32;
      --laranja: #ff9800;
      --cinza-claro: #f5f5f5;
      --cinza-escuro: #333333;
    }

    * {
      box-sizing: border-box;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    body {
      margin: 0;
      background: var(--cinza-claro);
      color: var(--cinza-escuro);
      display: flex;
      justify-content: center;
      padding: 24px;
    }

    .container {
      max-width: 640px;
      width: 100%;
      background: #ffffff;
      border-radius: 16px;
      padding: 24px 20px 28px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    }

    .top-banner {
      background: linear-gradient(90deg, var(--verde), var(--laranja));
      border-radius: 999px;
      padding: 10px 16px;
      color: #ffffff;
      margin-bottom: 14px;
      display: flex;
      flex-direction: column;
      gap: 2px;
    }

    .top-banner-line1 {
      font-size: 11px;
      letter-spacing: .18em;
      text-transform: uppercase;
      opacity: 0.9;
      font-weight: 600;
    }

    .top-banner-line2 {
      font-size: 18px;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .top-banner-line2 span.emoji {
      font-size: 20px;
    }

    h1 {
      margin: 0 0 8px;
      font-size: 22px;
      line-height: 1.3;
      color: var(--cinza-escuro);
    }

    h2 {
      font-size: 20px;
      margin-top: 24px;
      margin-bottom: 8px;
      color: var(--verde);
    }

    p {
      margin: 6px 0;
      line-height: 1.5;
      font-size: 15px;
    }

    ul {
      margin: 6px 0 0 18px;
      padding: 0;
      font-size: 15px;
      line-height: 1.5;
    }

    .highlight-box {
      background: rgba(255,152,0,0.08);
      border-left: 4px solid var(--laranja);
      border-radius: 12px;
      padding: 12px 14px;
      margin-top: 10px;
      font-size: 14px;
    }

    .buttons-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 10px;
      margin-top: 18px;
      margin-bottom: 10px;
    }

    @media (min-width: 600px) {
      .buttons-grid {
        grid-template-columns: 1fr 1fr;
      }
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 10px 12px;
      border-radius: 999px;
      border: none;
      text-decoration: none;
      font-size: 14px;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.08s ease, box-shadow 0.08s ease, filter 0.08s ease;
      white-space: nowrap;
    }

    .btn-primary {
      background: var(--verde);
      color: #ffffff;
      box-shadow: 0 3px 10px rgba(46,125,50,0.3);
    }

    .btn-primary:hover {
      filter: brightness(1.05);
      transform: translateY(-1px);
      box-shadow: 0 6px 18px rgba(46,125,50,0.35);
    }

    .btn-secondary {
      background: #ffffff;
      color: var(--verde);
      border: 1px solid rgba(46,125,50,0.25);
    }

    .btn-secondary:hover {
      background: rgba(46,125,50,0.03);
      transform: translateY(-1px);
    }

    .btn-ghost {
      background: transparent;
      color: var(--cinza-escuro);
      border: 1px solid rgba(0,0,0,0.06);
    }

    .btn-ghost:hover {
      background: rgba(0,0,0,0.02);
      transform: translateY(-1px);
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      margin-top: 6px;
      margin-bottom: 4px;
    }

    .pill {
      font-size: 11px;
      padding: 4px 8px;
      border-radius: 999px;
      border: 1px solid rgba(0,0,0,0.06);
      background: #fafafa;
    }

    .footer {
      margin-top: 20px;
      font-size: 12px;
      color: #777;
      text-align: center;
    }

    .hashtag-row {
      margin-top: 6px;
      font-size: 13px;
      color: #555;
    }

    .date-row {
      font-weight: 600;
      margin-top: 6px;
    }

    .pix-box {
      margin-top: 12px;
      font-size: 14px;
    }

    .pix-key {
      font-family: "Consolas", "SF Mono", Menlo, monospace;
      font-size: 14px;
      background: #f0f0f0;
      padding: 4px 8px;
      border-radius: 6px;
    }
  </style>
</head>
<body>
  <main class="container">
    <div class="top-banner">
      <div class="top-banner-line1">CONCURSO DE HISTÓRIAS</div>
      <div class="top-banner-line2">
        <span>A HORA DA ABOBRINHA</span>
        <span class="emoji">🎙️🥒</span>
      </div>
    </div>

    <h1>Conte sua história e participe de um episódio especial!</h1>

    <p>
      Participe do concurso de histórias do podcast <strong>A HORA DA ABOBRINHA</strong> e transforme
      sua ideia em um episódio especial. Criatividade liberada e bom humor em primeiro lugar. 😄
    </p>

    <div class="buttons-grid">
      <a class="btn btn-primary"
         href="https://wa.me/5511999110843?text=Ol%C3%A1%21+Quero+participar+do+concurso+de+hist%C3%B3rias+A+Hora+da+Abobrinha%21">
        Enviar história pelo WhatsApp
      </a>

      <a class="btn btn-secondary"
         href="mailto:ruyaschnaider@gmail.com?subject=Concurso%20A%20Hora%20da%20Abobrinha&body=Ol%C3%A1%21%20Quero%20participar%20do%20concurso%20de%20hist%C3%B3rias%20A%20Hora%20da%20Abobrinha.%20Segue%20minha%20hist%C3%B3ria%20em%20anexo%20ou%20no%20corpo%20do%20e-mail.">
        Enviar história por E-mail
      </a>

      <a class="btn btn-ghost"
         href="https://abrir.link/dyjvt"
         target="_blank" rel="noopener noreferrer">
        Ouça o podcast
      </a>

      <a class="btn btn-ghost"
         href="https://www.instagram.com/ahoradaabobrinha"
         target="_blank" rel="noopener noreferrer">
        Instagram @ahoradaabobrinha
      </a>
    </div>

    <div class="highlight-box">
      <strong>Inscrição:</strong> R$ 25,00 por história. <br>
      <strong>Envio:</strong> áudio ou texto, com até <strong>5 minutos</strong> ou <strong>500 palavras</strong>. <br>
      <strong>Tema livre</strong>, mas sem polêmicas ou conteúdo ofensivo.
    </div>

    <h2>Regras para participar</h2>
    <ul>
      <li>Envie sua história em <strong>áudio ou texto</strong>.</li>
      <li>Encaminhe para o e-mail <strong>ruyaschnaider@gmail.com</strong> ou para o WhatsApp <strong>(11) 99911-0843</strong>.</li>
      <li>A história deve ter no máximo <strong>5 minutos</strong> de duração (ou <strong>500 palavras</strong>).</li>
      <li>O tema é livre, mas sem polêmicas, discursos de ódio ou conteúdo ofensivo.</li>
      <li>As histórias devem ser <strong>originais</strong> e não publicadas anteriormente.</li>
    </ul>

    <h2>Premiação</h2>
    <p>
      🥇 A <strong>1ª colocada</strong> receberá uma <strong>abobrinha surpresa</strong> com caráter
      incentivador para novos projetos culturais!
    </p>
    <p>
      🎧 As <strong>5 primeiras colocadas</strong> farão parte de episódios especiais do podcast
      <strong>A HORA DA ABOBRINHA</strong>.
    </p>

    <h2>Pagamento da inscrição</h2>
    <div class="pix-box">
      <p><strong>Valor:</strong> R$ 25,00 por história</p>
      <p><strong>Forma de pagamento:</strong> PIX</p>
      <p><strong>Chave (celular):</strong> <span class="pix-key">11999110843</span></p>
      <p><strong>Nome:</strong> Ruy A Schneider</p>
      <p>
        Após o pagamento, envie o comprovante junto com sua história pelo WhatsApp ou e-mail.
      </p>
    </div>

    <h2>Datas importantes</h2>
    <p class="date-row">
      📅 Encerramento das inscrições: <strong>26/12/2025</strong><br>
      📢 Anúncio das histórias selecionadas: <strong>28/12/2025</strong>
    </p>

    <div class="highlight-box">
      <strong>NÃO PERCA ESSA OPORTUNIDADE!</strong><br>
      Envie sua história agora mesmo e concorra a um prêmio incrível – e, quem sabe, ao seu momento
      de glória no mundo dos podcasts! 🎙️
    </div>

    <div class="pill-row">
      <span class="pill">#AHoraDaAbobrinha</span>
      <span class="pill">#ConcursoDeHistórias</span>
      <span class="pill">#Podcast</span>
      <span class="pill">#Criatividade</span>
      <span class="pill">#ConteSuaHistória</span>
    </div>

    <p class="hashtag-row">
      Compartilhe nas redes marcando <strong>@ahoradaabobrinha</strong> e usando a hashtag
      <strong>#ConteSuaHistória</strong>.
    </p>

    <div class="footer">
      Produção: A HORA DA ABOBRINHA · Podcast &amp; Histórias com bom humor.<br>
      Dúvidas? Fale com a gente pelo WhatsApp: (11) 99911-0843.
    </div>
  </main>
</body>
</html>
