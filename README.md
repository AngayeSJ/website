<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Viosam</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
    }

    header {
      background: #008000;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header h1 {
      margin: 0;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
      margin: 0;
      padding: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 5rem 2rem;
    }

    section {
      padding: 2rem;
      background: white;
      margin: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #008000;
      color: white;
    }

    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Viosam</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Viosam</h2>
    <p>Empowering growth through innovation and sustainability.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Viosam is dedicated to providing quality services in agriculture, software, and sustainability. We believe in innovation and community development.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Agro Solutions</li>
      <li>Software Development</li>
      <li>Blockchain & Fintech Integration</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@viosam.com</p>
    <p>Phone: +234-800-000-0000</p>
  </section>

  <footer>
    <p>&copy; 2025 Viosam. All rights reserved.</p>
  </footer>
</body>
</html>
