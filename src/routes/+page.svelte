<script>
  // You can put your JavaScript code here
</script>
<main>
  <header class="header">
    <div class="logo">
      <img src="" alt="Your App Name">
    </div>
    <nav class="navbar">
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#pricing">Pricing</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Connect with the World</h1>
      <p>Join the social media revolution and connect with friends, family, and people from all over the world.</p>
      <form>
        <input type="email" placeholder="Enter your email">
        <button type="submit" class="btn btn-primary">Sign up</button>
      </form>
    </div>
    <div class="hero-image">
      <img src="#" alt="###">
    </div>
  </section>

  <div class="body-section">
    <section class="features" id="features">
      <h2>Key Features</h2>
      <div class="feature-cards">
        <div class="feature-card">
          <img src="" alt="Feature 1">
          <h3>Feature 1</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex.</p>
        </div>
        <div class="feature-card">
          <img src="" alt="Feature 2">
          <h3>Feature 2</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex.</p>
        </div>
        <div class="feature-card">
          <img src="" alt="Feature 3">
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
          <div class="price">$0</div>
          <ul>
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
        <div class="pricing-card">
          <h3>Pro</h3>
          <div class="price">$9.99/mo</div>
          <ul>
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
            <li>Feature 4</li>
            <li>Feature 5</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
        <div class="pricing-card">
          <h3>Premium</h3>
          <div class="price">$19.99/mo</div>
          <ul>
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
            <li>Feature 4</li>
            <li>Feature 5</li>
            <li>Feature 6</li>
            <li>Feature 7</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
      </div>
    </section>

    <section class="about" id="about">
      <h2>About Us</h2>
      <div class="about-content">
        <div class="about-text">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis augue auctor, varius ligula non, porttitor ex. Curabitur non quam id lacus ultrices bibendum. Donec ac quam et nunc accumsan sagittis. Fusce faucibus, orci eu mattis tempus, risus mauris sollicitudin velit, vel porttitor magna ipsum vel nisi.</p>
          <p>Sed quis augue auctor, varius ligula non, porttitor ex. Curabitur non quam id lacus ultrices bibendum. Donec ac quam et nunc accumsan sagittis. Fusce faucibus, orci eu mattis tempus, risus mauris sollicitudin velit, vel porttitor magna ipsum vel nisi.</p>
        </div>
        <div class="about-image">
          <img src="" alt="About Us">
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h2>Contact Us</h2>
      <div class="contact-form">
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>
          <label for="message">Message:</label>
          <textarea id="message" name="message" rows="5" required></textarea>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </section>
  </div>

  <footer class="footer">
    <div class="footer-content">
      <div class="logo">
        <img src="" alt="Your App Name">
      </div>
      <div class="social-links">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
    <div class="footer-disclaimer">
      <p>&copy; 2023 Your App Name. All rights reserved.</p>
    </div>
  </footer>
</main>

<style>
    * {
      margin:0;
      padding: 0;
      box-sizing: border-box;
    }

    main {
      font-family: Arial, sans-serif;
      font-size: 16px;
      line-height: 1.5;
      color: #333;
      background-color: #f9f9f9;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem;
      background-color: white;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .logo img {
      height: 50px;
    }

    .navbar ul {
      display: flex;
      list-style: none;
    }

    .navbar li {
      margin-left: 2rem;
    }

    .navbar a {
      color: #333;
      text-decoration: none;
      font-size: 1.2rem;
      font-weight: bold;
      text-transform: uppercase;
      transition: color 0.3s;
    }

    .navbar a:hover {
      color: #007bff;
    }

    /* Hero */
    .hero {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 5rem 1rem;
      background-color: #007bff;
      color: white;
      overflow: hidden;

      /* Use CSS Grid to arrange the elements */
      display: grid;
      grid-template-columns: 1fr 1fr;
    }

    .hero-content {
      max-width: 500px;
      margin: 0 auto;
      text-align: center;
    }

    .hero-content h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      text-shadow: 2px 2px 0 rgba(0, 0, 0, 0.1);
    }

    .hero-content p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
      text-shadow: 2px 2px 0 rgba(0, 0, 0, 0.1);
    }
    .hero img {
      width: 100%;
    }
    .body-section{
      padding: 0 46px 0 46px;
    } 

    form input[type="email"] {
      padding: 1rem;
      border-radius: 0.5rem 0 0 0.5rem;
      border: none;
      width: 60%;
      font-size: 1.2rem;
    }

    form button[type="submit"] {
      padding: 1rem 2rem;
      border-radius: 0 0.5
    }


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