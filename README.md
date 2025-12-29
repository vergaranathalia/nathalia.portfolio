# nathalia.portfolio
Portfólio profissional da Nathalia Vergara
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nathalia Vergara - Portfólio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Containers gerais */
    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    h2, h3 {
      margin-bottom: 20px;
      color: #222;
    }

    p {
      margin-bottom: 15px;
    }

    /* Layout de colunas */
    .row {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      align-items: center;
    }

    .col-50 {
      flex: 0 0 50%;
    }

    .col-33 {
      flex: 0 0 33.33%;
    }

    img {
      max-width: 100%;
      display: block;
      border-radius: 8px;
      object-fit: cover;
    }

    /* Botões */
    .btn {
      display: inline-block;
      padding: 12px 25px;
      background-color: #444;
      color: #fff;
      border-radius: 5px;
      transition: background-color 0.3s;
      margin-top: 15px;
    }

    .btn:hover {
      background-color: #222;
    }

    /* Títulos centrais */
    .text-center {
      text-align: center;
    }

    /* Blocos de destaque (cover) */
    .cover {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      margin-bottom: 40px;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
    }

    .cover img {
      width: 100%;
      height: auto;
      opacity: 0.5;
    }

    .cover-content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    /* Responsividade */
    @media(max-width: 900px){
      .col-50, .col-33 {
        flex: 0 0 100%;
      }
    }

  </style>
</head>
<body>

  <!-- Seção Sobre -->
  <section class="section" id="sobre">
    <div class="row">
      <div class="col-50">
        <h3>Sobre mim</h3>
        <h2>Nathalia Vergara</h2>
        <p>Jornalista formada pela UFOP. Tenho experiência com assessoria de imprensa, comunicação interna, redação, jornalismo, social media e edição de vídeos e áudios.</p>
        <p>Profissional de Comunicação com atuação estratégica em Assessoria de Imprensa, Comunicação Interna e Marketing Institucional. Tenho experiência na consolidação de fluxos de comunicação, desenvolvimento de projetos estruturantes, gestão de crises, produção de conteúdo multicanal e articulação com diferentes áreas da organização para garantir alinhamento e visibilidade. Atuo de forma integrada, combinando visão analítica, agilidade, rigor técnico e orientação a resultados — tanto na imprensa quanto nos canais internos da instituição.</p>
        <a href="#contato" class="btn">Contato</a>
      </div>
      <div class="col-50">
        <img src="https://vergaranathalia98-wuxyv.wordpress.com/wp-content/uploads/2025/12/eu.jpg" alt="Nathalia Vergara">
      </div>
    </div>
  </section>

  <!-- Seção Atuação -->
  <section class="section text-center">
    <h3>Minha atuação na Faculdade Santa Casa de SP em 2025:</h3>
    <p>Em 2025, fui responsável por duas frentes centrais da Comunicação Institucional: a Assessoria de Imprensa e a Comunicação Interna, garantindo resultados expressivos para a empresa.</p>
  </section>

  <!-- Seção Destaques / Cover -->
  <section class="section">
    <div class="row">
      <div class="col-33">
        <div class="cover" style="background-color:#92877a;">
          <img src="https://vergaranathalia98-wuxyv.wordpress.com/wp-content/uploads/2025/12/site-title-6952edeaed0d2.png" alt="">
          <div class="cover-content">
            <p>Assessoria de imprensa:</p>
            <p>— Proposição de pautas (proativas)<br>— Gestão de demandas da mídia (reativas)<br>— Produção de releases<br>— Relacionamento com jornalistas<br>— Apoio às áreas para garantir porta-vozes preparados</p>
          </div>
        </div>
      </div>
      <div class="col-33">
        <div class="cover" style="background-color:#8c8e89;">
          <img src="https://vergaranathalia98-wuxyv.wordpress.com/wp-content/uploads/2025/12/site-title-6952ede7e2259.png" alt="">
          <div class="cover-content">
            <p>Comunicação interna:</p>
            <p>— Planejamento, redação e gestão de mensagens<br>— Consolidação de newsletters<br>— Ações de endomarketing<br>— Campanhas temáticas<br>— Estruturação de novos canais<br>— Desenvolvimento de identidade visual<br>— Apoio em setores estratégicos</p>
          </div>
        </div>
      </div>
      <div class="col-33">
        <div class="cover" style="background-color:#948e88;">
          <img src="https://vergaranathalia98-wuxyv.wordpress.com/wp-content/uploads/2025/12/site-title-6952ede960f69.png" alt="">
          <div class="cover-content">
            <h3>Resultados</h3>
            <p>+ de 500 mil impactos combinados</p>
            <p>73 pautas proativas em 2025</p>
            <p>+ de 600 inserções espontâneas na imprensa</p>
            <p>Relacionamento ativo com grandes veículos</p>
            <p>Melhoria da narrativa institucional</p>
            <p>Ampliação da presença da instituição em temas de saúde, educação, pesquisa e extensão</p>
            <p>+ de 230 ações internas no ano</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Seção Projetos -->
  <section class="section">
    <h3>Principais projetos entregues:</h3>
    <div class="row">
      <div class="col-33">
        <p>Comunicação organizacional:</p>
        <p>✔ Identidade visual padronizada<br>✔ Nova assinatura de e-mail<br>✔ Newsletter mensal consolidada<br>✔ Murais físicos instalados<br>✔ Uso do wallpaper institucional<br>✔ Trilha de boas práticas<br>✔ Fluxo de boas-vindas a novos colaboradores<br>✔ Criação do Canal de WhatsApp<br>✔ Fortalecimento do LinkedIn institucional</p>
      </div>
      <div class="col-33">
        <p>Comunicação interna:</p>
        <p>✔ Abril Azul<br>✔ Campanha de Influenza<br>✔ Projetos de extensão Yoga Santa / Medita Santa<br>✔ Setembro Amarelo<br>✔ Outubro Rosa<br>✔ Novembro Azul<br>✔ Dezembro vermelho<br>✔ Plano de Abandono do SESMT<br>✔ SIPAT<br>✔ Divulgação de conquistas acadêmicas e científicas<br>✔ Divulgação de eventos e comunicados de segurança<br>✔ Trilhas de boas práticas para onboarding</p>
      </div>
      <div class="col-33">
        <p>Principais Releases:</p>
        <p>✔ texto<br>✔ texto<br>✔ texto<br>✔ texto</p>
      </div>
    </div>
    <h3>Conheça os projetos:</h3>
    <div class="row">
      <div class="col-33">
        <p>Releases:</p>
        <p>(inserir hiperlink)</p>
      </div>
      <div class="col-33">
        <p>Comunicação interna:</p>
        <p>(inserir hiperlink)</p>
      </div>
      <div class="col-33">
        <p>Notícias institucionais:</p>
        <p>(inserir hiperlink)</p>
      </div>
    </div>
  </section>

  <!-- Seção Footer / Sobre outras atuações -->
  <section class="section text-center" id="contato">
    <h3>Jornalista | Redatora | Social Media | Editora</h3>
    <p>(inserir resumo sobre minhas outras atuações)</p>
    <p>(inserir links de textos, portfólios e outros trabalhos)</p>
  </section>

</body>
</html>
