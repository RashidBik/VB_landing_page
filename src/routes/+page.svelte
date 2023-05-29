<script>
  // You can put your JavaScript code here
  let imageLink = `data:image/jpeg;base64,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`
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
      <img src="{imageLink}" alt="Your App Name">
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