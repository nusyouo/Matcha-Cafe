<!DOCTYPE html>
<html>
<head>
  <title>Matcha Cafe</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <!-- Add Poppins font here -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body, html {
      height: 100%;
      font-family: 'Poppins', sans-serif; /* Apply Poppins font */
      color: #333333;
      background-color: #f2f8f3;
    }

    /* Header Font */
    h1, h2, h3, h4, h5, h6 {
      font-family: 'Poppins', sans-serif; /* Apply Poppins font to headers */
      color: #3b7240;
    }

    /* Link and Button Colors */
    a, button {
      color: #ffffff;
      background-color: #5c9a63;
    }

    a:hover, button:hover {
      background-color: #49784b;
    }

    /* Custom Styles */
    header {
      background: url('https://files.oaiusercontent.com/file-Q9PNEfwSFSWn6CXULijSow?se=2024-11-23T04%3A41%3A05Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D79b6d396-1490-46ca-9bbb-f98f37be7771.webp&sig=JWG4RMyq/PXf8pwaauryoXUKtJp0WFPpL2UwItaOoKY%3D') no-repeat center center;
      background-size: cover;
      height: 100vh;
    }

    .matcha-title {
      font-size: 3em;
      color: white;
      text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
    }

    .w3-green-dark {
      background-color: #3b7240 !important;
    }

    .footer-text {
      color: #f2f8f3;
    }

    .section-spacing {
      padding: 64px 16px;
    }

    .w3-card {
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .w3-button {
      transition: 0.3s;
    }
  </style>
</head>
<body>

<!-- Navigation Bar -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-green-dark">
    <div class="w3-col s3"><a href="#" class="w3-button w3-block w3-green-dark">HOME</a></div>
    <div class="w3-col s3"><a href="#about" class="w3-button w3-block w3-green-dark">ABOUT</a></div>
    <div class="w3-col s3"><a href="#menu" class="w3-button w3-block w3-green-dark">MENU</a></div>
    <div class="w3-col s3"><a href="#where" class="w3-button w3-block w3-green-dark">WHERE</a></div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-middle w3-center">
    <span class="matcha-title">Sip Sip<br>The Exquisite Matcha Cafe in Bangi</span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large w3-opacity-min">
    <span class="w3-text-white w3-large">24 Jalan Matcha, 4778</span>
  </div>
</header>

<!-- About Section -->
<div class="w3-container section-spacing" id="about">
  <div class="w3-content" style="max-width:700px">
    <h2 class="w3-center w3-text-green-dark">About the Cafe</h2>
    <p>This cafe specializes in crafting the finest matcha beverages, using only the highest quality matcha sourced from Japan. Our passion for matcha began with a dream to bring the rich, creamy, and earthy flavors of this ancient green tea to the hearts of our customers. After months of testing and perfecting our recipes, we proudly present a menu of drinks tailored to satisfy every taste, from the sweet-tooth craving to those seeking a more traditional, calming matcha experience.</p>
<p> At Sip Sip Matcha Cafe, we believe in using fresh, locally-sourced ingredients that complement the vibrant flavors of matcha. Our drinks are more than just beverages—they're a celebration of health, flavor, and the vibrant Japanese culture. We offer a variety of matcha beverages, ranging from the classic Matcha Latte to inventive creations like the Strawberry Matcha and Blueberry Matcha, ensuring that every sip is a refreshing experience. Our specialty matcha powder, sourced directly from Kyoto, Japan, is of the highest quality, adding a premium touch to every drink. </p>
    <div class="w3-panel w3-leftbar w3-light-grey">

<!-- Image Display -->
    <div class="menu-image-container" style="text-align: center;">
      <img src="https://lh4.googleusercontent.com/sS_JY_eYiVq2zT3RFLef0hgHLpcha6TvJfZMG5_9fCYgaP01Gl-BkuOWucmjYtDxdNhZBFaV_WeG6YDkqM5iV41vaLfS4TxRWT5Vxkk0QjEeoDUIWOpQUEm55kPAlww3Zw=w1280" alt="Cafe Menu" style="max-width:50%; height:auto; border-radius: 8px; margin-bottom: 30px;">
    </div>

      <p><i>"Meow meow meow meowtcha" Fresh is the new sweet.</i></p>
      <p>Chef, Coffeeist, and Owner: Nusaybah Raihan</p>
    </div>
    <p><strong>Opening hours:</strong> Everyday from 8am to 8pm.</p>
    <p><strong>Address:</strong> 24 Jalan Matcha, 4778, Bangi</p>
  </div>
</div>

<!-- Menu Section -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:900px">

    <!-- Section Title -->
    <h5 class="w3-center w3-padding-48">
      <span class="w3-tag w3-white w3-round w3-white w3-xlarge">THE MENU</span>
    </h5>

    <!-- Image Display -->
    <div class="menu-image-container" style="text-align: center;">
      <img src="https://img.freepik.com/premium-photo/green-matcha-tea-drink-green-background-ai-generated_154515-10538.jpg" alt="Cafe Menu" style="max-width:100%; height:auto; border-radius: 8px; margin-bottom: 30px;">
    </div>

    <!-- Matcha Section -->
    <div class="w3-card w3-white w3-margin w3-padding w3-round-large">
      <h4 class="w3-green-dark w3-padding w3-round w3-text-white">🍵 Matcha Drinks</h4>
      <div class="w3-section">
        <p><strong>Matcha Latte</strong><br><span class="w3-text-grey">Matcha with fresh milk</span> <span class="w3-right"><strong>5.50</strong></span></p>
        <hr>
        <p><strong>Strawberry Matcha</strong><br><span class="w3-text-grey">Matcha with fresh milk + fresh strawberry syrup</span> <span class="w3-right"><strong>6.00</strong></span></p>
        <hr>
        <p><strong>Blueberry Matcha</strong><br><span class="w3-text-grey">Matcha with fresh milk + fresh blueberry syrup</span> <span class="w3-right"><strong>6.00</strong></span></p>
        <hr>
        <p><strong>Peach Matcha</strong><br><span class="w3-text-grey">Matcha with fresh milk + fresh peach syrup</span> <span class="w3-right"><strong>7.00</strong></span></p>
        <hr>
        <p><strong>Premium Matcha</strong><br><span class="w3-text-grey">Matcha using Sip Sip Matcha powder</span> <span class="w3-right"><strong>7.50</strong></span></p>
        <hr>
        <p><strong>Raspberry Matcha</strong><br><span class="w3-text-grey">Matcha with fresh milk + fresh raspberry syrup</span> <span class="w3-right"><strong>7.00</strong></span></p>
    </div>
</div>

<!-- Contact Section -->
<div class="w3-container" id="where">
  <div class="w3-padding-64 w3-center">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <p><input class="w3-input w3-padding-16 w3-border w3-round" type="text" placeholder="Name" required></p>
      <p><input class="w3-input w3-padding-16 w3-border w3-round" type="number" placeholder="Number of People" required></p>
      <p><input class="w3-input w3-padding-16 w3-border w3-round" type="datetime-local" required></p>
      <p><textarea class="w3-input w3-padding-16 w3-border w3-round" placeholder="Message / Special Requirements" rows="4" required></textarea></p>
      <p><button class="w3-button w3-green-dark w3-round" type="submit">Send Message</button></p>
    </form>
  </div>
</div>

<p>THIS IS A CLASS ASSIGNMENT AND EVERY IMAGE USED IS AI GENERATED EXCEPT NUSAYBAH 2319606 TMGT 2315
THANK YOU</p>

<!-- Footer -->
<footer class="w3-center w3-green-dark w3-padding-48">
  <p class="footer-text">Powered by 
    <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-light-grey">W3.CSS</a>
  </p>
</footer>

<!-- Add JavaScript just before the closing </body> tag -->
<script>
  // Smooth scroll for navigation links
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      document.querySelector(this.getAttribute('href')).scrollIntoView({
        behavior: 'smooth'
      });
    });
  });

  // Form submit alert
  document.getElementById("contactForm").addEventListener("submit", function (event) {
    event.preventDefault(); // Prevents actual form submission for demo purposes
    alert("Your message has been sent!");
  });
</script>

</body>
</html>
