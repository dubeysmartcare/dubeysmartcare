<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dubey Smart Care</title>
  <style>
    /* Basic Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }

    body { line-height: 1.6; color: #333; }

    header {
      background: #4CAF50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 { margin-bottom: 10px; }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover { text-decoration: underline; }

    section { padding: 60px 20px; text-align: center; }

    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .service-card {
      background: #f4f4f4;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .service-card h3 { margin-bottom: 10px; color: #4CAF50; }

    .contact form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .contact input, .contact textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact button {
      padding: 10px;
      border: none;
      background: #4CAF50;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      background: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    @media(max-width: 768px) {
      .services { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Dubey Smart Care</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome to Dubey Smart Care</h2>
    <p>Your trusted partner for computer services, software solutions, and smart care.</p>
  </section>

  <!-- About Section -->
  <section id="about" style="background:#f9f9f9;">
    <h2>About Us</h2>
    <p>Dubey Smart Care provides reliable and fast computer repair, software installation, and maintenance services to ensure your devices are always running smoothly.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Computer Repair</h3>
        <p>Hardware repair and troubleshooting for desktops and laptops.</p>
      </div>
      <div class="service-card">
        <h3>Software Installation</h3>
        <p>Installation of Windows, Office, antivirus, and other essential software.</p>
      </div>
      <div class="service-card">
        <h3>Network Setup</h3>
        <p>Reliable Wi-Fi and LAN setup for home and office environments.</p>
      </div>
      <div class="service-card">
        <h3>Data Recovery</h3>
        <p>Recover lost files and secure your important data safely.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" style="background:#f9f9f9;">
    <h2>Contact Us</h2>
    <div class="contact">
      <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <p>Or call us at: <strong>+91-XXXXXXXXXX</strong></p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Dubey Smart Care. All Rights Reserved.</p>
  </footer>

</body>
</html>
