<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fixr — We Solve. You Thrive.</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0b0c0f;
    --surface: #141519;
    --surface2: #1c1d23;
    --border: rgba(255,255,255,0.07);
    --accent: #f5e642;
    --accent2: #ff5e3a;
    --accent3: #3af5b4;
    --text: #f0eeea;
    --muted: #7a7a8a;
    --card-bg: #16171d;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    width: 12px; height: 12px;
    background: var(--accent);
    border-radius: 50%;
    position: fixed;
    pointer-events: none;
    z-index: 9999;
    transform: translate(-50%, -50%);
    transition: transform 0.1s, width 0.2s, height 0.2s, background 0.2s;
    mix-blend-mode: difference;
  }
  .cursor-ring {
    width: 38px; height: 38px;
    border: 1.5px solid rgba(245,230,66,0.5);
    border-radius: 50%;
    position: fixed;
    pointer-events: none;
    z-index: 9998;
    transform: translate(-50%, -50%);
    transition: transform 0.15s ease, width 0.3s, height 0.3s;
  }
  body:hover .cursor { opacity: 1; }

  /* Noise overlay */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9997;
    opacity: 0.3;
  }

  /* NAV */
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 24px 60px;
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    background: rgba(11,12,15,0.85);
    backdrop-filter: blur(16px);
    border-bottom: 1px solid var(--border);
  }
  .logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 1.6rem;
    letter-spacing: -0.04em;
    color: var(--text);
    text-decoration: none;
  }
  .logo span { color: var(--accent); }
  nav ul {
    list-style: none;
    display: flex;
    gap: 36px;
    align-items: center;
  }
  nav ul a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 400;
    letter-spacing: 0.02em;
    transition: color 0.2s;
  }
  nav ul a:hover { color: var(--text); }
  .nav-cta {
    background: var(--accent) !important;
    color: var(--bg) !important;
    padding: 10px 22px;
    border-radius: 100px;
    font-weight: 500 !important;
    font-size: 0.88rem !important;
    transition: transform 0.2s, box-shadow 0.2s !important;
  }
  .nav-cta:hover { transform: translateY(-2px); box-shadow: 0 6px 24px rgba(245,230,66,0.3); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding: 120px 60px 80px;
    position: relative;
    overflow: hidden;
  }
  .hero-bg {
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse 60% 50% at 70% 40%, rgba(245,230,66,0.07) 0%, transparent 70%),
      radial-gradient(ellipse 40% 40% at 20% 80%, rgba(58,245,180,0.05) 0%, transparent 60%);
  }
  .hero-grid {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
    background-size: 80px 80px;
    mask-image: radial-gradient(ellipse 70% 70% at center, black 0%, transparent 80%);
  }
  .hero-content {
    position: relative;
    z-index: 1;
    max-width: 820px;
  }
  .hero-tag {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(245,230,66,0.1);
    border: 1px solid rgba(245,230,66,0.25);
    color: var(--accent);
    font-size: 0.78rem;
    font-weight: 500;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 6px 14px;
    border-radius: 100px;
    margin-bottom: 32px;
    animation: fadeUp 0.6s ease both;
  }
  .hero-tag::before {
    content: '';
    width: 6px; height: 6px;
    background: var(--accent);
    border-radius: 50%;
    animation: pulse 2s infinite;
  }
  @keyframes pulse { 0%,100%{opacity:1;} 50%{opacity:0.3;} }

  h1 {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(3rem, 7vw, 6rem);
    line-height: 1.0;
    letter-spacing: -0.04em;
    margin-bottom: 28px;
    animation: fadeUp 0.6s ease 0.1s both;
  }
  h1 em {
    font-style: normal;
    color: var(--accent);
    position: relative;
  }
  h1 em::after {
    content: '';
    position: absolute;
    bottom: 4px; left: 0; right: 0;
    height: 3px;
    background: var(--accent);
    border-radius: 2px;
    animation: lineGrow 0.8s ease 0.7s both;
    transform-origin: left;
  }
  @keyframes lineGrow { from{transform:scaleX(0);} to{transform:scaleX(1);} }
  .hero-sub {
    font-size: 1.15rem;
    color: var(--muted);
    line-height: 1.7;
    max-width: 500px;
    margin-bottom: 44px;
    animation: fadeUp 0.6s ease 0.2s both;
  }
  .hero-actions {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
    animation: fadeUp 0.6s ease 0.3s both;
  }
  .btn-primary {
    background: var(--accent);
    color: var(--bg);
    padding: 16px 36px;
    border-radius: 100px;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.95rem;
    border: none;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 12px 36px rgba(245,230,66,0.35); }
  .btn-ghost {
    background: transparent;
    color: var(--text);
    padding: 15px 36px;
    border-radius: 100px;
    font-family: 'Syne', sans-serif;
    font-weight: 600;
    font-size: 0.95rem;
    border: 1px solid var(--border);
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: border-color 0.2s, background 0.2s;
  }
  .btn-ghost:hover { border-color: rgba(255,255,255,0.2); background: rgba(255,255,255,0.04); }

  .hero-stats {
    display: flex;
    gap: 48px;
    margin-top: 60px;
    padding-top: 48px;
    border-top: 1px solid var(--border);
    animation: fadeUp 0.6s ease 0.4s both;
  }
  .stat-val {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 2.2rem;
    letter-spacing: -0.04em;
  }
  .stat-val span { color: var(--accent); }
  .stat-label { font-size: 0.82rem; color: var(--muted); margin-top: 2px; }

  @keyframes fadeUp { from{opacity:0;transform:translateY(20px);} to{opacity:1;transform:translateY(0);} }

  /* TICKER */
  .ticker {
    background: var(--accent);
    padding: 14px 0;
    overflow: hidden;
    white-space: nowrap;
  }
  .ticker-track {
    display: inline-flex;
    animation: ticker 20s linear infinite;
  }
  .ticker-item {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.82rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--bg);
    padding: 0 32px;
  }
  .ticker-sep { color: rgba(0,0,0,0.3); }
  @keyframes ticker { from{transform:translateX(0);} to{transform:translateX(-50%);} }

  /* SECTION COMMON */
  section { padding: 100px 60px; }
  .section-tag {
    font-size: 0.75rem;
    font-weight: 500;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 16px;
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(2rem, 4vw, 3.2rem);
    letter-spacing: -0.03em;
    line-height: 1.1;
    margin-bottom: 16px;
  }
  .section-sub {
    color: var(--muted);
    font-size: 1rem;
    line-height: 1.7;
    max-width: 480px;
  }

  /* HOW IT WORKS */
  .how { background: var(--surface); }
  .how-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: center;
    margin-top: 64px;
  }
  .step {
    display: flex;
    gap: 24px;
    align-items: flex-start;
    margin-bottom: 44px;
    opacity: 0;
    transform: translateX(-20px);
    transition: opacity 0.5s ease, transform 0.5s ease;
  }
  .step.visible { opacity: 1; transform: translateX(0); }
  .step-num {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 3.5rem;
    line-height: 1;
    color: rgba(245,230,66,0.15);
    min-width: 60px;
  }
  .step-body h3 {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1.15rem;
    margin-bottom: 8px;
  }
  .step-body p { color: var(--muted); font-size: 0.92rem; line-height: 1.6; }
  .how-visual {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 24px;
    padding: 48px;
    display: flex;
    flex-direction: column;
    gap: 16px;
  }
  .chat-bubble {
    padding: 14px 20px;
    border-radius: 16px;
    font-size: 0.88rem;
    line-height: 1.5;
    max-width: 80%;
    animation: fadeUp 0.5s ease both;
  }
  .bubble-user {
    background: var(--accent);
    color: var(--bg);
    align-self: flex-end;
    border-bottom-right-radius: 4px;
    font-weight: 500;
  }
  .bubble-agent {
    background: rgba(255,255,255,0.06);
    border: 1px solid var(--border);
    color: var(--text);
    border-bottom-left-radius: 4px;
  }
  .bubble-status {
    display: flex;
    align-items: center;
    gap: 10px;
    background: rgba(58,245,180,0.08);
    border: 1px solid rgba(58,245,180,0.2);
    color: var(--accent3);
    padding: 12px 18px;
    border-radius: 12px;
    font-size: 0.82rem;
    font-weight: 500;
  }
  .status-dot { width:8px;height:8px;background:var(--accent3);border-radius:50%;animation:pulse 2s infinite; }

  /* CATEGORIES */
  .categories-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 16px;
    margin-top: 56px;
  }
  .cat-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 28px 24px;
    cursor: pointer;
    transition: border-color 0.2s, transform 0.2s, background 0.2s;
    position: relative;
    overflow: hidden;
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.4s ease, transform 0.4s ease, border-color 0.2s, background 0.2s;
  }
  .cat-card.visible { opacity: 1; transform: translateY(0); }
  .cat-card:hover { border-color: rgba(245,230,66,0.3); background: rgba(245,230,66,0.03); transform: translateY(-4px); }
  .cat-icon {
    font-size: 2rem;
    margin-bottom: 16px;
    display: block;
  }
  .cat-name {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1rem;
    margin-bottom: 6px;
  }
  .cat-count {
    font-size: 0.78rem;
    color: var(--muted);
  }
  .cat-badge {
    position: absolute;
    top: 16px; right: 16px;
    background: rgba(245,230,66,0.12);
    color: var(--accent);
    font-size: 0.65rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    padding: 4px 10px;
    border-radius: 100px;
  }

  /* PRICING */
  .pricing { background: var(--surface); }
  .pricing-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 56px;
  }
  .price-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 24px;
    padding: 40px 32px;
    position: relative;
    transition: transform 0.2s;
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.5s ease, transform 0.5s ease;
  }
  .price-card.visible { opacity: 1; transform: translateY(0); }
  .price-card:hover { transform: translateY(-6px); }
  .price-card.featured {
    border-color: rgba(245,230,66,0.4);
    background: linear-gradient(160deg, rgba(245,230,66,0.06) 0%, var(--card-bg) 60%);
  }
  .featured-badge {
    position: absolute;
    top: -12px; left: 50%;
    transform: translateX(-50%);
    background: var(--accent);
    color: var(--bg);
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.72rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 4px 16px;
    border-radius: 100px;
  }
  .plan-name {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.88rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 16px;
  }
  .plan-price {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 3rem;
    letter-spacing: -0.04em;
    line-height: 1;
    margin-bottom: 4px;
  }
  .plan-price sup { font-size: 1.2rem; vertical-align: super; }
  .plan-price sub { font-size: 0.9rem; color: var(--muted); font-weight: 400; }
  .plan-desc { font-size: 0.85rem; color: var(--muted); margin-bottom: 32px; }
  .plan-features { list-style: none; margin-bottom: 36px; }
  .plan-features li {
    font-size: 0.88rem;
    padding: 8px 0;
    border-bottom: 1px solid var(--border);
    display: flex;
    gap: 10px;
    align-items: center;
  }
  .plan-features li::before { content: '✓'; color: var(--accent3); font-weight: 700; min-width: 16px; }
  .plan-features li.dimmed::before { content: '–'; color: var(--muted); }
  .plan-features li.dimmed { color: var(--muted); }
  .btn-plan {
    width: 100%;
    padding: 14px;
    border-radius: 100px;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.9rem;
    border: none;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .btn-plan-outline {
    background: transparent;
    border: 1px solid var(--border);
    color: var(--text);
  }
  .btn-plan-outline:hover { border-color: rgba(255,255,255,0.2); background: rgba(255,255,255,0.04); }
  .btn-plan-fill {
    background: var(--accent);
    color: var(--bg);
  }
  .btn-plan-fill:hover { transform: translateY(-2px); box-shadow: 0 8px 28px rgba(245,230,66,0.3); }

  /* TESTIMONIALS */
  .testi-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 56px;
  }
  .testi-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 32px;
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.5s ease, transform 0.5s ease;
  }
  .testi-card.visible { opacity: 1; transform: translateY(0); }
  .stars { color: var(--accent); font-size: 0.85rem; margin-bottom: 16px; letter-spacing: 2px; }
  .testi-text { font-size: 0.92rem; line-height: 1.7; color: var(--text); margin-bottom: 24px; }
  .testi-author { display: flex; align-items: center; gap: 12px; }
  .testi-avatar {
    width: 40px; height: 40px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 0.9rem;
  }
  .testi-name { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 0.88rem; }
  .testi-role { font-size: 0.75rem; color: var(--muted); }

  /* SUBMIT FORM */
  .submit-section { background: var(--surface2); }
  .form-wrap {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: start;
    margin-top: 60px;
  }
  .problem-form { display: flex; flex-direction: column; gap: 16px; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .form-group { display: flex; flex-direction: column; gap: 8px; }
  .form-group label { font-size: 0.78rem; font-weight: 500; letter-spacing: 0.06em; text-transform: uppercase; color: var(--muted); }
  .form-control {
    background: rgba(255,255,255,0.04);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 14px 18px;
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.92rem;
    outline: none;
    transition: border-color 0.2s, background 0.2s;
    resize: none;
  }
  .form-control::placeholder { color: var(--muted); }
  .form-control:focus { border-color: rgba(245,230,66,0.4); background: rgba(245,230,66,0.03); }
  select.form-control option { background: var(--surface2); }
  .submit-btn {
    background: var(--accent);
    color: var(--bg);
    padding: 16px;
    border-radius: 12px;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1rem;
    border: none;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
    margin-top: 8px;
  }
  .submit-btn:hover { transform: translateY(-2px); box-shadow: 0 10px 32px rgba(245,230,66,0.3); }
  .trust-items { display: flex; flex-direction: column; gap: 24px; }
  .trust-item {
    display: flex;
    gap: 20px;
    align-items: flex-start;
    padding: 24px;
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 16px;
  }
  .trust-icon {
    width: 48px; height: 48px;
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.4rem;
    flex-shrink: 0;
  }
  .trust-body h4 { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 0.95rem; margin-bottom: 4px; }
  .trust-body p { font-size: 0.83rem; color: var(--muted); line-height: 1.5; }

  /* FOOTER */
  footer {
    background: var(--surface);
    border-top: 1px solid var(--border);
    padding: 60px;
  }
  .footer-inner {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 48px;
    margin-bottom: 48px;
  }
  .footer-brand p { font-size: 0.85rem; color: var(--muted); line-height: 1.6; margin-top: 12px; max-width: 280px; }
  .footer-col h5 { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 0.82rem; letter-spacing: 0.1em; text-transform: uppercase; color: var(--muted); margin-bottom: 16px; }
  .footer-col ul { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  .footer-col ul a { color: var(--text); text-decoration: none; font-size: 0.88rem; transition: color 0.2s; }
  .footer-col ul a:hover { color: var(--accent); }
  .footer-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 32px;
    border-top: 1px solid var(--border);
    font-size: 0.8rem;
    color: var(--muted);
  }

  /* Success modal */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.8);
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.3s;
  }
  .modal-overlay.active { opacity: 1; pointer-events: all; }
  .modal-box {
    background: var(--surface2);
    border: 1px solid rgba(245,230,66,0.3);
    border-radius: 24px;
    padding: 48px;
    max-width: 440px;
    width: 90%;
    text-align: center;
    transform: translateY(20px);
    transition: transform 0.3s;
  }
  .modal-overlay.active .modal-box { transform: translateY(0); }
  .modal-icon { font-size: 3rem; margin-bottom: 16px; }
  .modal-box h3 { font-family: 'Syne', sans-serif; font-weight: 800; font-size: 1.5rem; margin-bottom: 12px; }
  .modal-box p { color: var(--muted); font-size: 0.92rem; line-height: 1.6; margin-bottom: 28px; }
  .modal-close {
    background: var(--accent);
    color: var(--bg);
    padding: 12px 32px;
    border-radius: 100px;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    border: none;
    cursor: pointer;
    font-size: 0.9rem;
  }

  @media (max-width: 900px) {
    nav { padding: 20px 28px; }
    nav ul { display: none; }
    .hero { padding: 100px 28px 60px; }
    section { padding: 70px 28px; }
    .how-grid, .form-wrap { grid-template-columns: 1fr; gap: 40px; }
    .pricing-grid, .testi-grid { grid-template-columns: 1fr; }
    .hero-stats { flex-wrap: wrap; gap: 28px; }
    .footer-inner { grid-template-columns: 1fr 1fr; }
    footer { padding: 40px 28px; }
    .form-row { grid-template-columns: 1fr; }
    body { cursor: auto; }
    .cursor, .cursor-ring { display: none; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav>
  <a href="#" class="logo">Fix<span>r</span></a>
  <ul>
    <li><a href="#how">How it works</a></li>
    <li><a href="#categories">Services</a></li>
    <li><a href="#pricing">Pricing</a></li>
    <li><a href="#submit">Submit Problem</a></li>
    <li><a href="#submit" class="nav-cta">Get Help Now</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="hero-content">
    <div class="hero-tag">Live Problem Solvers · Real Results</div>
    <h1>Your Problem<br>Solved — <em>Fast</em></h1>
    <p class="hero-sub">From tech headaches to legal paperwork, financial confusion to home repairs — our vetted experts handle your toughest everyday problems so you can get back to living.</p>
    <div class="hero-actions">
      <a href="#submit" class="btn-primary">Describe Your Problem</a>
      <a href="#how" class="btn-ghost">See How It Works</a>
    </div>
    <div class="hero-stats">
      <div>
        <div class="stat-val">12<span>k+</span></div>
        <div class="stat-label">Problems Solved</div>
      </div>
      <div>
        <div class="stat-val">98<span>%</span></div>
        <div class="stat-label">Satisfaction Rate</div>
      </div>
      <div>
        <div class="stat-val">&lt;2<span>h</span></div>
        <div class="stat-label">Avg Response Time</div>
      </div>
      <div>
        <div class="stat-val">340<span>+</span></div>
        <div class="stat-label">Expert Solvers</div>
      </div>
    </div>
  </div>
</section>

<!-- TICKER -->
<div class="ticker">
  <div class="ticker-track" id="ticker">
    <span class="ticker-item">Tech Support <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Legal Help <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Financial Advice <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Home Repairs <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Tax Filing <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Career Help <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Health Queries <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Immigration Forms <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Visa Assistance <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Business Setup <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Tech Support <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Legal Help <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Financial Advice <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Home Repairs <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Tax Filing <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Career Help <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Health Queries <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Immigration Forms <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Visa Assistance <span class="ticker-sep">·</span></span>
    <span class="ticker-item">Business Setup <span class="ticker-sep">·</span></span>
  </div>
</div>

<!-- HOW IT WORKS -->
<section class="how" id="how">
  <div class="section-tag">Process</div>
  <div class="how-grid">
    <div>
      <h2 class="section-title">Three steps from<br>chaos to solved</h2>
      <p class="section-sub" style="margin-bottom:48px;">We've removed all the friction. Tell us what's wrong, we match you with the right expert, and you get results — guaranteed.</p>
      <div class="step" data-anim>
        <div class="step-num">01</div>
        <div class="step-body">
          <h3>Describe Your Problem</h3>
          <p>Submit a quick description in plain language. No jargon needed — just tell us what's bothering you and when you need it resolved.</p>
        </div>
      </div>
      <div class="step" data-anim>
        <div class="step-num">02</div>
        <div class="step-body">
          <h3>Get Matched Instantly</h3>
          <p>Our system routes your request to the most qualified solver available. You'll see their profile, rating, and estimated resolution time.</p>
        </div>
      </div>
      <div class="step" data-anim>
        <div class="step-num">03</div>
        <div class="step-body">
          <h3>Problem Solved, You Pay</h3>
          <p>Only pay when your problem is resolved to your satisfaction. Fixed flat fees — no hourly surprises, no hidden costs.</p>
        </div>
      </div>
    </div>
    <div class="how-visual">
      <div style="font-family:'Syne',sans-serif;font-weight:700;font-size:0.78rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--muted);margin-bottom:8px;">Live Session Preview</div>
      <div class="chat-bubble bubble-user" style="animation-delay:0.2s">My laptop keeps disconnecting from WiFi every 20 mins. It's driving me crazy!</div>
      <div class="chat-bubble bubble-agent" style="animation-delay:0.5s">Got it! This sounds like a driver issue or power management setting. I can fix this remotely in about 15 minutes. ⚡</div>
      <div class="chat-bubble bubble-user" style="animation-delay:0.8s">How much will it cost?</div>
      <div class="chat-bubble bubble-agent" style="animation-delay:1.1s">This falls under our Tech Fix plan — flat $19. No charge if I can't resolve it within 30 min.</div>
      <div class="bubble-status" style="animation-delay:1.4s">
        <span class="status-dot"></span>
        Expert connected · Resolution in progress
      </div>
      <div style="display:flex;gap:12px;margin-top:8px;">
        <div style="flex:1;background:rgba(58,245,180,0.08);border:1px solid rgba(58,245,180,0.15);border-radius:12px;padding:14px;text-align:center;">
          <div style="font-family:'Syne',sans-serif;font-weight:800;color:var(--accent3);font-size:1.3rem;">✓</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:4px;">Problem Solved</div>
        </div>
        <div style="flex:1;background:rgba(245,230,66,0.06);border:1px solid rgba(245,230,66,0.15);border-radius:12px;padding:14px;text-align:center;">
          <div style="font-family:'Syne',sans-serif;font-weight:800;color:var(--accent);font-size:1.3rem;">$19</div>
          <div style="font-size:0.75rem;color:var(--muted);margin-top:4px;">Flat Fee</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CATEGORIES -->
<section id="categories">
  <div class="section-tag">Services</div>
  <h2 class="section-title">Every problem has<br>an expert here</h2>
  <p class="section-sub">From the urgent to the complex — we've got specialists for every category of life's headaches.</p>
  <div class="categories-grid">
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">💻</span>
      <div class="cat-name">Tech Support</div>
      <div class="cat-count">94 experts · from $19</div>
      <div class="cat-badge">Popular</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">⚖️</span>
      <div class="cat-name">Legal Help</div>
      <div class="cat-count">47 experts · from $49</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">💰</span>
      <div class="cat-name">Finance & Tax</div>
      <div class="cat-count">63 experts · from $35</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">🏠</span>
      <div class="cat-name">Home Repairs</div>
      <div class="cat-count">112 experts · from $29</div>
      <div class="cat-badge">Popular</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">🩺</span>
      <div class="cat-name">Health Queries</div>
      <div class="cat-count">38 experts · from $39</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">✈️</span>
      <div class="cat-name">Visa & Immigration</div>
      <div class="cat-count">29 experts · from $59</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">🚀</span>
      <div class="cat-name">Business Setup</div>
      <div class="cat-count">51 experts · from $79</div>
    </div>
    <div class="cat-card" data-anim-card>
      <span class="cat-icon">📝</span>
      <div class="cat-name">Career & Resume</div>
      <div class="cat-count">76 experts · from $29</div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section class="pricing" id="pricing">
  <div class="section-tag">Pricing</div>
  <h2 class="section-title">Simple, flat pricing.<br>No surprises.</h2>
  <p class="section-sub">Pay only when your problem is solved. Choose a plan or pay per problem — your call.</p>
  <div class="pricing-grid">
    <div class="price-card" data-anim-price>
      <div class="plan-name">Starter</div>
      <div class="plan-price"><sup>$</sup>0<sub>/mo</sub></div>
      <div class="plan-desc">Pay as you go — perfect for one-off problems</div>
      <ul class="plan-features">
        <li>1 problem at a time</li>
        <li>Standard response (4h)</li>
        <li>Text-based support</li>
        <li class="dimmed">Priority matching</li>
        <li class="dimmed">Video/screen share</li>
        <li class="dimmed">Problem history</li>
      </ul>
      <button class="btn-plan btn-plan-outline" onclick="document.getElementById('submit').scrollIntoView({behavior:'smooth'})">Get Started Free</button>
    </div>
    <div class="price-card featured" data-anim-price>
      <div class="featured-badge">Most Popular</div>
      <div class="plan-name">Pro</div>
      <div class="plan-price"><sup>$</sup>29<sub>/mo</sub></div>
      <div class="plan-desc">Unlimited submissions with priority access</div>
      <ul class="plan-features">
        <li>Unlimited submissions</li>
        <li>Priority response (&lt;2h)</li>
        <li>Text + video support</li>
        <li>Priority matching</li>
        <li>Screen share sessions</li>
        <li>Full problem history</li>
      </ul>
      <button class="btn-plan btn-plan-fill" onclick="document.getElementById('submit').scrollIntoView({behavior:'smooth'})">Start Pro Trial</button>
    </div>
    <div class="price-card" data-anim-price>
      <div class="plan-name">Business</div>
      <div class="plan-price"><sup>$</sup>99<sub>/mo</sub></div>
      <div class="plan-desc">For teams and growing companies</div>
      <ul class="plan-features">
        <li>5 team members</li>
        <li>Instant response (&lt;30m)</li>
        <li>Dedicated account manager</li>
        <li>API access</li>
        <li>White-glove onboarding</li>
        <li>Custom SLAs</li>
      </ul>
      <button class="btn-plan btn-plan-outline" onclick="document.getElementById('submit').scrollIntoView({behavior:'smooth'})">Contact Sales</button>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials">
  <div class="section-tag">Social Proof</div>
  <h2 class="section-title">People who stopped<br>stressing, started living</h2>
  <div class="testi-grid">
    <div class="testi-card" data-anim-testi>
      <div class="stars">★★★★★</div>
      <p class="testi-text">"Got my visa renewal sorted in one session. The expert knew exactly which forms to fill and caught three errors I had made. Worth every penny."</p>
      <div class="testi-author">
        <div class="testi-avatar" style="background:rgba(245,230,66,0.15);color:var(--accent);">SA</div>
        <div>
          <div class="testi-name">Sara Ahmed</div>
          <div class="testi-role">Freelance Designer, Dubai</div>
        </div>
      </div>
    </div>
    <div class="testi-card" data-anim-testi>
      <div class="stars">★★★★★</div>
      <p class="testi-text">"My laptop issue had been going on for 3 weeks. Fixr resolved it in 12 minutes. I'm not even exaggerating. The screen share session was seamless."</p>
      <div class="testi-author">
        <div class="testi-avatar" style="background:rgba(58,245,180,0.12);color:var(--accent3);">MK</div>
        <div>
          <div class="testi-name">Marcus K.</div>
          <div class="testi-role">Startup Founder, London</div>
        </div>
      </div>
    </div>
    <div class="testi-card" data-anim-testi>
      <div class="stars">★★★★★</div>
      <p class="testi-text">"Used Fixr to set up my LLC. The business advisor walked me through everything step by step. What would've taken weeks at a law firm took 2 hours here."</p>
      <div class="testi-author">
        <div class="testi-avatar" style="background:rgba(255,94,58,0.12);color:var(--accent2);">PR</div>
        <div>
          <div class="testi-name">Priya R.</div>
          <div class="testi-role">E-commerce Owner, Toronto</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SUBMIT PROBLEM -->
<section class="submit-section" id="submit">
  <div class="section-tag">Get Help</div>
  <h2 class="section-title">Submit your problem.<br>Get it solved today.</h2>
  <div class="form-wrap">
    <div class="problem-form">
      <div class="form-row">
        <div class="form-group">
          <label>Your Name</label>
          <input type="text" class="form-control" placeholder="John Doe" id="f-name">
        </div>
        <div class="form-group">
          <label>Email</label>
          <input type="email" class="form-control" placeholder="you@email.com" id="f-email">
        </div>
      </div>
      <div class="form-group">
        <label>Problem Category</label>
        <select class="form-control" id="f-cat">
          <option value="">Select a category...</option>
          <option>💻 Tech Support</option>
          <option>⚖️ Legal Help</option>
          <option>💰 Finance & Tax</option>
          <option>🏠 Home Repairs</option>
          <option>🩺 Health Queries</option>
          <option>✈️ Visa & Immigration</option>
          <option>🚀 Business Setup</option>
          <option>📝 Career & Resume</option>
          <option>🔧 Other</option>
        </select>
      </div>
      <div class="form-group">
        <label>Urgency</label>
        <select class="form-control" id="f-urgency">
          <option>ASAP (within 2 hours)</option>
          <option>Today (within 8 hours)</option>
          <option>This week</option>
          <option>Flexible</option>
        </select>
      </div>
      <div class="form-group">
        <label>Describe Your Problem</label>
        <textarea class="form-control" rows="5" placeholder="Tell us what's going on in plain language. The more detail, the faster we can help..." id="f-desc"></textarea>
      </div>
      <button class="submit-btn" onclick="handleSubmit()">→ Submit & Get Matched Now</button>
    </div>
    <div class="trust-items">
      <div class="trust-item">
        <div class="trust-icon" style="background:rgba(245,230,66,0.1);">🔒</div>
        <div class="trust-body">
          <h4>100% Confidential</h4>
          <p>Your problem details are encrypted and only shared with your assigned expert. We never sell your data.</p>
        </div>
      </div>
      <div class="trust-item">
        <div class="trust-icon" style="background:rgba(58,245,180,0.1);">✅</div>
        <div class="trust-body">
          <h4>Satisfaction Guarantee</h4>
          <p>If your problem isn't resolved to your satisfaction, you pay nothing. Zero risk, all reward.</p>
        </div>
      </div>
      <div class="trust-item">
        <div class="trust-icon" style="background:rgba(255,94,58,0.1);">⚡</div>
        <div class="trust-body">
          <h4>Vetted Experts Only</h4>
          <p>Every solver passes a rigorous background check and skills assessment before joining our network.</p>
        </div>
      </div>
      <div class="trust-item">
        <div class="trust-icon" style="background:rgba(130,100,255,0.1);">💳</div>
        <div class="trust-body">
          <h4>Secure Payments</h4>
          <p>Payments are held in escrow until your problem is solved. Stripe-powered, bank-level security.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-brand">
      <a href="#" class="logo">Fix<span>r</span></a>
      <p>Real experts solving real problems for real people — fast, fairly priced, and guaranteed.</p>
    </div>
    <div class="footer-col">
      <h5>Services</h5>
      <ul>
        <li><a href="#">Tech Support</a></li>
        <li><a href="#">Legal Help</a></li>
        <li><a href="#">Finance & Tax</a></li>
        <li><a href="#">Home Repairs</a></li>
        <li><a href="#">All Categories</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Company</h5>
      <ul>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Become an Expert</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Careers</a></li>
        <li><a href="#">Press</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Support</h5>
      <ul>
        <li><a href="#">Help Center</a></li>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
        <li><a href="#">Refund Policy</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2025 Fixr. All rights reserved.</span>
    <span>Built for people who have better things to do.</span>
  </div>
</footer>

<!-- SUCCESS MODAL -->
<div class="modal-overlay" id="modal">
  <div class="modal-box">
    <div class="modal-icon">🎯</div>
    <h3>Problem Received!</h3>
    <p>We're matching you with the best available expert right now. You'll get a confirmation email within 5 minutes with your expert's profile and estimated resolution time.</p>
    <button class="modal-close" onclick="closeModal()">Got it, thanks!</button>
  </div>
</div>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; cursor.style.left = mx+'px'; cursor.style.top = my+'px'; });
  function animRing() { rx += (mx-rx)*0.12; ry += (my-ry)*0.12; ring.style.left = rx+'px'; ring.style.top = ry+'px'; requestAnimationFrame(animRing); }
  animRing();
  document.querySelectorAll('a,button,[data-anim-card]').forEach(el => {
    el.addEventListener('mouseenter', () => { cursor.style.width='20px'; cursor.style.height='20px'; ring.style.width='54px'; ring.style.height='54px'; });
    el.addEventListener('mouseleave', () => { cursor.style.width='12px'; cursor.style.height='12px'; ring.style.width='38px'; ring.style.height='38px'; });
  });

  // Intersection observer for animations
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        const delay = entry.target.dataset.delay || 0;
        setTimeout(() => entry.target.classList.add('visible'), delay);
      }
    });
  }, { threshold: 0.15 });

  document.querySelectorAll('.step[data-anim]').forEach((el, i) => {
    el.dataset.delay = i * 120;
    observer.observe(el);
  });
  document.querySelectorAll('.cat-card[data-anim-card]').forEach((el, i) => {
    el.dataset.delay = i * 80;
    observer.observe(el);
  });
  document.querySelectorAll('.price-card[data-anim-price]').forEach((el, i) => {
    el.dataset.delay = i * 120;
    observer.observe(el);
  });
  document.querySelectorAll('.testi-card[data-anim-testi]').forEach((el, i) => {
    el.dataset.delay = i * 100;
    observer.observe(el);
  });

  // Form submit
  function handleSubmit() {
    const name = document.getElementById('f-name').value.trim();
    const email = document.getElementById('f-email').value.trim();
    const cat = document.getElementById('f-cat').value;
    const desc = document.getElementById('f-desc').value.trim();
    if (!name || !email || !cat || !desc) {
      alert('Please fill in all required fields before submitting.');
      return;
    }
    document.getElementById('modal').classList.add('active');
  }

  function closeModal() {
    document.getElementById('modal').classList.remove('active');
    ['f-name','f-email','f-desc'].forEach(id => document.getElementById(id).value = '');
    document.getElementById('f-cat').value = '';
  }

  document.getElementById('modal').addEventListener('click', function(e) {
    if (e.target === this) closeModal();
  });
</script>
</body>
</html>
