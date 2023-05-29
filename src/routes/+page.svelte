<script>
  // You can put your JavaScript code here
</script>
<main>
  <header class="header">
    <div class="logo">
      <img src="" alt="VoiceBook">
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
      <h1>For Seal 40% off</h1>
      <p>Welcome to our new social media app designed exclusively for Narrators! We are thrilled to introduce our app that is packed with innovative features to help you stay connected with your fellow Narrators.</p>
      <form>
        <input type="email" placeholder="Enter your email">
        <button type="submit" class="btn btn-primary">Sign up</button>
      </form>
      <div class="store">
        <div>
          <h1>Welcome to My App</h1>
          <p>Download our app on:</p>
          <div class="app-links">
            <a href="https://play.google.com/store/apps/details?id=com.yourapp.android" target="_blank">
              <img src="path/to/google-play-badge.png" alt="Google Play" />
            </a>
            <a href="https://itunes.apple.com/app/your-app/id1234567890" target="_blank">
              <img src="path/to/app-store-badge.png" alt="App Store" />
            </a>
          </div>
        </div>
      </div>
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
          <p>Our app is not just another social media platform. We have incorporated new and exciting features that have never been seen before on any other social media app. Our app is designed to be user-friendly, with an intuitive user interface that makes it easy to navigate and use.</p>
        </div>
        <div class="feature-card">
          <img src="" alt="Feature 2">
          <h3>Feature 2</h3>
          <p>One of the best features of our app is the ability to create and join groups. This feature ensures that you can connect with other Narrators, share ideas, and stay informed about the latest developments in your community. Our app also has a chat feature that allows you to connect with other Narrators in real-time, no matter where you are in the world.</p>
        </div>
        <div class="feature-card">
          <img src="" alt="Feature 3">
          <h3>Feature 3</h3>
          <p>Our app also has a newsfeed that is tailored to your interests. You can customize your newsfeed to show content that interests you the most, from news articles to social media posts from other Narrators.</p>
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
            <li>Join our community to develop</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
        <div class="pricing-card">
          <h3>Pro</h3>
          <div class="price">$5%</div>
          <ul>
            <li>Own the project and support the ex owner by 5%</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
        <div class="pricing-card">
          <h3>Premium</h3>
          <div class="price">$2500.00/total</div>
          <ul>
            <li>Buy the whole project</li>
          </ul>
          <button class="btn btn-primary">Sign up</button>
        </div>
      </div>
    </section>

    <section class="about" id="about">
      <h2>About Us</h2>
      <div class="about-content">
        <div class="about-text">
          <p>We are committed to providing the best user experience for our Narrator community, and that's why we are constantly updating and improving our app. Our team is always working on new features and ideas to ensure that our app remains the best social media platform for Narrators.</p>
          <p>Our app is not yet released, but we are working hard to bring it to you soon. Sign up now to be one of the first to know when our app is available. Don't miss out on the opportunity to join the best social media platform for Narrators. Stay connected, stay informed, and stay ahead of the game with our app.</p>
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
        <img src="" alt="VoiceBook">
      </div>
      <div class="social-links">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
    <div class="footer-disclaimer">
      <p>&copy; 2023 VoiceBook. All rights reserved.</p>
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
    .store{
      display: flex;
      width: 100%;
      padding: 10px;
      justify-content: space-evenly;
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