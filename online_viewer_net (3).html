<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Stackabilli Entertainment</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #facc15;
    --gold-dark: #b8860b;
    --deep: #0a0a0a;
    --surface: #111111;
    --surface2: #1a1a1a;
    --text: #f0f0f0;
    --muted: #888;
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--deep);
    color: var(--text);
    font-family: 'Outfit', sans-serif;
    overflow-x: hidden;
    cursor: none;
  }

  /* CUSTOM CURSOR */
  .cursor {
    position: fixed;
    width: 12px; height: 12px;
    background: var(--gold);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transform: translate(-50%, -50%);
    transition: transform 0.1s, width 0.3s, height 0.3s, opacity 0.3s;
    mix-blend-mode: difference;
  }
  .cursor-ring {
    position: fixed;
    width: 40px; height: 40px;
    border: 1px solid rgba(250,204,21,0.5);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transform: translate(-50%, -50%);
    transition: transform 0.15s ease-out, width 0.3s, height 0.3s;
  }
  body:hover .cursor { opacity: 1; }

  /* LASER LIGHTS CANVAS */
  #laserCanvas {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    pointer-events: none;
    z-index: 1;
    opacity: 0.15;
  }

  /* NOISE TEXTURE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 2;
    opacity: 0.4;
  }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 1.5rem 4rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: background 0.4s, backdrop-filter 0.4s;
  }
  nav.scrolled {
    background: rgba(10,10,10,0.92);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(250,204,21,0.1);
  }
  .nav-logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 2rem;
    letter-spacing: 0.15em;
    color: var(--gold);
    text-decoration: none;
    position: relative;
  }
  .nav-logo::after {
    content: '';
    position: absolute;
    bottom: -4px; left: 0; right: 0;
    height: 2px;
    background: var(--gold);
    transform: scaleX(0);
    transition: transform 0.3s;
  }
  .nav-logo:hover::after { transform: scaleX(1); }

  .nav-links {
    display: flex;
    gap: 3rem;
    list-style: none;
  }
  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.85rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    font-weight: 500;
    transition: color 0.3s;
    position: relative;
  }
  .nav-links a::after {
    content: '';
    position: absolute;
    bottom: -4px; left: 0;
    width: 0; height: 1px;
    background: var(--gold);
    transition: width 0.3s;
  }
  .nav-links a:hover { color: var(--gold); }
  .nav-links a:hover::after { width: 100%; }

  .nav-cta {
    background: var(--gold);
    color: #000;
    font-family: 'Outfit', sans-serif;
    font-weight: 700;
    font-size: 0.8rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 0.75rem 2rem;
    border: none;
    cursor: none;
    transition: background 0.3s, transform 0.2s, box-shadow 0.3s;
    clip-path: polygon(8px 0%, 100% 0%, calc(100% - 8px) 100%, 0% 100%);
  }
  .nav-cta:hover {
    background: #fff;
    transform: translateY(-2px);
    box-shadow: 0 8px 30px rgba(250,204,21,0.4);
  }

  /* HERO */
  .hero {
    position: relative;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    overflow: hidden;
    z-index: 5;
  }

  /* BG VIDEO PLACEHOLDER / ANIMATED GRADIENT */
  .hero-bg {
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse 80% 60% at 50% 110%, rgba(250,204,21,0.12) 0%, transparent 70%),
      radial-gradient(ellipse 40% 40% at 20% 50%, rgba(139,0,255,0.08) 0%, transparent 60%),
      radial-gradient(ellipse 40% 40% at 80% 30%, rgba(255,50,50,0.06) 0%, transparent 60%),
      #0a0a0a;
    animation: bgPulse 8s ease-in-out infinite alternate;
  }
  @keyframes bgPulse {
    from { opacity: 0.8; }
    to { opacity: 1; }
  }

  /* SCANLINE */
  .hero::before {
    content: '';
    position: absolute;
    inset: 0;
    background: repeating-linear-gradient(
      0deg,
      transparent,
      transparent 2px,
      rgba(0,0,0,0.03) 2px,
      rgba(0,0,0,0.03) 4px
    );
    pointer-events: none;
    z-index: 2;
  }

  /* DISCO SPOTLIGHTS */
  .spotlight {
    position: absolute;
    border-radius: 50%;
    filter: blur(80px);
    animation: spotMove 6s ease-in-out infinite;
    pointer-events: none;
  }
  .spotlight-1 {
    width: 600px; height: 600px;
    background: rgba(250,204,21,0.07);
    top: -200px; left: -100px;
    animation-delay: 0s;
  }
  .spotlight-2 {
    width: 500px; height: 500px;
    background: rgba(139,0,255,0.07);
    top: -150px; right: -100px;
    animation-delay: -2s;
  }
  .spotlight-3 {
    width: 400px; height: 400px;
    background: rgba(255,50,50,0.05);
    bottom: 0; left: 30%;
    animation-delay: -4s;
  }
  @keyframes spotMove {
    0%, 100% { transform: translate(0, 0) scale(1); }
    33% { transform: translate(60px, 40px) scale(1.1); }
    66% { transform: translate(-40px, 20px) scale(0.9); }
  }

  .hero-eyebrow {
    font-size: 0.75rem;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.5rem;
    position: relative;
    z-index: 5;
    opacity: 0;
    transform: translateY(20px);
    animation: fadeUp 0.8s ease forwards 0.3s;
  }
  .hero-eyebrow span {
    display: inline-block;
    padding: 0.4rem 1.5rem;
    border: 1px solid rgba(250,204,21,0.3);
    background: rgba(250,204,21,0.05);
  }

  .hero-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(4rem, 12vw, 10rem);
    line-height: 0.9;
    letter-spacing: 0.02em;
    position: relative;
    z-index: 5;
    opacity: 0;
    transform: translateY(30px);
    animation: fadeUp 0.9s ease forwards 0.5s;
  }
  .hero-title .line-gold { color: var(--gold); }
  .hero-title .line-outline {
    -webkit-text-stroke: 2px rgba(250,204,21,0.5);
    color: transparent;
  }

  .hero-sub {
    margin-top: 1.5rem;
    font-size: 1.1rem;
    color: var(--muted);
    font-weight: 300;
    max-width: 480px;
    line-height: 1.7;
    position: relative;
    z-index: 5;
    opacity: 0;
    animation: fadeUp 0.9s ease forwards 0.8s;
  }

  .hero-actions {
    display: flex;
    gap: 1.5rem;
    margin-top: 3rem;
    position: relative;
    z-index: 5;
    opacity: 0;
    animation: fadeUp 0.9s ease forwards 1s;
  }

  .btn-primary {
    background: var(--gold);
    color: #000;
    font-weight: 700;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 1rem 2.5rem;
    border: none;
    cursor: none;
    transition: all 0.3s;
    clip-path: polygon(10px 0%, 100% 0%, calc(100% - 10px) 100%, 0% 100%);
    position: relative;
    overflow: hidden;
  }
  .btn-primary::before {
    content: '';
    position: absolute;
    inset: 0;
    background: rgba(255,255,255,0.2);
    transform: translateX(-100%) skewX(-15deg);
    transition: transform 0.4s;
  }
  .btn-primary:hover::before { transform: translateX(200%) skewX(-15deg); }
  .btn-primary:hover { box-shadow: 0 0 40px rgba(250,204,21,0.5); transform: translateY(-3px); }

  .btn-outline {
    background: transparent;
    color: var(--gold);
    font-weight: 600;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 1rem 2.5rem;
    border: 1px solid rgba(250,204,21,0.4);
    cursor: none;
    transition: all 0.3s;
  }
  .btn-outline:hover {
    background: rgba(250,204,21,0.08);
    border-color: var(--gold);
    box-shadow: 0 0 20px rgba(250,204,21,0.15), inset 0 0 20px rgba(250,204,21,0.05);
  }

  /* SCROLL INDICATOR */
  .scroll-hint {
    position: absolute;
    bottom: 3rem;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    color: var(--muted);
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    z-index: 5;
    opacity: 0;
    animation: fadeUp 1s ease forwards 1.4s;
  }
  .scroll-line {
    width: 1px;
    height: 50px;
    background: linear-gradient(to bottom, var(--gold), transparent);
    animation: scrollDrop 2s ease-in-out infinite;
  }
  @keyframes scrollDrop {
    0% { transform: scaleY(0); transform-origin: top; opacity: 1; }
    50% { transform: scaleY(1); transform-origin: top; opacity: 1; }
    100% { transform: scaleY(1); transform-origin: bottom; opacity: 0; }
  }

  /* TICKER */
  .ticker {
    position: relative;
    z-index: 10;
    background: var(--gold);
    color: #000;
    padding: 0.75rem 0;
    overflow: hidden;
    white-space: nowrap;
  }
  .ticker-track {
    display: inline-flex;
    animation: tickerScroll 20s linear infinite;
  }
  .ticker-item {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1rem;
    letter-spacing: 0.15em;
    padding: 0 3rem;
  }
  .ticker-dot {
    display: inline-block;
    width: 6px; height: 6px;
    background: rgba(0,0,0,0.3);
    border-radius: 50%;
    vertical-align: middle;
    margin: 0 1rem;
  }
  @keyframes tickerScroll {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }

  /* STATS BAR */
  .stats-bar {
    position: relative;
    z-index: 10;
    padding: 4rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1px;
    background: rgba(250,204,21,0.1);
    border-top: 1px solid rgba(250,204,21,0.1);
    border-bottom: 1px solid rgba(250,204,21,0.1);
  }
  .stat-item {
    background: var(--deep);
    padding: 2rem 3rem;
    text-align: center;
    transition: background 0.3s;
  }
  .stat-item:hover { background: #0f0f0f; }
  .stat-num {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 3.5rem;
    color: var(--gold);
    line-height: 1;
    display: block;
  }
  .stat-label {
    font-size: 0.75rem;
    color: var(--muted);
    letter-spacing: 0.15em;
    text-transform: uppercase;
    margin-top: 0.5rem;
  }

  /* SECTION COMMON */
  section {
    position: relative;
    z-index: 10;
  }
  .section-label {
    font-size: 0.7rem;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }
  .section-label::before {
    content: '';
    display: block;
    width: 30px; height: 1px;
    background: var(--gold);
  }
  .section-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(3rem, 6vw, 5.5rem);
    line-height: 0.95;
    letter-spacing: 0.02em;
  }
  .section-title .accent { color: var(--gold); }

  /* SERVICES */
  #services {
    padding: 8rem 4rem;
    background: var(--deep);
  }
  .services-header {
    max-width: 700px;
    margin-bottom: 5rem;
  }
  .services-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.05);
  }
  .service-card {
    background: var(--surface);
    padding: 3rem;
    position: relative;
    overflow: hidden;
    transition: background 0.4s;
    cursor: none;
  }
  .service-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(250,204,21,0.06) 0%, transparent 60%);
    opacity: 0;
    transition: opacity 0.4s;
  }
  .service-card:hover { background: var(--surface2); }
  .service-card:hover::before { opacity: 1; }

  .service-icon {
    font-size: 2.5rem;
    margin-bottom: 1.5rem;
    display: block;
    transition: transform 0.3s;
  }
  .service-card:hover .service-icon { transform: scale(1.2) rotate(-5deg); }

  .service-num {
    position: absolute;
    top: 2rem; right: 2rem;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 4rem;
    color: rgba(255,255,255,0.04);
    line-height: 1;
    transition: color 0.4s;
  }
  .service-card:hover .service-num { color: rgba(250,204,21,0.08); }

  .service-name {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1.8rem;
    letter-spacing: 0.05em;
    margin-bottom: 0.75rem;
  }
  .service-desc {
    font-size: 0.9rem;
    color: var(--muted);
    line-height: 1.7;
    margin-bottom: 2rem;
  }
  .service-link {
    font-size: 0.75rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--gold);
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    transition: gap 0.3s;
  }
  .service-link:hover { gap: 1rem; }
  .service-card-bar {
    position: absolute;
    bottom: 0; left: 0;
    height: 2px;
    background: var(--gold);
    width: 0;
    transition: width 0.4s ease;
  }
  .service-card:hover .service-card-bar { width: 100%; }

  /* PACKAGES */
  #packages {
    padding: 8rem 4rem;
    background: var(--surface);
  }
  .packages-header {
    text-align: center;
    max-width: 600px;
    margin: 0 auto 5rem;
  }
  .packages-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .package-card {
    background: var(--deep);
    padding: 3rem 2.5rem;
    position: relative;
    overflow: hidden;
    transition: transform 0.4s, box-shadow 0.4s;
    cursor: none;
    border: 1px solid rgba(255,255,255,0.05);
  }
  .package-card.featured {
    border: 1px solid var(--gold);
    background: #0d0d0d;
    transform: translateY(-8px);
  }
  .package-card:hover {
    transform: translateY(-12px);
    box-shadow: 0 30px 80px rgba(0,0,0,0.5);
  }
  .package-card.featured:hover {
    box-shadow: 0 30px 80px rgba(250,204,21,0.2);
  }
  .package-badge {
    display: inline-block;
    background: var(--gold);
    color: #000;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    padding: 0.3rem 0.8rem;
    margin-bottom: 1.5rem;
  }
  .package-tier {
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.3em;
    text-transform: uppercase;
    margin-bottom: 0.5rem;
  }
  .package-name {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 2.5rem;
    letter-spacing: 0.05em;
    margin-bottom: 1rem;
    color: var(--gold);
  }
  .package-price {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 3.5rem;
    line-height: 1;
    margin-bottom: 0.25rem;
  }
  .package-price-note {
    font-size: 0.75rem;
    color: var(--muted);
    margin-bottom: 2rem;
    padding-bottom: 2rem;
    border-bottom: 1px solid rgba(255,255,255,0.07);
  }
  .package-features {
    list-style: none;
    margin-bottom: 2.5rem;
  }
  .package-features li {
    font-size: 0.9rem;
    color: var(--muted);
    padding: 0.6rem 0;
    border-bottom: 1px solid rgba(255,255,255,0.04);
    display: flex;
    align-items: center;
    gap: 0.75rem;
  }
  .package-features li::before {
    content: '';
    display: block;
    width: 5px; height: 5px;
    background: var(--gold);
    border-radius: 50%;
    flex-shrink: 0;
  }
  .package-features li.inactive { opacity: 0.3; }
  .package-features li.inactive::before { background: var(--muted); }

  /* GALLERY STRIP */
  #gallery {
    padding: 6rem 0;
    overflow: hidden;
    background: var(--deep);
  }
  .gallery-header {
    padding: 0 4rem;
    margin-bottom: 3rem;
  }
  .gallery-track {
    display: flex;
    gap: 2px;
    animation: galleryScroll 30s linear infinite;
    width: max-content;
  }
  .gallery-track:hover { animation-play-state: paused; }
  .gallery-item {
    width: 320px;
    height: 220px;
    background: var(--surface2);
    overflow: hidden;
    position: relative;
    flex-shrink: 0;
    cursor: none;
  }
  .gallery-item .inner {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    transition: transform 0.5s;
  }
  .gallery-item:hover .inner { transform: scale(1.1); }
  .gallery-overlay {
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.5);
    display: flex;
    align-items: flex-end;
    padding: 1.5rem;
    opacity: 0;
    transition: opacity 0.3s;
  }
  .gallery-item:hover .gallery-overlay { opacity: 1; }
  .gallery-overlay span {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1.2rem;
    letter-spacing: 0.1em;
    color: var(--gold);
  }
  @keyframes galleryScroll {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }

  /* GALLERY COLORS */
  .g1 { background: linear-gradient(135deg, #1a0a00, #3d1f00); }
  .g2 { background: linear-gradient(135deg, #0a001a, #1f003d); }
  .g3 { background: linear-gradient(135deg, #001a0a, #003d1f); }
  .g4 { background: linear-gradient(135deg, #1a0000, #3d0000); }
  .g5 { background: linear-gradient(135deg, #00001a, #00003d); }
  .g6 { background: linear-gradient(135deg, #0f0a00, #2a1f00); }

  /* TESTIMONIALS */
  #testimonials {
    padding: 8rem 4rem;
    background: var(--surface);
  }
  .testimonials-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
    margin-top: 4rem;
  }
  .testimonial-card {
    background: var(--deep);
    border: 1px solid rgba(255,255,255,0.05);
    padding: 2.5rem;
    position: relative;
    transition: border-color 0.3s, transform 0.3s;
    cursor: none;
  }
  .testimonial-card:hover {
    border-color: rgba(250,204,21,0.3);
    transform: translateY(-4px);
  }
  .testimonial-card::before {
    content: '"';
    font-family: 'Bebas Neue', sans-serif;
    font-size: 8rem;
    color: rgba(250,204,21,0.06);
    position: absolute;
    top: -1rem; left: 1.5rem;
    line-height: 1;
  }
  .testimonial-stars {
    display: flex;
    gap: 3px;
    margin-bottom: 1.5rem;
  }
  .star { color: var(--gold); font-size: 0.9rem; }
  .testimonial-text {
    font-size: 0.95rem;
    color: #bbb;
    line-height: 1.8;
    margin-bottom: 2rem;
    font-style: italic;
  }
  .testimonial-author {
    display: flex;
    align-items: center;
    gap: 1rem;
  }
  .author-avatar {
    width: 44px; height: 44px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 0.9rem;
  }
  .author-name {
    font-weight: 600;
    font-size: 0.9rem;
  }
  .author-role {
    font-size: 0.75rem;
    color: var(--muted);
  }

  /* CTA */
  #cta {
    padding: 10rem 4rem;
    text-align: center;
    background: var(--deep);
    position: relative;
    overflow: hidden;
  }
  #cta::before {
    content: '';
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    width: 800px; height: 800px;
    background: radial-gradient(circle, rgba(250,204,21,0.06) 0%, transparent 70%);
    pointer-events: none;
  }
  .cta-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(3rem, 8vw, 7rem);
    line-height: 0.95;
    position: relative;
    z-index: 2;
  }
  .cta-sub {
    color: var(--muted);
    font-size: 1.1rem;
    max-width: 500px;
    margin: 2rem auto 3rem;
    position: relative;
    z-index: 2;
  }
  .cta-actions {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    position: relative;
    z-index: 2;
  }

  /* BOOKING MODAL */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.9);
    backdrop-filter: blur(10px);
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.4s;
  }
  .modal-overlay.active {
    opacity: 1;
    pointer-events: all;
  }
  .modal-box {
    background: var(--surface);
    border: 1px solid rgba(250,204,21,0.2);
    width: 600px;
    max-width: 90vw;
    max-height: 90vh;
    overflow-y: auto;
    padding: 3rem;
    position: relative;
    transform: translateY(40px) scale(0.95);
    transition: transform 0.4s ease;
  }
  .modal-overlay.active .modal-box {
    transform: translateY(0) scale(1);
  }
  .modal-close {
    position: absolute;
    top: 1.5rem; right: 1.5rem;
    background: none;
    border: 1px solid rgba(255,255,255,0.1);
    color: var(--muted);
    width: 36px; height: 36px;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.2rem;
    cursor: none;
    transition: border-color 0.3s, color 0.3s;
  }
  .modal-close:hover { border-color: var(--gold); color: var(--gold); }
  .modal-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 2.5rem;
    letter-spacing: 0.05em;
    margin-bottom: 0.5rem;
  }
  .modal-sub {
    color: var(--muted);
    font-size: 0.9rem;
    margin-bottom: 2.5rem;
  }
  .form-group {
    margin-bottom: 1.5rem;
  }
  .form-label {
    display: block;
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 0.5rem;
  }
  .form-input, .form-select, .form-textarea {
    width: 100%;
    background: var(--surface2);
    border: 1px solid rgba(255,255,255,0.07);
    color: var(--text);
    font-family: 'Outfit', sans-serif;
    font-size: 0.95rem;
    padding: 0.85rem 1rem;
    outline: none;
    transition: border-color 0.3s;
    cursor: none;
  }
  .form-input:focus, .form-select:focus, .form-textarea:focus {
    border-color: var(--gold);
    box-shadow: 0 0 0 3px rgba(250,204,21,0.08);
  }
  .form-select option { background: var(--surface2); }
  .form-textarea { min-height: 100px; resize: vertical; }
  .form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
  }
  .form-submit {
    width: 100%;
    background: var(--gold);
    color: #000;
    font-family: 'Outfit', sans-serif;
    font-weight: 700;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 1.1rem;
    border: none;
    cursor: none;
    margin-top: 1rem;
    transition: background 0.3s, transform 0.2s;
    position: relative;
    overflow: hidden;
  }
  .form-submit:hover { background: #fff; transform: translateY(-2px); }

  /* FOOTER */
  footer {
    background: var(--surface);
    border-top: 1px solid rgba(255,255,255,0.05);
    padding: 4rem;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 3rem;
    position: relative;
    z-index: 10;
  }
  .footer-brand .logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 2rem;
    letter-spacing: 0.15em;
    color: var(--gold);
    display: block;
    margin-bottom: 1rem;
  }
  .footer-brand p {
    font-size: 0.85rem;
    color: var(--muted);
    line-height: 1.7;
    max-width: 280px;
  }
  .footer-col h4 {
    font-size: 0.7rem;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.5rem;
  }
  .footer-col ul { list-style: none; }
  .footer-col ul li {
    margin-bottom: 0.75rem;
  }
  .footer-col ul li a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.85rem;
    transition: color 0.3s;
  }
  .footer-col ul li a:hover { color: var(--gold); }
  .footer-bottom {
    grid-column: 1 / -1;
    border-top: 1px solid rgba(255,255,255,0.05);
    padding-top: 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: var(--muted);
    font-size: 0.75rem;
  }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .reveal {
    opacity: 0;
    transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* BEAT VISUALIZER */
  .beat-viz {
    display: flex;
    align-items: flex-end;
    gap: 3px;
    height: 30px;
    margin-left: 1rem;
  }
  .beat-bar {
    width: 3px;
    background: var(--gold);
    border-radius: 2px;
    animation: beatPulse 0.8s ease-in-out infinite;
  }
  .beat-bar:nth-child(1) { animation-delay: 0s; height: 40%; }
  .beat-bar:nth-child(2) { animation-delay: 0.1s; height: 80%; }
  .beat-bar:nth-child(3) { animation-delay: 0.2s; height: 60%; }
  .beat-bar:nth-child(4) { animation-delay: 0.15s; height: 100%; }
  .beat-bar:nth-child(5) { animation-delay: 0.05s; height: 50%; }
  .beat-bar:nth-child(6) { animation-delay: 0.25s; height: 70%; }
  @keyframes beatPulse {
    0%, 100% { transform: scaleY(0.3); opacity: 0.5; }
    50% { transform: scaleY(1); opacity: 1; }
  }

  /* GLITCH TEXT */
  .glitch {
    position: relative;
  }
  .glitch::before, .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
    font-family: inherit;
    font-size: inherit;
    font-weight: inherit;
    color: inherit;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
  }
  .glitch::before {
    left: 2px;
    color: #ff0040;
    animation: glitch1 4s steps(1) infinite;
  }
  .glitch::after {
    left: -2px;
    color: #00ffff;
    clip-path: polygon(0 60%, 100% 60%, 100% 100%, 0 100%);
    animation: glitch2 4s steps(1) infinite;
  }
  @keyframes glitch1 {
    0%, 90%, 100% { clip-path: polygon(0 0, 100% 0, 100% 0%, 0 0%); }
    91% { clip-path: polygon(0 20%, 100% 20%, 100% 40%, 0 40%); transform: translate(3px, 0); }
    93% { clip-path: polygon(0 50%, 100% 50%, 100% 70%, 0 70%); transform: translate(-3px, 0); }
    95% { clip-path: polygon(0 0, 100% 0, 100% 0%, 0 0%); }
  }
  @keyframes glitch2 {
    0%, 90%, 100% { clip-path: polygon(0 0, 100% 0, 100% 0%, 0 0%); }
    92% { clip-path: polygon(0 60%, 100% 60%, 100% 80%, 0 80%); transform: translate(-2px, 0); }
    94% { clip-path: polygon(0 30%, 100% 30%, 100% 50%, 0 50%); transform: translate(2px, 0); }
    96% { clip-path: polygon(0 0, 100% 0, 100% 0%, 0 0%); }
  }

  /* SELECTED PACKAGE */
  .package-card.selected {
    border-color: var(--gold) !important;
    box-shadow: 0 0 40px rgba(250,204,21,0.2);
  }

  /* MOBILE */
  @media (max-width: 768px) {
    nav { padding: 1rem 1.5rem; }
    .nav-links { display: none; }
    .services-grid, .packages-grid, .testimonials-grid { grid-template-columns: 1fr; }
    .stats-bar { grid-template-columns: repeat(2, 1fr); }
    footer { grid-template-columns: 1fr; }
    .form-row { grid-template-columns: 1fr; }
    #services, #packages, #gallery, #testimonials, #cta { padding: 5rem 1.5rem; }
    .gallery-header { padding: 0 1.5rem; }
    .package-card.featured { transform: none; }
  }
</style>
</head>
<body>

<!-- CUSTOM CURSOR -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- LASER CANVAS -->
<canvas id="laserCanvas"></canvas>

<!-- NAV -->
<nav id="navbar">
  <a class="nav-logo" href="#">STACKABILLI ENTERTAINMENT</a>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#packages">Packages</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#testimonials">Reviews</a></li>
    <li><a href="#cta">Contact</a></li>
  </ul>
  <button class="nav-cta" onclick="openModal()">BOOK NOW</button>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="spotlight spotlight-1"></div>
  <div class="spotlight spotlight-2"></div>
  <div class="spotlight spotlight-3"></div>

  <div class="hero-eyebrow"><span>kenya's Premier Entertainment Agency</span></div>

  <h1 class="hero-title">
    <div class="glitch" data-text="TRANSFORM">TRANSFORM</div>
    <div class="line-outline">YOUR VENUE</div>
    <div class="line-gold">TONIGHT</div>
  </h1>
  
  <h1 class="hero-title"><div class="line-gold">"just the vibes."</div></h1>

  <p class="hero-sub">
    We bring the pulse, the lights, and the talent. Unforgettable nights crafted for clubs, events, and private gatherings across kenya.
  </p>

  <div class="hero-actions">
    <button class="btn-primary" onclick="openModal()">Book Your Event</button>
    <a href="#packages" class="btn-outline">View Packages</a>
  </div>

  <div class="scroll-hint">
    <div class="scroll-line"></div>
    <span>Scroll</span>
  </div>
</section>

<!-- TICKER -->
<div class="ticker">
  <div class="ticker-track" id="ticker">
    <span class="ticker-item">DJ BOOKINGS<span class="ticker-dot"></span></span>
    <span class="ticker-item">VIP EXPERIENCES<span class="ticker-dot"></span></span>
    <span class="ticker-item">LIVE PERFORMANCES<span class="ticker-dot"></span></span>
    <span class="ticker-item">DJ BOOKINGS<span class="ticker-dot"></span></span>
    <span class="ticker-item">VIP EXPERIENCES<span class="ticker-dot"></span></span>
    <span class="ticker-item">LIVE PERFORMANCES<span class="ticker-dot"></span></span>
    
  </div>
</div>

<!-- STATS -->
<div class="stats-bar">
  <div class="stat-item reveal">
    <span class="stat-num" data-target="500">0</span>
    <div class="stat-label">Events Delivered</div>
  </div>
  <div class="stat-item reveal">
    <span class="stat-num" data-target="120">0</span>
    <div class="stat-label">Resident DJs</div>
  </div>
  <div class="stat-item reveal">
    <span class="stat-num" data-target="8">0</span>
    <div class="stat-label">Years in Business</div>
  </div>
  <div class="stat-item reveal">
    <span class="stat-num" data-target="98">0</span>
    <div class="stat-label">Client Satisfaction %</div>
  </div>
</div>

<!-- SERVICES -->
<section id="services">
  <div class="services-header reveal">
    <div class="section-label">What We Do</div>
    <h2 class="section-title">WE CREATE <span class="accent">EXPERIENCES</span> NOT JUST EVENTS</h2>
  </div>

  <div class="services-grid">
    <div class="service-card reveal">
      <span class="service-icon">🎧</span>
      <span class="service-num">01</span>
      <div class="service-name">DJ Booking & Management</div>
      <p class="service-desc">Access our roster of 120+ resident and touring DJs across Afrobeats, Tech House, Hip-Hop, R&B and more. We match the vibe to your crowd.</p>
      <a href="#packages" class="service-link">View DJs →</a>
      <div class="service-card-bar"></div>
    </div>
    <div class="service-card reveal">
      <span class="service-icon">🎤</span>
      <span class="service-num">04</span>
      <div class="service-name">Live Acts & Performers</div>
      <p class="service-desc">Hype MCs, saxophonists, vocalists, aerialists, and more. Layer live performance on top of your DJ set for a night no one forgets.</p>
      <a href="#packages" class="service-link">See Performers →</a>
      <div class="service-card-bar"></div>
    </div>
    <div class="service-card reveal">
      <span class="service-icon">🎬</span>
      <span class="service-num">05</span>
      <div class="service-name">Visual Content & VJing</div>
      <p class="service-desc">Real-time video mixing, LED wall content creation, and custom branding overlays that keep every screen in your venue alive with energy.</p>
      <a href="#packages" class="service-link">View Visuals →</a>
      <div class="service-card-bar"></div>
      
    </div>
  </div>
</section>

<!-- PACKAGES -->
<section id="packages">
  <div class="packages-header reveal">
    <div class="section-label" style="justify-content:center">Pricing</div>
    <h2 class="section-title">CHOOSE YOUR <span class="accent">PACKAGE</span></h2>
    <p style="color:var(--muted);margin-top:1rem;font-size:0.9rem;">Six premium entertainment packages tailored to your venue's needs</p>
  </div>

  <div class="packages-grid" style="grid-template-columns:repeat(3,1fr)">
    <!-- Signature Themed Show -->
    <div class="package-card reveal" onclick="selectPackage(this, 'Signature Themed Show')">
      <div class="package-tier">Package 01</div>
      <div class="package-name">SIGNATURE THEMED SHOW</div>
      <div class="package-price">KES 18K</div>
      <div class="package-price-note">Transform regular nights with themed experiences (90s Throwback, All-White Party, Karaoke, Reggae Night)</div>
      <ul class="package-features">
        <li>Audience: Corporate crowds, genre enthusiasts, weekend club-goers</li>
        <li>Capacity: 50–150+ guests</li>
        <li>1 DJ</li>
        <li>1 MC</li>
        <li>1 Bouncer</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('Signature Themed Show')">Select Package</button>
    </div>

    <!-- The Ultimate Party -->
    <div class="package-card reveal" onclick="selectPackage(this, 'The Ultimate Party')">
      <div class="package-tier">Package 02</div>
      <div class="package-name">THE ULTIMATE PARTY</div>
      <div class="package-price">KES 22K</div>
      <div class="package-price-note">Festival feel with top-tier talent driving foot traffic and liquor sales. Perfect for holidays or grand openings.</div>
      <ul class="package-features">
        <li>Audience: Young professionals, college students, influencers</li>
        <li>Capacity: 100–300+ guests</li>
        <li>1 DJ</li>
        <li>1 MC</li>
        <li>2 Bouncers</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('The Ultimate Party')">Select Package</button>
    </div>

    <!-- Rhythm & Flex -->
    <div class="package-card reveal" onclick="selectPackage(this, 'Rhythm & Flex')">
      <div class="package-tier">Package 03</div>
      <div class="package-name">RHYTHM &amp; FLEX</div>
      <div class="package-price">KES 30K</div>
      <div class="package-price-note">High-energy visual performance with dedicated dance showcase setting the tempo.</div>
      <ul class="package-features">
        <li>Audience: Young adults, bachelor/bachelorette groups</li>
        <li>Capacity: 100–250+ guests</li>
        <li>2 Dancers</li>
        <li>1 DJ</li>
        <li>1 MC &amp; 2 Bouncers</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('Rhythm & Flex')">Select Package</button>
    </div>

    <!-- The Night Reveler -->
    <div class="package-card featured reveal" onclick="selectPackage(this, 'The Night Reveler')">
      <div class="package-badge">Premium</div>
      <div class="package-tier">Package 04</div>
      <div class="package-name">THE NIGHT REVELER</div>
      <div class="package-price">KES 35K</div>
      <div class="package-price-note">Premium, high-ticket adult entertainment for exclusive late-night events with exotic dancing experience.</div>
      <ul class="package-features">
        <li>Audience: Executive clients, high spenders, bachelor parties, exclusive adult-only</li>
        <li>Capacity: 50–150+ guests</li>
        <li>2 Strippers</li>
        <li>1 DJ &amp; 1 MC</li>
        <li>2 Bouncers</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('The Night Reveler')">Select Package</button>
    </div>

    <!-- Celebration Central -->
    <div class="package-card reveal" onclick="selectPackage(this, 'Celebration Central')">
      <div class="package-tier">Package 05</div>
      <div class="package-name">CELEBRATION CENTRAL</div>
      <div class="package-price">KES 15K</div>
      <div class="package-price-note">Customized intimate entertainment with personal shout-outs and reserved seating management.</div>
      <ul class="package-features">
        <li>Audience: Milestone celebrations, friend groups, socialites</li>
        <li>Capacity: 10–50 guests</li>
        <li>1 DJ</li>
        <li>1 MC</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('Celebration Central')">Select Package</button>
    </div>

    <!-- The Social Escape -->
    <div class="package-card reveal" onclick="selectPackage(this, 'The Social Escape')">
      <div class="package-tier">Package 06</div>
      <div class="package-name">THE SOCIAL ESCAPE</div>
      <div class="package-price">KES 20K</div>
      <div class="package-price-note">Mobile entertainment bringing the club vibe to the open road. <em style="font-size:0.75rem;color:var(--muted)">(Excludes vehicle rental, fuel, driver, and permit costs which vary by distance)</em></div>
      <ul class="package-features">
        <li>Audience: Milestone celebrations, friend groups, socialites</li>
        <li>Capacity: 10–50 guests</li>
        <li>1 DJ</li>
        <li>1 MC</li>
      </ul>
      <button class="btn-primary" style="width:100%;clip-path:none" onclick="openModal('The Social Escape')">Select Package</button>
    </div>
  </div>

  <!-- Customize Your Vibe -->
  <div style="max-width:700px;margin:4rem auto 0;padding:2.5rem;background:var(--deep);border:1px solid rgba(250,204,21,0.15);text-align:center;" class="reveal">
    <div class="section-label" style="justify-content:center;margin-bottom:1rem">Customize Your Vibe</div>
    <p style="color:var(--muted);font-size:0.85rem;margin-bottom:1.5rem">Add individual talent to any package at the following rates:</p>
    <div style="display:flex;flex-wrap:wrap;gap:1rem;justify-content:center">
      <span style="background:var(--surface2);border:1px solid rgba(250,204,21,0.15);padding:0.5rem 1.2rem;font-size:0.85rem;letter-spacing:0.05em">DJ — <strong style="color:var(--gold)">KES 4,500</strong></span>
      <span style="background:var(--surface2);border:1px solid rgba(250,204,21,0.15);padding:0.5rem 1.2rem;font-size:0.85rem;letter-spacing:0.05em">MC — <strong style="color:var(--gold)">KES 4,500</strong></span>
      <span style="background:var(--surface2);border:1px solid rgba(250,204,21,0.15);padding:0.5rem 1.2rem;font-size:0.85rem;letter-spacing:0.05em">TWERKER — <strong style="color:var(--gold)">KES 5,000</strong></span>
      <span style="background:var(--surface2);border:1px solid rgba(250,204,21,0.15);padding:0.5rem 1.2rem;font-size:0.85rem;letter-spacing:0.05em">STRIPPER — <strong style="color:var(--gold)">KES 6,000</strong></span>
      <span style="background:var(--surface2);border:1px solid rgba(250,204,21,0.15);padding:0.5rem 1.2rem;font-size:0.85rem;letter-spacing:0.05em">BOUNCER — <strong style="color:var(--gold)">KES 4,000</strong></span>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery">
  <div class="gallery-header reveal">
    <div class="section-label">Past Events</div>
    <h2 class="section-title" style="display:flex;align-items:center;gap:1rem">THE NIGHTS WE'VE <span class="accent">BUILT</span>
      <div class="beat-viz">
        <div class="beat-bar"></div>
        <div class="beat-bar"></div>
        <div class="beat-bar"></div>
        <div class="beat-bar"></div>
        <div class="beat-bar"></div>
        <div class="beat-bar"></div>
      </div>
    </h2>
  </div>

  <div style="overflow:hidden">
    <div class="gallery-track">
      <div class="gallery-item"><div class="inner g1">🎧</div><div class="gallery-overlay"><span>Club Privé — Westlands</span></div></div>
      <div class="gallery-item"><div class="inner g2">💡</div><div class="gallery-overlay"><span>NYE Laser Spectacular</span></div></div>
      <div class="gallery-item"><div class="inner g3">🎤</div><div class="gallery-overlay"><span>Live at KICC</span></div></div>
      <div class="gallery-item"><div class="inner g4">🔊</div><div class="gallery-overlay"><span>Afrobeats Festival</span></div></div>
      <div class="gallery-item"><div class="inner g5">🥂</div><div class="gallery-overlay"><span>VIP Rooftop — Gigiri</span></div></div>
      <div class="gallery-item"><div class="inner g6">🎬</div><div class="gallery-overlay"><span>Brand Launch — Uhuru Park</span></div></div>
      <div class="gallery-item"><div class="inner g1">🎧</div><div class="gallery-overlay"><span>Warehouse Rave — Ind Area</span></div></div>
      <div class="gallery-item"><div class="inner g2">💡</div><div class="gallery-overlay"><span>Corporate Gala — Serena</span></div></div>
      <!-- duplicate for infinite scroll -->
      <div class="gallery-item"><div class="inner g3">🎤</div><div class="gallery-overlay"><span>Club Privé — Westlands</span></div></div>
      <div class="gallery-item"><div class="inner g4">🔊</div><div class="gallery-overlay"><span>NYE Laser Spectacular</span></div></div>
      <div class="gallery-item"><div class="inner g5">🥂</div><div class="gallery-overlay"><span>Live at KICC</span></div></div>
      <div class="gallery-item"><div class="inner g6">🎬</div><div class="gallery-overlay"><span>Afrobeats Festival</span></div></div>
      <div class="gallery-item"><div class="inner g1">🎧</div><div class="gallery-overlay"><span>VIP Rooftop — Gigiri</span></div></div>
      <div class="gallery-item"><div class="inner g2">💡</div><div class="gallery-overlay"><span>Brand Launch — Uhuru Park</span></div></div>
      <div class="gallery-item"><div class="inner g3">🎤</div><div class="gallery-overlay"><span>Warehouse Rave — Ind Area</span></div></div>
      <div class="gallery-item"><div class="inner g4">🔊</div><div class="gallery-overlay"><span>Corporate Gala — Serena</span></div></div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials">
  <div class="reveal" style="max-width:600px">
    <div class="section-label">Client Reviews</div>
    <h2 class="section-title">WHAT THEY <span class="accent">SAY</span></h2>
  </div>
  <div class="testimonials-grid">
    <div class="testimonial-card reveal">
      <div class="testimonial-stars">
        <span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span>
      </div>
      <p class="testimonial-text">Stackabilli turned our product launch into the talk of Nairobi. The lighting design was next-level — I've never seen anything like it outside of a world-class festival.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:rgba(250,204,21,0.1);color:var(--gold)">AK</div>
        <div><div class="author-name">Amina Kariuki</div><div class="author-role">Marketing Director, Safaricom</div></div>
      </div>
    </div>
    <div class="testimonial-card reveal">
      <div class="testimonial-stars">
        <span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span>
      </div>
      <p class="testimonial-text">We run quarterly events at our venue and Stackabilli has been our exclusive partner for two years. Consistent, professional, and the crowd always goes wild.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:rgba(139,0,255,0.15);color:#bf7fff">JN</div>
        <div><div class="author-name">James Njoroge</div><div class="author-role">Owner, Club Privé</div></div>
      </div>
    </div>
    <div class="testimonial-card reveal">
      <div class="testimonial-stars">
        <span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span><span class="star">★</span>
      </div>
      <p class="testimonial-text">Our NYE party with the Blackout package was absolutely insane. 600 guests and every single one of them said it was the best party they'd ever been to. Worth every shilling.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:rgba(255,50,50,0.1);color:#ff8080">SM</div>
        <div><div class="author-name">Sophia Muthoni</div><div class="author-role">Private Client</div></div>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<section id="cta">
  <div class="reveal">
    <div class="section-label" style="justify-content:center">Ready?</div>
    <h2 class="cta-title">
      LET'S BUILD<br>
      <span style="color:var(--gold)">YOUR NIGHT</span>
    </h2>
    <p class="cta-sub">Drop us a message and our team will craft a custom production plan for your event within 24 hours.</p>
    <div class="cta-actions">
      <button class="btn-primary" onclick="openModal()">Book a Consultation</button>
      <a href="tel:+254705509744" class="btn-outline">Call Us Now</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-brand">
    <span class="logo">STACKABILLI</span>
    <p>Nairobi's most trusted entertainment production agency. Transforming venues into unforgettable experiences — just the vibes.</p>
    <p style="margin-top:0.75rem;font-size:0.8rem;color:var(--muted)">Contact: <strong style="color:var(--text)">Andrew Obare</strong> (Alias: Wan$ven)</p>
  </div>
  <div class="footer-col">
    <h4>Services</h4>
    <ul>
      <li><a href="#services">DJ Booking</a></li>
      <li><a href="#services">Lighting Design</a></li>
      <li><a href="#services">Sound Systems</a></li>
      <li><a href="#services">Live Acts</a></li>
      <li><a href="#services">VIP Production</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Company</h4>
    <ul>
      <li><a href="#">About Us</a></li>
      <li><a href="#">Our DJs</a></li>
      <li><a href="#gallery">Portfolio</a></li>
      <li><a href="#testimonials">Reviews</a></li>
      <li><a href="#">Careers</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Contact</h4>
    <ul>
      <li><a href="tel:+254705509744">+254 705 509 744</a></li>
      <li><a href="mailto:stackabillient@gmail.com">stackabillient@gmail.com</a></li>
      <li><a href="#">Nairobi</a></li>
      <li><a href="#">Instagram</a></li>
      <li><a href="https://wa.me/254705509744">WhatsApp</a></li>
    </ul>
  </div>
  <div class="footer-bottom">
    <span>© 2025 Stackabilli Entertainment. All rights reserved.</span>
    <span>Nairobi · Mombasa · Kampala</span>
  </div>
</footer>

<!-- BOOKING MODAL -->
<div class="modal-overlay" id="modal" onclick="closeModalOnOverlay(event)">
  <div class="modal-box">
    <button class="modal-close" onclick="closeModal()">✕</button>
    <div class="modal-title">BOOK YOUR EVENT</div>
    <div class="modal-sub">Fill in the details below and we'll get back to you within 24 hours.</div>
    <div class="form-row">
      <div class="form-group">
        <label class="form-label">First Name</label>
        <input type="text" class="form-input" placeholder="Amina">
      </div>
      <div class="form-group">
        <label class="form-label">Last Name</label>
        <input type="text" class="form-input" placeholder="Kariuki">
      </div>
    </div>
    <div class="form-group">
      <label class="form-label">Email Address</label>
      <input type="email" class="form-input" placeholder="you@example.com">
    </div>
    <div class="form-group">
      <label class="form-label">Phone / WhatsApp</label>
      <input type="tel" class="form-input" placeholder="+254 7XX XXX XXX">
    </div>
    <div class="form-row">
      <div class="form-group">
        <label class="form-label">Event Date</label>
        <input type="date" class="form-input" id="eventDate">
      </div>
      <div class="form-group">
        <label class="form-label">Expected Guests</label>
        <input type="number" class="form-input" placeholder="e.g. 200">
      </div>
    </div>
    <div class="form-group">
      <label class="form-label">Package Interest</label>
      <select class="form-select" id="packageSelect">
        <option value="">— Select a package —</option>
        <option value="Signature Themed Show">Signature Themed Show — KES 18,000</option>
        <option value="The Ultimate Party">The Ultimate Party — KES 22,000</option>
        <option value="Rhythm & Flex">Rhythm &amp; Flex — KES 30,000</option>
        <option value="The Night Reveler">The Night Reveler — KES 35,000</option>
        <option value="Celebration Central">Celebration Central — KES 15,000</option>
        <option value="The Social Escape">The Social Escape — KES 20,000</option>
        <option value="Custom">Not sure, need advice</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Tell Us About Your Event</label>
      <textarea class="form-textarea" placeholder="Venue, theme, special requirements..."></textarea>
    </div>
    <button class="form-submit" onclick="submitForm()">SEND ENQUIRY →</button>
  </div>
</div>

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

  function animateRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    ring.style.left = rx + 'px';
    ring.style.top = ry + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  document.querySelectorAll('a,button,.service-card,.package-card,.gallery-item,.testimonial-card').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.width = '20px';
      cursor.style.height = '20px';
      ring.style.width = '60px';
      ring.style.height = '60px';
      ring.style.borderColor = 'rgba(250,204,21,0.8)';
    });
    el.addEventListener('mouseleave', () => {
      cursor.style.width = '12px';
      cursor.style.height = '12px';
      ring.style.width = '40px';
      ring.style.height = '40px';
      ring.style.borderColor = 'rgba(250,204,21,0.5)';
    });
  });

  // LASER CANVAS
  const canvas = document.getElementById('laserCanvas');
  const ctx = canvas.getContext('2d');
  let lasers = [];

  function resizeCanvas() {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  }
  resizeCanvas();
  window.addEventListener('resize', resizeCanvas);

  const laserColors = ['#facc15','#ff0080','#00ffff','#8000ff','#ff4400'];

  function createLaser() {
    const side = Math.floor(Math.random() * 4);
    let x, y, angle;
    if (side === 0) { x = Math.random() * canvas.width; y = 0; angle = Math.random() * Math.PI; }
    else if (side === 1) { x = canvas.width; y = Math.random() * canvas.height; angle = Math.PI/2 + Math.random() * Math.PI; }
    else if (side === 2) { x = Math.random() * canvas.width; y = canvas.height; angle = Math.PI + Math.random() * Math.PI; }
    else { x = 0; y = Math.random() * canvas.height; angle = -Math.PI/2 + Math.random() * Math.PI; }
    return {
      x, y, angle,
      speed: 0.005 + Math.random() * 0.01,
      color: laserColors[Math.floor(Math.random() * laserColors.length)],
      length: 300 + Math.random() * 500,
      life: 1, decay: 0.005 + Math.random() * 0.01,
      width: 0.5 + Math.random() * 1
    };
  }

  function drawLasers() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    if (lasers.length < 8 && Math.random() < 0.05) lasers.push(createLaser());
    lasers = lasers.filter(l => l.life > 0);
    lasers.forEach(l => {
      l.angle += l.speed;
      l.life -= l.decay;
      ctx.save();
      ctx.globalAlpha = l.life * 0.6;
      ctx.strokeStyle = l.color;
      ctx.lineWidth = l.width;
      ctx.beginPath();
      ctx.moveTo(l.x, l.y);
      ctx.lineTo(l.x + Math.cos(l.angle) * l.length, l.y + Math.sin(l.angle) * l.length);
      ctx.stroke();
      ctx.restore();
    });
    requestAnimationFrame(drawLasers);
  }
  drawLasers();

  // NAV SCROLL
  window.addEventListener('scroll', () => {
    document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 60);
  });

  // REVEAL ON SCROLL
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((e, i) => {
      if (e.isIntersecting) {
        setTimeout(() => e.target.classList.add('visible'), i * 80);
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(r => observer.observe(r));

  // COUNTER ANIMATION
  function animateCounter(el, target) {
    let current = 0;
    const increment = target / 60;
    const timer = setInterval(() => {
      current += increment;
      if (current >= target) { current = target; clearInterval(timer); }
      el.textContent = Math.floor(current) + (el.dataset.target == '98' ? '%' : '+');
    }, 25);
  }

  const counterObserver = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        const nums = e.target.querySelectorAll('[data-target]');
        nums.forEach(n => animateCounter(n, parseInt(n.dataset.target)));
        counterObserver.unobserve(e.target);
      }
    });
  }, { threshold: 0.5 });
  document.querySelectorAll('.stats-bar').forEach(el => counterObserver.observe(el));

  // MODAL
  function openModal(pkg = '') {
    document.getElementById('modal').classList.add('active');
    document.body.style.overflow = 'hidden';
    if (pkg) {
      const sel = document.getElementById('packageSelect');
      if (sel) sel.value = pkg;
    }
  }
  function closeModal() {
    document.getElementById('modal').classList.remove('active');
    document.body.style.overflow = '';
  }
  function closeModalOnOverlay(e) {
    if (e.target === document.getElementById('modal')) closeModal();
  }
  function selectPackage(card, pkg) {
    document.querySelectorAll('.package-card').forEach(c => c.classList.remove('selected'));
    card.classList.add('selected');
  }
  function submitForm() {
    const btn = document.querySelector('.form-submit');
    btn.textContent = 'SENDING...';
    btn.style.background = '#333';
    setTimeout(() => {
      btn.textContent = '✓ ENQUIRY SENT!';
      btn.style.background = '#1a7a1a';
      setTimeout(() => { closeModal(); btn.textContent = 'SEND ENQUIRY →'; btn.style.background = ''; }, 2000);
    }, 1200);
  }

  // ESC key close
  document.addEventListener('keydown', e => { if (e.key === 'Escape') closeModal(); });

  // PARALLAX HERO
  window.addEventListener('scroll', () => {
    const y = window.scrollY;
    const heroBg = document.querySelector('.hero-bg');
    if (heroBg) heroBg.style.transform = `translateY(${y * 0.4}px)`;
  });
</script>
</body>
</html>
