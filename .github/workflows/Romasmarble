<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Luxury Marble Studio</title>

  <!-- GOOGLE FONTS -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Cormorant+Garamond:wght@400;500;600&display=swap" rel="stylesheet">

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:'Inter',sans-serif;
      background:#f5f2ed;
      color:#111;
      overflow-x:hidden;
    }

    a{
      text-decoration:none;
      color:inherit;
    }

    img{
      width:100%;
      display:block;
    }

    .container{
      width:90%;
      max-width:1400px;
      margin:auto;
    }

    /* =========================
       HEADER
    ========================== */

    header{
      position:absolute;
      top:0;
      left:0;
      width:100%;
      z-index:100;
      padding:25px 0;
    }

    .navbar{
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .logo{
      color:white;
      font-size:34px;
      font-weight:600;
      letter-spacing:2px;
    }

    .nav-links{
      display:flex;
      gap:40px;
      color:white;
      font-size:14px;
    }

    .nav-right{
      display:flex;
      align-items:center;
      gap:20px;
    }

    .contact-btn{
      background:white;
      color:#111;
      padding:14px 28px;
      border-radius:40px;
      font-size:14px;
      font-weight:500;
    }

    /* =========================
       HERO
    ========================== */

    .hero{
      height:100vh;
      position:relative;
      background:url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=2000') center/cover no-repeat;
      display:flex;
      align-items:center;
    }

    .hero::after{
      content:'';
      position:absolute;
      inset:0;
      background:rgba(0,0,0,0.35);
    }

    .hero-content{
      position:relative;
      z-index:2;
      width:100%;
      color:white;
    }

    .hero-grid{
      display:grid;
      grid-template-columns:1fr 350px;
      align-items:end;
      gap:60px;
    }

    .hero-left h1{
      font-family:'Cormorant Garamond',serif;
      font-size:88px;
      line-height:0.95;
      font-weight:500;
      margin-bottom:30px;
    }

    .hero-left p{
      font-size:18px;
      width:70%;
      line-height:1.8;
      opacity:0.9;
      margin-bottom:40px;
    }

    .hero-btn{
      display:inline-block;
      padding:16px 34px;
      border:1px solid white;
      border-radius:40px;
      font-size:14px;
      transition:0.4s;
    }

    .hero-btn:hover{
      background:white;
      color:#111;
    }

    .hero-card{
      background:rgba(255,255,255,0.08);
      backdrop-filter:blur(10px);
      padding:35px;
      border:1px solid rgba(255,255,255,0.15);
    }

    .hero-card h3{
      font-size:26px;
      margin-bottom:20px;
      font-family:'Cormorant Garamond',serif;
    }

    .hero-card p{
      line-height:1.8;
      opacity:0.85;
    }

    /* =========================
       PRODUCTS
    ========================== */

    .products{
      padding:120px 0;
      background:#f7f4ef;
    }

    .section-top{
      display:flex;
      justify-content:space-between;
      margin-bottom:70px;
      align-items:end;
    }

    .section-title{
      font-size:62px;
      font-family:'Cormorant Garamond',serif;
      line-height:1;
      width:50%;
    }

    .section-desc{
      width:30%;
      line-height:1.8;
      color:#555;
    }

    .product-grid{
      display:grid;
      grid-template-columns:repeat(4,1fr);
      gap:25px;
    }

    .product-card{
      position:relative;
      overflow:hidden;
      cursor:pointer;
    }

    .product-card img{
      height:500px;
      object-fit:cover;
      transition:0.6s;
    }

    .product-card:hover img{
      transform:scale(1.08);
    }

    .product-info{
      position:absolute;
      bottom:25px;
      left:25px;
      color:white;
    }

    .product-info h4{
      font-size:28px;
      font-family:'Cormorant Garamond',serif;
      margin-bottom:8px;
    }

    /* =========================
       SHOWCASE
    ========================== */

    .showcase{
      background:#0f0f0f;
      color:white;
      padding:120px 0;
    }

    .showcase-grid{
      display:grid;
      grid-template-columns:400px 1fr;
      gap:70px;
      align-items:center;
    }

    .showcase h2{
      font-size:68px;
      font-family:'Cormorant Garamond',serif;
      line-height:1;
      margin-bottom:30px;
    }

    .showcase p{
      line-height:1.9;
      opacity:0.8;
      margin-bottom:40px;
    }

    .showcase-btn{
      border:1px solid white;
      padding:14px 30px;
      display:inline-block;
      border-radius:40px;
    }

    .showcase img{
      height:650px;
      object-fit:cover;
    }

    /* =========================
       WHY US
    ========================== */

    .why{
      padding:120px 0;
    }

    .why-head{
      display:flex;
      justify-content:space-between;
      margin-bottom:70px;
    }

    .why h2{
      font-size:58px;
      font-family:'Cormorant Garamond',serif;
    }

    .why-grid{
      display:grid;
      grid-template-columns:repeat(4,1fr);
      gap:40px;
    }

    .why-card{
      padding:40px;
      background:white;
      border-radius:12px;
      transition:0.4s;
    }

    .why-card:hover{
      transform:translateY(-10px);
    }

    .why-card h4{
      margin:20px 0;
      font-size:22px;
    }

    .why-card p{
      line-height:1.8;
      color:#666;
    }

    /* =========================
       COLLECTION
    ========================== */

    .collection{
      background:#111;
      color:white;
      padding:120px 0;
    }

    .collection-head{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-bottom:50px;
    }

    .collection-head h2{
      font-size:64px;
      font-family:'Cormorant Garamond',serif;
    }

    .collection-grid{
      display:grid;
      grid-template-columns:repeat(4,1fr);
      gap:20px;
    }

    .collection-card{
      position:relative;
      overflow:hidden;
    }

    .collection-card img{
      height:380px;
      object-fit:cover;
      transition:0.6s;
    }

    .collection-card:hover img{
      transform:scale(1.08);
    }

    .collection-content{
      position:absolute;
      bottom:25px;
      left:25px;
    }

    .collection-content h4{
      font-size:30px;
      font-family:'Cormorant Garamond',serif;
      margin-bottom:10px;
    }

    /* =========================
       CTA
    ========================== */

    .cta{
      background:#111;
      color:white;
      padding:100px 0;
      border-top:1px solid rgba(255,255,255,0.08);
    }

    .cta-grid{
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .cta h2{
      font-size:60px;
      width:40%;
      font-family:'Cormorant Garamond',serif;
      line-height:1;
    }

    .cta-btn{
      padding:18px 40px;
      border-radius:50px;
      border:1px solid white;
    }

    /* =========================
       FOOTER
    ========================== */

    footer{
      background:#0b0b0b;
      color:white;
      padding:80px 0 40px;
    }

    .footer-grid{
      display:grid;
      grid-template-columns:2fr 1fr 1fr 1fr;
      gap:50px;
      margin-bottom:60px;
    }

    .footer-logo{
      font-size:42px;
      margin-bottom:20px;
      font-family:'Cormorant Garamond',serif;
    }

    .footer-desc{
      line-height:1.9;
      opacity:0.7;
      width:70%;
    }

    .footer-links h4{
      margin-bottom:25px;
      font-size:20px;
    }

    .footer-links a{
      display:block;
      margin-bottom:15px;
      opacity:0.7;
      transition:0.3s;
    }

    .footer-links a:hover{
      opacity:1;
    }

    .copyright{
      border-top:1px solid rgba(255,255,255,0.08);
      padding-top:30px;
      opacity:0.6;
      font-size:14px;
    }

    /* =========================
       RESPONSIVE
    ========================== */

    @media(max-width:1100px){

      .hero-grid,
      .showcase-grid,
      .footer-grid,
      .product-grid,
      .collection-grid,
      .why-grid{
        grid-template-columns:1fr;
      }

      .section-title,
      .section-desc,
      .cta h2,
      .hero-left p{
        width:100%;
      }

      .hero-left h1{
        font-size:58px;
      }

      .section-title,
      .showcase h2,
      .collection-head h2,
      .cta h2{
        font-size:48px;
      }

      .nav-links{
        display:none;
      }

      .cta-grid,
      .section-top,
      .why-head{
        flex-direction:column;
        gap:30px;
        align-items:flex-start;
      }

    }

  </style>
</head>
<body>

<!-- =========================
     HEADER
========================= -->

<header>
  <div class="container navbar">

    <div class="logo">
      ROMAS
    </div>

    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Collections</a>
      <a href="#">Projects</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>

    <div class="nav-right">
      <a href="#" class="contact-btn">Get In Touch</a>
    </div>

  </div>
</header>

<!-- =========================
     HERO
========================= -->

<section class="hero">

  <div class="container hero-content">

    <div class="hero-grid">

      <div class="hero-left">

        <h1>
          Discover The Art Of Luxury Marble
        </h1>

        <p>
          Premium marble, granite, onyx, quartz and travertine
          collections crafted for luxury villas, hotels and
          architectural spaces worldwide.
        </p>

        <a href="#" class="hero-btn">
          Explore Collection
        </a>

      </div>

      <div class="hero-card">

        <h3>
          Signature Collection
        </h3>

        <p>
          Timeless natural stone solutions designed to elevate
          interiors with elegance, sophistication and lasting beauty.
        </p>

      </div>

    </div>

  </div>

</section>

<!-- =========================
     PRODUCTS
========================= -->

<section class="products">

  <div class="container">

    <div class="section-top">

      <h2 class="section-title">
        Premium Surfaces. Timeless Beauty.
      </h2>

      <p class="section-desc">
        Handpicked natural stones sourced globally for luxurious
        architectural and interior projects.
      </p>

    </div>

    <div class="product-grid">

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?q=80&w=1200" alt="">
        <div class="product-info">
          <h4>Marble</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?q=80&w=1200" alt="">
        <div class="product-info">
          <h4>Granite</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1200" alt="">
        <div class="product-info">
          <h4>Onyx</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1200" alt="">
        <div class="product-info">
          <h4>Travertine</h4>
          <span>Explore →</span>
        </div>
      </div>

    </div>

  </div>

</section>

<!-- =========================
     SHOWCASE
========================= -->

<section class="showcase">

  <div class="container">

    <div class="showcase-grid">

      <div>

        <h2>
          Designed For Spaces That Inspire
        </h2>

        <p>
          From modern interiors to luxury hospitality spaces,
          our stones bring elegance, warmth and sophistication
          into every environment.
        </p>

        <a href="#" class="showcase-btn">
          View Projects
        </a>

      </div>

      <div>
        <img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?q=80&w=2000" alt="">
      </div>

    </div>

  </div>

</section>

<!-- =========================
     WHY CHOOSE US
========================= -->

<section class="why">

  <div class="container">

    <div class="why-head">

      <h2>
        Why Choose ROMAS?
      </h2>

      <p>
        Quality, craftsmanship and trust at the core of every project.
      </p>

    </div>

    <div class="why-grid">

      <div class="why-card">
        <h4>Premium Quality</h4>
        <p>
          Carefully sourced natural stones selected from the
          finest quarries worldwide.
        </p>
      </div>

      <div class="why-card">
        <h4>Expert Craftsmanship</h4>
        <p>
          Precision finishing and advanced cutting technology
          for flawless results.
        </p>
      </div>

      <div class="why-card">
        <h4>Wide Selection</h4>
        <p>
          Extensive collection of marble, granite, quartz,
          onyx and travertine surfaces.
        </p>
      </div>

      <div class="why-card">
        <h4>Global Delivery</h4>
        <p>
          Delivering premium stone materials across international
          architectural projects.
        </p>
      </div>

    </div>

  </div>

</section>

<!-- =========================
     COLLECTION
========================= -->

<section class="collection">

  <div class="container">

    <div class="collection-head">

      <h2>
        Luxury In Every Detail
      </h2>

      <a href="#">
        View All →
      </a>

    </div>

    <div class="collection-grid">

      <div class="collection-card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1200">
        <div class="collection-content">
          <h4>Bathrooms</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="collection-card">
        <img src="https://images.unsplash.com/photo-1600607687644-c7171b42498f?q=80&w=1200">
        <div class="collection-content">
          <h4>Kitchen</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="collection-card">
        <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?q=80&w=1200">
        <div class="collection-content">
          <h4>Living Area</h4>
          <span>Explore →</span>
        </div>
      </div>

      <div class="collection-card">
        <img src="https://images.unsplash.com/photo-1484154218962-a197022b5858?q=80&w=1200">
        <div class="collection-content">
          <h4>Wall Cladding</h4>
          <span>Explore →</span>
        </div>
      </div>

    </div>

  </div>

</section>

<!-- =========================
     CTA
========================= -->

<section class="cta">

  <div class="container">

    <div class="cta-grid">

      <h2>
        Let's Create Something Extraordinary Together
      </h2>

      <a href="#" class="cta-btn">
        Get In Touch
      </a>

    </div>

  </div>

</section>

<!-- =========================
     FOOTER
========================= -->

<footer>

  <div class="container">

    <div class="footer-grid">

      <div>

        <div class="footer-logo">
          ROMAS
        </div>

        <p class="footer-desc">
          Bringing luxury marble and premium natural surfaces
          into modern architectural and interior spaces.
        </p>

      </div>

      <div class="footer-links">

        <h4>Quick Links</h4>

        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Collections</a>
        <a href="#">Projects</a>

      </div>

      <div class="footer-links">

        <h4>Products</h4>

        <a href="#">Marble</a>
        <a href="#">Granite</a>
        <a href="#">Onyx</a>
        <a href="#">Travertine</a>

      </div>

      <div class="footer-links">

        <h4>Contact</h4>

        <a href="#">+973 5559 2717</a>
        <a href="#">info@romasmarble.com</a>
        <a href="#">Bahrain</a>

      </div>

    </div>

    <div class="copyright">
      © 2026 ROMAS Marble. All Rights Reserved.
    </div>

  </div>

</footer>

</body>
</html>
