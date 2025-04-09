
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simple Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
    }

    header {
      background: #e6e3e3;
      color: #091cc4;
      padding: 1rem 0;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 3rem;
    }

    nav a {
      color: rgb(176, 19, 29);
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
      color: rgb(158, 29, 37);
      text-align: center;
      padding: 100px 40px;
    }

    .hero h1 {
      font-size: 4rem;
    }

    .hero button {
      padding: 10px 20px;
      font-size: 1rem;
      background: #dee7e0;
      border: none;
      color: rgb(192, 39, 67);
      cursor: pointer;
      margin-top: 20px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .services, .testimonials {
      background-color: #e6ebe99f;
    }

    .contact-form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .contact-form input, .contact-form textarea {
      padding: 10px;
      font-size: 1rem;
      width: 100%;
      box-sizing: border-box;
    }

    .contact-form button {
      background: #302f2b;
      color: rgb(236, 242, 236);
      border: none;
      padding: 10px;

      
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: rgb(255, 255, 255);
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <header>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome dear  joshi Website</h1>
    <p>Your success  HTML AND CSS WEBSITE starts here.</p>
    <button>Get Started</button>
  </section>

  <!-- Introduction Section -->
  <section id="about">
    <h2>INTRODECTION </h2>
    <p>We are a company dedicated to providing top-notch services to help you succeed. Our mission is to deliver quality and excellence.</p>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>OUR SERVICES </h2>
    <ul>
      <li>Web Development</li>
      <li>Digital Marketing</li>
      <li>Consulting</li>
      <li>software Development</li>
      <li>SEO strategies</li>
      <li>supply chain mangement </li>
    </ul>
  </section>

  <!-- Testimonials Section -->
  <section class="testimonials">
    <h2>TESTIMONIALS</h2>
    <p>“Great service and support. Highly recommend!” – Client A</p>
    <p>“Professional team and timely delivery.” – Client B</p>
    <p>“their team devlivered our projecton time and within budget .Great communication and high quality work !” – Client A</p>
  </section> 

  <!-- Contact Form -->
  <section id="contact">
    <h2>CONTACT  US</h2>
    <form class="contact-form">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Simple Website. All rights reserved.</p>
  </footer>

</body>
</html>
...
Displaying Document from N K JOSHI.
