# nashoe
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>StepStyle Shoes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4; /* Light gray background */
      margin: 0;
      padding: 0;
      color: #111; /* Dark text for readability */
    }
    header {
      background-color: #111; /* Black header */
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background-color: #333; /* Dark gray nav */
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: white;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }
    .product {
      background-color: white;
      width: 220px;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 10px;
    }
    a {
      color: #333;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>StepStyle Shoes</h1>
    <p>Where Comfort Meets Class</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Shoes</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome to StepStyle!</h2>
    <p>Premium shoes for every step you take.</p>
  </section>

  <!-- Products Section -->
  <section id="products">
    <h2>Our Featured Shoes</h2>
    <div class="products">
      <div class="product">
        <a href="shoe1.jpg" target="_blank">
          <img src="shoe1.jpg" alt="White Sneakers">
        </a>
        <h3>White Sneakers</h3>
        <p>₱1,299</p>
      </div>
      <div class="product">
        <a href="shoe2.jpg" target="_blank">
          <img src="shoe2.jpg" alt="Black Runners">
        </a>
        <h3>Black Runners</h3>
        <p>₱1,499</p>
      </div>
      <div class="product">
        <a href="shoe3.jpg" target="_blank">
          <img src="shoe3.jpg" alt="Gray Slip-ons">
        </a>
        <h3>Gray Slip-ons</h3>
        <p>₱1,699</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:stepstyle@gmail.com">stepstyle@gmail.com</a></p>
    <p>Phone: <a href="tel:+639123456789">0912-345-6789</a></p>
    <p>Facebook: <a href="https://facebook.com/stepstyle" target="_blank">StepStyle Shoes</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 StepStyle Shoes. All rights reserved.</p>
  </footer>

</body>
</html>
