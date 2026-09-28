<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nawar Perfumes | Chattogram</title>

  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      font-family:Arial,sans-serif;
      background:#0b0b0b;
      color:#fff;
    }

    nav{
      padding:20px 7%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
      z-index:1000;
      background:rgba(10,10,10,.96);
      border-bottom:1px solid #8f713b;
    }

    .logo{
      font-family:Georgia,serif;
      font-size:27px;
      color:#d4af62;
      letter-spacing:3px;
      font-weight:bold;
    }

    .menu{
      display:flex;
      gap:25px;
    }

    .menu a{
      color:white;
      text-decoration:none;
      font-size:14px;
    }

    .menu a:hover{color:#d4af62}

    .hero{
      min-height:90vh;
      display:flex;
      align-items:center;
      padding:70px 8%;
      background:
        radial-gradient(circle at 80% 40%,#46371e 0%,transparent 30%),
        linear-gradient(120deg,#0b0b0b,#19150e);
    }

    .hero-content{max-width:700px}

    .small-title{
      color:#d4af62;
      letter-spacing:5px;
      font-size:12px;
      margin-bottom:20px;
    }

    .hero h1{
      font-family:Georgia,serif;
      font-size:clamp(55px,9vw,100px);
      line-height:.95;
    }

    .hero h1 span{
      color:#d4af62;
      font-style:italic;
    }

    .hero p{
      color:#bdbdbd;
      max-width:500px;
      margin:30px 0;
      line-height:1.8;
    }

    .button{
      display:inline-block;
      padding:15px 28px;
      margin:5px;
      border:1px solid #d4af62;
      color:white;
      text-decoration:none;
      text-transform:uppercase;
      font-size:12px;
      letter-spacing:1px;
      transition:.3s;
    }

    .button:hover{
      background:#d4af62;
      color:#000;
    }

    section{padding:100px 8%}

    .section-title{
      text-align:center;
      margin-bottom:50px;
    }

    .section-title small{
      color:#d4af62;
      letter-spacing:4px;
    }

    .section-title h2{
      font-family:Georgia,serif;
      font-size:50px;
      margin-top:10px;
    }

    .section-title p{
      color:#999;
      margin-top:15px;
    }

    .products{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:25px;
    }

    .product{
      background:#151515;
      border:1px solid #30291e;
    }

    .product-image{
      height:350px;
      display:flex;
      align-items:center;
      justify-content:center;
      background:radial-gradient(circle,#514329,#171717 55%);
      color:#9d8b68;
      letter-spacing:3px;
      font-size:11px;
    }

    .product-info{padding:25px}

    .product-info h3{
      font-family:Georgia,serif;
      font-size:28px;
    }

    .product-info p{
      color:#999;
      margin:8px 0 15px;
      font-size:13px;
    }

    .price{
      color:#d4af62;
      font-size:20px;
      font-weight:bold;
      margin-bottom:20px;
    }

    .about{
      background:#151515;
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:70px;
      align-items:center;
    }

    .about h2{
      font-family:Georgia,serif;
      font-size:58px;
    }

    .about p{
      color:#aaa;
      line-height:1.9;
    }

    .location{
      text-align:center;
      background:
        radial-gradient(circle at center,#302719,#0b0b0b 55%);
    }

    .location h2{
      font-family:Georgia,serif;
      font-size:55px;
      margin:15px 0;
    }

    .location p{
      color:#aaa;
      margin-bottom:15px;
    }

    .address{
      color:#d4af62;
      line-height:1.8;
      margin-bottom:25px;
    }

    .contact{text-align:center}

    .contact-box{
      max-width:850px;
      margin:auto;
      border:1px solid #5d4a2a;
      padding:60px 30px;
    }

    .contact h2{
      font-family:Georgia,serif;
      font-size:50px;
    }

    .contact p{
      color:#aaa;
      margin:20px 0 30px;
    }

    .phone{
      color:#d4af62;
      font-size:25px;
      margin-bottom:25px;
    }

    footer{
      padding:40px 8%;
      border-top:1px solid #29251e;
      text-align:center;
      color:#777;
    }

    footer .logo{margin-bottom:10px}

    @media(max-width:800px){
      .menu{gap:10px}
      .menu a{font-size:11px}
      .products{grid-template-columns:1fr}
      .about{grid-template-columns:1fr}
      .hero h1{font-size:60px}
      .section-title h2,
      .location h2,
      .contact h2,
      .about h2{font-size:42px}
    }
  </style>
</head>

<body>

<nav>
  <div class="logo">NAWAR</div>

  <div class="menu">
    <a href="#home">Home</a>
    <a href="#collection">Collection</a>
    <a href="#about">About</a>
    <a href="#location">Location</a>
    <a href="#contact">Contact</a>
  </div>
</nav>


<!-- HOME -->

<section class="hero" id="home">

  <div class="hero-content">

    <div class="small-title">
      THE ART OF FRAGRANCE
    </div>

    <h1>
      A scent that
      <span>stays.</span>
    </h1>

    <p>
      Discover beautiful fragrances made for people
      who want their presence to be remembered.
    </p>

    <a href="#collection" class="button">
      Explore Collection
    </a>

    <a
      href="tel:01888037830"
      class="button">
      Call Now
    </a>

  </div>

</section>


<!-- COLLECTION -->

<section id="collection">

  <div class="section-title">

    <small>OUR COLLECTION</small>

    <h2>Find Your Signature Scent</h2>

    <p>
      Our perfume collection will be updated soon.
    </p>

  </div>

  <div class="products">

    <div class="product">

      <div class="product-image">
        PRODUCT IMAGE
      </div>

      <div class="product-info">
        <h3>Coming Soon</h3>

        <p>
          Nawar Perfumes Collection
        </p>

        <div class="price">
          Available Soon
        </div>

      </div>

    </div>


    <div class="product">

      <div class="product-image">
        PRODUCT IMAGE
      </div>

      <div class="product-info">
        <h3>Coming Soon</h3>

        <p>
          Nawar Perfumes Collection
        </p>

        <div class="price">
          Available Soon
        </div>

      </div>

    </div>


    <div class="product">

      <div class="product-image">
        PRODUCT IMAGE
      </div>

      <div class="product-info">
        <h3>Coming Soon</h3>

        <p>
          Nawar Perfumes Collection
        </p>

        <div class="price">
          Available Soon
        </div>

      </div>

    </div>

  </div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

  <div>

    <div class="small-title">
      ABOUT NAWAR
    </div>

    <h2>
      Fragrance with a feeling.
    </h2>

  </div>

  <div>

    <p>
      Nawar Perfumes brings together beautiful
      fragrances for people who want their scent
      to feel personal, memorable and elegant.
    </p>

    <br>

    <p>
      Visit our store in Chattogram and discover
      fragrances that match your personality and style.
    </p>

  </div>

</section>


<!-- LOCATION -->

<section class="location" id="location">

  <div class="small-title">
    VISIT US
  </div>

  <h2>
    Find Nawar Perfumes
  </h2>

  <p>
    Visit our store in Chattogram.
  </p>

  <div class="address">
    Level-4, Shop No. 29/30<br>
    Moti Complex, Chattogram 4212<br>
    Plus Code: 9R5P+9Q Chattogram
  </div>

  <a
    href="https://maps.app.goo.gl/X9RNGvMzR1zcCFb38"
    target="_blank"
    class="button">

    Open Google Maps

  </a>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

  <div class="contact-box">

    <div class="small-title">
      GET IN TOUCH
    </div>

    <h2>
      Ready to find your scent?
    </h2>

    <p>
      Contact Nawar Perfumes for orders,
      product information and availability.
    </p>

    <div class="phone">
      01888037830
    </div>

    <a
      href="tel:01888037830"
      class="button">

      Call Us

    </a>

    <a
      href="https://wa.me/8801888037830"
      target="_blank"
      class="button">

      WhatsApp

    </a>

  </div>

</section>


<!-- FOOTER -->

<footer>

  <div class="logo">
    NAWAR
  </div>

  <p>
    Nawar Perfumes · Chattogram
  </p>

  <p>
    © 2026 Nawar Perfumes. All Rights Reserved.
  </p>

</footer>

</body>
</html># nawar-perfumes
