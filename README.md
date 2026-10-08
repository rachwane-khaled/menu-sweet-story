<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">


  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #f7f1ea;
      color: #34251f;
      font-family: 'Montserrat', sans-serif;
      padding: 35px 15px;
    }

    .menu {
      max-width: 900px;
      margin: auto;
      background: #fffaf5;
      padding: 60px 70px;
      border: 1px solid #d8c2ad;
      box-shadow: 0 15px 45px rgba(70, 45, 30, 0.12);
      position: relative;
    }

    /* Decorative border */
    .menu::before {
      content: "";
      position: absolute;
      inset: 14px;
      border: 1px solid #d8c2ad;
      pointer-events: none;
    }

    header {
      text-align: center;
      position: relative;
      z-index: 2;
      margin-bottom: 45px;
    }

    .small-title {
      font-size: 11px;
      letter-spacing: 5px;
      text-transform: uppercase;
      color: #9b7255;
      margin-bottom: 10px;
    }

    .logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 68px;
      font-weight: 600;
      letter-spacing: 2px;
      color: #4b3025;
      line-height: 0.9;
    }

    .tagline {
      margin-top: 15px;
      font-family: 'Cormorant Garamond', serif;
      font-size: 20px;
      font-style: italic;
      color: #9b7255;
    }

    .line {
      width: 80px;
      height: 1px;
      background: #b99678;
      margin: 20px auto;
    }

    .section {
      position: relative;
      z-index: 2;
      margin-bottom: 38px;
    }

    .section-title {
      text-align: center;
      font-family: 'Cormorant Garamond', serif;
      font-size: 30px;
      font-weight: 600;
      color: #5a3828;
      margin-bottom: 22px;
      letter-spacing: 1px;
    }

    .item {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      gap: 15px;
      padding: 13px 0;
      border-bottom: 1px dotted #cdb8a5;
    }

    .item:last-child {
      border-bottom: none;
    }

    .item-info h3 {
      font-family: 'Cormorant Garamond', serif;
      font-size: 22px;
      font-weight: 600;
      color: #3f2a21;
    }

    .description {
      font-size: 12px;
      color: #8b7668;
      margin-top: 3px;
      font-weight: 300;
    }

    .price {
      font-family: 'Cormorant Garamond', serif;
      font-size: 21px;
      font-weight: 600;
      color: #8c6248;
      white-space: nowrap;
    }

    .featured {
      background: #f2e7dc;
      padding: 18px 20px;
      margin: 12px -10px;
      border-left: 3px solid #a97958;
      border-bottom: none;
    }

    footer {
      text-align: center;
      position: relative;
      z-index: 2;
      margin-top: 40px;
      padding-top: 25px;
      border-top: 1px solid #d8c2ad;
    }

    .footer-logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 26px;
      font-weight: 600;
      color: #5a3828;
    }

    .footer-text {
      font-size: 11px;
      letter-spacing: 2px;
      color: #9b7255;
      margin-top: 7px;
      text-transform: uppercase;
    }

    @media (max-width: 600px) {
      body {
        padding: 15px 8px;
      }

      .menu {
        padding: 45px 25px;
      }

      .menu::before {
        inset: 8px;
      }

      .logo {
        font-size: 52px;
      }

      .section-title {
        font-size: 27px;
      }

      .item-info h3 {
        font-size: 19px;
      }
    }
  </style>
</head>

<body>

  <div class="menu">

    <header>
      <div class="small-title">Luxury Dessert Boutique</div>

      <div class="logo">Sweet Story</div>

      <div class="line"></div>

      <div class="tagline">
        Every dessert tells a story.
      </div>
    </header>


    <!-- CAKES -->
    <section class="section">
      <h2 class="section-title">Cakes</h2>

      <div class="item featured">
        <div class="item-info">
          <h3>Signature Chocolate Cake</h3>
          <p class="description">
            Rich chocolate sponge · Belgian chocolate cream
          </p>
        </div>
        <div class="price">$35</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Red Velvet</h3>
          <p class="description">
            Classic red velvet · Cream cheese frosting
          </p>
        </div>
        <div class="price">$38</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Vanilla Dream</h3>
          <p class="description">
            Vanilla sponge · Premium vanilla cream
          </p>
        </div>
        <div class="price">$32</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Lotus Cake</h3>
          <p class="description">
            Lotus biscuit · Cream · Caramel
          </p>
        </div>
        <div class="price">$36</div>
      </div>
    </section>


    <!-- TIRAMISU -->
    <section class="section">
      <h2 class="section-title">Tiramisu</h2>

      <div class="item featured">
        <div class="item-info">
          <h3>Classic Tiramisu</h3>
          <p class="description">
            Mascarpone · Espresso · Cocoa
          </p>
        </div>
        <div class="price">$8</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Pistachio Tiramisu</h3>
          <p class="description">
            Mascarpone · Pistachio cream · Espresso
          </p>
        </div>
        <div class="price">$9</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Lotus Tiramisu</h3>
          <p class="description">
            Mascarpone · Lotus cream · Biscuit
          </p>
        </div>
        <div class="price">$9</div>
      </div>
    </section>


    <!-- DESSERTS -->
    <section class="section">
      <h2 class="section-title">Desserts</h2>

      <div class="item">
        <div class="item-info">
          <h3>Chocolate Fondant</h3>
          <p class="description">
            Warm chocolate cake · Melting center
          </p>
        </div>
        <div class="price">$7</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Cheesecake</h3>
          <p class="description">
            Creamy cheesecake · Berry topping
          </p>
        </div>
        <div class="price">$7</div>
      </div>

      <div class="item">
        <div class="item-info">
          <h3>Pistachio Delight</h3>
          <p class="description">
            Pistachio cream · Crunchy biscuit
          </p>
        </div>
        <div class="price">$8</div>
      </div>
    </section>


    <footer>
      <div class="footer-logo">Sweet Story</div>
      <div class="footer-text">
        Crafted with love · Served with a story
      </div>
    </footer>

  </div>

</body>
</html>
```
