[index.html](https://github.com/user-attachments/files/27801053/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>🍼 Silla Plegable de Bebé ✅ | Envío Gratis Colombia</title>
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800;900&family=Paytone+One&display=swap" rel="stylesheet"/>
<style>
  :root {
    --primary: #FF6B35;
    --primary-dark: #e85520;
    --accent: #FFD700;
    --green: #22c55e;
    --green-dark: #16a34a;
    --bg: #fff8f4;
    --text: #1a1a2e;
    --muted: #6b7280;
    --card: #ffffff;
    --border: #ffe0d0;
  }
  * { margin:0; padding:0; box-sizing:border-box; }
  body { font-family:'Nunito',sans-serif; background:var(--bg); color:var(--text); overflow-x:hidden; }

  /* BANNER */
  .top-bar {
    background: var(--primary);
    color: #fff;
    text-align:center;
    padding: 10px 16px;
    font-weight:800;
    font-size:14px;
    letter-spacing:.5px;
    animation: pulse-bg 2s infinite alternate;
  }
  @keyframes pulse-bg { from{background:var(--primary)} to{background:#e85520} }

  /* HEADER */
  header {
    background: linear-gradient(135deg,#fff8f4 0%,#ffe8d6 100%);
    text-align:center;
    padding:28px 16px 16px;
    border-bottom:3px solid var(--border);
  }
  .badge-hot {
    display:inline-block;
    background:var(--primary);
    color:#fff;
    font-size:11px;
    font-weight:800;
    padding:4px 12px;
    border-radius:50px;
    letter-spacing:1px;
    margin-bottom:10px;
    text-transform:uppercase;
    animation: bounce 1.5s infinite;
  }
  @keyframes bounce {
    0%,100%{transform:translateY(0)} 50%{transform:translateY(-4px)}
  }
  h1 {
    font-family:'Paytone One',sans-serif;
    font-size:clamp(22px,6vw,38px);
    color:var(--text);
    line-height:1.15;
    margin-bottom:8px;
  }
  h1 span { color:var(--primary); }
  .subtitle {
    font-size:15px;
    color:var(--muted);
    max-width:480px;
    margin:0 auto 16px;
  }
  .trust-row {
    display:flex;
    justify-content:center;
    gap:16px;
    flex-wrap:wrap;
    margin-top:12px;
  }
  .trust-pill {
    background:#fff;
    border:2px solid var(--border);
    border-radius:50px;
    padding:6px 14px;
    font-size:13px;
    font-weight:700;
    color:var(--text);
    display:flex;
    align-items:center;
    gap:5px;
  }
  .trust-pill .icon { font-size:16px; }

  /* PRODUCT IMAGES GALLERY */
  .gallery {
    max-width:520px;
    margin:0 auto;
    padding:20px 16px 0;
  }
  .main-img {
    width:100%;
    aspect-ratio:4/3;
    background:#f5ede8;
    border-radius:20px;
    margin-bottom:6px;
    box-shadow:0 8px 32px rgba(255,107,53,.18);
    position:relative;
    overflow:hidden;
  }
  .main-img img, .main-img video {
    width:100%; height:100%;
    object-fit:cover;
    border-radius:18px;
    display:block;
  }
  .color-label {
    text-align:center;
    font-size:12px;
    font-weight:800;
    color:var(--primary);
    margin:0 0 6px;
    letter-spacing:.5px;
    text-transform:uppercase;
  }
  .thumbnails {
    display:flex;
    gap:8px;
  }
  .thumb {
    flex:1;
    aspect-ratio:1;
    background:#f5ede8;
    border-radius:12px;
    overflow:hidden;
    cursor:pointer;
    border:3px solid transparent;
    transition:border-color .2s, transform .15s;
    position:relative;
  }
  .thumb img { width:100%; height:100%; object-fit:cover; display:block; }
  .thumb .play-icon {
    position:absolute; inset:0;
    display:flex; align-items:center; justify-content:center;
    background:rgba(0,0,0,.22);
    font-size:20px;
    color:#fff;
  }
  .thumb:hover,.thumb.active { border-color:var(--primary); transform:scale(1.05); }

  /* PRICE SECTION */
  .price-section {
    max-width:520px;
    margin:20px auto 0;
    padding:0 16px;
  }
  .countdown-box {
    background:var(--text);
    color:#fff;
    border-radius:16px;
    padding:14px 20px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    margin-bottom:16px;
  }
  .countdown-label { font-size:13px; font-weight:700; opacity:.8; }
  .countdown-timer {
    display:flex;
    gap:8px;
    align-items:center;
  }
  .time-block {
    background:var(--primary);
    border-radius:8px;
    padding:6px 10px;
    text-align:center;
    min-width:44px;
  }
  .time-block .num {
    font-family:'Paytone One',sans-serif;
    font-size:22px;
    line-height:1;
    display:block;
  }
  .time-block .lbl {
    font-size:9px;
    opacity:.85;
    text-transform:uppercase;
  }
  .time-sep { font-size:22px; font-weight:900; color:var(--primary); }

  /* PACKAGE SELECTOR */
  .pkg-grid {
    display:flex;
    flex-direction:column;
    gap:12px;
    margin-bottom:20px;
  }
  .pkg-card {
    border:3px solid var(--border);
    border-radius:16px;
    padding:16px;
    cursor:pointer;
    transition:all .2s;
    background:#fff;
    position:relative;
  }
  .pkg-card:hover { border-color:var(--primary); transform:translateY(-2px); }
  .pkg-card.selected { border-color:var(--primary); background:#fff5f0; box-shadow:0 4px 16px rgba(255,107,53,.2); }
  .pkg-card .popular-tag {
    position:absolute;
    top:-12px; right:16px;
    background:var(--primary);
    color:#fff;
    font-size:11px;
    font-weight:800;
    padding:3px 12px;
    border-radius:50px;
    text-transform:uppercase;
  }
  .pkg-header {
    display:flex;
    justify-content:space-between;
    align-items:center;
  }
  .pkg-name { font-size:16px; font-weight:800; }
  .pkg-price-main {
    font-family:'Paytone One',sans-serif;
    font-size:24px;
    color:var(--primary);
  }
  .pkg-price-old {
    font-size:13px;
    color:var(--muted);
    text-decoration:line-through;
  }
  .pkg-save {
    font-size:12px;
    color:var(--green);
    font-weight:700;
  }
  .pkg-radio {
    width:20px; height:20px;
    border-radius:50%;
    border:2px solid #ccc;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    flex-shrink:0;
    transition:all .2s;
  }
  .pkg-card.selected .pkg-radio {
    border-color:var(--primary);
    background:var(--primary);
  }
  .pkg-card.selected .pkg-radio::after {
    content:'';
    width:8px; height:8px;
    background:#fff;
    border-radius:50%;
  }

  /* CTA BUTTON */
  .cta-btn {
    display:block;
    width:100%;
    background:linear-gradient(135deg, var(--green), var(--green-dark));
    color:#fff;
    font-family:'Paytone One',sans-serif;
    font-size:18px;
    padding:18px 24px;
    border-radius:16px;
    border:none;
    cursor:pointer;
    text-align:center;
    text-decoration:none;
    box-shadow:0 6px 24px rgba(34,197,94,.35);
    transition:all .2s;
    position:relative;
    overflow:hidden;
    margin-bottom:12px;
  }
  .cta-btn::after {
    content:'';
    position:absolute;
    top:0; left:-100%;
    width:60%;
    height:100%;
    background:linear-gradient(90deg, transparent, rgba(255,255,255,.25), transparent);
    animation: shimmer 2s infinite;
  }
  @keyframes shimmer { to{left:150%} }
  .cta-btn:hover { transform:translateY(-3px); box-shadow:0 10px 32px rgba(34,197,94,.45); }
  .stock-note {
    text-align:center;
    font-size:13px;
    color:var(--primary);
    font-weight:700;
    margin-bottom:20px;
  }

  /* FEATURES */
  .section { max-width:520px; margin:0 auto; padding:0 16px 24px; }
  .section-title {
    font-family:'Paytone One',sans-serif;
    font-size:20px;
    color:var(--text);
    margin-bottom:14px;
    text-align:center;
  }
  .section-title span { color:var(--primary); }
  .feature-list { display:flex; flex-direction:column; gap:12px; }
  .feature-item {
    background:#fff;
    border-radius:14px;
    padding:16px;
    display:flex;
    gap:12px;
    align-items:flex-start;
    border:2px solid var(--border);
    box-shadow:0 2px 8px rgba(0,0,0,.04);
  }
  .feat-icon { font-size:30px; flex-shrink:0; }
  .feat-text h4 { font-size:15px; font-weight:800; margin-bottom:3px; }
  .feat-text p { font-size:13px; color:var(--muted); line-height:1.5; }

  /* TESTIMONIALS */
  .reviews { display:flex; flex-direction:column; gap:12px; }
  .review-card {
    background:#fff;
    border-radius:14px;
    padding:16px;
    border:2px solid var(--border);
  }
  .review-top { display:flex; justify-content:space-between; align-items:center; margin-bottom:8px; }
  .reviewer { font-weight:800; font-size:14px; }
  .stars { color:#FFD700; font-size:16px; }
  .review-text { font-size:13px; color:var(--muted); line-height:1.5; }
  .verified { font-size:11px; color:var(--green); font-weight:700; margin-top:6px; }

  /* DIVIDER */
  .divider {
    max-width:520px;
    margin:8px auto 24px;
    height:3px;
    background:linear-gradient(90deg, transparent, var(--border), transparent);
    border-radius:10px;
  }

  /* FORM */
  .form-section {
    max-width:520px;
    margin:0 auto;
    padding:0 16px 32px;
  }
  .form-box {
    background:#fff;
    border-radius:20px;
    padding:24px;
    border:3px solid var(--primary);
    box-shadow:0 8px 32px rgba(255,107,53,.1);
  }
  .form-box h2 {
    font-family:'Paytone One',sans-serif;
    font-size:20px;
    text-align:center;
    margin-bottom:6px;
  }
  .form-box .sub {
    text-align:center;
    font-size:13px;
    color:var(--muted);
    margin-bottom:20px;
  }
  .form-group { margin-bottom:14px; }
  .form-group label {
    display:block;
    font-size:13px;
    font-weight:700;
    margin-bottom:5px;
    color:var(--text);
  }
  .form-group input,
  .form-group select {
    width:100%;
    padding:13px 14px;
    border:2px solid #e5e7eb;
    border-radius:12px;
    font-size:15px;
    font-family:'Nunito',sans-serif;
    color:var(--text);
    outline:none;
    transition:border-color .2s;
    background:#fff;
  }
  .form-group input:focus,
  .form-group select:focus { border-color:var(--primary); }
  .form-row { display:grid; grid-template-columns:1fr 1fr; gap:12px; }
  .order-summary {
    background:#fff5f0;
    border-radius:12px;
    padding:14px;
    margin-bottom:16px;
    border:2px solid var(--border);
  }
  .summary-row {
    display:flex;
    justify-content:space-between;
    font-size:14px;
    margin-bottom:6px;
  }
  .summary-row.total {
    font-weight:800;
    font-size:17px;
    color:var(--primary);
    border-top:2px solid var(--border);
    padding-top:8px;
    margin-top:6px;
  }
  .summary-row .green { color:var(--green); font-weight:700; }
  .commit-notice {
    background:#fef9c3;
    border:2px solid #fde047;
    border-radius:12px;
    padding:12px;
    font-size:12px;
    color:#854d0e;
    margin-bottom:16px;
    line-height:1.5;
  }

  /* SUCCESS */
  #success-msg {
    display:none;
    background:#f0fdf4;
    border:3px solid var(--green);
    border-radius:20px;
    padding:32px 24px;
    text-align:center;
  }
  #success-msg .big-icon { font-size:64px; margin-bottom:12px; }
  #success-msg h3 { font-family:'Paytone One',sans-serif; font-size:22px; color:var(--green-dark); margin-bottom:8px; }
  #success-msg p { font-size:14px; color:var(--muted); }

  /* LOADING */
  #loading-overlay {
    display:none;
    position:fixed;
    inset:0;
    background:rgba(0,0,0,.5);
    z-index:999;
    align-items:center;
    justify-content:center;
  }
  #loading-overlay.show { display:flex; }
  .spinner {
    background:#fff;
    border-radius:20px;
    padding:32px 40px;
    text-align:center;
  }
  .spin {
    width:48px; height:48px;
    border:5px solid var(--border);
    border-top-color:var(--primary);
    border-radius:50%;
    animation:spin .8s linear infinite;
    margin:0 auto 16px;
  }
  @keyframes spin { to{transform:rotate(360deg)} }
  .spinner p { font-weight:700; font-size:15px; }

  /* FOOTER */
  footer {
    background:var(--text);
    color:rgba(255,255,255,.7);
    text-align:center;
    padding:24px 16px;
    font-size:12px;
  }
  footer a { color:rgba(255,255,255,.5); text-decoration:none; }
  footer .footer-trust {
    display:flex;
    justify-content:center;
    gap:20px;
    margin-bottom:12px;
    flex-wrap:wrap;
  }
  footer .ft { display:flex; align-items:center; gap:4px; font-size:13px; color:rgba(255,255,255,.8); }

  /* WHATSAPP BTN */
  .wa-float {
    position:fixed;
    bottom:24px;
    right:20px;
    background:#25d366;
    color:#fff;
    width:58px; height:58px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:26px;
    box-shadow:0 4px 16px rgba(37,211,102,.5);
    z-index:100;
    text-decoration:none;
    animation: wa-pulse 2s infinite;
  }
  @keyframes wa-pulse {
    0%,100%{box-shadow:0 4px 16px rgba(37,211,102,.5)}
    50%{box-shadow:0 4px 28px rgba(37,211,102,.8)}
  }
</style>
</head>
<body>

<!-- TOP BAR -->
<div class="top-bar">🔥 ENVÍO GRATIS + PAGO CONTRA ENTREGA A TODO COLOMBIA 🔥</div>

<!-- HEADER -->
<header>
  <div class="badge-hot">🍼 Oferta Limitada</div>
  <h1>Silla Plegable<br><span>de Bebé Premium</span></h1>
  <p class="subtitle">De 6 meses a 3 años · Arnés 5 puntos · Bandeja extraíble · Diseño compacto</p>
  <div class="trust-row">
    <div class="trust-pill"><span class="icon">✅</span>Pago contra entrega</div>
    <div class="trust-pill"><span class="icon">🚚</span>Envío gratis</div>
    <div class="trust-pill"><span class="icon">⭐</span>+500 mamás felices</div>
  </div>
</header>

<!-- GALLERY -->
<div class="gallery">
  <div class="main-img" id="mainImg">
    <img id="mainMedia" src="https://res.cloudinary.com/dks7awyhv/image/upload/v1778839335/Silla_gris_pvs89y.webp" alt="Silla Plegable Bebé - Gris"/>
  </div>
  <div class="color-label" id="colorLabel">🩶 Color: Gris</div>
  <div class="thumbnails">
    <div class="thumb active" onclick="setMedia(this,'img','https://res.cloudinary.com/dks7awyhv/image/upload/v1778839335/Silla_gris_pvs89y.webp','🩶 Color: Gris')">
      <img src="https://res.cloudinary.com/dks7awyhv/image/upload/w_120,h_120,c_fill/v1778839335/Silla_gris_pvs89y.webp" alt="Gris"/>
    </div>
    <div class="thumb" onclick="setMedia(this,'img','https://res.cloudinary.com/dks7awyhv/image/upload/v1778839323/Silla_Rosada_soqgs8.png','🩷 Color: Rosado')">
      <img src="https://res.cloudinary.com/dks7awyhv/image/upload/w_120,h_120,c_fill/v1778839323/Silla_Rosada_soqgs8.png" alt="Rosado"/>
    </div>
    <div class="thumb" onclick="setMedia(this,'img','https://res.cloudinary.com/dks7awyhv/image/upload/v1778839312/Silla_Beigs_lgms8a.png','🤎 Color: Beige')">
      <img src="https://res.cloudinary.com/dks7awyhv/image/upload/w_120,h_120,c_fill/v1778839312/Silla_Beigs_lgms8a.png" alt="Beige"/>
    </div>
    <div class="thumb" onclick="setMedia(this,'img','https://res.cloudinary.com/dks7awyhv/image/upload/v1778839261/Silla_Verde_bgw9gj.png','💚 Color: Verde')">
      <img src="https://res.cloudinary.com/dks7awyhv/image/upload/w_120,h_120,c_fill/v1778839261/Silla_Verde_bgw9gj.png" alt="Verde"/>
    </div>
    <div class="thumb" onclick="setMedia(this,'video','https://res.cloudinary.com/dks7awyhv/video/upload/v1778839495/Silla_para_Bebe_uxsnvz.mp4','▶️ Ver video')">
      <img src="https://res.cloudinary.com/dks7awyhv/video/upload/w_120,h_120,c_fill,so_2/v1778839495/Silla_para_Bebe_uxsnvz.jpg" alt="Video"/>
      <div class="play-icon">▶️</div>
    </div>
  </div>
</div>

<!-- COUNTDOWN -->
<div class="price-section">
  <div class="countdown-box">
    <div>
      <div class="countdown-label">⏰ OFERTA TERMINA EN</div>
    </div>
    <div class="countdown-timer">
      <div class="time-block"><span class="num" id="ch">00</span><span class="lbl">Hrs</span></div>
      <span class="time-sep">:</span>
      <div class="time-block"><span class="num" id="cm">14</span><span class="lbl">Min</span></div>
      <span class="time-sep">:</span>
      <div class="time-block"><span class="num" id="cs">59</span><span class="lbl">Seg</span></div>
    </div>
  </div>

  <!-- PACKAGES -->
  <div class="pkg-grid" id="pkgGrid">
    <div class="pkg-card selected" data-qty="1" data-price="99900" onclick="selectPkg(this)">
      <div class="pkg-header">
        <div>
          <div class="pkg-name">1 Unidad</div>
          <div class="pkg-price-old">$129.900</div>
          <div class="pkg-save">Ahorras $30.000</div>
        </div>
        <div>
          <div class="pkg-price-main">$99.900</div>
          <div class="pkg-radio"></div>
        </div>
      </div>
    </div>
    <div class="pkg-card" data-qty="2" data-price="169900" onclick="selectPkg(this)">
      <div class="popular-tag">🔥 Más Vendido</div>
      <div class="pkg-header">
        <div>
          <div class="pkg-name">2 Unidades</div>
          <div class="pkg-price-old">$259.800</div>
          <div class="pkg-save">Ahorras $89.900</div>
        </div>
        <div>
          <div class="pkg-price-main">$169.900</div>
          <div class="pkg-radio"></div>
        </div>
      </div>
    </div>
    <div class="pkg-card" data-qty="3" data-price="229900" onclick="selectPkg(this)">
      <div class="pkg-header">
        <div>
          <div class="pkg-name">3 Unidades</div>
          <div class="pkg-price-old">$389.700</div>
          <div class="pkg-save">Ahorras $159.800</div>
        </div>
        <div>
          <div class="pkg-price-main">$229.900</div>
          <div class="pkg-radio"></div>
        </div>
      </div>
    </div>
  </div>

  <a href="#form-order" class="cta-btn">🔥 ¡QUIERO PEDIR AHORA! – PAGAS CUANDO LO RECIBES 🤝</a>
  <div class="stock-note">⚠️ Solo 14 unidades disponibles hoy</div>
</div>

<!-- FEATURES -->
<div class="divider"></div>
<div class="section">
  <div class="section-title">¿Por qué elegir <span>esta silla</span>?</div>
  <div class="feature-list">
    <div class="feature-item">
      <div class="feat-icon">🛡️</div>
      <div class="feat-text">
        <h4>Arnés de seguridad 5 puntos</h4>
        <p>Mantiene a tu bebé protegido y bien sujeto en todo momento, sin restricciones de movimiento.</p>
      </div>
    </div>
    <div class="feature-item">
      <div class="feat-icon">📐</div>
      <div class="feat-text">
        <h4>Diseño ergonómico y compacto</h4>
        <p>Postura correcta para tu bebé y fácil de plegar. Cabe en cualquier maletero o armario.</p>
      </div>
    </div>
    <div class="feature-item">
      <div class="feat-icon">🧩</div>
      <div class="feat-text">
        <h4>Bandeja extraíble de juego</h4>
        <p>Tu bebé puede jugar, comer o aprender mientras está seguro y cómodo.</p>
      </div>
    </div>
    <div class="feature-item">
      <div class="feat-icon">✈️</div>
      <div class="feat-text">
        <h4>Ideal para viajes y salidas</h4>
        <p>Llévala al parque, casa de familiares o de vacaciones. Ligera y fácil de transportar.</p>
      </div>
    </div>
    <div class="feature-item">
      <div class="feat-icon">📅</div>
      <div class="feat-text">
        <h4>De 6 meses a 3 años</h4>
        <p>Se adapta al crecimiento de tu bebé. Una sola compra para toda la etapa.</p>
      </div>
    </div>
  </div>
</div>

<!-- REVIEWS -->
<div class="divider"></div>
<div class="section">
  <div class="section-title">Lo que dicen <span>las mamás</span> 💬</div>
  <div class="reviews">
    <div class="review-card">
      <div class="review-top">
        <span class="reviewer">Valentina G. — Bogotá</span>
        <span class="stars">⭐⭐⭐⭐⭐</span>
      </div>
      <div class="review-text">¡Llegó súper rápido y la calidad es excelente! Mi niña de 8 meses la ama. El arnés da mucha tranquilidad.</div>
      <div class="verified">✅ Compra verificada</div>
    </div>
    <div class="review-card">
      <div class="review-top">
        <span class="reviewer">Marcela R. — Medellín</span>
        <span class="stars">⭐⭐⭐⭐⭐</span>
      </div>
      <div class="review-text">Compré 2 unidades, una para la casa y otra para la abuela. Plega facilísimo y es muy resistente. ¡Totalmente recomendada!</div>
      <div class="verified">✅ Compra verificada</div>
    </div>
    <div class="review-card">
      <div class="review-top">
        <span class="reviewer">Camila T. — Cali</span>
        <span class="stars">⭐⭐⭐⭐⭐</span>
      </div>
      <div class="review-text">Pago contra entrega me dio confianza para comprar. Llegó en 3 días y mi bebé está feliz. ¡Gracias!</div>
      <div class="verified">✅ Compra verificada</div>
    </div>
  </div>
</div>

<!-- ORDER FORM -->
<div class="divider"></div>
<div class="form-section" id="form-order">
  <div class="form-box" id="orderForm">
    <h2>👇 Completa tu Pedido</h2>
    <p class="sub">¡Recuerda que <strong>pagas solo cuando lo recibes</strong>! 🤝</p>

    <div class="order-summary" id="orderSummary">
      <div class="summary-row"><span>Producto:</span><span id="s-prod">Silla Plegable × 1</span></div>
      <div class="summary-row"><span>Envío:</span><span class="green">GRATIS 🚚</span></div>
      <div class="summary-row total"><span>TOTAL A PAGAR:</span><span id="s-total">$99.900</span></div>
    </div>

    <div class="form-row">
      <div class="form-group">
        <label>Nombre *</label>
        <input type="text" id="firstName" placeholder="Tu nombre" required/>
      </div>
      <div class="form-group">
        <label>Apellido *</label>
        <input type="text" id="lastName" placeholder="Tu apellido" required/>
      </div>
    </div>
    <div class="form-group">
      <label>WhatsApp / Celular *</label>
      <input type="tel" id="phone" placeholder="Ej: 3001234567" maxlength="10" required/>
    </div>
    <div class="form-group">
      <label>Correo electrónico</label>
      <input type="email" id="email" placeholder="tucorreo@gmail.com"/>
    </div>
    <div class="form-group">
      <label>Departamento *</label>
      <select id="department" onchange="loadCities(this.value)" required>
        <option value="">— Selecciona departamento —</option>
        <option value="Antioquia">Antioquia</option>
        <option value="Atlántico">Atlántico</option>
        <option value="Bogotá D.C.">Bogotá D.C.</option>
        <option value="Bolívar">Bolívar</option>
        <option value="Boyacá">Boyacá</option>
        <option value="Caldas">Caldas</option>
        <option value="Caquetá">Caquetá</option>
        <option value="Cauca">Cauca</option>
        <option value="Cesar">Cesar</option>
        <option value="Córdoba">Córdoba</option>
        <option value="Cundinamarca">Cundinamarca</option>
        <option value="Huila">Huila</option>
        <option value="La Guajira">La Guajira</option>
        <option value="Magdalena">Magdalena</option>
        <option value="Meta">Meta</option>
        <option value="Nariño">Nariño</option>
        <option value="Norte de Santander">Norte de Santander</option>
        <option value="Quindío">Quindío</option>
        <option value="Risaralda">Risaralda</option>
        <option value="Santander">Santander</option>
        <option value="Sucre">Sucre</option>
        <option value="Tolima">Tolima</option>
        <option value="Valle del Cauca">Valle del Cauca</option>
      </select>
    </div>
    <div class="form-group">
      <label>Ciudad *</label>
      <input type="text" id="city" placeholder="Ej: Medellín, Bogotá, Cali..." required/>
    </div>
    <div class="form-group">
      <label>Dirección completa *</label>
      <input type="text" id="address" placeholder="Ej: Calle 14 #43-56, Apto 203, Barrio Las Palmas" required/>
    </div>

    <div class="commit-notice">
      ⚠️ <strong>ATENCIÓN:</strong> Tu pedido es un compromiso de compra. Confirma solo si estás 100% segur@ de recibirlo. El envío gratuito tiene un costo logístico real. ¡Gracias por tu responsabilidad! 🙏
    </div>

    <button class="cta-btn" onclick="submitOrder()" style="background:linear-gradient(135deg,var(--primary),var(--primary-dark));">
      🔥 CONFIRMAR COMPRA — PAGAS AL RECIBIR 🤝
    </button>
  </div>

  <!-- SUCCESS -->
  <div id="success-msg">
    <div class="big-icon">✅</div>
    <h3>¡Pedido Confirmado!</h3>
    <p>Gracias <strong id="successName"></strong>. Tu pedido fue registrado exitosamente.<br><br>
    Un asesor te contactará al <strong id="successPhone"></strong> para confirmar tu dirección.<br><br>
    <em>Recuerda: pagas cuando lo recibas 🤝</em></p>
  </div>
</div>

<!-- LOADING -->
<div id="loading-overlay">
  <div class="spinner">
    <div class="spin"></div>
    <p>Confirmando pedido...</p>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-trust">
    <div class="ft">✅ Pago contra entrega</div>
    <div class="ft">🚚 Envío gratis</div>
    <div class="ft">🛡️ Compra segura</div>
  </div>
  <p>© 2024 Tienda En Línea · Colombia · Bodega disponible en CO - EC - PA - MX - ES</p>
  <br>
  <p>
    <a href="#">Términos y Condiciones</a> &nbsp;·&nbsp;
    <a href="#">Política de Envíos</a> &nbsp;·&nbsp;
    <a href="#">Política de Devoluciones</a>
  </p>
</footer>

<!-- WHATSAPP FLOAT -->
<a class="wa-float" href="https://wa.me/573023645607?text=Hola!%20Quiero%20información%20sobre%20la%20Silla%20Plegable%20de%20Bebé" target="_blank" title="Compra asistida por WhatsApp">💬</a>

<script>
// --- COUNTDOWN TIMER ---
let totalSeconds = 14 * 60 + 59;
function updateTimer() {
  const h = Math.floor(totalSeconds / 3600);
  const m = Math.floor((totalSeconds % 3600) / 60);
  const s = totalSeconds % 60;
  document.getElementById('ch').textContent = String(h).padStart(2,'0');
  document.getElementById('cm').textContent = String(m).padStart(2,'0');
  document.getElementById('cs').textContent = String(s).padStart(2,'0');
  if (totalSeconds > 0) totalSeconds--;
}
setInterval(updateTimer, 1000);
updateTimer();

// --- GALLERY ---
function setMedia(el, type, src, label) {
  document.querySelectorAll('.thumb').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
  document.getElementById('colorLabel').textContent = label;
  const container = document.getElementById('mainImg');
  if (type === 'video') {
    container.innerHTML = `<video src="${src}" autoplay muted loop playsinline style="width:100%;height:100%;object-fit:cover;border-radius:18px;display:block;"></video>`;
  } else {
    container.innerHTML = `<img src="${src}" alt="Silla Plegable" style="width:100%;height:100%;object-fit:cover;border-radius:18px;display:block;"/>`;
  }
}

// --- PACKAGE SELECTION ---
let selectedPrice = 99900;
let selectedQty = 1;

function selectPkg(el) {
  document.querySelectorAll('.pkg-card').forEach(c => c.classList.remove('selected'));
  el.classList.add('selected');
  selectedPrice = parseInt(el.dataset.price);
  selectedQty = parseInt(el.dataset.qty);
  updateSummary();
}

function updateSummary() {
  const formatted = new Intl.NumberFormat('es-CO', {style:'currency', currency:'COP', minimumFractionDigits:0}).format(selectedPrice);
  document.getElementById('s-prod').textContent = `Silla Plegable × ${selectedQty}`;
  document.getElementById('s-total').textContent = formatted;
}

// ============================================================
// CONFIGURACIÓN DROPI — EDITA SOLO ESTAS 2 LÍNEAS
// ============================================================
const DROPI_TOKEN      = "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9hcHAuZHJvcGkuY286ODAiLCJpYXQiOjE3Nzg4NDE0MjYsImV4cCI6NDkzNDUxNTAyNiwibmJmIjoxNzc4ODQxNDI2LCJqdGkiOiJUd2hGcXRTRUp6eGgxTmI2Iiwic3ViIjoyNzYzNzksInBydiI6Ijg3ZTBhZjFlZjlmZDE1ODEyZmRlYzk3MTUzYTE0ZTBiMDQ3NTQ2YWEiLCJhdWQiOiJEcm9wUGFnZSIsInRva2VuX3R5cGUiOiJJTlRFR1JBVElPTlMiLCJ3Yl9pZCI6MSwiaW50ZWdyYXRpb25fdHlwZSI6IkRyb3BQYWdlIiwiaW50ZWdyYXRpb25fdHlwZV9pZCI6MTA0NywiaXBfdXJsIjpbeyJ1cmwiOiJlc3RyYXRlZ2FzaWEuY29tIiwiaXAiOm51bGx9LHsidXJsIjpudWxsLCJpcCI6IjIwOC43Ny4yNDQuMTUifSx7InVybCI6Imh0dHBzOlwvXC9zaG9waWVzdHJhdGVnYXMtcHJvZHVjdGlvbi51cC5yYWlsd2F5LmFwcCIsImlwIjpudWxsfV0sImludGVncmF0aW9uX3VybCI6IiJ9.Xo4bRqTnF3kic58mtOwHiyuHAFGHOP4XOXuXNrFaDGk";   // <-- token Dropi configurado
const DROPI_PRODUCT_ID = 1983119;           // ID del producto en Dropi (ya configurado)
// ============================================================

// Mapa de ciudades principales Colombia → código DANE
const DANE_CITIES = {
  "bogota":1100100,"bogotá":1100100,
  "medellin":5001000,"medellín":5001000,
  "cali":7600100,
  "barranquilla":800100,
  "cartagena":1300100,
  "cucuta":5400100,"cúcuta":5400100,
  "bucaramanga":6800100,
  "pereira":6600100,
  "manizales":1700100,
  "ibague":7300100,"ibagué":7300100,
  "villavicencio":5000100,
  "santa marta":4700100,
  "neiva":4100100,
  "armenio":6300100,
  "pasto":5200100,
  "monteria":2300100,"montería":2300100,
  "sincelejo":7000100,
  "valledupar":2000100,
  "popayan":1900100,"popayán":1900100,
  "tunja":1500100,
  "florencia":1800100,
  "riohacha":4400100,
  "quibdo":2700100,"quibdó":2700100,
  "mocoa":8600100,
  "yopal":8500100,
  "arauca":8100100,
  "leticia":9100100,
  "inirida":9400100,"inírida":9400100,
  "mitu":9700100,"mitú":9700100,
  "puerto carreno":9900100,"puerto carreño":9900100,
  "san jose del guaviare":9500100
};

function getCodDane(cityName) {
  const key = cityName.toLowerCase().normalize("NFD").replace(/[\u0300-\u036f]/g,"");
  for (const [k, v] of Object.entries(DANE_CITIES)) {
    const normK = k.normalize("NFD").replace(/[\u0300-\u036f]/g,"");
    if (normK === key) return String(v);
  }
  return null;
}

// --- FORM SUBMIT (Dropi API real) ---
async function submitOrder() {
  const firstName = document.getElementById('firstName').value.trim();
  const lastName  = document.getElementById('lastName').value.trim();
  const phone     = document.getElementById('phone').value.trim();
  const email     = document.getElementById('email').value.trim();
  const dept      = document.getElementById('department').value;
  const city      = document.getElementById('city').value.trim();
  const address   = document.getElementById('address').value.trim();

  if (!firstName || !lastName || !phone || !dept || !city || !address) {
    alert('⚠️ Por favor completa todos los campos obligatorios.');
    return;
  }
  if (phone.length < 7) {
    alert('⚠️ Ingresa un número de celular válido.');
    return;
  }
  if (DROPI_TOKEN === "TU_TOKEN_AQUI") {
    alert('⚠️ El formulario aún no está configurado. Escríbenos por WhatsApp para hacer tu pedido.');
    return;
  }

  const codDane = getCodDane(city);
  if (!codDane) {
    alert('⚠️ Ciudad no reconocida. Por favor escribe el nombre exacto de tu ciudad principal (Ej: Bogotá, Medellín, Cali...)');
    return;
  }

  const overlay = document.getElementById('loading-overlay');
  overlay.classList.add('show');

  // Payload según documentación oficial Dropi Integrations API
  const dropiPayload = {
    EnvioConCobro: true,
    amount: selectedPrice,
    ciudad_destino: { cod_dane: codDane },
    products: [
      {
        product_id: DROPI_PRODUCT_ID,
        quantity: selectedQty,
        price: selectedPrice
      }
    ],
    name: firstName,
    surname: lastName,
    phone: phone,
    client_email: email || "",
    dir: address,
    state: dept,
    city: city,
    country: "COLOMBIA",
    notes: `Pedido desde LP - ${selectedQty} unidad(es)`
  };

  try {
    const res = await fetch('https://app.dropi.co:80/api/integrations/orders/store', {
      method: 'POST',
      headers: {
        'Content-Type': 'application/json',
        'dropi-integracion-key': DROPI_TOKEN
      },
      body: JSON.stringify(dropiPayload)
    });

    const data = await res.json();
    overlay.classList.remove('show');

    if (data.isSuccess || res.ok) {
      document.getElementById('orderForm').style.display = 'none';
      const succ = document.getElementById('success-msg');
      succ.style.display = 'block';
      document.getElementById('successName').textContent = firstName + ' ' + lastName;
      document.getElementById('successPhone').textContent = phone;
      succ.scrollIntoView({behavior:'smooth', block:'center'});
    } else {
      const msg = data.message || 'Error desconocido';
      alert('❌ No se pudo crear el pedido: ' + msg + '\n\nPor favor escríbenos por WhatsApp.');
    }

  } catch(err) {
    overlay.classList.remove('show');
    alert('❌ Error de conexión. Por favor escríbenos por WhatsApp para hacer tu pedido manualmente.');
  }
}
</script>
</body>
</html>
