<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Shopping</title>
  <link rel="icon" href="favicon.ico" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ff4081;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #f8f8f8;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 1rem;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #ff4081;
      text-decoration: underline;
    }
    .hero {
      background-color: #ffe6eb;
      padding: 2rem;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 1rem;
    }
    .product {
      border: 1px solid #ccc;
      padding: 1rem;
      text-align: center;
      width: 100%;
      max-width: 200px;
      flex: 1 1 200px;
      transition: all 0.3s ease-in-out;
    }
    .product:hover {
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transform: scale(1.03);
    }
    button {
      background-color: #ff4081;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #e60073;
    }
    footer {
      background-color: #ff4081;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Happy Shopping</h1>
    <p>Buy Everything You Need – All in One Place</p>
  </header>
  <nav>
    <a href="#home" aria-label="Go to Home">Home</a>
    <a href="#products" aria-label="Browse Products">Products</a>
    <a href="#contact" aria-label="Contact Us">Contact</a>
    <a href="#about" aria-label="About Us">About</a>
  </nav>
  <section class="hero" id="home">
    <h2>Welcome to Happy Shopping!</h2>
    <p>Best deals on clothes, electronics, home goods, and more.</p>
  </section>
  <section class="products" id="products">
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Stylish Shoes" />
      <h3>Stylish Shoes</h3>
      <p>Rs. 1,999</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Smartphone" />
      <h3>Smartphone</h3>
      <p>Rs. 25,000</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Kitchen Set" />
      <h3>Kitchen Set</h3>
      <p>Rs. 3,499</p>
      <button>Buy Now</button>
    </div>
  </section>
  <section id="contact" style="padding: 2rem; text-align: center;">
    <h2>Contact Us</h2>
    <p>WhatsApp: 03XX-XXXXXXX</p>
    <p>Email: happyshopping@example.com</p>
  </section>
  <section id="about" style="padding: 2rem; text-align: center;">
    <h2>About Us</h2>
    <p>We offer a variety of quality products with fast delivery and trusted service. Shop with confidence at Happy Shopping!</p>
  </section>
  <footer>
    <p>&copy; 2025 Happy Shopping. All rights reserved.</p>
  </footer>
</body>
</html>
