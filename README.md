<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Digital Marketing Website</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #f5f7fa;
      color: #333;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, #007bff, #00b4d8);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 2.8rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    /* Navigation */
    nav {
      background: #023e8a;
      display: flex;
      justify-content: center;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #90e0ef;
    }

    /* Sections */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    h2 {
      color: #007bff;
      font-size: 2rem;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    /* Services */
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      margin-top: 30px;
    }

    .service {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      width: 280px;
      padding: 25px;
      transition: transform 0.3s ease;
    }

    .service:hover {
      transform: translateY(-5px);
    }

    .service h3 {
      color: #007bff;
      margin-bottom: 10px;
    }

    /* Contact Section */
    button {
      background-color: #007bff;
      border: none;
      color: white;
      padding: 12px 25px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
      transition: background 0.3s ease;
    }

    button:hover {
      background-color: #0056b3;
    }

    /* Footer */
    footer {
      background: #023e8a;
      color: white;
      text-align: center;
      padding: 25px 10px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .services {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>My Digital Marketing Website</h1>
    <p>Empowering brands to grow with data-driven marketing strategies</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>We are a creative digital marketing agency focused on delivering measurable results through SEO, social media marketing, and content creation. Our goal is to help businesses build strong online visibility and attract the right audience.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>SEO Optimization</h3>
        <p>Boost your Google ranking and get discovered by your customers organically.</p>
      </div>
      <div class="service">
        <h3>Social Media Marketing</h3>
        <p>Connect with your audience and grow your brand presence on social platforms.</p>
      </div>
      <div class="service">
        <h3>Content Strategy</h3>
        <p>Engaging blogs, videos, and campaigns that drive real engagement and conversions.</p>
      </div>
      <div class="service">
        <h3>Email Marketing</h3>
        <p>Personalized campaigns to nurture leads and boost sales effectively.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Ready to take your business to the next level? Let’s talk about your goals today!</p>
    <button onclick="alert('Thank you! We will contact you soon.')">Get in Touch</button>
  </section>

  <footer>
    <p>© 2025 My Digital Marketing Website | Designed with ❤️</p>
  </footer>

</body>
</html>

