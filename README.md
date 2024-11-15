# Ryderszone

#HTML code for the Website 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ryders Zone</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
</head>
<body>
  <header class="main-header">
    <div class="logo">
      <img src="images/logo.png" alt="Ryders Zone Logo">
      <span>Ryders Zone</span>
    </div>
    <nav class="nav-links">
      <a href="collections.html">Collections</a>
      <a href="#skate">Skate</a>
      <a href="#bike">Bike</a>
      <a href="#accessories">Accessories</a>
    </nav>
  </header>

  <section class="banner">
    <div class="overlay">
      <h1>Unleash Your Ride</h1>
      <p>Top-Quality Parts & Gear for the Bold and Brave. Fuel Your Passion for Adventure!</p>
      <button class="cta-button" onclick="showPromo()">Check Our Latest Deals!</button>
    </div>
  </section>

  <main>
    <section class="products">
      <h2>Explore Our Products</h2>
      <div class="product-grid">
        <div class="product fade-in">
          <img src="images/bike-part.jpg" alt="Bike Part">
          <h3>Premium Bike Parts</h3>
          <p>Durable, high-performance parts for every rider.</p>
          <button class="buy-button">Shop Now</button>
        </div>
        <div class="product fade-in">
          <img src="images/skate-part.jpg" alt="Skate Part">
          <h3>Quality Skate Accessories</h3>
          <p>Boost your skate experience with premium gear.</p>
          <button class="buy-button">Shop Now</button>
        </div>
        <div class="product fade-in">
          <img src="images/accessory.jpg" alt="Accessory">
          <h3>Adventure Accessories</h3>
          <p>Stay equipped for every journey.</p>
          <button class="buy-button">Shop Now</button>
        </div>
      </div>
    </section>
  </main>

  <section class="promo" id="promo-section">
    <div class="promo-content">
      <h2>Exclusive Offer!</h2>
      <p>Get 20% off on all bike parts this week only!</p>
      <button class="close-button" onclick="closePromo()">Close</button>
    </div>
  </section>

  <section class="reviews">
    <h2>Customer Reviews</h2>
    <div class="review-container">
      <div class="review fade-in">
        <div class="review-header">
          <span class="reviewer-name">John Doe</span>
          <span class="review-rating">⭐⭐⭐⭐☆</span>
        </div>
        <p class="review-text">"Amazing quality parts! My bike feels like new, and the service was exceptional."</p>
      </div>
      <div class="review fade-in">
        <div class="review-header">
          <span class="reviewer-name">Sarah Smith</span>
          <span class="review-rating">⭐⭐⭐⭐⭐</span>
        </div>
        <p class="review-text">"Fantastic skateboard accessories! The grip tape is top-notch. Highly recommend!"</p>
      </div>
      <div class="review fade-in">
        <div class="review-header">
          <span class="reviewer-name">Alex Johnson</span>
          <span class="review-rating">⭐⭐⭐⭐☆</span>
        </div>
        <p class="review-text">"Good prices and fast shipping. Couldn't be happier with my purchase."</p>
      </div>
    </div>
    <div class="leave-review fade-in">
      <h3>Leave a Review</h3>
      <textarea placeholder="Write your review here..." rows="5"></textarea>
      <div class="rating">
        <label for="rating">Rating: </label>
        <select id="rating">
          <option value="1">⭐</option>
          <option value="2">⭐⭐</option>
          <option value="3">⭐⭐⭐</option>
          <option value="4">⭐⭐⭐⭐</option>
          <option value="5">⭐⭐⭐⭐⭐</option>
        </select>
      </div>
      <button class="submit-review">Submit Review</button>
    </div>
  </section>

  <section class="signup">
    <div class="signup-container">
      <div class="signup-text">
        <h2>SIGN UP...</h2>
        <p>For Priority Access to Releases, Deals & Offers</p>
      </div>
      <form id="signup-form">
        <input type="email" id="email" placeholder="Enter email address" required />
        <button type="submit" class="signup-button">SIGN ME UP</button>
      </form>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-container">
      <div class="footer-section">
        <h3>About Us</h3>
        <ul>
          <li><a href="#">Our Story</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Sustainability</a></li>
          <li><a href="#">Press</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h3>Customer Service</h3>
        <ul>
          <li><a href="#">Contact Us</a></li>
          <li><a href="#">Returns</a></li>
          <li><a href="#">Shipping Info</a></li>
          <li><a href="#">FAQ</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h3>Policies</h3>
        <ul>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Terms of Service</a></li>
          <li><a href="#">Refund Policy</a></li>
          <li><a href="#">Legal Notice</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h3>Follow Us</h3>
        <div class="social-links">
          <a href="#"><img src="icons/facebook.png" alt="Facebook"></a>
          <a href="#"><img src="icons/instagram.png" alt="Instagram"></a>
          <a href="#"><img src="icons/twitter.png" alt="Twitter"></a>
          <a href="#"><img src="icons/youtube.png" alt="YouTube"></a>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <p>&copy; 2024 Ryders Zone. All rights reserved. Designed by Bruno Muniz.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Fonts */
body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
}

/* Header */
.main-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #222;
  color: #fff;
}

.logo {
  display: flex;
  align-items: center;
}

.logo img {
  width: 40px;
  margin-right: 10px;
}

.nav-links a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #ffdd57;
}

/* Banner */
.banner {
  position: relative;
  background-image: url("images/banner-image.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 400px;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.overlay {
  text-align: center;
  padding: 20px;
  background: rgba(0, 0, 0, 0.6); /* Added overlay background for better text contrast */
}

.overlay h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.overlay p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.cta-button {
  padding: 10px 20px;
  font-size: 1rem;
  background-color: #ffdd57;
  color: #222;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #ffc107;
  color: #000;
}

/* General Button Styling - Applies to all buttons */
button {
  border-radius: 25px; /* Makes all buttons rounded */
  cursor: pointer;
  font-size: 16px;
  transition: background-color 0.3s ease;
}


/* Product Section */
.products {
  padding: 50px 20px;
  text-align: center;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.product {
  background: #f9f9f9;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.product img {
  max-width: 100%;
  height: auto;
  border-radius: 5px;
  margin-bottom: 15px;
}

.buy-button {
  padding: 10px 15px;
  font-size: 1rem;
  background-color: #222;
  color: #fff;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.buy-button:hover {
  background-color: #ffdd57;
  color: #000;
}

/* Promo Section */
.promo {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.8);
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.promo-content {
  background: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 8px;
  width: 90%;
  max-width: 400px;
}

.close-button {
  padding: 10px 20px;
  background-color: #222;
  color: #fff;
  border: none;
  cursor: pointer;
  margin-top: 15px;
  transition: background-color 0.3s ease;
}

.close-button:hover {
  background-color: #ffdd57;
}

/* Reviews */
.reviews {
  padding: 50px 20px;
  background-color: #f1f1f1;
}

.review-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.review {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.review-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.review-text {
  margin-top: 10px;
}

/* Leave a Review Section */
.leave-review {
  margin: 30px auto; /* Centers the box and adds space above and below */
  padding: 30px;
  max-width: 500px;
  background: #f9f9f9;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.reviews {
  padding: 50px 20px;
  background-color: #f1f1f1;
  margin-bottom: 50px; /* Adds more space below reviews */
}

.leave-review h3 {
  text-align: center;
  margin-bottom: 20px;
}


.leave-review textarea {
  width: 100%;
  height: 100px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  resize: vertical;
}

.submit-review {
  margin-top: 15px;
  padding: 10px 20px;
  width: 100%;
  background-color: #222;
  color: #fff;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.submit-review:hover {
  background-color: #ffdd57;
}

/* Signup Section */
.signup {
  padding: 50px 20px;
  background-color: #222;
  color: #fff;
  text-align: center;
}

.signup-container {
  max-width: 400px;
  margin: 0 auto;
}

.signup-text {
  margin: 20px;
}

.signup-button {
  padding: 10px 20px;
  background-color: #ffdd57;
  color: #222;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.signup-button:hover {
  background-color: #ffc107;
}

/* Footer */
.footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  font-size: 0.9rem;
}

.footer-container {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.footer-section {
  margin: 10px 0;
}

.footer-section h3 {
  font-size: 1.1rem;
  margin-bottom: 10px;
}

.footer-section ul {
  list-style: none;
}

.footer-section a {
  color: #fff;
  text-decoration: none;
}

.footer-section a:hover {
  color: #ffdd57;
}

.footer-bottom {
  text-align: center;
  margin-top: 15px;
}

/* Footer social links container */
.footer .social-links {
  display: flex;
  gap: 15px; /* Space between icons */
  justify-content: center;
  margin-top: 10px;
}

/* Base style for icons */
.footer .social-links img {
  width: 30px; /* Default icon size for desktop */
  height: 30px;
  transition: width 0.3s ease, height 0.3s ease; /* Smooth transition for resizing */
}

/* Adjust icon size for tablets */
@media (max-width: 768px) {
  .footer .social-links img {
    width: 24px;
    height: 24px;
  }
}

/* Adjust icon size for mobile devices */
@media (max-width: 480px) {
  .footer .social-links img {
    width: 20px;
    height: 20px;
  }
}

/* Animations */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s ease forwards;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}


/* General Styling for Collection Page */
.banner {
  background: url('images/collections-banner.jpg') center/cover no-repeat;
  opacity: 95%;
  height: 50vh;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.collections-section {
  padding: 40px 20px;
  text-align: center;
}

.collection-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.collection-item {
  background-color: #f5f5f5;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  text-align: center;
  width: 300px;
  transition: transform 0.3s;
}

.collection-item:hover {
  transform: scale(1.05);
}

.collection-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.collection-item h3 {
  font-size: 1.5em;
  margin: 15px 0 10px;
}

.collection-item p {
  padding: 0 15px 15px;
  font-size: 1em;
  color: #333;
}

.collection-button {
  background-color: #ff6b6b;
  color: #fff;
  border: none;
  border-radius: 25px;
  padding: 10px 20px;
  font-size: 1em;
  margin: 15px 0 20px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.collection-button:hover {
  background-color: #ff4a4a;
}

/* Responsive Adjustments */
@media (max-width: 768px) {
  .collection-grid {
    flex-direction: column;
    align-items: center;
  }
}
