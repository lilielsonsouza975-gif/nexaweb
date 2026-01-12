<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>NexaWeb | Agência Digital Premium</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
:root{
  --primary:#2563eb;
  --dark:#020617;
  --text:#0f172a;
  --muted:#64748b;
  --bg:#ffffff;
  --soft:#f8fafc;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Inter',sans-serif;
}

body{
  background:var(--bg);
  color:var(--text);
  line-height:1.6;
}

.container{
  max-width:1200px;
  margin:auto;
  padding:0 24px;
}

/* HEADER */
header{
  position:fixed;
  top:0;
  width:100%;
  background:rgba(255,255,255,.85);
  backdrop-filter:blur(12px);
  border-bottom:1px solid #e5e7eb;
  z-index:100;
}

header .container{
  height:80px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.logo{
  font-size:1.9rem;
  font-weight:800;
}

.logo span{
  color:var(--primary);
}

.btn{
  padding:14px 32px;
  border-radius:12px;
  text-decoration:none;
  font-weight:600;
  transition:.3s;
}

.btn.primary{
  background:var(--primary);
  color:#fff;
}

.btn.primary:hover{
  transform:translateY(-2px);
  box-shadow:0 15px 35px rgba(37,99,235,.35);
}

/* HERO */
.hero{
  padding:180px 0 140px;
  background:linear-gradient(180deg,#f8fafc,#fff);
}

.hero-grid{
  display:grid;
  grid-template-columns:1.2fr .8fr;
  gap:100px;
  align-items:center;
}

.hero h1{
  font-size:3.8rem;
  font-weight:800;
  line-height:1.1;
  opacity:0;
  transform:translateY(20px);
  animation:fadeUp 1s ease forwards;
}

.hero h1 span{
  background:linear-gradient(90deg,var(--primary),#60a5fa);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

.hero p{
  margin:32px 0 44px;
  font-size:1.15rem;
  color:var(--muted);
  max-width:520px;
  opacity:0;
  transform:translateY(20px);
  animation:fadeUp 1s ease forwards;
  animation-delay:.15s;
}

.hero .btn{
  opacity:0;
  transform:translateY(20px);
  animation:fadeUp 1s ease forwards;
  animation-delay:.3s;
}

.hero-card{
  background:#fff;
  padding:44px;
  border-radius:24px;
  border:1px solid #e5e7eb;
  box-shadow:0 40px 90px rgba(0,0,0,.08);
}

.hero-card div{
  margin-bottom:18px;
  font-weight:500;
}

/* SECTIONS */
section{
  padding:140px 0;
}

.title{
  text-align:center;
  max-width:640px;
  margin:0 auto 90px;
}

.title h2{
  font-size:2.8rem;
  margin-bottom:18px;
}

.title p{
  color:var(--muted);
  font-size:1.05rem;
}

/* FEATURES */
.features{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:48px;
}

.feature{
  background:#fff;
  padding:42px;
  border-radius:22px;
  border:1px solid #e5e7eb;
  transition:.4s;
}

.feature:hover{
  transform:translateY(-8px);
  box-shadow:0 35px 70px rgba(0,0,0,.08);
}

/* PRICING */
.pricing{
  background:var(--soft);
}

.plans{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:48px;
}

.plan{
  background:#fff;
  padding:48px;
  border-radius:26px;
  border:1px solid #e5e7eb;
}

.plan.featured{
  border:2px solid var(--primary);
  transform:scale(1.05);
}

.plan h3{
  font-size:1.3rem;
}

.price{
  font-size:1.7rem;
  font-weight:800;
  color:var(--primary);
  margin:22px 0;
}

.plan li{
  margin-bottom:14px;
  color:#475569;
}

/* CTA */
.cta{
  background:linear-gradient(135deg,#020617,#0f172a);
  color:#fff;
  text-align:center;
  padding:160px 20px;
}

.cta h2{
  font-size:3rem;
  margin-bottom:36px;
}

/* FOOTER */
footer{
  background:#020617;
  color:#94a3b8;
  text-align:center;
  padding:32px;
}

/* ANIMAÇÃO */
@keyframes fadeUp{
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* RESPONSIVO */
@media(max-width:900px){
  .hero-grid{
    grid-template-columns:1fr;
  }
  .hero h1{
    font-size:2.6rem;
  }
}
</style>
</head>

<body>

<header>
  <div class="container">
    <div class="logo">Nexa<span>Web</span></div>
    <a href="https://wa.me/5596984109690" target="_blank" class="btn primary">Fazer orçamento</a>
  </div>
</header>

<section class="hero">
  <div class="container hero-grid">
    <div>
      <h1>Presença digital <span>premium</span> para marcas que exigem mais</h1>
      <p>
        Criamos sites de alto padrão focados em credibilidade,
        performance e conversão real de clientes.
      </p>
      <a href="https://wa.me/5596984109690" target="_blank" class="btn primary">
        Solicitar orçamento
      </a>
    </div>

    <div class="hero-card">
      <div>✔ Design exclusivo e elegante</div>
      <div>✔ Experiência focada em conversão</div>
      <div>✔ Integração total com WhatsApp</div>
      <div>✔ Conteúdo estratégico com IA</div>
    </div>
  </div>
</section>

<section>
  <div class="container">
    <div class="title">
      <h2>Por que a NexaWeb?</h2>
      <p>Não entregamos sites. Entregamos posicionamento digital.</p>
    </div>

    <div class="features">
      <div class="feature">Design premium de alto nível</div>
      <div class="feature">Velocidade, SEO e performance</div>
      <div class="feature">Arquitetura focada em conversão</div>
      <div class="feature">Atendimento e entrega profissional</div>
    </div>
  </div>
</section>

<section class="pricing">
  <div class="container">
    <div class="title">
      <h2>Planos</h2>
      <p>Soluções sob medida para cada fase do seu negócio.</p>
    </div>

    <div class="plans">
      <div class="plan">
        <h3>🟢 Básico</h3>
        <div class="price">R$ 497 a R$ 897</div>
        <ul>
          <li>Site institucional</li>
          <li>Design profissional</li>
          <li>Botão WhatsApp</li>
        </ul>
        <a href="https://wa.me/5596984109690" class="btn primary">Fazer orçamento</a>
      </div>

      <div class="plan featured">
        <h3>🔵 Profissional</h3>
        <div class="price">R$ 997 a R$ 1.997</div>
        <ul>
          <li>Até 5 páginas</li>
          <li>SEO básico</li>
          <li>Formulário de contato</li>
        </ul>
        <a href="https://wa.me/5596984109690" class="btn primary">Fazer orçamento</a>
      </div>

      <div class="plan">
        <h3>🟣 Premium</h3>
        <div class="price">R$ 2.500+</div>
        <ul>
          <li>Chatbot com IA</li>
          <li>Integração avançada</li>
          <li>Manutenção mensal</li>
        </ul>
        <a href="https://wa.me/5596984109690" class="btn primary">Fazer orçamento</a>
      </div>
    </div>
  </div>
</section>

<section class="cta">
  <h2>Vamos elevar sua marca ao próximo nível?</h2>
  <a href="https://wa.me/5596984109690" class="btn primary">Falar com um especialista</a>
</section>

<footer>
  © 2026 NexaWeb — Agência Digital Premium
</footer>

</body>
</html>
