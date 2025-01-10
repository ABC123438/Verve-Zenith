<!DOCTYPE html>
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
      font-size: 2rem;
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
      transition: background 0.3s;
      cursor: pointer;
    }
    nav a:hover {
      background: #555;
    }

    /* Section Styles */
    section {
      display: none;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    section.active {
      display: block;
    }
    h2 {
      font-size: 1.8rem;
      text-align: center;
      margin-bottom: 20px;
      color: #222;
    }
    .content {
      text-align: center;
      font-size: 1.1rem;
      color: #555;
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
    .product a {
      display: inline-block;
      background: #28a745;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .product a:hover {
      background: #218838;
    }

    /* Footer */
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 30px;
    }
    footer p {
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Verve Zenith Hoodie Store</h1>
  </header>
  <nav>
    <a href="#" onclick="showSection('home')">Home</a>
    <a href="#" onclick="showSection('shop')">Shop</a>
    <a href="#" onclick="showSection('contact')">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home" class="active">
    <h2>Welcome to Verve Zenith</h2>
    <div class="content">
      <p>Explore our exclusive collection of hoodies and premium wear. Style yourself with Verve Zenith!</p>
      <div class="product-grid">
        <!-- Product 1 -->
        <div class="product">
          <img src="hoodie1.jpg.png" alt="Hoodie 1">
        </div>
        <!-- Product 2 -->
        <div class="product">
          <img src="hoodie2.jpg.png" alt="Hoodie 2">
        </div>
        <!-- Product 3 -->
        <div class="product">
          <img src="hoodi3.png" alt="Hoodie 3">
        </div>
        <!-- Product 4 -->
        <div class="product">
          <img src="hoodi4.png" alt="Hoodie 4">
        </div>
        <!-- Product 5 -->
        <div class="product">
          <img src="hoddie5.png" alt="Hoodie 5">
        </div>
        <!-- Product 6 -->
        <div class="product">
          <img src="hoodi6.png" alt="Hoodie 6">
        </div>
        <!-- Product 7 -->
        <div class="product">
          <img src="Screenshot 2024-12-24 141439.png" alt="Hoodie 7">
        </div>
        <!-- Product 8 -->
        <div class="product">
          <img src="hoodi8.png" alt="Hoodie 8">
        </div>
        <!-- Product 9 -->
        <div class="product">
          <img src="hoodi9.png" alt="Hoodie 9">
        </div>
        <!-- Product 10 -->
        <div class="product">
          <img src="hoodi10.png" alt="Hoodie 10">
        </div>
         <!-- Product 11 -->
         <div class="product">
          <img src="hoodi11.png" alt="Hoodie 10">
        </div>
         <!-- Product 12 -->
         <div class="product">
          <img src="hoodi12.png" alt="Hoodie 10">
        </div>
        <!-- Repeat the same structure for more products -->
      </div>
    </div>
  </section>

  <!-- Shop Section -->
  <section id="shop">
    <h2>Our Hoodie Collection</h2>
    <div class="product-grid">
      <!-- Product 1 -->
      <div class="product">
        <img src="hoodie1.jpg.png" alt="Hoodie 1">
        <h3>Ryomen Sukuna</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 2 -->
      <div class="product">
        <img src="hoodie2.jpg.png" alt="Hoodie 2">
        <h3>Ryomen Sukuna</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 3 -->
      <div class="product">
        <img src="hoodi3.png" alt="Hoodie 2">
        <h3>shunsui kyoraku</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 4 -->
      <div class="product">
        <img src="hoodi4.png" alt="Hoodie 2">
        <h3>Toji fushiguro</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 5 -->
      <div class="product">
        <img src="hoddie5.png" alt="Hoodie 2">
        <h3>Attack on titan</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 6 -->
      <div class="product">
        <img src="hoodi6.png" alt="Hoodie 2">
        <h3>Baki Hanma</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 7 -->
      <div class="product">
        <img src="Screenshot 2024-12-24 141439.png" alt="Hoodie 2">
        <h3>Monkey D.Luffy</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 8 -->
      <div class="product">
        <img src="hoodi8.png" alt="Hoodie 2">
        <h3>Blue lock Nagi</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 9 -->
      <div class="product">
        <img src="hoodi9.png" alt="Hoodie 2">
        <h3>Goku black</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 10 -->
      <div class="product">
        <img src="hoodi10.png" alt="Hoodie 2">
        <h3>Vinland saga</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 11 -->
      <div class="product">
        <img src="hoodi11.png" alt="Hoodie 2">
        <h3>Prince vegeta</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Product 12 -->
      <div class="product">
        <img src="hoodi12.png" alt="Hoodie 2">
        <h3>Black clover Asta</h3>
        <p>₹800 (20% off)</p>
        <a href="https://www.instagram.com/vervezenith_co?igsh=Mmk1aXE4M3oyMjN5" target="_blank">Buy Now</a>
      </div>
      <!-- Add more products here as before -->
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <div class="content">
      <p>For orders and queries, join our WhatsApp community:</p>
      <p><strong>Contact:</strong> +91 9265481410 | +91 9998510217</p>
      <a href="https://chat.whatsapp.com/J6rtbIlCElXH9pzFCiXUYx" target="_blank">Join WhatsApp</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Verve Zenith | All rights reserved.</p>
  </footer>

  <script>
    function showSection(sectionId) {
      // Hide all sections
      const sections = document.querySelectorAll('section');
      sections.forEach(section => section.classList.remove('active'));

      // Show the selected section
      const activeSection = document.getElementById(sectionId);
      activeSection.classList.add('active');
    }
  </script>
</body>
</html>
