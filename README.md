<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KESEREWear | Active Apparel for All</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background: #fff;
      color: #111;
      line-height: 1.6;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-size: 1.8rem;
    }
    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1602810313346-2f88de9d5d9e') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 120px 20px;
    }
    .hero h2 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 60px 20px;
    }
    .product {
      border: 1px solid #ddd;
      padding: 20px;
      text-align: center;
    }
    .product img {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      margin-bottom: 15px;
    }
    .product h3 {
      font-size: 1.2rem;
      margin-bottom: 10px;
    }
    .product p {
      font-size: 1rem;
      margin-bottom: 15px;
    }
    .product button {
      background: #000;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>KESEREWear</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#products">Shop</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Activewear That Moves With You</h2>
    <p>Bold designs. Built for performance. Made for men, women & youth.</p>
  </section>
  <section class="products" id="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1600180758890-6f1923fbdffc" alt="T-shirt">
      <h3>KESERE Logo Tee</h3>
      <p>Minimalist fit with maximum impact.</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1574680096145-d03f3eebfeba" alt="Hoodie">
      <h3>KESERE Hoodie</h3>
      <p>Warm, breathable, and boldly branded.</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1584945460010-9b56c016b1a9" alt="Joggers">
      <h3>KESERE Joggers</h3>
      <p>Built to move, styled to last.</p>
      <button>Add to Cart</button>
    </div>
  </section>
  <footer>
    <p>&copy; 2025 KESEREWear. All rights reserved.</p>
  </footer>
</body>
</html>
