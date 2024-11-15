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
