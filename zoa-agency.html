<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ZOA Agency — Dijital Büyüme Ajansı</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Syne:wght@400;500;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #060606;
    --white: #f5f4f0;
    --gray: #8a8a8a;
    --gray-dim: #2a2a2a;
    --accent: #f5f4f0;
    --border: rgba(245,244,240,0.08);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--black);
    color: var(--white);
    font-family: 'DM Sans', sans-serif;
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* CURSOR */
  .cursor {
    position: fixed;
    width: 8px; height: 8px;
    background: var(--white);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.15s ease, opacity 0.15s ease;
    transform: translate(-50%, -50%);
  }
  .cursor-ring {
    position: fixed;
    width: 36px; height: 36px;
    border: 1px solid rgba(245,244,240,0.4);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transition: transform 0.4s cubic-bezier(0.16,1,0.3,1), width 0.3s, height 0.3s, opacity 0.3s;
    transform: translate(-50%, -50%);
  }
  body:hover .cursor { opacity: 1; }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 28px 60px;
    border-bottom: 1px solid transparent;
    transition: border-color 0.4s, backdrop-filter 0.4s, background 0.4s;
  }
  nav.scrolled {
    border-color: var(--border);
    backdrop-filter: blur(20px);
    background: rgba(6,6,6,0.8);
  }
  .nav-logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 22px;
    letter-spacing: 0.18em;
    color: var(--white);
    text-decoration: none;
  }
  .nav-logo span {
    font-family: 'DM Sans', sans-serif;
    font-size: 9px;
    letter-spacing: 0.3em;
    font-weight: 300;
    opacity: 0.4;
    display: block;
    margin-top: -2px;
  }
  .nav-links {
    display: flex;
    gap: 40px;
    list-style: none;
  }
  .nav-links a {
    font-size: 12px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--gray);
    text-decoration: none;
    transition: color 0.2s;
    font-weight: 400;
  }
  .nav-links a:hover { color: var(--white); }
  .nav-cta {
    font-size: 11px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    font-weight: 500;
    color: var(--black);
    background: var(--white);
    padding: 10px 24px;
    text-decoration: none;
    transition: opacity 0.2s;
  }
  .nav-cta:hover { opacity: 0.85; }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 60px 80px;
    position: relative;
    overflow: hidden;
  }
  .hero-bg {
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse 60% 50% at 70% 40%, rgba(245,244,240,0.03) 0%, transparent 70%),
      radial-gradient(ellipse 40% 60% at 20% 80%, rgba(245,244,240,0.02) 0%, transparent 60%);
  }
  .hero-grid {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 80px 80px;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 0%, transparent 100%);
    opacity: 0.4;
  }
  .hero-tag {
    font-size: 10px;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--gray);
    margin-bottom: 24px;
    opacity: 0;
    animation: fadeUp 1s 0.3s forwards;
  }
  .hero-headline {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(80px, 12vw, 180px);
    line-height: 0.92;
    letter-spacing: -0.01em;
    text-transform: uppercase;
    opacity: 0;
    animation: fadeUp 1s 0.5s forwards;
  }
  .hero-headline .dim { color: rgba(245,244,240,0.15); }
  .hero-sub-row {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    margin-top: 48px;
    opacity: 0;
    animation: fadeUp 1s 0.8s forwards;
  }
  .hero-desc {
    font-size: 15px;
    line-height: 1.8;
    color: var(--gray);
    max-width: 400px;
  }
  .hero-desc strong { color: var(--white); font-weight: 400; }
  .hero-actions { display: flex; gap: 16px; align-items: center; }
  .btn-primary {
    font-size: 11px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    font-weight: 500;
    color: var(--black);
    background: var(--white);
    padding: 14px 32px;
    text-decoration: none;
    display: inline-block;
    transition: opacity 0.2s;
  }
  .btn-primary:hover { opacity: 0.85; }
  .btn-ghost {
    font-size: 11px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    font-weight: 400;
    color: var(--gray);
    text-decoration: none;
    border-bottom: 1px solid var(--gray-dim);
    padding-bottom: 2px;
    transition: color 0.2s, border-color 0.2s;
  }
  .btn-ghost:hover { color: var(--white); border-color: var(--white); }
  .hero-scroll {
    position: absolute;
    right: 60px;
    bottom: 80px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 12px;
    opacity: 0;
    animation: fadeUp 1s 1.2s forwards;
  }
  .hero-scroll span {
    font-size: 9px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gray);
    writing-mode: vertical-rl;
  }
  .scroll-line {
    width: 1px;
    height: 60px;
    background: linear-gradient(to bottom, var(--gray), transparent);
    animation: scrollLine 2s 1.5s infinite;
  }
  @keyframes scrollLine {
    0% { transform: scaleY(0); transform-origin: top; }
    50% { transform: scaleY(1); transform-origin: top; }
    51% { transform: scaleY(1); transform-origin: bottom; }
    100% { transform: scaleY(0); transform-origin: bottom; }
  }

  /* TICKER */
  .ticker {
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    padding: 16px 0;
    overflow: hidden;
    white-space: nowrap;
  }
  .ticker-inner {
    display: inline-flex;
    gap: 0;
    animation: ticker 25s linear infinite;
  }
  .ticker-item {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 13px;
    letter-spacing: 0.2em;
    color: var(--gray);
    padding: 0 40px;
  }
  .ticker-item span { color: rgba(245,244,240,0.15); margin-right: 40px; }
  @keyframes ticker {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }

  /* SECTION SHARED */
  section { padding: 120px 60px; }
  .section-tag {
    font-size: 10px;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--gray);
    margin-bottom: 16px;
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(36px, 5vw, 64px);
    font-weight: 800;
    line-height: 1.05;
    letter-spacing: -0.02em;
  }
  .section-title .dim { color: rgba(245,244,240,0.2); }
  .divider { width: 100%; height: 1px; background: var(--border); }

  /* ABOUT */
  .about { display: grid; grid-template-columns: 1fr 1fr; gap: 80px; align-items: center; }
  .about-left .section-title { margin-bottom: 40px; }
  .about-text {
    font-size: 16px;
    line-height: 1.9;
    color: var(--gray);
    margin-bottom: 20px;
  }
  .about-text strong { color: var(--white); font-weight: 400; }
  .about-right { position: relative; }
  .about-card {
    background: var(--gray-dim);
    border: 1px solid var(--border);
    padding: 48px;
    position: relative;
  }
  .about-card::before {
    content: '';
    position: absolute;
    top: -1px; left: -1px; right: -1px; bottom: -1px;
    background: linear-gradient(135deg, rgba(245,244,240,0.06) 0%, transparent 60%);
    pointer-events: none;
  }
  .about-stat {
    margin-bottom: 36px;
    padding-bottom: 36px;
    border-bottom: 1px solid var(--border);
  }
  .about-stat:last-child { margin-bottom: 0; padding-bottom: 0; border-bottom: none; }
  .stat-num {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 56px;
    letter-spacing: 0.02em;
    line-height: 1;
    margin-bottom: 6px;
  }
  .stat-label { font-size: 12px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--gray); }

  /* SERVICES */
  .services-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-bottom: 64px;
  }
  .services-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    border-top: 1px solid var(--border);
    border-left: 1px solid var(--border);
  }
  .service-card {
    padding: 40px 36px;
    border-right: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    position: relative;
    overflow: hidden;
    transition: background 0.3s;
  }
  .service-card::after {
    content: '';
    position: absolute;
    inset: 0;
    background: rgba(245,244,240,0.03);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .service-card:hover::after { opacity: 1; }
  .service-num {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 11px;
    letter-spacing: 0.2em;
    color: rgba(245,244,240,0.2);
    margin-bottom: 32px;
  }
  .service-icon {
    width: 36px; height: 36px;
    margin-bottom: 20px;
    opacity: 0.7;
  }
  .service-name {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    margin-bottom: 12px;
    line-height: 1.3;
  }
  .service-desc { font-size: 13px; line-height: 1.7; color: var(--gray); }
  .service-arrow {
    position: absolute;
    bottom: 32px; right: 32px;
    font-size: 20px;
    color: rgba(245,244,240,0.15);
    transition: color 0.2s, transform 0.2s;
  }
  .service-card:hover .service-arrow { color: var(--white); transform: translate(4px, -4px); }

  /* PROCESS */
  .process-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0;
    margin-top: 64px;
    position: relative;
  }
  .process-grid::before {
    content: '';
    position: absolute;
    top: 28px;
    left: 40px; right: 40px;
    height: 1px;
    background: linear-gradient(to right, transparent, var(--border) 20%, var(--border) 80%, transparent);
  }
  .process-step { padding: 0 40px; }
  .process-dot {
    width: 10px; height: 10px;
    border-radius: 50%;
    background: var(--white);
    margin-bottom: 32px;
    position: relative;
    z-index: 1;
  }
  .process-step:nth-child(2) .process-dot,
  .process-step:nth-child(3) .process-dot { background: var(--gray-dim); border: 1px solid var(--gray); }
  .process-num {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 10px;
    letter-spacing: 0.2em;
    color: rgba(245,244,240,0.2);
    margin-bottom: 12px;
  }
  .process-title {
    font-family: 'Syne', sans-serif;
    font-size: 20px;
    font-weight: 700;
    margin-bottom: 12px;
  }
  .process-desc { font-size: 13px; line-height: 1.7; color: var(--gray); }

  /* WHY ZOA */
  .why {
    background: rgba(245,244,240,0.02);
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
  }
  .why-inner {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: center;
  }
  .why-list { margin-top: 48px; }
  .why-item {
    display: flex;
    gap: 24px;
    padding: 28px 0;
    border-bottom: 1px solid var(--border);
  }
  .why-item:first-child { border-top: 1px solid var(--border); }
  .why-check {
    font-size: 12px;
    color: var(--white);
    opacity: 0.4;
    flex-shrink: 0;
    margin-top: 3px;
  }
  .why-text { font-size: 15px; line-height: 1.7; color: var(--gray); }
  .why-text strong { color: var(--white); font-weight: 400; display: block; margin-bottom: 4px; font-family: 'Syne', sans-serif; font-size: 16px; font-weight: 700; }
  .why-quote {
    font-family: 'Syne', sans-serif;
    font-size: clamp(24px, 3vw, 40px);
    font-weight: 800;
    line-height: 1.3;
    letter-spacing: -0.01em;
  }
  .why-quote .accent { color: rgba(245,244,240,0.25); }

  /* CTA */
  .cta-section {
    text-align: center;
    padding: 160px 60px;
    position: relative;
    overflow: hidden;
  }
  .cta-bg {
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 60% 60% at 50% 50%, rgba(245,244,240,0.04) 0%, transparent 70%);
  }
  .cta-label { font-size: 10px; letter-spacing: 0.22em; text-transform: uppercase; color: var(--gray); margin-bottom: 32px; }
  .cta-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(60px, 10vw, 140px);
    line-height: 0.92;
    letter-spacing: -0.01em;
    margin-bottom: 48px;
  }
  .cta-title .dim { color: rgba(245,244,240,0.12); }
  .cta-actions { display: flex; gap: 20px; justify-content: center; align-items: center; }
  .cta-note { font-size: 12px; color: var(--gray); margin-top: 24px; letter-spacing: 0.08em; }

  /* FOOTER */
  footer {
    padding: 48px 60px;
    border-top: 1px solid var(--border);
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .footer-logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 18px;
    letter-spacing: 0.2em;
    color: var(--white);
  }
  .footer-logo span {
    font-family: 'DM Sans', sans-serif;
    font-size: 8px;
    letter-spacing: 0.3em;
    opacity: 0.3;
    display: block;
  }
  .footer-links { display: flex; gap: 32px; }
  .footer-links a {
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--gray);
    text-decoration: none;
    transition: color 0.2s;
  }
  .footer-links a:hover { color: var(--white); }
  .footer-copy { font-size: 11px; color: rgba(245,244,240,0.2); letter-spacing: 0.06em; }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .reveal {
    opacity: 0;
    transform: translateY(40px);
    transition: opacity 0.9s cubic-bezier(0.16,1,0.3,1), transform 0.9s cubic-bezier(0.16,1,0.3,1);
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }
  .reveal-delay-1 { transition-delay: 0.1s; }
  .reveal-delay-2 { transition-delay: 0.2s; }
  .reveal-delay-3 { transition-delay: 0.3s; }
  .reveal-delay-4 { transition-delay: 0.4s; }

  @media (max-width: 900px) {
    nav { padding: 20px 24px; }
    .nav-links { display: none; }
    section { padding: 80px 24px; }
    .hero { padding: 0 24px 60px; }
    .hero-scroll { display: none; }
    .hero-sub-row { flex-direction: column; gap: 32px; align-items: flex-start; }
    .about { grid-template-columns: 1fr; gap: 48px; }
    .services-grid { grid-template-columns: 1fr 1fr; }
    .process-grid { grid-template-columns: 1fr 1fr; gap: 48px; }
    .process-grid::before { display: none; }
    .why-inner { grid-template-columns: 1fr; gap: 48px; }
    .cta-section { padding: 100px 24px; }
    footer { flex-direction: column; gap: 24px; text-align: center; }
    .footer-links { flex-wrap: wrap; justify-content: center; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav id="nav">
  <a href="#" class="nav-logo">ZOA<span>Agency</span></a>
  <ul class="nav-links">
    <li><a href="#services">Hizmetler</a></li>
    <li><a href="#process">Süreç</a></li>
    <li><a href="#why">Neden ZOA</a></li>
    <li><a href="#contact">İletişim</a></li>
  </ul>
  <a href="#contact" class="nav-cta">Teklif Al</a>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="hero-tag">Modern Dijital Büyüme Ajansı — İzmir, TR</div>
  <div class="hero-headline">
    Dijitalde<br>
    <span class="dim">Güçlü</span><br>
    Görün.
  </div>
  <div class="hero-sub-row">
    <p class="hero-desc">
      Sadece site yapmıyoruz.<br>
      <strong>Markanın dijitaldeki tüm sistemini kuruyoruz.</strong>
    </p>
    <div class="hero-actions">
      <a href="#contact" class="btn-primary">Büyümeye Başla</a>
      <a href="#services" class="btn-ghost">Hizmetleri Gör</a>
    </div>
  </div>
  <div class="hero-scroll">
    <div class="scroll-line"></div>
    <span>Scroll</span>
  </div>
</section>

<!-- TICKER -->
<div class="ticker">
  <div class="ticker-inner" id="tickerInner"></div>
</div>

<!-- ABOUT -->
<section>
  <div class="about">
    <div class="about-left reveal">
      <div class="section-tag">Hakkımızda</div>
      <h2 class="section-title">Biz Kimiz?<br><span class="dim">Ne Yapıyoruz?</span></h2>
      <p class="about-text">ZOA Agency, markaların dijital dünyada <strong>profesyonel, güvenilir ve satış odaklı</strong> bir kimlik kazanması için kurulmuş modern bir dijital büyüme ajansıdır.</p>
      <p class="about-text">Farklı kişilerle uğraşmak yerine, <strong>web sitesi, yazılım, e-ticaret, sosyal medya, reklam ve SEO</strong> süreçlerini tek çatı altında yönetiyoruz.</p>
    </div>
    <div class="about-right reveal reveal-delay-2">
      <div class="about-card">
        <div class="about-stat">
          <div class="stat-num">8+</div>
          <div class="stat-label">Hizmet Alanı</div>
        </div>
        <div class="about-stat">
          <div class="stat-num">Tek</div>
          <div class="stat-label">Çatı Altında Tam Dijital Çözüm</div>
        </div>
        <div class="about-stat">
          <div class="stat-num">∞</div>
          <div class="stat-label">Ölçülebilir Büyüme</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- SERVICES -->
<section id="services">
  <div class="services-header reveal">
    <div>
      <div class="section-tag">Hizmetlerimiz</div>
      <h2 class="section-title">Tek Çatı Altında<br><span class="dim">Her Şey</span></h2>
    </div>
    <a href="#contact" class="btn-ghost">Tümünü Gör →</a>
  </div>
  <div class="services-grid">
    <div class="service-card reveal">
      <div class="service-num">01</div>
      <div class="service-name">Kurumsal Web Tasarımı</div>
      <div class="service-desc">Markaya özel, hızlı ve mobil uyumlu web siteleri. İlk izlenim her şeydir.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-1">
      <div class="service-num">02</div>
      <div class="service-name">Yazılım Geliştirme</div>
      <div class="service-desc">CRM, randevu sistemi, teklif paneli, otomasyon. İşletmene özel çözümler.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-2">
      <div class="service-num">03</div>
      <div class="service-name">E-Ticaret Kurulumu</div>
      <div class="service-desc">Online satış altyapısı, ödeme sistemi ve pazaryeri entegrasyonları.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-3">
      <div class="service-num">04</div>
      <div class="service-name">Mobil Uygulama</div>
      <div class="service-desc">Markanıza özel iOS ve Android uygulama geliştirme projeleri.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal">
      <div class="service-num">05</div>
      <div class="service-name">Sosyal Medya Yönetimi</div>
      <div class="service-desc">İçerik planı, post tasarımı, reels fikirleri, marka dili ve hesap yönetimi.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-1">
      <div class="service-num">06</div>
      <div class="service-name">Dijital Pazarlama</div>
      <div class="service-desc">Google Ads, Meta Ads, reklam stratejisi. Satış ve lead odaklı büyüme.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-2">
      <div class="service-num">07</div>
      <div class="service-name">SEO Yönetimi</div>
      <div class="service-desc">Teknik SEO, içerik stratejisi ve anahtar kelime çalışmalarıyla organik büyüme.</div>
      <div class="service-arrow">↗</div>
    </div>
    <div class="service-card reveal reveal-delay-3">
      <div class="service-num">08</div>
      <div class="service-name">Entegrasyonlar</div>
      <div class="service-desc">Pazaryeri, muhasebe, XML, kargo, ödeme sistemi ve e-arşiv bağlantıları.</div>
      <div class="service-arrow">↗</div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- PROCESS -->
<section id="process">
  <div class="reveal">
    <div class="section-tag">Çalışma Sürecimiz</div>
    <h2 class="section-title">Nasıl <span class="dim">Çalışıyoruz?</span></h2>
  </div>
  <div class="process-grid">
    <div class="process-step reveal">
      <div class="process-dot"></div>
      <div class="process-num">01</div>
      <div class="process-title">Keşif & Analiz</div>
      <div class="process-desc">Marka, hedef kitle ve rekabet analizi yapıyoruz. Dijital ihtiyaçları belirliyoruz.</div>
    </div>
    <div class="process-step reveal reveal-delay-1">
      <div class="process-dot"></div>
      <div class="process-num">02</div>
      <div class="process-title">Strateji</div>
      <div class="process-desc">Markaya özel dijital büyüme planı oluşturuyoruz. Hedefler ve yol haritası belirleniyor.</div>
    </div>
    <div class="process-step reveal reveal-delay-2">
      <div class="process-dot"></div>
      <div class="process-num">03</div>
      <div class="process-title">Uygulama</div>
      <div class="process-desc">Tasarım, geliştirme ve yayına alma süreçlerini hızlı ve kaliteli şekilde tamamlıyoruz.</div>
    </div>
    <div class="process-step reveal reveal-delay-3">
      <div class="process-dot"></div>
      <div class="process-num">04</div>
      <div class="process-title">Büyüme</div>
      <div class="process-desc">Sürekli optimizasyon, raporlama ve iyileştirmelerle ölçülebilir büyüme sağlıyoruz.</div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- WHY ZOA -->
<section class="why" id="why">
  <div class="why-inner">
    <div class="reveal">
      <div class="section-tag">Neden ZOA?</div>
      <div class="why-quote">
        Farklı kişilerle<br>
        uğraşmadan,<br>
        <span class="accent">dijital sürecini<br>
        tek ekip yönetir.</span>
      </div>
    </div>
    <div class="why-list reveal reveal-delay-2">
      <div class="why-item">
        <div class="why-check">✦</div>
        <div class="why-text">
          <strong>Tek Çatı Avantajı</strong>
          Web sitesi, sosyal medya, reklam, SEO ve yazılımı aynı anda yönetiyoruz.
        </div>
      </div>
      <div class="why-item">
        <div class="why-check">✦</div>
        <div class="why-text">
          <strong>Sonuç Odaklı</strong>
          Her proje satış, büyüme veya görünürlük hedefiyle başlar. Estetik değil, performans önce.
        </div>
      </div>
      <div class="why-item">
        <div class="why-check">✦</div>
        <div class="why-text">
          <strong>Modern Teknoloji</strong>
          Güncel altyapılar, hızlı web siteleri ve ölçeklenebilir sistemler kuruyoruz.
        </div>
      </div>
      <div class="why-item">
        <div class="why-check">✦</div>
        <div class="why-text">
          <strong>Şeffaf İletişim</strong>
          Raporlar, toplantılar ve net süreçlerle her adımda yanınızdayız.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section" id="contact">
  <div class="cta-bg"></div>
  <div class="cta-label reveal">Hadi Başlayalım</div>
  <div class="cta-title reveal">
    Büyümeye<br>
    <span class="dim">Hazır</span><br>
    Mısın?
  </div>
  <div class="cta-actions reveal">
    <a href="mailto:info@zoaagency.com" class="btn-primary">İletişime Geç</a>
    <a href="https://instagram.com/zoaxagency" class="btn-ghost" target="_blank">@zoaxagency →</a>
  </div>
  <div class="cta-note reveal">DM → "GROWTH" yaz, seni arayalım.</div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">ZOA<span>Agency — 2025</span></div>
  <div class="footer-links">
    <a href="#services">Hizmetler</a>
    <a href="#process">Süreç</a>
    <a href="#why">Neden ZOA</a>
    <a href="https://instagram.com/zoaxagency" target="_blank">Instagram</a>
  </div>
  <div class="footer-copy">© 2025 ZOA Agency. Tüm hakları saklıdır.</div>
</footer>

<script>
// CURSOR
const cursor = document.getElementById('cursor');
const ring = document.getElementById('cursorRing');
let mx = 0, my = 0, rx = 0, ry = 0;
document.addEventListener('mousemove', e => {
  mx = e.clientX; my = e.clientY;
  cursor.style.left = mx + 'px';
  cursor.style.top = my + 'px';
});
function animRing() {
  rx += (mx - rx) * 0.12;
  ry += (my - ry) * 0.12;
  ring.style.left = rx + 'px';
  ring.style.top = ry + 'px';
  requestAnimationFrame(animRing);
}
animRing();
document.querySelectorAll('a, button').forEach(el => {
  el.addEventListener('mouseenter', () => {
    ring.style.width = '60px'; ring.style.height = '60px';
    ring.style.opacity = '0.5';
  });
  el.addEventListener('mouseleave', () => {
    ring.style.width = '36px'; ring.style.height = '36px';
    ring.style.opacity = '1';
  });
});

// NAV SCROLL
window.addEventListener('scroll', () => {
  document.getElementById('nav').classList.toggle('scrolled', window.scrollY > 40);
});

// TICKER
const items = ['Web Tasarımı', 'Yazılım', 'E-Ticaret', 'Mobil Uygulama', 'SEO', 'Dijital Pazarlama', 'Sosyal Medya', 'Entegrasyon'];
const inner = document.getElementById('tickerInner');
let html = '';
for (let i = 0; i < 4; i++) {
  items.forEach(item => {
    html += `<span class="ticker-item"><span>✦</span>${item}</span>`;
  });
}
inner.innerHTML = html;

// REVEAL
const observer = new IntersectionObserver(entries => {
  entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold: 0.1 });
document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
</script>
</body>
</html>
