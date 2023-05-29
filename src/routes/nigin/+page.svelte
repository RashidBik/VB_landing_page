<script>
  // Your JavaScript code goes here
</script>

<main>
  <header>
    <nav>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#pricing">Pricing</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
    <div>
      <img src="path/to/logo.png" alt="Your App Name">
    </div>
  </header>

  <section class="hero">
    <div>
      <h1>Connect with the World</h1>
      <p>Join the social media revolution and connect with friends, family, and people from all over the world.</p>
      <form>
        <input type="email" placeholder="Enter your email">
        <button type="submit">Sign Up</button>
      </form>
    </div>
    <img src="path/to/hero-image.png" alt="Your App Name">
  </section>

  <section class="features" id="features">
    <h2>Key Features</h2>
    <div class="feature-cards">
      <div class="feature-card">
        <img src="path/to/feature-icon-1.png" alt="Feature 1">
        <h3>Feature 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex.</p>
      </div>
      <div class="feature-card">
        <img src="path/to/feature-icon-2.png" alt="Feature 2">
        <h3>Feature 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex.</p>
      </div>
      <div class="feature-card">
        <img src="path/to/feature-icon-3.png" alt="Feature 3">
        <h3>Feature 3</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex.</p>
      </div>
    </div>
  </section>

  <section class="pricing" id="pricing">
    <h2>Pricing Plans</h2>
    <div class="pricing-table">
      <div class="pricing-card">
        <h3>Basic</h3>
        <div>$0/.00/month</div>
        <ul>
          <li>Feature 1</li>
          <li>Feature 2</li>
          <li>Feature 3</li>
        </ul>
        <button>Sign Up</button>
      </div>
      <div class="pricing-card">
        <h3>Pro</h3>
        <div>$9.99/month</div>
        <ul>
          <li>Feature 1</li>
          <li>Feature 2</li>
          <li>Feature 3</li>
          <li>Feature 4</li>
          <li>Feature 5</li>
        </ul>
        <button>Sign Up</button>
      </div>
      <div class="pricing-card">
        <h3>Premium</h3>
        <div>$19.99/month</div>
        <ul>
          <li>Feature 1</li>
          <li>Feature 2</li>
          <li>Feature 3</li>
          <li>Feature 4</li>
          <li>Feature 5</li>
          <li>Feature 6</li>
          <li>Feature 7</li>
        </ul>
        <button>Sign Up</button>
      </div>
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Us</h2>
    <div>
      <img src="path/to/about-image.png" alt="About Us">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex. Nulla facilisi. In hac habitasse platea dictumst. Donec at mi libero. </p>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <div>
      <img src="path/to/logo.png" alt="Your App Name">
    </div>
    <nav>
      <ul>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
        <li><a href="#">FAQ</a></li>
      </ul>
    </nav>

    <div class="social-links">
      <a href="#"><i class="fab fa-facebook"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
    </div>
    <p>&copy; 2023 Your App Name. All rights reserved.</p>
  </footer>
</main>

<style>
  /* Reset styles for all elements */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Set a default font family and size */
body {
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 16px;
}

/* Style the header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 999;
}

nav ul {
  display: flex;
}

nav li {
  margin-left: 1rem;
}

nav a {
  color: #333;
  text-decoration: none;
  font-weight: bold;
  font-size: 0.9rem;
  text-transform: uppercase;
}

nav a:hover {
  color: #007bff;
}

header img {
  height: 40px;
}

/* Style the hero section */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 4rem 2rem;
  background-color: #f8f9fa;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: #333;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  color: #666;
}

.hero form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
}

.hero input[type="email"] {
  padding: 0.5rem;
  margin-bottom: 1rem;
  border: none;
  border-radius: 4px;
  font-size: 1.2rem;
  color: #333;
}

.hero button[type="submit"] {
  background-color: #007bff;
  color: #fff;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 4px;
  font-size: 1.2rem;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

.hero button[type="submit"]:hover {
  background-color: #0062cc;
}

.hero img {
  max-width: 50%;
  height: auto;
}

/* Style the features section */
.features {
  padding: 4rem 2rem;
  background-color: #fff;
}

.features h2 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

.feature-cards {
  display: flex;
  justify-content: space-between;
}

.feature-card {
  flex-basis: calc(33.33% - 2rem);
  padding: 2rem;
  background-color: #f8f9fa;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease-in-out;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.feature-card img {
  max-width: 70px;
  height: auto;
  margin-bottom: 1rem;
}

.feature-card h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.feature-card p {
  font-size: 1.2rem;
  color: #666;
}

/* Style the pricing section */
.pricing {
  padding: 4rem 2rem;
  background-color: #f8f9fa;
}

.pricing h2 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

.pricing-table {
  display: flex;
  justify-content: space-between;
}

.pricing-card {
  flex-basis:calc(33.33% - 2rem);
  padding: 2rem;
  background-color: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease-in-out;
}

.pricing-card:hover {
  transform: translateY(-5px);
}

.pricing-card h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.pricing-card div {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #333;
}

.pricing-card ul {
  margin-bottom: 2rem;
}

.pricing-card li {
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
  color: #666;
}

.pricing-card button {
  background-color: #007bff;
  color: #fff;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 4px;
  font-size: 1.2rem;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

.pricing-card button:hover {
  background-color: #0062cc;
}

/* Style the about section */
.about {
  padding: 4rem 2rem;
  background-color: #fff;
}

.about h2 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

.about img {
  max-width: 50%;
  height: auto;
  margin-right: 2rem;
}

.about p {
  font-size: 1.2rem;
  color: #666;
}

/* Style the contact section */
.contact {
  padding: 4rem 2rem;
  background-color: #f8f9fa;
}

.contact h2 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

.contact form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
}

.contact label {
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
  color: #333;
}

.contact input[type="text"],
.contact input[type="email"],
.contact textarea {
  padding: 0.5rem;
  margin-bottom: 1rem;
  border: none;
  border-radius: 4px;
  font-size: 1.2rem;
  color: #333;
}

.contact textarea {
  height: 100px;
}

.contact button[type="submit"] {
  background-color: #007bff;
  color: #fff;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 4px;
  font-size: 1.2rem;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

.contact button[type="submit"]:hover {
  background-color: #0062cc;
}

/* Style the footer */
footer {
  padding: 2rem;
  background-color: #f8f9fa;
  text-align: center;
}

footer p {
  font-size: 1.2rem;
  color: #666;
}

footer a {
  color: #007bff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.2s ease-in-out;
}

footer a:hover {
  color: #0056b3;
}
</style>