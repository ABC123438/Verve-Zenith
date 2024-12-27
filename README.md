# Verve-Zenith
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Verve Zenith - Hoodie Store</title>
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      background-color: #f8f9fa;
      color: #333;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, #333, #555);
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.2rem;
      font-weight: bold;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background: #444;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      margin: 0 10px;
      font-size: 1rem;
      font-weight: bold;
      border-radius: 5px;
    }
    nav a:hover {
      background: #555;
    }

    /* Main Container */
    .container {
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .container h2 {
      font-size: 1.8rem;
      text-align: center;
      margin-bottom: 20px;
      color: #222;
    }

    /* Product Grid */
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .product h3 {
      font-size: 1.2rem;
      margin-bottom: 10px;
      color: #555;
    }
    .product p {
      font-size: 1rem;
      color: #666;
      margin-bottom: 15px;
    }
    .product button {
      background: #28a745;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
    }
    .product button:hover {
      background: #218838;
    }

    /* WhatsApp Button */
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      border: none;
      border-radius: 50%;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
      cursor: pointer;
      transition: transform 0.3s;
    }
    .whatsapp-btn:hover {
      transform: scale(1.1);
    }
    .whatsapp-btn img {
      width: 30px;
      height: 30px;
    }

    /* Footer */
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 30px;
    }
    footer p {
      font-size: 0.9rem;
    }

    /* Media Queries */
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.5rem;
      }
      nav a {
        font-size: 0.9rem;
        padding: 8px 15px;
      }
      .container h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Verve Zenith Hoodie Store</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#shop">Shop</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="container" id="shop">
    <h2>Our Exclusive Collection</h2>
    <div class="product-grid">
      <div class="product">
        <img src="hoddie5.png" alt="Black Hoodie">
        <h3>Attack on titan</h3>
        <p>20%off 800</p>
        <button>cash on delivery</button>
      </div>
      <div class="product">
        <img src="hoodie2.jpg.png" alt="Gray Hoodie">
        <h3>Ryomen Sukuna</h3>
        <p>20%off 800</p>
        <button>cash on delivery</button>
      </div>
      <div class="product">
        <img src="hoodi3.png" alt="Red Hoodie">
        <h3>Shunsul kyoraku</h3>
        <p>20%off 800</p>
        <button>cash on delivery</button>
      </div>
      <div class="product">
        <img src="hoodi6.png" alt="Blue Hoodie">
        <h3>Baki</h3>
        <p>20%off 800</p>
        <button>cash on delivery</button>
      </div>
      <div class="product">
        <img src="hoodie1.jpg.png" alt="White Hoodie">
        <h3>Ryomen Sukuna</h3>
        <p>20%off800</p>
        <button>uplode soon</button>
      </div>
      <div class="product">
        <img src="Screenshot 2024-12-24 141439.png" alt="Green Hoodie">
        <h3>Luffy</h3>
        <p>20%off800</p>
        <button>upload soon</button>
      </div>
    </div>
  </div>
  <a href="https://chat.whatsapp.com/J6rtbIlCElXH9pzFCiXUYx" class="whatsapp-btn" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
  <footer>
    <p>To order please join on whatsapp and contact on Community Admin</p>
    <p>© 2025 Verve Zenith | All rights reserved.</p>
    <p>contacts +917874131655</p>
    <p>contacts +919054619314</p>
  </footer>
</body>
</html>
