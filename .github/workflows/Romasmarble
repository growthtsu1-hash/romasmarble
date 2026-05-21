<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Y — Simply Beautiful Design</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
 
  :root {
    --cream: #f5f2ee;
    --dark: #1a1a18;
    --mid: #2e2e2a;
    --charcoal: #3a3935;
    --warm-gray: #8a8780;
    --light-gray: #d4d0ca;
    --accent: #c8b89a;
    --white: #ffffff;
    --font-display: 'Cormorant Garamond', serif;
    --font-body: 'DM Sans', sans-serif;
  }
 
  html { scroll-behavior: smooth; }
 
  body {
    font-family: var(--font-body);
    background: var(--cream);
    color: var(--dark);
    font-size: 14px;
    line-height: 1.6;
    overflow-x: hidden;
  }
 
  /* ─── NAVBAR ─────────────────────────────────────── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 40px;
    background: rgba(26,26,24,0.55);
    backdrop-filter: blur(14px);
    -webkit-backdrop-filter: blur(14px);
  }
 
  .nav-logo {
    display: flex;
    align-items: center;
    gap: 10px;
    color: var(--white);
    text-decoration: none;
  }
 
  .logo-mark {
    width: 34px; height: 34px;
    border: 1.5px solid var(--white);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: var(--font-display);
    font-size: 20px;
    font-weight: 300;
    letter-spacing: -1px;
  }
 
  .logo-text {
    font-family: var(--font-body);
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
    font-weight: 300;
    opacity: 0.7;
  }
 
  .nav-links {
    display: flex;
    align-items: center;
    gap: 34px;
    list-style: none;
  }
 
  .nav-links a {
    color: rgba(255,255,255,0.75);
    text-decoration: none;
    font-size: 13px;
    font-weight: 300;
    letter-spacing: 0.5px;
    transition: color 0.2s;
  }
 
  .nav-links a:hover { color: var(--white); }
 
  .nav-right {
    display: flex;
    align-items: center;
    gap: 14px;
  }
 
  .btn-outline {
    border: 1px solid rgba(255,255,255,0.5);
    color: var(--white);
    padding: 9px 22px;
    font-size: 12px;
    letter-spacing: 1px;
    text-transform: uppercase;
    background: transparent;
    cursor: pointer;
    font-family: var(--font-body);
    transition: background 0.25s, border-color 0.25s;
    text-decoration: none;
    display: inline-block;
  }
 
  .btn-outline:hover { background: rgba(255,255,255,0.12); border-color: var(--white); }
 
  .hamburger {
    width: 36px; height: 36px;
    border: 1px solid rgba(255,255,255,0.4);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    background: transparent;
    gap: 0;
  }
 
  .hamburger svg { stroke: var(--white); }
 
  /* ─── HERO ──────────────────────────────────────── */
  .hero {
    position: relative;
    height: 100vh;
    min-height: 620px;
    overflow: hidden;
    display: flex;
    align-items: flex-end;
    padding-bottom: 80px;
  }
 
  .hero-bg {
    position: absolute;
    inset: 0;
    background: linear-gradient(
      to bottom,
      rgba(26,26,24,0.35) 0%,
      rgba(26,26,24,0.15) 40%,
      rgba(26,26,24,0.55) 100%
    ),
    /* Simulated stone/bathroom texture using CSS gradients */
    repeating-linear-gradient(
      92deg,
      rgba(90,85,78,0.18) 0px, rgba(90,85,78,0.18) 1px,
      transparent 1px, transparent 60px
    ),
    linear-gradient(175deg, #4a473f 0%, #2c2a24 30%, #383530 55%, #4d4a42 100%);
    background-size: cover;
  }
 
  /* Decorative vertical lines mimicking bathroom tiles/grooves */
  .hero-bg::after {
    content: '';
    position: absolute;
    inset: 0;
    background:
      repeating-linear-gradient(
        90deg,
        transparent 0px,
        transparent 58px,
        rgba(200,184,154,0.07) 58px,
        rgba(200,184,154,0.07) 60px
      );
  }
 
  .hero-content {
    position: relative;
    z-index: 2;
    padding: 0 60px;
    max-width: 560px;
  }
 
  .hero-content h1 {
    font-family: var(--font-display);
    font-size: clamp(44px, 6vw, 70px);
    font-weight: 300;
    color: var(--white);
    line-height: 1.1;
    letter-spacing: -0.5px;
    margin-bottom: 18px;
  }
 
  .hero-content p {
    color: rgba(255,255,255,0.65);
    font-size: 13px;
    font-weight: 300;
    max-width: 340px;
    margin-bottom: 36px;
    letter-spacing: 0.3px;
  }
 
  .btn-circle {
    display: inline-flex;
    align-items: center;
    gap: 14px;
    color: var(--white);
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    font-weight: 400;
  }
 
  .btn-circle .circle-icon {
    width: 40px; height: 40px;
    border: 1px solid rgba(255,255,255,0.5);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.25s;
  }
 
  .btn-circle:hover .circle-icon { background: rgba(255,255,255,0.15); }
 
  .hero-badge {
    position: absolute;
    bottom: 60px;
    right: 60px;
    z-index: 2;
    background: rgba(26,26,24,0.7);
    backdrop-filter: blur(8px);
    border: 1px solid rgba(255,255,255,0.1);
    padding: 20px 24px;
    max-width: 240px;
    color: var(--white);
  }
 
  .hero-badge .badge-title {
    font-family: var(--font-display);
    font-size: 15px;
    font-weight: 400;
    margin-bottom: 6px;
    line-height: 1.3;
  }
 
  .hero-badge .badge-sub {
    font-size: 11px;
    color: rgba(255,255,255,0.55);
    font-weight: 300;
    margin-bottom: 14px;
    line-height: 1.5;
  }
 
  .badge-nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
 
  .badge-counter {
    font-size: 11px;
    color: rgba(255,255,255,0.45);
    letter-spacing: 1px;
  }
 
  .badge-progress {
    width: 60px;
    height: 1px;
    background: rgba(255,255,255,0.2);
    position: relative;
  }
 
  .badge-progress::after {
    content: '';
    position: absolute;
    left: 0; top: 0;
    width: 100%;
    height: 100%;
    background: rgba(255,255,255,0.6);
  }
 
  .badge-arrows {
    display: flex;
    gap: 10px;
    color: rgba(255,255,255,0.5);
    font-size: 14px;
  }
 
  .badge-arrows span { cursor: pointer; transition: color 0.2s; }
  .badge-arrows span:hover { color: var(--white); }
 
  /* ─── CHAT BUBBLE ───────────────────────────────── */
  .chat-bubble {
    position: absolute;
    right: -1px;
    top: 50%;
    transform: translateY(-50%);
    z-index: 3;
    width: 38px; height: 38px;
    background: var(--dark);
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
  }
 
  /* ─── PRODUCTS SECTION ─────────────────────────── */
  .section-products {
    background: var(--cream);
    padding: 90px 60px;
  }
 
  .section-label {
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--warm-gray);
    margin-bottom: 28px;
  }
 
  .products-header {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    margin-bottom: 50px;
    gap: 40px;
  }
 
  .products-header h2 {
    font-family: var(--font-display);
    font-size: clamp(34px, 4vw, 52px);
    font-weight: 300;
    color: var(--dark);
    line-height: 1.15;
    letter-spacing: -0.5px;
    max-width: 400px;
  }
 
  .products-header-right {
    display: flex;
    align-items: center;
    gap: 24px;
    flex-shrink: 0;
  }
 
  .products-header-right p {
    font-size: 13px;
    color: var(--warm-gray);
    font-weight: 300;
    max-width: 220px;
    line-height: 1.6;
  }
 
  .btn-arrow {
    width: 42px; height: 42px;
    border: 1px solid var(--light-gray);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    background: transparent;
    transition: background 0.25s, border-color 0.25s;
    flex-shrink: 0;
  }
 
  .btn-arrow:hover { background: var(--dark); border-color: var(--dark); }
  .btn-arrow:hover svg { stroke: var(--white); }
 
  .products-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
  }
 
  .product-card {
    position: relative;
    aspect-ratio: 3/4;
    overflow: hidden;
    cursor: pointer;
  }
 
  .product-card-bg {
    position: absolute;
    inset: 0;
    background-size: cover;
    background-position: center;
    transition: transform 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94);
  }
 
  .product-card:hover .product-card-bg { transform: scale(1.04); }
 
  /* Stone texture simulations */
  .marble-bg {
    background:
      radial-gradient(ellipse at 20% 30%, rgba(210,200,195,0.6) 0%, transparent 50%),
      radial-gradient(ellipse at 80% 70%, rgba(185,175,168,0.4) 0%, transparent 45%),
      linear-gradient(135deg, #e8e2dc 0%, #d4ccc6 30%, #c8beb8 60%, #ddd5ce 100%);
  }
 
  .marble-bg::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      repeating-linear-gradient(
        45deg,
        transparent 0px, transparent 20px,
        rgba(150,140,135,0.08) 20px, rgba(150,140,135,0.08) 21px
      ),
      repeating-linear-gradient(
        -30deg,
        transparent 0px, transparent 40px,
        rgba(200,190,185,0.12) 40px, rgba(200,190,185,0.12) 41px
      );
  }
 
  .granite-bg {
    background:
      radial-gradient(circle at 30% 40%, rgba(80,60,50,0.7) 0%, transparent 40%),
      radial-gradient(circle at 70% 20%, rgba(110,90,70,0.5) 0%, transparent 35%),
      radial-gradient(circle at 50% 80%, rgba(60,50,45,0.6) 0%, transparent 45%),
      linear-gradient(160deg, #3a3028 0%, #2a2218 40%, #382e22 70%, #2e2418 100%);
  }
 
  .granite-bg::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      radial-gradient(circle at 25% 25%, rgba(180,160,140,0.15) 0%, transparent 20%),
      radial-gradient(circle at 75% 55%, rgba(160,140,120,0.12) 0%, transparent 18%),
      radial-gradient(circle at 45% 80%, rgba(200,170,140,0.1) 0%, transparent 15%);
  }
 
  .onyx-bg {
    background:
      radial-gradient(ellipse at 50% 40%, rgba(220,200,160,0.5) 0%, transparent 50%),
      radial-gradient(ellipse at 20% 70%, rgba(190,165,120,0.4) 0%, transparent 40%),
      linear-gradient(130deg, #c8a870 0%, #b89060 25%, #d4b885 50%, #a87840 75%, #c09060 100%);
  }
 
  .onyx-bg::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      repeating-linear-gradient(
        20deg,
        transparent 0px, transparent 15px,
        rgba(255,240,200,0.08) 15px, rgba(255,240,200,0.08) 16px
      );
  }
 
  .travertine-bg {
    background:
      radial-gradient(ellipse at 30% 20%, rgba(220,210,195,0.5) 0%, transparent 45%),
      linear-gradient(160deg, #d4c8b4 0%, #c8baa0 35%, #d8ccb8 65%, #c4b89a 100%);
  }
 
  .travertine-bg::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      repeating-linear-gradient(
        0deg,
        rgba(190,175,155,0.15) 0px, rgba(190,175,155,0.15) 1px,
        transparent 1px, transparent 8px
      );
  }
 
  .product-card-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(20,18,14,0.75) 0%, transparent 55%);
  }
 
  .product-card-plus {
    position: absolute;
    top: 16px; right: 16px;
    width: 32px; height: 32px;
    border: 1px solid rgba(255,255,255,0.5);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    background: rgba(26,26,24,0.4);
    backdrop-filter: blur(4px);
    cursor: pointer;
    transition: background 0.2s;
  }
 
  .product-card-plus:hover { background: rgba(26,26,24,0.7); }
 
  .product-card-info {
    position: absolute;
    bottom: 0; left: 0; right: 0;
    padding: 20px 18px;
  }
 
  .product-card-name {
    font-family: var(--font-display);
    font-size: 20px;
    font-weight: 400;
    color: var(--white);
    margin-bottom: 6px;
  }
 
  .product-card-link {
    font-size: 11px;
    color: rgba(255,255,255,0.6);
    letter-spacing: 1px;
    text-transform: uppercase;
    display: flex;
    align-items: center;
    gap: 5px;
  }
 
  /* ─── INSPIRE SECTION ───────────────────────────── */
  .section-inspire {
    background: var(--dark);
    display: grid;
    grid-template-columns: 1fr 1fr;
    min-height: 540px;
  }
 
  .inspire-text {
    padding: 80px 60px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
 
  .inspire-text h2 {
    font-family: var(--font-display);
    font-size: clamp(36px, 4vw, 56px);
    font-weight: 300;
    color: var(--white);
    line-height: 1.15;
    letter-spacing: -0.5px;
    margin-bottom: 24px;
  }
 
  .inspire-text p {
    color: rgba(255,255,255,0.5);
    font-size: 13px;
    font-weight: 300;
    max-width: 280px;
    margin-bottom: 40px;
    line-height: 1.7;
  }
 
  .btn-circle-dark {
    display: inline-flex;
    align-items: center;
    gap: 14px;
    color: var(--white);
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
  }
 
  .btn-circle-dark .circle-icon {
    width: 40px; height: 40px;
    border: 1px solid rgba(255,255,255,0.35);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.25s;
  }
 
  .btn-circle-dark:hover .circle-icon { background: rgba(255,255,255,0.12); }
 
  .inspire-image {
    position: relative;
    overflow: hidden;
  }
 
  .inspire-image-bg {
    position: absolute;
    inset: 0;
    background:
      radial-gradient(ellipse at 40% 50%, rgba(220,210,195,0.25) 0%, transparent 55%),
      linear-gradient(135deg, #5a5548 0%, #3a3830 40%, #4a4840 70%, #3e3c34 100%);
  }
 
  /* Countertop / reception desk visual */
  .inspire-image-bg::after {
    content: '';
    position: absolute;
    bottom: 0; left: 0; right: 0;
    height: 45%;
    background: linear-gradient(
      to top,
      rgba(200,190,170,0.35) 0%,
      transparent 100%
    );
    border-top: 1px solid rgba(200,190,170,0.2);
  }
 
  .inspire-desk {
    position: absolute;
    bottom: 20%;
    left: 50%;
    transform: translateX(-50%);
    width: 65%;
    height: 140px;
    background: linear-gradient(135deg, #d4cabb 0%, #c8bfaa 50%, #d8d0bc 100%);
    box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  }
 
  .inspire-desk::before {
    content: '';
    position: absolute;
    inset: 0;
    background: repeating-linear-gradient(
      0deg,
      transparent 0px, transparent 12px,
      rgba(160,150,130,0.12) 12px, rgba(160,150,130,0.12) 13px
    );
  }
 
  /* ─── WHY CHOOSE ─────────────────────────────────── */
  .section-why {
    background: var(--cream);
    padding: 90px 60px;
  }
 
  .why-header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    margin-bottom: 70px;
    gap: 40px;
  }
 
  .why-header h2 {
    font-family: var(--font-display);
    font-size: clamp(32px, 4vw, 50px);
    font-weight: 300;
    color: var(--dark);
    letter-spacing: -0.5px;
  }
 
  .why-header p {
    font-size: 13px;
    color: var(--warm-gray);
    max-width: 240px;
    font-weight: 300;
    line-height: 1.6;
    text-align: right;
  }
 
  .why-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 40px;
  }
 
  .why-item { }
 
  .why-icon {
    width: 40px; height: 40px;
    margin-bottom: 20px;
    opacity: 0.6;
  }
 
  .why-item h3 {
    font-size: 14px;
    font-weight: 500;
    color: var(--dark);
    margin-bottom: 10px;
    letter-spacing: 0.2px;
  }
 
  .why-item p {
    font-size: 13px;
    color: var(--warm-gray);
    font-weight: 300;
    line-height: 1.65;
  }
 
  /* ─── COLLECTION SECTION ────────────────────────── */
  .section-collection {
    background: #2a2925;
    padding: 80px 0 0;
  }
 
  .collection-header {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    padding: 0 60px 50px;
  }
 
  .collection-label {
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: rgba(255,255,255,0.35);
    margin-bottom: 14px;
  }
 
  .collection-header h2 {
    font-family: var(--font-display);
    font-size: clamp(32px, 4vw, 52px);
    font-weight: 300;
    color: var(--white);
    letter-spacing: -0.5px;
  }
 
  .collection-header-right {
    display: flex;
    align-items: center;
    gap: 16px;
    flex-shrink: 0;
  }
 
  .view-all-text {
    font-size: 12px;
    letter-spacing: 1px;
    text-transform: uppercase;
    color: rgba(255,255,255,0.55);
  }
 
  .collection-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
  }
 
  .collection-card {
    position: relative;
    aspect-ratio: 3/4;
    overflow: hidden;
    cursor: pointer;
  }
 
  .collection-card-bg {
    position: absolute;
    inset: 0;
    background-size: cover;
    background-position: center;
    transition: transform 0.65s cubic-bezier(0.25, 0.46, 0.45, 0.94);
  }
 
  .collection-card:hover .collection-card-bg { transform: scale(1.05); }
 
  .bathroom-col {
    background:
      radial-gradient(ellipse at 30% 60%, rgba(210,200,185,0.3) 0%, transparent 55%),
      linear-gradient(145deg, #4a4840 0%, #3a3830 40%, #5a5650 70%, #403e38 100%);
  }
 
  .kitchen-col {
    background:
      radial-gradient(ellipse at 60% 30%, rgba(200,190,175,0.25) 0%, transparent 50%),
      linear-gradient(145deg, #2e2e28 0%, #3a3830 50%, #302e28 100%);
  }
 
  .living-col {
    background:
      radial-gradient(ellipse at 40% 50%, rgba(215,205,190,0.3) 0%, transparent 50%),
      linear-gradient(145deg, #5a5850 0%, #4a4840 50%, #504e48 100%);
  }
 
  .wall-col {
    background:
      radial-gradient(ellipse at 50% 40%, rgba(230,220,205,0.2) 0%, transparent 50%),
      linear-gradient(145deg, #3e3c35 0%, #4a4840 45%, #3c3a33 100%);
  }
 
  .collection-card-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(10,10,8,0.8) 0%, transparent 55%);
  }
 
  .collection-card-info {
    position: absolute;
    bottom: 0; left: 0; right: 0;
    padding: 22px 20px;
  }
 
  .collection-card-name {
    font-family: var(--font-display);
    font-size: 22px;
    font-weight: 400;
    color: var(--white);
    margin-bottom: 8px;
  }
 
  .collection-card-link {
    font-size: 11px;
    color: rgba(255,255,255,0.5);
    letter-spacing: 1px;
    text-transform: uppercase;
    display: flex;
    align-items: center;
    gap: 5px;
  }
 
  /* ─── CTA SECTION ───────────────────────────────── */
  .section-cta {
    background: var(--cream);
    padding: 90px 60px;
    display: grid;
    grid-template-columns: 1fr 1fr auto;
    gap: 40px;
    align-items: center;
    border-top: 1px solid var(--light-gray);
  }
 
  .cta-left h2 {
    font-family: var(--font-display);
    font-size: clamp(28px, 3.5vw, 46px);
    font-weight: 300;
    color: var(--dark);
    line-height: 1.2;
    letter-spacing: -0.3px;
  }
 
  .cta-left h2 em {
    font-style: italic;
    color: var(--warm-gray);
  }
 
  .cta-mid p {
    font-size: 13px;
    color: var(--warm-gray);
    font-weight: 300;
    max-width: 300px;
    line-height: 1.65;
  }
 
  .btn-filled {
    display: inline-flex;
    align-items: center;
    gap: 14px;
    background: var(--dark);
    color: var(--white);
    padding: 14px 28px;
    font-size: 12px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    cursor: pointer;
    border: none;
    font-family: var(--font-body);
    transition: background 0.25s;
    white-space: nowrap;
    text-decoration: none;
  }
 
  .btn-filled:hover { background: var(--charcoal); }
 
  .btn-filled .circle-icon {
    width: 28px; height: 28px;
    border: 1px solid rgba(255,255,255,0.35);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
 
  /* ─── FOOTER ─────────────────────────────────────── */
  footer {
    background: var(--dark);
    padding: 70px 60px 30px;
  }
 
  .footer-top {
    display: grid;
    grid-template-columns: 1.4fr 1fr 1fr 1fr 1.4fr;
    gap: 40px;
    padding-bottom: 50px;
    border-bottom: 1px solid rgba(255,255,255,0.08);
  }
 
  .footer-brand .logo-mark {
    margin-bottom: 18px;
  }
 
  .footer-brand p {
    font-size: 12px;
    color: rgba(255,255,255,0.4);
    font-weight: 300;
    max-width: 200px;
    line-height: 1.7;
    margin-bottom: 24px;
  }
 
  .footer-social {
    display: flex;
    gap: 14px;
  }
 
  .social-icon {
    width: 30px; height: 30px;
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: border-color 0.2s;
  }
 
  .social-icon:hover { border-color: rgba(255,255,255,0.5); }
 
  .footer-col h4 {
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: rgba(255,255,255,0.4);
    margin-bottom: 20px;
    font-weight: 400;
  }
 
  .footer-col ul {
    list-style: none;
  }
 
  .footer-col ul li {
    margin-bottom: 10px;
  }
 
  .footer-col ul li a {
    font-size: 13px;
    color: rgba(255,255,255,0.55);
    text-decoration: none;
    font-weight: 300;
    transition: color 0.2s;
  }
 
  .footer-col ul li a:hover { color: var(--white); }
 
  .footer-contact-item {
    font-size: 13px;
    color: rgba(255,255,255,0.55);
    font-weight: 300;
    margin-bottom: 10px;
    display: flex;
    align-items: flex-start;
    gap: 8px;
  }
 
  .footer-newsletter p {
    font-size: 12px;
    color: rgba(255,255,255,0.4);
    font-weight: 300;
    margin-bottom: 16px;
    line-height: 1.6;
  }
 
  .newsletter-form {
    display: flex;
    align-items: center;
    border: 1px solid rgba(255,255,255,0.2);
  }
 
  .newsletter-form input {
    flex: 1;
    background: transparent;
    border: none;
    padding: 12px 16px;
    font-family: var(--font-body);
    font-size: 12px;
    color: var(--white);
    outline: none;
  }
 
  .newsletter-form input::placeholder { color: rgba(255,255,255,0.3); }
 
  .newsletter-form button {
    width: 42px; height: 42px;
    background: rgba(255,255,255,0.1);
    border: none;
    border-left: 1px solid rgba(255,255,255,0.2);
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.2s;
  }
 
  .newsletter-form button:hover { background: rgba(255,255,255,0.2); }
 
  .footer-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 24px;
  }
 
  .footer-bottom p {
    font-size: 11px;
    color: rgba(255,255,255,0.25);
    font-weight: 300;
  }
 
  .footer-bottom-links {
    display: flex;
    gap: 24px;
  }
 
  .footer-bottom-links a {
    font-size: 11px;
    color: rgba(255,255,255,0.3);
    text-decoration: none;
    font-weight: 300;
    transition: color 0.2s;
  }
 
  .footer-bottom-links a:hover { color: rgba(255,255,255,0.6); }
 
  /* ─── DIVIDER ─────────────────────────────────────── */
  .section-divider { width: 1px; height: 40px; background: rgba(255,255,255,0.2); }
 
  /* ─── ANIMATIONS ─────────────────────────────────── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(28px); }
    to   { opacity: 1; transform: translateY(0); }
  }
 
  .hero-content h1 { animation: fadeUp 1s ease both 0.3s; }
  .hero-content p  { animation: fadeUp 1s ease both 0.5s; }
  .hero-content a  { animation: fadeUp 1s ease both 0.7s; }
  .hero-badge      { animation: fadeUp 1s ease both 0.9s; }
 
  /* ─── RESPONSIVE ─────────────────────────────────── */
  @media (max-width: 1024px) {
    nav { padding: 16px 24px; }
    .nav-links { gap: 20px; }
    .section-products, .section-why, .section-cta { padding: 70px 32px; }
    .inspire-text { padding: 60px 40px; }
    .collection-header { padding: 0 32px 40px; }
    footer { padding: 60px 32px 24px; }
    .products-grid, .collection-grid { grid-template-columns: repeat(2, 1fr); }
    .why-grid { grid-template-columns: repeat(2, 1fr); }
    .footer-top { grid-template-columns: 1fr 1fr; }
    .section-cta { grid-template-columns: 1fr; }
    .section-inspire { grid-template-columns: 1fr; }
    .inspire-image { height: 380px; }
  }
 
  @media (max-width: 768px) {
    .nav-links { display: none; }
    .hero-content { padding: 0 24px; }
    .hero-badge { right: 24px; bottom: 24px; max-width: 200px; }
    .products-header { flex-direction: column; align-items: flex-start; }
    .why-header { flex-direction: column; }
    .why-header p { text-align: left; }
    .footer-top { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>
 
<!-- ═══ NAVBAR ═══════════════════════════════════════════ -->
<nav>
  <a href="#" class="nav-logo">
    <div class="logo-mark">Y</div>
    <span class="logo-text">Your Logo</span>
  </a>
 
  <ul class="nav-links">
    <li><a href="#">Home</a></li>
    <li><a href="#">Products</a></li>
    <li><a href="#">Collections</a></li>
    <li><a href="#">Projects</a></li>
    <li><a href="#">About Us</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
 
  <div class="nav-right">
    <a href="#" class="btn-outline">Get In Touch</a>
    <button class="hamburger" aria-label="Menu">
      <svg width="14" height="10" viewBox="0 0 14 10" fill="none" stroke-width="1.5">
        <line x1="0" y1="1" x2="14" y2="1"/>
        <line x1="0" y1="5" x2="14" y2="5"/>
        <line x1="0" y1="9" x2="14" y2="9"/>
      </svg>
    </button>
  </div>
</nav>
 
<!-- ═══ HERO ═════════════════════════════════════════════ -->
<section class="hero">
  <div class="hero-bg"></div>
 
  <div class="hero-content">
    <h1>Simply<br>Beautiful Design</h1>
    <p>Innovative textures, elegant bathrooms and luxurious home accessories and furniture.</p>
    <a href="#" class="btn-circle">
      <span class="circle-icon">
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" stroke="white" stroke-width="1.5">
          <circle cx="7" cy="7" r="6"/>
          <line x1="5" y1="7" x2="9" y2="7"/>
          <polyline points="7,5 9,7 7,9"/>
        </svg>
      </span>
      Explore Collection
    </a>
  </div>
 
  <!-- Slide counter badge -->
  <div class="hero-badge">
    <div class="badge-title">The Adda bathroom collection</div>
    <div class="badge-sub">The enduring beauty of natural stone meets the warmth of wood</div>
    <div class="badge-nav">
      <span class="badge-counter">9 / 9</span>
      <div class="badge-progress"></div>
      <div class="badge-arrows">
        <span>←</span>
        <span>→</span>
      </div>
    </div>
  </div>
 
  <!-- Chat icon -->
  <div class="chat-bubble" style="position:absolute;right:0;bottom:180px;">
    <svg width="16" height="16" viewBox="0 0 16 16" fill="none" stroke="white" stroke-width="1.5">
      <path d="M14 10a2 2 0 01-2 2H5l-3 3V4a2 2 0 012-2h8a2 2 0 012 2z"/>
    </svg>
  </div>
</section>
 
<!-- ═══ PRODUCTS ══════════════════════════════════════════ -->
<section class="section-products">
  <p class="section-label">Our Products</p>
 
  <div class="products-header">
    <h2>Premium Surfaces.<br>Timeless Beauty.</h2>
    <div class="products-header-right">
      <p>Handpicked natural stones and premium surfaces crafted for luxury living.</p>
      <button class="btn-arrow" aria-label="View all">
        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" stroke="#1a1a18" stroke-width="1.5">
          <line x1="3" y1="8" x2="13" y2="8"/>
          <polyline points="9,4 13,8 9,12"/>
        </svg>
      </button>
    </div>
  </div>
 
  <div class="products-grid">
    <!-- Marble -->
    <div class="product-card">
      <div class="product-card-bg marble-bg"></div>
      <div class="product-card-overlay"></div>
      <button class="product-card-plus">
        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" stroke="white" stroke-width="1.5">
          <line x1="6" y1="1" x2="6" y2="11"/>
          <line x1="1" y1="6" x2="11" y2="6"/>
        </svg>
      </button>
      <div class="product-card-info">
        <div class="product-card-name">Marble</div>
        <div class="product-card-link">Explore →</div>
      </div>
    </div>
 
    <!-- Granite -->
    <div class="product-card">
      <div class="product-card-bg granite-bg"></div>
      <div class="product-card-overlay"></div>
      <button class="product-card-plus">
        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" stroke="white" stroke-width="1.5">
          <line x1="6" y1="1" x2="6" y2="11"/>
          <line x1="1" y1="6" x2="11" y2="6"/>
        </svg>
      </button>
      <div class="product-card-info">
        <div class="product-card-name">Granite</div>
        <div class="product-card-link">Explore →</div>
      </div>
    </div>
 
    <!-- Onyx -->
    <div class="product-card">
      <div class="product-card-bg onyx-bg"></div>
      <div class="product-card-overlay"></div>
      <button class="product-card-plus">
        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" stroke="white" stroke-width="1.5">
          <line x1="6" y1="1" x2="6" y2="11"/>
          <line x1="1" y1="6" x2="11" y2="6"/>
        </svg>
      </button>
      <div class="product-card-info">
        <div class="product-card-name">Onyx</div>
        <div class="product-card-link">Explore →</div>
      </div>
    </div>
 
    <!-- Travertine -->
    <div class="product-card">
      <div class="product-card-bg travertine-bg"></div>
      <div class="product-card-overlay"></div>
      <button class="product-card-plus">
        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" stroke="white" stroke-width="1.5">
          <line x1="6" y1="1" x2="6" y2="11"/>
          <line x1="1" y1="6" x2="11" y2="6"/>
        </svg>
      </button>
      <div class="product-card-info">
        <div class="product-card-name">Travertine</div>
        <div class="product-card-link">Explore →</div>
      </div>
    </div>
  </div>
</section>
 
<!-- ═══ INSPIRE ═══════════════════════════════════════════ -->
<section class="section-inspire">
  <div class="inspire-text">
    <h2>Designed For<br>Spaces That<br>Inspire</h2>
    <p>From interiors to exteriors, our surfaces bring elegance, durability and sophistication to every detail.</p>
    <a href="#" class="btn-circle-dark">
      <span class="circle-icon">
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" stroke="white" stroke-width="1.5">
          <line x1="3" y1="7" x2="11" y2="7"/>
          <polyline points="7,3 11,7 7,11"/>
        </svg>
      </span>
      View Projects
    </a>
  </div>
 
  <div class="inspire-image">
    <div class="inspire-image-bg"></div>
    <div class="inspire-desk"></div>
  </div>
</section>
 
<!-- ═══ WHY CHOOSE ════════════════════════════════════════ -->
<section class="section-why">
  <div class="why-header">
    <h2>Why Choose Y?</h2>
    <p>Quality, craftsmanship and trust at the heart of everything we do.</p>
  </div>
 
  <div class="why-grid">
    <div class="why-item">
      <svg class="why-icon" viewBox="0 0 40 40" fill="none" stroke="#1a1a18" stroke-width="1.2">
        <circle cx="20" cy="20" r="10"/>
        <circle cx="20" cy="20" r="18"/>
        <line x1="20" y1="2" x2="20" y2="10"/>
        <line x1="20" y1="30" x2="20" y2="38"/>
        <line x1="2" y1="20" x2="10" y2="20"/>
        <line x1="30" y1="20" x2="38" y2="20"/>
      </svg>
      <h3>Premium Quality</h3>
      <p>Handpicked natural stones of the finest quality.</p>
    </div>
    <div class="why-item">
      <svg class="why-icon" viewBox="0 0 40 40" fill="none" stroke="#1a1a18" stroke-width="1.2">
        <polygon points="20,4 36,34 4,34"/>
        <line x1="20" y1="16" x2="20" y2="24"/>
        <circle cx="20" cy="28" r="1" fill="#1a1a18"/>
      </svg>
      <h3>Expert Craftsmanship</h3>
      <p>Precision craftsmanship for perfect finishes.</p>
    </div>
    <div class="why-item">
      <svg class="why-icon" viewBox="0 0 40 40" fill="none" stroke="#1a1a18" stroke-width="1.2">
        <rect x="4" y="10" width="32" height="22" rx="1"/>
        <line x1="4" y1="16" x2="36" y2="16"/>
        <line x1="14" y1="10" x2="14" y2="32"/>
        <line x1="26" y1="10" x2="26" y2="32"/>
      </svg>
      <h3>Wide Selection</h3>
      <p>A vast range of stones for every style.</p>
    </div>
    <div class="why-item">
      <svg class="why-icon" viewBox="0 0 40 40" fill="none" stroke="#1a1a18" stroke-width="1.2">
        <rect x="6" y="8" width="28" height="22" rx="1"/>
        <line x1="12" y1="8" x2="12" y2="30"/>
        <line x1="20" y1="8" x2="20" y2="30"/>
        <line x1="28" y1="8" x2="28" y2="30"/>
        <line x1="6" y1="18" x2="34" y2="18"/>
        <path d="M6 34 Q20 38 34 34"/>
      </svg>
      <h3>Trusted Worldwide</h3>
      <p>Delivering excellence across the globe.</p>
    </div>
  </div>
</section>
 
<!-- ═══ COLLECTION ════════════════════════════════════════ -->
<section class="section-collection">
  <div class="collection-header">
    <div>
      <p class="collection-label">Our Collection</p>
      <h2>Luxury In Every Detail</h2>
    </div>
    <div class="collection-header-right">
      <span class="view-all-text">View All</span>
      <button class="btn-arrow" style="border-color:rgba(255,255,255,0.2);" aria-label="View all">
        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" stroke="white" stroke-width="1.5">
          <line x1="3" y1="8" x2="13" y2="8"/>
          <polyline points="9,4 13,8 9,12"/>
        </svg>
      </button>
    </div>
  </div>
 
  <div class="collection-grid">
    <div class="collection-card">
      <div class="collection-card-bg bathroom-col"></div>
      <div class="collection-card-overlay"></div>
      <div class="collection-card-info">
        <div class="collection-card-name">Bathroom</div>
        <div class="collection-card-link">Explore →</div>
      </div>
    </div>
    <div class="collection-card">
      <div class="collection-card-bg kitchen-col"></div>
      <div class="collection-card-overlay"></div>
      <div class="collection-card-info">
        <div class="collection-card-name">Kitchen</div>
        <div class="collection-card-link">Explore →</div>
      </div>
    </div>
    <div class="collection-card">
      <div class="collection-card-bg living-col"></div>
      <div class="collection-card-overlay"></div>
      <div class="collection-card-info">
        <div class="collection-card-name">Living Area</div>
        <div class="collection-card-link">Explore →</div>
      </div>
    </div>
    <div class="collection-card">
      <div class="collection-card-bg wall-col"></div>
      <div class="collection-card-overlay"></div>
      <div class="collection-card-info">
        <div class="collection-card-name">Wall Cladding</div>
        <div class="collection-card-link">Explore →</div>
      </div>
    </div>
  </div>
</section>
 
<!-- ═══ CTA ═══════════════════════════════════════════════ -->
<section class="section-cta">
  <div class="cta-left">
    <h2>Let's Create Something<br><em>Extraordinary</em> Together</h2>
  </div>
  <div class="cta-mid">
    <p>Have a project in mind? Get in touch with our team for expert guidance and personalized support.</p>
  </div>
  <div>
    <a href="#" class="btn-filled">
      Get In Touch
      <span class="circle-icon">
        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" stroke="white" stroke-width="1.5">
          <line x1="2" y1="6" x2="10" y2="6"/>
          <polyline points="7,3 10,6 7,9"/>
        </svg>
      </span>
    </a>
  </div>
</section>
 
<!-- ═══ FOOTER ════════════════════════════════════════════ -->
<footer>
  <div class="footer-top">
    <div class="footer-brand">
      <div class="logo-mark" style="color:white;border-color:rgba(255,255,255,0.3);margin-bottom:16px;">Y</div>
      <span style="font-size:11px;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,0.5);display:block;margin-bottom:18px;">YOUR LOGO</span>
      <p>Bringing nature's finest surfaces to life with passion and precision.</p>
      <div class="footer-social">
        <div class="social-icon">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="rgba(255,255,255,0.55)" stroke-width="1.5">
            <rect x="2" y="2" width="20" height="20" rx="5"/>
            <circle cx="12" cy="12" r="4"/>
            <circle cx="17.5" cy="6.5" r="1" fill="rgba(255,255,255,0.55)" stroke="none"/>
          </svg>
        </div>
        <div class="social-icon">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="rgba(255,255,255,0.55)" stroke-width="1.5">
            <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"/>
          </svg>
        </div>
        <div class="social-icon">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="rgba(255,255,255,0.55)" stroke-width="1.5">
            <path d="M2 3h6a4 4 0 014 4v14a3 3 0 00-3-3H2z"/>
            <path d="M22 3h-6a4 4 0 00-4 4v14a3 3 0 013-3h7z"/>
          </svg>
        </div>
      </div>
    </div>
 
    <div class="footer-col">
      <h4>Quick Links</h4>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">Collections</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </div>
 
    <div class="footer-col">
      <h4>Products</h4>
      <ul>
        <li><a href="#">Marble</a></li>
        <li><a href="#">Granite</a></li>
        <li><a href="#">Onyx</a></li>
        <li><a href="#">Travertine</a></li>
      </ul>
    </div>
 
    <div class="footer-col">
      <h4>Contact</h4>
      <div class="footer-contact-item">+971 58 123 4567</div>
      <div class="footer-contact-item">info@example.com</div>
      <div class="footer-contact-item">Dubai, UAE</div>
    </div>
 
    <div class="footer-col footer-newsletter">
      <h4>Newsletter</h4>
      <p>Stay updated with our latest collections and offers.</p>
      <div class="newsletter-form">
        <input type="email" placeholder="Enter your email"/>
        <button aria-label="Subscribe">
          <svg width="14" height="14" viewBox="0 0 14 14" fill="none" stroke="white" stroke-width="1.5">
            <line x1="2" y1="7" x2="12" y2="7"/>
            <polyline points="8,3 12,7 8,11"/>
          </svg>
        </button>
      </div>
    </div>
  </div>
 
  <div class="footer-bottom">
    <p>© 2025 Your Company. All Rights Reserved.</p>
    <div class="footer-bottom-links">
      <a href="#">Privacy Policy</a>
      <a href="#">Terms & Conditions</a>
    </div>
  </div>
</footer>
 
</body>
</html>
