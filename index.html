<!DOCTYPE html>
<html lang="pt">
<select onchange="changeLanguage(this value)">
<option value="pt">Português</option>
<option value="en">English</option>
<option value="es">Spañol</option>
</select>

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SonMovingui – Mobiliário Made in Portugal</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --cream: #F5F0E8;
    --warm-white: #FAF8F4;
    --gold: #B8913A;
    --gold-light: #D4A84B;
    --gold-dark: #8A6A22;
    --brown: #3D2B1F;
    --brown-mid: #6B4C35;
    --brown-light: #A07850;
    --charcoal: #2C2420;
    --text-muted: #8B7355;
    --border: rgba(184,145,58,0.25);
    --shadow: rgba(61,43,31,0.12);
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--warm-white);
    color: var(--charcoal);
    overflow-x: hidden;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 1000;
    background: rgba(250,248,244,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    padding: 0 5%;
    display: flex; align-items: center; justify-content: space-between;
    height: 72px;
    transition: all 0.3s ease;
  }
  nav.scrolled {
    background: rgba(250,248,244,0.98);
    box-shadow: 0 4px 24px var(--shadow);
  }
  .nav-logo img { height: 44px; object-fit: contain; }
  .nav-links { display: flex; gap: 36px; list-style: none; }
  .nav-links a {
    font-size: 14px; font-weight: 500; letter-spacing: 0.04em;
    color: var(--brown); text-decoration: none; text-transform: uppercase;
    position: relative; padding-bottom: 4px;
    transition: color 0.3s;
  }
  .nav-links a::after {
    content: ''; position: absolute; bottom: 0; left: 0; right: 100%;
    height: 1px; background: var(--gold);
    transition: right 0.35s ease;
  }
  .nav-links a:hover { color: var(--gold); }
  .nav-links a:hover::after { right: 0; }
  .nav-cta {
    background: var(--gold); color: white; border: none;
    padding: 10px 24px; border-radius: 2px;
    font-family: 'DM Sans', sans-serif; font-size: 13px; font-weight: 500;
    letter-spacing: 0.06em; text-transform: uppercase; cursor: pointer;
    transition: background 0.3s, transform 0.2s;
  }
  .nav-cta:hover { background: var(--gold-dark); transform: translateY(-1px); }
  .hamburger { display: none; flex-direction: column; gap: 5px; cursor: pointer; }
  .hamburger span { width: 26px; height: 2px; background: var(--brown); transition: 0.3s; }

  /* HERO */
  #inicio {
    min-height: 100vh;
    background: var(--brown);
    position: relative; overflow: hidden;
    display: flex; align-items: center;
  }
  .hero-bg {
    position: absolute; inset: 0;
    background: linear-gradient(135deg, #2C2420 0%, #3D2B1F 40%, #4A3525 70%, #2C2420 100%);
  }
  .hero-particles {
    position: absolute; inset: 0; overflow: hidden;
  }
  .particle {
    position: absolute;
    width: 2px; height: 2px;
    background: var(--gold);
    border-radius: 50%;
    animation: float linear infinite;
    opacity: 0;
  }
  @keyframes float {
    0% { transform: translateY(100vh) translateX(0); opacity: 0; }
    10% { opacity: 0.6; }
    90% { opacity: 0.4; }
    100% { transform: translateY(-10vh) translateX(40px); opacity: 0; }
  }
  .hero-lines {
    position: absolute; inset: 0;
    background-image:
      repeating-linear-gradient(90deg, transparent, transparent 79px, rgba(184,145,58,0.06) 80px);
  }
  .hero-content {
    position: relative; z-index: 10;
    padding: 0 8%; width: 100%;
    display: grid; grid-template-columns: 1fr 1fr; gap: 60px; align-items: center;
    padding-top: 80px;
  }
  .hero-text {}
  .hero-tag {
    display: inline-block;
    background: rgba(184,145,58,0.15);
    border: 1px solid rgba(184,145,58,0.4);
    color: var(--gold-light); font-size: 11px; letter-spacing: 0.2em;
    text-transform: uppercase; padding: 6px 16px; margin-bottom: 28px;
    animation: fadeUp 0.8s ease forwards;
  }
  .hero-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(40px, 5vw, 68px);
    font-weight: 700; line-height: 1.1;
    color: var(--cream); margin-bottom: 24px;
    animation: fadeUp 0.8s ease 0.15s forwards; opacity: 0;
  }
  .hero-title span { color: var(--gold-light); }
  .hero-desc {
    font-size: 16px; line-height: 1.8;
    color: rgba(245,240,232,0.72);
    max-width: 420px; margin-bottom: 40px;
    animation: fadeUp 0.8s ease 0.3s forwards; opacity: 0;
  }
  .hero-btns {
    display: flex; gap: 16px;
    animation: fadeUp 0.8s ease 0.45s forwards; opacity: 0;
  }
  .btn-primary {
    background: var(--gold); color: white;
    padding: 14px 32px; border: none; border-radius: 2px;
    font-family: 'DM Sans', sans-serif; font-size: 14px; font-weight: 500;
    letter-spacing: 0.06em; text-transform: uppercase; cursor: pointer;
    transition: all 0.3s; text-decoration: none; display: inline-block;
  }
  .btn-primary:hover { background: var(--gold-dark); transform: translateY(-2px); box-shadow: 0 8px 24px rgba(184,145,58,0.35); }
  .btn-outline {
    background: transparent; color: var(--cream);
    padding: 14px 32px; border: 1px solid rgba(245,240,232,0.35); border-radius: 2px;
    font-family: 'DM Sans', sans-serif; font-size: 14px; font-weight: 500;
    letter-spacing: 0.06em; text-transform: uppercase; cursor: pointer;
    transition: all 0.3s; text-decoration: none; display: inline-block;
  }
  .btn-outline:hover { border-color: var(--gold); color: var(--gold-light); }
  .hero-visual {
    position: relative;
    animation: fadeRight 1s ease 0.3s forwards; opacity: 0;
  }
  .hero-img-frame {
    position: relative;
    border: 1px solid rgba(184,145,58,0.3);
    border-radius: 4px; overflow: hidden;
    aspect-ratio: 4/3;
    background: rgba(255,255,255,0.04);
  }
  .hero-img-frame img {
    width: 100%; height: 100%; object-fit: cover; opacity: 0.9;
    transition: transform 8s ease; transform: scale(1.05);
  }
  .hero-img-frame:hover img { transform: scale(1); }
  .hero-img-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to bottom, transparent 50%, rgba(44,36,32,0.7));
  }
  .hero-stats {
    position: absolute; bottom: -20px; left: -20px;
    background: var(--gold);
    padding: 20px 28px;
    border-radius: 2px;
  }
  .hero-stats-num {
    font-family: 'Playfair Display', serif; font-size: 36px; font-weight: 700;
    color: white; display: block; line-height: 1;
  }
  .hero-stats-label { font-size: 12px; color: rgba(255,255,255,0.85); letter-spacing: 0.08em; text-transform: uppercase; }
  .hero-corner {
    position: absolute; top: -16px; right: -16px;
    width: 80px; height: 80px;
    border-top: 2px solid var(--gold);
    border-right: 2px solid var(--gold);
  }

  /* SCROLL INDICATOR */
  .scroll-hint {
    position: absolute; bottom: 32px; left: 50%; transform: translateX(-50%);
    display: flex; flex-direction: column; align-items: center; gap: 8px;
    color: rgba(184,145,58,0.6); font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase;
    animation: bounce 2s ease infinite;
  }
  .scroll-hint-line {
    width: 1px; height: 40px;
    background: linear-gradient(to bottom, rgba(184,145,58,0.6), transparent);
  }
  @keyframes bounce { 0%,100%{transform:translateX(-50%) translateY(0)} 50%{transform:translateX(-50%) translateY(8px)} }

  @keyframes fadeUp { from{opacity:0;transform:translateY(30px)} to{opacity:1;transform:translateY(0)} }
  @keyframes fadeRight { from{opacity:0;transform:translateX(40px)} to{opacity:1;transform:translateX(0)} }

  /* SECTION COMMONS */
  section { padding: 100px 8%; }
  .section-tag {
    display: inline-block; font-size: 11px; letter-spacing: 0.2em;
    text-transform: uppercase; color: var(--gold); margin-bottom: 12px;
  }
  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(32px, 3.5vw, 52px); font-weight: 700;
    color: var(--charcoal); line-height: 1.15; margin-bottom: 16px;
  }
  .section-title span { color: var(--gold); }
  .section-sub {
    font-size: 16px; line-height: 1.8; color: var(--text-muted);
    max-width: 560px; margin-bottom: 56px;
  }
  .divider {
    width: 48px; height: 2px; background: var(--gold);
    margin: 16px 0 24px;
  }

  /* ABOUT */
  #empresa {
    background: var(--cream);
  }
  .about-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 72px; align-items: center;
  }
  .about-imgs {
    position: relative;
  }
  .about-img-main {
    width: 100%; aspect-ratio: 3/4; object-fit: cover; border-radius: 4px;
    animation: kenBurns 8s ease-in-out infinite alternate;
  }
  @keyframes kenBurns { from{transform:scale(1)} to{transform:scale(1.04)} }
  .about-img-accent {
    position: absolute; bottom: -28px; right: -28px;
    width: 55%; aspect-ratio: 1; object-fit: cover; border-radius: 4px;
    border: 6px solid var(--cream);
    box-shadow: 0 16px 48px var(--shadow);
  }
  .about-badge {
    position: absolute; top: 28px; left: -28px;
    background: var(--brown); color: var(--cream);
    padding: 20px; text-align: center; border-radius: 2px;
    box-shadow: 0 8px 32px rgba(61,43,31,0.3);
  }
  .about-badge-num {
    font-family: 'Playfair Display', serif; font-size: 40px; font-weight: 700;
    color: var(--gold-light); display: block; line-height: 1;
  }
  .about-badge-text { font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; opacity: 0.8; }
  .features-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 32px;
  }
  .feature-item {
    display: flex; gap: 12px; align-items: flex-start;
  }
  .feature-icon {
    width: 40px; height: 40px; background: rgba(184,145,58,0.12);
    border: 1px solid rgba(184,145,58,0.25); border-radius: 2px;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0; font-size: 18px;
  }
  .feature-item h4 { font-size: 14px; font-weight: 500; margin-bottom: 4px; }
  .feature-item p { font-size: 13px; color: var(--text-muted); line-height: 1.6; }

  /* SERVICES */
  #servicos { background: var(--warm-white); }
  .services-grid {
    display: grid; grid-template-columns: repeat(3, 1fr); gap: 2px;
    border: 1px solid var(--border);
  }
  .service-card {
    padding: 40px 32px;
    border-right: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    background: white; position: relative; overflow: hidden;
    transition: all 0.4s ease; cursor: default;
  }
  .service-card::before {
    content: ''; position: absolute; bottom: 0; left: 0; right: 100%; height: 3px;
    background: var(--gold); transition: right 0.4s ease;
  }
  .service-card:hover::before { right: 0; }
  .service-card:hover { background: rgba(184,145,58,0.03); transform: translateY(-4px); box-shadow: 0 12px 40px var(--shadow); z-index: 1; }
  .service-num {
    font-family: 'Playfair Display', serif; font-size: 52px; font-weight: 700;
    color: rgba(184,145,58,0.12); line-height: 1; margin-bottom: 16px;
    transition: color 0.4s;
  }
  .service-card:hover .service-num { color: rgba(184,145,58,0.25); }
  .service-icon-wrap {
    width: 52px; height: 52px; margin-bottom: 20px;
    background: rgba(184,145,58,0.1); border: 1px solid rgba(184,145,58,0.2);
    border-radius: 4px; display: flex; align-items: center; justify-content: center;
    font-size: 22px; transition: all 0.4s;
  }
  .service-card:hover .service-icon-wrap { background: var(--gold); }
  .service-card h3 { font-size: 18px; font-weight: 600; margin-bottom: 12px; }
  .service-card p { font-size: 14px; line-height: 1.7; color: var(--text-muted); }

  /* PORTFOLIO */
  #portfolio { background: var(--charcoal); }
  #portfolio .section-title { color: var(--cream); }
  #portfolio .section-sub { color: rgba(245,240,232,0.55); }
  .portfolio-filter {
    display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 40px;
  }
  .filter-btn {
    padding: 8px 20px; border: 1px solid rgba(184,145,58,0.3);
    background: transparent; color: rgba(245,240,232,0.7);
    font-family: 'DM Sans', sans-serif; font-size: 13px; letter-spacing: 0.06em;
    text-transform: uppercase; cursor: pointer; border-radius: 2px;
    transition: all 0.3s;
  }
  .filter-btn.active, .filter-btn:hover {
    background: var(--gold); color: white; border-color: var(--gold);
  }
  .portfolio-grid {
    display: grid; grid-template-columns: repeat(3, 1fr); gap: 3px;
  }
  .portfolio-item {
    position: relative; overflow: hidden; aspect-ratio: 4/3; cursor: pointer;
    background: rgba(255,255,255,0.05);
  }
  .portfolio-item.wide { grid-column: span 2; }
  .portfolio-item.tall { grid-row: span 2; }
  .portfolio-item img {
    width: 100%; height: 100%; object-fit: cover;
    transition: transform 0.6s ease; filter: brightness(0.85);
  }
  .portfolio-item:hover img { transform: scale(1.08); filter: brightness(0.7); }
  .portfolio-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(44,36,32,0.92) 0%, transparent 60%);
    display: flex; flex-direction: column; justify-content: flex-end;
    padding: 28px; transform: translateY(20px); opacity: 0.7;
    transition: all 0.4s ease;
  }
  .portfolio-item:hover .portfolio-overlay { transform: translateY(0); opacity: 1; }
  .portfolio-overlay h4 {
    font-family: 'Playfair Display', serif; font-size: 18px;
    color: var(--cream); margin-bottom: 4px;
  }
  .portfolio-overlay span { font-size: 12px; color: var(--gold-light); letter-spacing: 0.1em; text-transform: uppercase; }
  .portfolio-cat {
    position: absolute; top: 16px; left: 16px;
    background: var(--gold); color: white; font-size: 11px;
    padding: 4px 12px; letter-spacing: 0.08em; text-transform: uppercase;
  }

  /* QUIZ */
  #orcamento { background: var(--cream); }
  .quiz-container {
    max-width: 740px; margin: 0 auto;
    background: white;
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    box-shadow: 0 24px 64px var(--shadow);
  }
  .quiz-header {
    background: var(--brown);
    padding: 32px 40px;
    display: flex; align-items: center; gap: 16px;
  }
  .quiz-header-icon { font-size: 28px; }
  .quiz-header h3 {
    font-family: 'Playfair Display', serif; font-size: 22px;
    color: var(--cream); font-weight: 600;
  }
  .quiz-header p { font-size: 13px; color: rgba(245,240,232,0.65); margin-top: 4px; }
  .quiz-progress {
    height: 3px; background: rgba(184,145,58,0.2);
  }
  .quiz-progress-bar {
    height: 100%; background: var(--gold);
    transition: width 0.5s ease;
  }
  .quiz-step {
    padding: 40px;
    display: none;
    animation: fadeUp 0.4s ease forwards;
  }
  .quiz-step.active { display: block; }
  .quiz-step-label {
    font-size: 11px; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--gold); margin-bottom: 8px;
  }
  .quiz-question {
    font-family: 'Playfair Display', serif; font-size: 22px; font-weight: 600;
    color: var(--charcoal); margin-bottom: 28px; line-height: 1.3;
  }
  .quiz-options {
    display: grid; grid-template-columns: 1fr 1fr; gap: 12px;
  }
  .quiz-option {
    border: 1.5px solid var(--border); border-radius: 3px;
    padding: 16px 20px; cursor: pointer;
    display: flex; align-items: center; gap: 12px;
    transition: all 0.25s; background: white;
    font-family: 'DM Sans', sans-serif;
  }
  .quiz-option:hover { border-color: var(--gold); background: rgba(184,145,58,0.04); }
  .quiz-option.selected {
    border-color: var(--gold); background: rgba(184,145,58,0.08);
    box-shadow: 0 0 0 1px var(--gold);
  }
  .quiz-option-icon { font-size: 20px; width: 32px; text-align: center; flex-shrink: 0; }
  .quiz-option-label { font-size: 14px; font-weight: 500; color: var(--charcoal); }
  .quiz-option-sub { font-size: 12px; color: var(--text-muted); }
  .quiz-nav {
    display: flex; justify-content: space-between; align-items: center;
    margin-top: 32px; padding-top: 24px; border-top: 1px solid var(--border);
  }
  .quiz-back {
    background: none; border: 1px solid var(--border); border-radius: 2px;
    padding: 10px 24px; cursor: pointer; font-family: 'DM Sans', sans-serif;
    font-size: 13px; color: var(--text-muted); transition: all 0.3s;
  }
  .quiz-back:hover { border-color: var(--brown); color: var(--brown); }
  .quiz-next {
    background: var(--gold); color: white; border: none; border-radius: 2px;
    padding: 12px 32px; cursor: pointer; font-family: 'DM Sans', sans-serif;
    font-size: 14px; font-weight: 500; letter-spacing: 0.05em; text-transform: uppercase;
    transition: all 0.3s;
  }
  .quiz-next:hover { background: var(--gold-dark); transform: translateY(-1px); }
  .quiz-next:disabled { background: #ccc; cursor: not-allowed; transform: none; }
  .quiz-result {
    padding: 48px 40px; text-align: center; display: none;
    animation: fadeUp 0.5s ease forwards;
  }
  .quiz-result.active { display: block; }
  .quiz-result-icon { font-size: 48px; margin-bottom: 16px; }
  .quiz-result h3 {
    font-family: 'Playfair Display', serif; font-size: 28px; font-weight: 700;
    color: var(--charcoal); margin-bottom: 12px;
  }
  .quiz-result p { font-size: 15px; line-height: 1.8; color: var(--text-muted); max-width: 440px; margin: 0 auto 24px; }
  .quiz-summary {
    background: rgba(184,145,58,0.07); border: 1px solid rgba(184,145,58,0.2);
    border-radius: 4px; padding: 20px; margin: 24px 0; text-align: left;
  }
  .quiz-summary-item {
    display: flex; justify-content: space-between; align-items: center;
    padding: 8px 0; border-bottom: 1px solid rgba(184,145,58,0.1); font-size: 14px;
  }
  .quiz-summary-item:last-child { border-bottom: none; }
  .quiz-summary-item span:first-child { color: var(--text-muted); }
  .quiz-summary-item span:last-child { font-weight: 500; color: var(--charcoal); }

  /* CONTACTS */
  #contactos { background: var(--warm-white); }
  .contacts-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 64px; align-items: start;
  }
  .contact-info h3 {
    font-family: 'Playfair Display', serif; font-size: 28px; font-weight: 600;
    margin-bottom: 20px;
  }
  .contact-info p { font-size: 15px; line-height: 1.8; color: var(--text-muted); margin-bottom: 36px; }
  .contact-items { display: flex; flex-direction: column; gap: 24px; }
  .contact-item {
    display: flex; gap: 16px; align-items: flex-start;
  }
  .contact-item-icon {
    width: 48px; height: 48px; flex-shrink: 0;
    background: rgba(184,145,58,0.1); border: 1px solid rgba(184,145,58,0.2);
    border-radius: 2px; display: flex; align-items: center; justify-content: center;
    font-size: 20px;
  }
  .contact-item h4 { font-size: 13px; letter-spacing: 0.08em; text-transform: uppercase; color: var(--gold); margin-bottom: 4px; }
  .contact-item p { font-size: 15px; color: var(--charcoal); line-height: 1.6; }
  .contact-map-placeholder {
    margin-top: 28px;
    height: 200px; background: rgba(184,145,58,0.05);
    border: 1px solid var(--border); border-radius: 4px;
    display: flex; align-items: center; justify-content: center;
    overflow: hidden;
  }
  .contact-map-placeholder iframe {
    width: 100%; height: 100%; border: none; filter: sepia(0.2) contrast(0.9);
  }

  /* FORM */
  .contact-form-wrap {
    background: white; border: 1px solid var(--border);
    border-radius: 4px; padding: 40px;
    box-shadow: 0 8px 32px var(--shadow);
  }
  .contact-form-wrap h3 {
    font-family: 'Playfair Display', serif; font-size: 22px; font-weight: 600;
    margin-bottom: 8px;
  }
  .contact-form-wrap p { font-size: 14px; color: var(--text-muted); margin-bottom: 28px; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .form-group { margin-bottom: 20px; }
  .form-group label {
    display: block; font-size: 12px; letter-spacing: 0.08em; text-transform: uppercase;
    color: var(--brown-mid); margin-bottom: 8px; font-weight: 500;
  }
  .form-group input, .form-group select, .form-group textarea {
    width: 100%; padding: 12px 16px;
    border: 1.5px solid var(--border); border-radius: 2px;
    font-family: 'DM Sans', sans-serif; font-size: 14px; color: var(--charcoal);
    background: white;
    transition: border-color 0.3s, box-shadow 0.3s;
    outline: none; appearance: none;
  }
  .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
    border-color: var(--gold);
    box-shadow: 0 0 0 3px rgba(184,145,58,0.12);
  }
  .form-group textarea { resize: vertical; min-height: 120px; }
  .form-submit {
    width: 100%; padding: 14px;
    background: var(--brown); color: var(--cream); border: none; border-radius: 2px;
    font-family: 'DM Sans', sans-serif; font-size: 14px; font-weight: 500;
    letter-spacing: 0.08em; text-transform: uppercase; cursor: pointer;
    transition: all 0.3s; position: relative; overflow: hidden;
  }
  .form-submit::after {
    content: ''; position: absolute; inset: 0;
    background: rgba(255,255,255,0); transition: background 0.3s;
  }
  .form-submit:hover { background: var(--charcoal); transform: translateY(-1px); box-shadow: 0 8px 24px rgba(61,43,31,0.3); }
  .form-success {
    display: none; text-align: center; padding: 32px;
    color: var(--gold-dark); font-size: 15px;
  }
  .form-success .success-icon { font-size: 48px; margin-bottom: 12px; }

  /* FOOTER */
  footer {
    background: var(--charcoal); color: rgba(245,240,232,0.65);
    padding: 64px 8% 32px;
  }
  .footer-grid {
    display: grid; grid-template-columns: 2fr 1fr 1fr 1fr; gap: 48px;
    margin-bottom: 48px;
  }
  .footer-brand img { height: 40px; margin-bottom: 20px; filter: brightness(2); }
  .footer-brand p { font-size: 14px; line-height: 1.8; max-width: 280px; }
  .footer-col h5 {
    font-size: 12px; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--gold-light); margin-bottom: 20px; font-weight: 500;
  }
  .footer-col ul { list-style: none; }
  .footer-col ul li { margin-bottom: 10px; }
  .footer-col ul li a {
    font-size: 14px; color: rgba(245,240,232,0.65); text-decoration: none;
    transition: color 0.3s;
  }
  .footer-col ul li a:hover { color: var(--gold-light); }
  .footer-bottom {
    border-top: 1px solid rgba(184,145,58,0.15);
    padding-top: 24px;
    display: flex; justify-content: space-between; align-items: center;
    font-size: 13px;
  }
  .social-links { display: flex; gap: 12px; }
  .social-link {
    width: 36px; height: 36px; border: 1px solid rgba(184,145,58,0.25); border-radius: 2px;
    display: flex; align-items: center; justify-content: center; font-size: 16px;
    text-decoration: none; color: rgba(245,240,232,0.65);
    transition: all 0.3s;
  }
  .social-link:hover { border-color: var(--gold); color: var(--gold-light); }

  /* FLOATING WHATSAPP */
  .whatsapp-float {
    position: fixed; bottom: 28px; right: 28px; z-index: 999;
    width: 56px; height: 56px; border-radius: 50%;
    background: #25D366; display: flex; align-items: center; justify-content: center;
    box-shadow: 0 8px 24px rgba(37,211,102,0.4);
    cursor: pointer; text-decoration: none; font-size: 26px;
    transition: transform 0.3s, box-shadow 0.3s;
    animation: pulse 2s ease infinite;
  }
  .whatsapp-float:hover { transform: scale(1.1); box-shadow: 0 12px 32px rgba(37,211,102,0.5); }
  @keyframes pulse { 0%,100%{box-shadow:0 8px 24px rgba(37,211,102,0.4)} 50%{box-shadow:0 8px 40px rgba(37,211,102,0.65)} }

  /* ANIMATIONS ON SCROLL */
  .reveal { opacity: 0; transform: translateY(40px); transition: all 0.7s ease; }
  .reveal.visible { opacity: 1; transform: translateY(0); }
  .reveal-left { opacity: 0; transform: translateX(-40px); transition: all 0.7s ease; }
  .reveal-left.visible { opacity: 1; transform: translateX(0); }
  .reveal-right { opacity: 0; transform: translateX(40px); transition: all 0.7s ease; }
  .reveal-right.visible { opacity: 1; transform: translateX(0); }

  /* NOTIFICATION */
  .notif {
    position: fixed; top: 88px; right: 24px; z-index: 9999;
    background: var(--brown); color: var(--cream);
    padding: 14px 20px; border-radius: 3px;
    border-left: 3px solid var(--gold);
    font-size: 14px; max-width: 300px;
    transform: translateX(120%); transition: transform 0.4s ease;
    box-shadow: 0 8px 24px rgba(61,43,31,0.35);
  }
  .notif.show { transform: translateX(0); }

  /* MOBILE */
  @media (max-width: 900px) {
    .hero-content { grid-template-columns: 1fr; padding-top: 100px; }
    .hero-visual { display: none; }
    .about-grid, .contacts-grid { grid-template-columns: 1fr; gap: 40px; }
    .about-badge { display: none; }
    .services-grid { grid-template-columns: 1fr; }
    .portfolio-grid { grid-template-columns: 1fr 1fr; }
    .portfolio-item.wide { grid-column: span 1; }
    .portfolio-item.tall { grid-row: span 1; }
    .footer-grid { grid-template-columns: 1fr 1fr; }
    .nav-links, .nav-cta { display: none; }
    .hamburger { display: flex; }
    section { padding: 64px 6%; }
    .quiz-options { grid-template-columns: 1fr; }
    .form-row { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav id="mainNav">
  <a href="#inicio" class="nav-logo">
    <img src="https://sonmovingui.com/wp-content/uploads/2019/07/sonmovingui-logo-300x100.png" alt="SonMovingui">
  </a>
  <ul class="nav-links">
    <li><a href="#inicio">Início</a></li>
    <li><a href="#empresa">Empresa</a></li>
    <li><a href="#servicos">Serviços</a></li>
    <li><a href="#portfolio">Portfólio</a></li>
    <li><a href="#orcamento">Orçamento</a></li>
    <li><a href="#contactos">Contactos</a></li>
  </ul>
  <button class="nav-cta" onclick="scrollTo('#orcamento')">Pedir Orçamento</button>
  <div class="hamburger" onclick="toggleMenu()">
    <span></span><span></span><span></span>
  </div>
</nav>

<!-- HERO -->
<section id="inicio">
  <div class="hero-bg"></div>
  <div class="hero-particles" id="particles"></div>
  <div class="hero-lines"></div>
  <div class="hero-content">
    <div class="hero-text">
      <div class="hero-tag">✦ Made in Portugal &nbsp;·&nbsp; Lordelo, Porto</div>
      <h1 class="hero-title">
        Mobiliário <span>Exclusivo</span><br>por Medida
      </h1>
      <p class="hero-desc">
        15 anos a criar peças únicas que transformam espaços. Sediados no maior centro de fabrico de móveis da Europa — qualidade portuguesa para o mundo.
      </p>
      <div class="hero-btns">
        <a href="#portfolio" class="btn-primary">Ver Portfólio</a>
        <a href="#orcamento" class="btn-outline">Pedir Orçamento</a>
      </div>
    </div>
    <div class="hero-visual">
      <div class="hero-img-frame">
        <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?w=800&q=80" alt="Mobiliário SonMovingui">
        <div class="hero-img-overlay"></div>
      </div>
      <div class="hero-stats">
        <span class="hero-stats-num">15+</span>
        <span class="hero-stats-label">Anos de experiência</span>
      </div>
      <div class="hero-corner"></div>
    </div>
  </div>
  <div class="scroll-hint">
    <span>Descobrir</span>
    <div class="scroll-hint-line"></div>
  </div>
</section>

<!-- EMPRESA -->
<section id="empresa">
  <div class="about-grid">
    <div class="about-imgs reveal-left">
      <img class="about-img-main"
        src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?w=700&q=80"
        alt="Oficina SonMovingui">
      <img class="about-img-accent"
        src="https://images.unsplash.com/photo-1555041469-a586c61ea9bc?w=400&q=80"
        alt="Detalhe mobiliário">
      <div class="about-badge">
        <span class="about-badge-num">500+</span>
        <span class="about-badge-text">Projetos concluídos</span>
      </div>
    </div>
    <div class="reveal-right">
      <span class="section-tag">✦ A Nossa História</span>
      <h2 class="section-title">Garantia de sucesso<br>em cada <span>projeto</span></h2>
      <div class="divider"></div>
      <p style="font-size:15px;line-height:1.9;color:var(--text-muted);margin-bottom:20px;">
        Somos um grupo de trabalho onde o profissionalismo, a prestação de um serviço qualificado e a aposta no design, funcionalidade e qualidade dos produtos são a garantia do sucesso no nosso trabalho.
      </p>
      <p style="font-size:15px;line-height:1.9;color:var(--text-muted);margin-bottom:32px;">
        Somos especialistas em mobiliário maciço, cozinhas por medida e representamos as melhores marcas do mercado mundial — para que os seus desejos se tornem realidade.
      </p>
      <div class="features-grid">
        <div class="feature-item">
          <div class="feature-icon">🪵</div>
          <div><h4>Madeira Maciça</h4><p>Materiais de excelência, selecionados criteriosamente</p></div>
        </div>
        <div class="feature-item">
          <div class="feature-icon">📐</div>
          <div><h4>Por Medida</h4><p>Cada peça desenhada para o seu espaço</p></div>
        </div>
        <div class="feature-item">
          <div class="feature-icon">🌍</div>
          <div><h4>Exportação</h4><p>Projetos em vários pontos da Europa</p></div>
        </div>
        <div class="feature-item">
          <div class="feature-icon">🏆</div>
          <div><h4>15 Anos</h4><p>De experiência no setor do mobiliário</p></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVIÇOS -->
<section id="servicos">
  <div style="text-align:center;margin-bottom:60px;" class="reveal">
    <span class="section-tag">✦ O Que Oferecemos</span>
    <h2 class="section-title">Os Nossos <span>Serviços</span></h2>
    <div class="divider" style="margin:16px auto 0;"></div>
  </div>
  <div class="services-grid reveal">
    <div class="service-card">
      <div class="service-num">01</div>
      <div class="service-icon-wrap">🤝</div>
      <h3>Atendimento Personalizado</h3>
      <p>A nossa equipa atende cada cliente individualmente, atendendo às suas necessidades e buscando a melhor solução em cada situação.</p>
    </div>
    <div class="service-card">
      <div class="service-num">02</div>
      <div class="service-icon-wrap">💬</div>
      <h3>Orçamentos Gratuitos</h3>
      <p>Acreditamos que os valores praticados são justos. Damos cotação para cada serviço solicitado, sem custos extra.</p>
    </div>
    <div class="service-card">
      <div class="service-num">03</div>
      <div class="service-icon-wrap">📐</div>
      <h3>Mobiliário por Medida</h3>
      <p>Desenhamos, cortamos, montamos e acabamos cada peça exclusiva e original, pensada ao milímetro para o seu espaço.</p>
    </div>
    <div class="service-card">
      <div class="service-num">04</div>
      <div class="service-icon-wrap">🔧</div>
      <h3>Assistência Pós-Venda</h3>
      <p>Garantimos aos nossos clientes a assistência necessária em toda a Europa, em todas as fases da obra.</p>
    </div>
    <div class="service-card">
      <div class="service-num">05</div>
      <div class="service-icon-wrap">🚚</div>
      <h3>Transporte e Montagem</h3>
      <p>Tratamos do transporte e montagem dentro dos prazos definidos, para que o nosso cliente fique 100% satisfeito.</p>
    </div>
    <div class="service-card">
      <div class="service-num">06</div>
      <div class="service-icon-wrap">👷</div>
      <h3>Acompanhamento Técnico</h3>
      <p>A nossa equipa altamente qualificada acompanha cada fase do projeto, reunindo conhecimento e experiência.</p>
    </div>
  </div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio">
  <div style="display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:24px;margin-bottom:36px;">
    <div class="reveal">
      <span class="section-tag">✦ Os Nossos Trabalhos</span>
      <h2 class="section-title">Portfólio</h2>
      <div class="divider"></div>
    </div>
    <div class="portfolio-filter reveal">
      <button class="filter-btn active" onclick="filterPortfolio('all',this)">Todos</button>
      <button class="filter-btn" onclick="filterPortfolio('cozinha',this)">Cozinhas</button>
      <button class="filter-btn" onclick="filterPortfolio('quarto',this)">Quartos</button>
      <button class="filter-btn" onclick="filterPortfolio('sala',this)">Salas</button>
      <button class="filter-btn" onclick="filterPortfolio('escritorio',this)">Escritórios</button>
    </div>
  </div>
  <div class="portfolio-grid" id="portfolioGrid">
    <div class="portfolio-item wide" data-cat="cozinha">
      <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?w=900&q=80" alt="Cozinha moderna">
      <div class="portfolio-overlay"><h4>Cozinha Contemporânea</h4><span>Cozinhas</span></div>
      <div class="portfolio-cat">Cozinhas</div>
    </div>
    <div class="portfolio-item tall" data-cat="quarto">
      <img src="https://images.unsplash.com/photo-1616594039964-ae9021a400a0?w=600&q=80" alt="Quarto">
      <div class="portfolio-overlay"><h4>Suite Master</h4><span>Quartos</span></div>
      <div class="portfolio-cat">Quartos</div>
    </div>
    <div class="portfolio-item" data-cat="sala">
      <img src="https://images.unsplash.com/photo-1555041469-a586c61ea9bc?w=600&q=80" alt="Sala">
      <div class="portfolio-overlay"><h4>Sala de Estar</h4><span>Salas</span></div>
      <div class="portfolio-cat">Salas</div>
    </div>
    <div class="portfolio-item" data-cat="escritorio">
      <img src="https://images.unsplash.com/photo-1598300042247-d088f8ab3a91?w=600&q=80" alt="Escritório">
      <div class="portfolio-overlay"><h4>Home Office Premium</h4><span>Escritórios</span></div>
      <div class="portfolio-cat">Escritórios</div>
    </div>
    <div class="portfolio-item" data-cat="cozinha">
      <img src="https://images.unsplash.com/photo-1556909172-54557c7e4fb7?w=600&q=80" alt="Cozinha rústica">
      <div class="portfolio-overlay"><h4>Cozinha Rústica</h4><span>Cozinhas</span></div>
      <div class="portfolio-cat">Cozinhas</div>
    </div>
    <div class="portfolio-item" data-cat="sala">
      <img src="https://images.unsplash.com/photo-1560185007-5f0bb1866cab?w=600&q=80" alt="Sala de jantar">
      <div class="portfolio-overlay"><h4>Sala de Jantar</h4><span>Salas</span></div>
      <div class="portfolio-cat">Salas</div>
    </div>
    <div class="portfolio-item" data-cat="quarto">
      <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?w=600&q=80" alt="Roupeiro">
      <div class="portfolio-overlay"><h4>Roupeiro por Medida</h4><span>Quartos</span></div>
      <div class="portfolio-cat">Quartos</div>
    </div>
    <div class="portfolio-item" data-cat="escritorio">
      <img src="https://images.unsplash.com/photo-1497366216548-37526070297c?w=600&q=80" alt="Escritório corporativo">
      <div class="portfolio-overlay"><h4>Escritório Corporativo</h4><span>Escritórios</span></div>
      <div class="portfolio-cat">Escritórios</div>
    </div>
  </div>
</section>

<!-- QUIZ / ORÇAMENTO -->
<section id="orcamento">
  <div style="text-align:center;margin-bottom:52px;" class="reveal">
    <span class="section-tag">✦ Orçamento Inteligente</span>
    <h2 class="section-title">Qual é o seu<br><span>projeto de sonho?</span></h2>
    <div class="divider" style="margin:16px auto 0;"></div>
    <p class="section-sub" style="margin:16px auto 0;">Responda a algumas perguntas e receba um orçamento personalizado em menos de 24h.</p>
  </div>
  <div class="quiz-container reveal">
    <div class="quiz-header">
      <div class="quiz-header-icon">🏠</div>
      <div>
        <h3>Configurador de Orçamento</h3>
        <p>5 perguntas rápidas · Resposta em 24h</p>
      </div>
    </div>
    <div class="quiz-progress">
      <div class="quiz-progress-bar" id="quizProgress" style="width:20%"></div>
    </div>

    <!-- STEP 1 -->
    <div class="quiz-step active" id="step1">
      <div class="quiz-step-label">Pergunta 1 de 5</div>
      <div class="quiz-question">Que tipo de mobiliário pretende?</div>
      <div class="quiz-options">
        <div class="quiz-option" onclick="selectOption(this,'tipo','Cozinha por medida')">
          <div class="quiz-option-icon">🍳</div>
          <div><div class="quiz-option-label">Cozinha</div><div class="quiz-option-sub">Por medida ou renovação</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'tipo','Quarto / Roupeiro')">
          <div class="quiz-option-icon">🛏️</div>
          <div><div class="quiz-option-label">Quarto / Roupeiro</div><div class="quiz-option-sub">Suite, roupeiro, cabeceira</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'tipo','Sala de estar / Jantar')">
          <div class="quiz-option-icon">🛋️</div>
          <div><div class="quiz-option-label">Sala de Estar</div><div class="quiz-option-sub">Estante, aparador, mesa</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'tipo','Escritório')">
          <div class="quiz-option-icon">💼</div>
          <div><div class="quiz-option-label">Escritório</div><div class="quiz-option-sub">Secretária, libraria, home office</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'tipo','Casa de banho')">
          <div class="quiz-option-icon">🚿</div>
          <div><div class="quiz-option-label">Casa de Banho</div><div class="quiz-option-sub">Móvel lavatório, espelheira</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'tipo','Projeto completo')">
          <div class="quiz-option-icon">🏡</div>
          <div><div class="quiz-option-label">Projeto Completo</div><div class="quiz-option-sub">Toda a habitação</div></div>
        </div>
      </div>
      <div class="quiz-nav">
        <button class="quiz-back" disabled style="opacity:0.3">← Anterior</button>
        <button class="quiz-next" id="next1" disabled onclick="nextStep(2)">Próximo →</button>
      </div>
    </div>

    <!-- STEP 2 -->
    <div class="quiz-step" id="step2">
      <div class="quiz-step-label">Pergunta 2 de 5</div>
      <div class="quiz-question">Qual o estilo que mais lhe agrada?</div>
      <div class="quiz-options">
        <div class="quiz-option" onclick="selectOption(this,'estilo','Moderno / Contemporâneo')">
          <div class="quiz-option-icon">◼</div>
          <div><div class="quiz-option-label">Moderno</div><div class="quiz-option-sub">Linhas retas, tons neutros</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'estilo','Clássico / Tradicional')">
          <div class="quiz-option-icon">🏛️</div>
          <div><div class="quiz-option-label">Clássico</div><div class="quiz-option-sub">Elegante, atemporal</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'estilo','Rústico / Natural')">
          <div class="quiz-option-icon">🪵</div>
          <div><div class="quiz-option-label">Rústico</div><div class="quiz-option-sub">Madeira maciça, autenticidade</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'estilo','Minimalista')">
          <div class="quiz-option-icon">⬜</div>
          <div><div class="quiz-option-label">Minimalista</div><div class="quiz-option-sub">Menos é mais</div></div>
        </div>
      </div>
      <div class="quiz-nav">
        <button class="quiz-back" onclick="prevStep(1)">← Anterior</button>
        <button class="quiz-next" id="next2" disabled onclick="nextStep(3)">Próximo →</button>
      </div>
    </div>

    <!-- STEP 3 -->
    <div class="quiz-step" id="step3">
      <div class="quiz-step-label">Pergunta 3 de 5</div>
      <div class="quiz-question">Qual o orçamento aproximado que tem em mente?</div>
      <div class="quiz-options">
        <div class="quiz-option" onclick="selectOption(this,'budget','Até 3.000€')">
          <div class="quiz-option-icon">💰</div>
          <div><div class="quiz-option-label">Até 3.000€</div><div class="quiz-option-sub">Projeto base / peça única</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'budget','3.000€ – 8.000€')">
          <div class="quiz-option-icon">💰</div>
          <div><div class="quiz-option-label">3.000€ – 8.000€</div><div class="quiz-option-sub">Divisão completa</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'budget','8.000€ – 20.000€')">
          <div class="quiz-option-icon">💎</div>
          <div><div class="quiz-option-label">8.000€ – 20.000€</div><div class="quiz-option-sub">Projeto premium</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'budget','Mais de 20.000€')">
          <div class="quiz-option-icon">🏆</div>
          <div><div class="quiz-option-label">+20.000€</div><div class="quiz-option-sub">Projeto de habitação completo</div></div>
        </div>
      </div>
      <div class="quiz-nav">
        <button class="quiz-back" onclick="prevStep(2)">← Anterior</button>
        <button class="quiz-next" id="next3" disabled onclick="nextStep(4)">Próximo →</button>
      </div>
    </div>

    <!-- STEP 4 -->
    <div class="quiz-step" id="step4">
      <div class="quiz-step-label">Pergunta 4 de 5</div>
      <div class="quiz-question">Quando pretende iniciar o projeto?</div>
      <div class="quiz-options">
        <div class="quiz-option" onclick="selectOption(this,'prazo','Urgente – 1 mês')">
          <div class="quiz-option-icon">⚡</div>
          <div><div class="quiz-option-label">Urgente</div><div class="quiz-option-sub">Dentro de 1 mês</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'prazo','2 a 4 meses')">
          <div class="quiz-option-icon">📅</div>
          <div><div class="quiz-option-label">Breve prazo</div><div class="quiz-option-sub">2 a 4 meses</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'prazo','4 a 8 meses')">
          <div class="quiz-option-icon">🗓️</div>
          <div><div class="quiz-option-label">Médio prazo</div><div class="quiz-option-sub">4 a 8 meses</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'prazo','Ainda a planear')">
          <div class="quiz-option-icon">💭</div>
          <div><div class="quiz-option-label">A planear</div><div class="quiz-option-sub">Ainda em fase de ideias</div></div>
        </div>
      </div>
      <div class="quiz-nav">
        <button class="quiz-back" onclick="prevStep(3)">← Anterior</button>
        <button class="quiz-next" id="next4" disabled onclick="nextStep(5)">Próximo →</button>
      </div>
    </div>

    <!-- STEP 5 -->
    <div class="quiz-step" id="step5">
      <div class="quiz-step-label">Pergunta 5 de 5</div>
      <div class="quiz-question">Onde se localiza o projeto?</div>
      <div class="quiz-options">
        <div class="quiz-option" onclick="selectOption(this,'local','Porto / Norte de Portugal')">
          <div class="quiz-option-icon">📍</div>
          <div><div class="quiz-option-label">Porto / Norte</div><div class="quiz-option-sub">Entrega e montagem incluídas</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'local','Centro / Lisboa')">
          <div class="quiz-option-icon">📍</div>
          <div><div class="quiz-option-label">Centro / Lisboa</div><div class="quiz-option-sub">Entrega e montagem disponíveis</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'local','Sul / Algarve')">
          <div class="quiz-option-icon">🌞</div>
          <div><div class="quiz-option-label">Sul / Algarve</div><div class="quiz-option-sub">Consultar disponibilidade</div></div>
        </div>
        <div class="quiz-option" onclick="selectOption(this,'local','Outro país – Europa')">
          <div class="quiz-option-icon">🌍</div>
          <div><div class="quiz-option-label">Europa</div><div class="quiz-option-sub">Exportação disponível</div></div>
        </div>
      </div>
      <div class="quiz-nav">
        <button class="quiz-back" onclick="prevStep(4)">← Anterior</button>
        <button class="quiz-next" id="next5" disabled onclick="showQuizResult()">Ver Resultado ✓</button>
      </div>
    </div>

    <!-- RESULT -->
    <div class="quiz-result" id="quizResult">
      <div class="quiz-result-icon">🎉</div>
      <h3>Perfil de Projeto Identificado!</h3>
      <p>Excelente! Com base nas suas respostas, elaborámos um resumo do seu projeto. A nossa equipa entrará em contacto nas próximas 24h com um orçamento detalhado.</p>
      <div class="quiz-summary" id="quizSummary"></div>
      <button class="btn-primary" onclick="scrollTo('#contactos')" style="margin-top:8px">Enviar Contacto →</button>
      <p style="font-size:13px;color:var(--text-muted);margin-top:16px;cursor:pointer;" onclick="restartQuiz()">Recomeçar questionário</p>
    </div>
  </div>
</section>

<!-- CONTACTOS -->
<section id="contactos">
  <div style="text-align:center;margin-bottom:60px;" class="reveal">
    <span class="section-tag">✦ Fale Connosco</span>
    <h2 class="section-title">Entre em <span>Contacto</span></h2>
    <div class="divider" style="margin:16px auto 0;"></div>
  </div>
  <div class="contacts-grid">
    <div class="contact-info reveal-left">
      <h3>Estamos à sua disposição</h3>
      <p>Visite-nos, ligue-nos ou envie-nos uma mensagem. A nossa equipa está pronta para lhe dar toda a assistência necessária para tornar o seu projeto realidade.</p>
      <div class="contact-items">
        <div class="contact-item">
          <div class="contact-item-icon">📍</div>
          <div>
            <h4>Morada</h4>
            <p>R. Nova Cerqueda 1029<br>4580-846 Lordelo, Porto</p>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">📞</div>
          <div>
            <h4>Telefone</h4>
            <p>+351 224 445 221<br>+351 916 039 930</p>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">✉️</div>
          <div>
            <h4>Email</h4>
            <p>geral@sonmovingui.com</p>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">🕐</div>
          <div>
            <h4>Horário</h4>
            <p>Seg – Sex: 9h00 – 18h00<br>Sáb: 10h00 – 13h00</p>
          </div>
        </div>
      </div>
      <div class="contact-map-placeholder">
        <iframe
          src="https://maps.google.com/maps?q=R.+Nova+Cerqueda+1029,+4580-846+Lordelo&output=embed"
          loading="lazy" allowfullscreen referrerpolicy="no-referrer-when-downgrade"
          title="Localização SonMovingui">
        </iframe>
      </div>
    </div>
    <div class="reveal-right">
      <div class="contact-form-wrap">
        <h3>Envie-nos uma mensagem</h3>
        <p>Responderemos em menos de 24 horas úteis.</p>
        <div id="contactForm">
          <div class="form-row">
            <div class="form-group">
              <label>Nome</label>
              <input type="text" id="fname" placeholder="O seu nome">
            </div>
            <div class="form-group">
              <label>Apelido</label>
              <input type="text" id="lname" placeholder="O seu apelido">
            </div>
          </div>
          <div class="form-group">
            <label>Email</label>
            <input type="email" id="femail" placeholder="email@exemplo.com">
          </div>
          <div class="form-group">
            <label>Telefone</label>
            <input type="tel" id="fphone" placeholder="+351 9XX XXX XXX">
          </div>
          <div class="form-group">
            <label>Tipo de Projeto</label>
            <select id="ftype">
              <option value="">Selecione uma opção</option>
              <option>Cozinha por medida</option>
              <option>Quarto / Roupeiro</option>
              <option>Sala de estar</option>
              <option>Escritório</option>
              <option>Casa de banho</option>
              <option>Projeto completo</option>
              <option>Outro</option>
            </select>
          </div>
          <div class="form-group">
            <label>Mensagem</label>
            <textarea id="fmessage" placeholder="Descreva o seu projeto, espaço disponível, preferências de material e prazo..."></textarea>
          </div>
          <button class="form-submit" onclick="submitForm()">Enviar Mensagem</button>
        </div>
        <div class="form-success" id="formSuccess">
          <div class="success-icon">✅</div>
          <h4 style="font-family:'Playfair Display',serif;font-size:20px;margin-bottom:8px;">Mensagem enviada!</h4>
          <p style="color:var(--text-muted);font-size:14px;">Obrigado pelo seu contacto. A nossa equipa responderá em menos de 24 horas úteis.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-grid">
    <div class="footer-brand">
      <img src="https://sonmovingui.com/wp-content/uploads/2019/07/sonmovingui-logo-300x100.png" alt="SonMovingui">
      <p>Sediados no maior centro de fabrico de móveis da Europa, com 15 anos de experiência no mobiliário Made in Portugal.</p>
    </div>
    <div class="footer-col">
      <h5>Navegação</h5>
      <ul>
        <li><a href="#inicio">Início</a></li>
        <li><a href="#empresa">Empresa</a></li>
        <li><a href="#servicos">Serviços</a></li>
        <li><a href="#portfolio">Portfólio</a></li>
        <li><a href="#orcamento">Orçamento</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Serviços</h5>
      <ul>
        <li><a href="#servicos">Cozinhas</a></li>
        <li><a href="#servicos">Quartos</a></li>
        <li><a href="#servicos">Salas</a></li>
        <li><a href="#servicos">Escritórios</a></li>
        <li><a href="#servicos">Por Medida</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Contacto</h5>
      <ul>
        <li><a href="#">Lordelo, Porto</a></li>
        <li><a href="tel:+351224445221">224 445 221</a></li>
        <li><a href="tel:+351916039930">916 039 930</a></li>
        <li><a href="mailto:geral@sonmovingui.com">geral@sonmovingui.com</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2025 SonMovingui – Furniture. Todos os direitos reservados.</span>
    <div class="social-links">
      <a class="social-link" href="#" title="Facebook">f</a>
      <a class="social-link" href="#" title="Instagram">📸</a>
      <a class="social-link" href="#" title="LinkedIn">in</a>
    </div>
  </div>
</footer>

<!-- WHATSAPP -->
<a class="whatsapp-float" href="https://wa.me/351916039930" target="_blank" title="WhatsApp">💬</a>

<!-- NOTIFICATION -->
<div class="notif" id="notif"></div>

<script>
// PARTICLES
(function(){
  const c = document.getElementById('particles');
  for(let i=0;i<30;i++){
    const p = document.createElement('div');
    p.className='particle';
    p.style.cssText=`left:${Math.random()*100}%;width:${1+Math.random()*3}px;height:${1+Math.random()*3}px;animation-duration:${6+Math.random()*14}s;animation-delay:${Math.random()*10}s;`;
    c.appendChild(p);
  }
})();

// NAV SCROLL
window.addEventListener('scroll',()=>{
  document.getElementById('mainNav').classList.toggle('scrolled',window.scrollY>50);
});

// SCROLL REVEAL
const observer = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add('visible'); });
},{threshold:0.1});
document.querySelectorAll('.reveal,.reveal-left,.reveal-right').forEach(el=>observer.observe(el));

// SCROLL TO
function scrollTo(id){ document.querySelector(id)?.scrollIntoView({behavior:'smooth'}); }

// MOBILE MENU
function toggleMenu(){
  document.querySelector('.nav-links').style.display =
    document.querySelector('.nav-links').style.display==='flex' ? 'none' : 'flex';
}

// PORTFOLIO FILTER
function filterPortfolio(cat, btn){
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('.portfolio-item').forEach(item=>{
    const show = cat==='all' || item.dataset.cat===cat;
    item.style.display = show ? 'block' : 'none';
    item.style.opacity = show ? '1' : '0';
    item.style.transition = 'opacity 0.4s ease';
  });
}

// QUIZ
const quizData = {};
function selectOption(el, key, val){
  el.closest('.quiz-options').querySelectorAll('.quiz-option').forEach(o=>o.classList.remove('selected'));
  el.classList.add('selected');
  quizData[key]=val;
  const step = el.closest('.quiz-step').id.replace('step','');
  const btn = document.getElementById('next'+step);
  if(btn){ btn.disabled=false; btn.style.opacity='1'; }
}
function nextStep(n){
  document.querySelectorAll('.quiz-step').forEach(s=>s.classList.remove('active'));
  document.getElementById('step'+n).classList.add('active');
  document.getElementById('quizProgress').style.width=(n*20)+'%';
}
function prevStep(n){
  document.querySelectorAll('.quiz-step').forEach(s=>s.classList.remove('active'));
  document.getElementById('step'+n).classList.add('active');
  document.getElementById('quizProgress').style.width=(n*20)+'%';
}
function showQuizResult(){
  document.querySelectorAll('.quiz-step').forEach(s=>s.classList.remove('active'));
  document.getElementById('quizResult').classList.add('active');
  document.getElementById('quizProgress').style.width='100%';
  const labels = {tipo:'Tipo de Projeto',estilo:'Estilo Pretendido',budget:'Orçamento',prazo:'Prazo',local:'Localização'};
  let html='';
  for(const k in labels){
    if(quizData[k]) html+=`<div class="quiz-summary-item"><span>${labels[k]}</span><span>${quizData[k]}</span></div>`;
  }
  document.getElementById('quizSummary').innerHTML=html;
  showNotif('✅ Perfil criado! Preencha os contactos abaixo.');
}
function restartQuiz(){
  Object.keys(quizData).forEach(k=>delete quizData[k]);
  document.querySelectorAll('.quiz-option').forEach(o=>o.classList.remove('selected'));
  document.querySelectorAll('.quiz-next').forEach(b=>{b.disabled=true;b.style.opacity='0.5';});
  document.getElementById('quizResult').classList.remove('active');
  document.querySelectorAll('.quiz-step').forEach(s=>s.classList.remove('active'));
  document.getElementById('step1').classList.add('active');
  document.getElementById('quizProgress').style.width='20%';
}

// FORM
function submitForm(){
  const fields = ['fname','lname','femail','fphone','ftype','fmessage'];
  let valid=true;
  fields.forEach(f=>{ if(!document.getElementById(f)?.value){ valid=false; document.getElementById(f)?.style.setProperty('border-color','#e24b4a'); }
    else document.getElementById(f)?.style.setProperty('border-color',''); });
  if(!valid){ showNotif('⚠️ Por favor preencha todos os campos.'); return; }
  document.getElementById('contactForm').style.display='none';
  document.getElementById('formSuccess').style.display='block';
  showNotif('🎉 Mensagem enviada com sucesso!');
}

// NOTIFICATION
function showNotif(msg){
  const n=document.getElementById('notif');
  n.textContent=msg; n.classList.add('show');
  setTimeout(()=>n.classList.remove('show'),4000);
}
</script>
</body>
</html>
