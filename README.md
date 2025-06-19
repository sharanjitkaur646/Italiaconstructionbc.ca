<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Italia Construction</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #ffffff;
      background-color: #2c2f38; /* Dark Blue-Grey */
    }
    header {
      background: #2c2f38;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin: 10px 0 20px;
      font-size: 1.2em;
      color: #ccc; /* Light grey text */
    }
    header img {
      width: 150px; /* adjust logo size */
      margin-bottom: 20px;
      border-radius: 10px; /* optional: to make logo edges slightly rounded */
    }
    header .btn {
      background: #ffffff;
      color: #2c2f38;
      padding: 15px 30px;
      text-decoration: none;
      border-radius: 4px;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    h2 {
      border-bottom: 1px solid #fff;
      padding-bottom: 10px;
    }
    .services .card {
      background: #3d3f49;
      border: 1px solid #fff;
      padding: 20px;
      margin: 10px;
      border-radius: 4px;
      flex: 1;
      color: #fff;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .btn-secondary {
      background: #ffffff;
      color: #2c2f38;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 4px;
      font-weight: bold;
      display: inline-block;
      margin-top: 10px;
    }
    footer {
      background: #1d1f24;
      padding: 20px;
      text-align: center;
      color: #aaa;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
      box-sizing: border-box;
      border: 1px solid #fff;
      background: #3d3f49;
      color: #fff;
    }
    .contact-form button {
      background: #ffffff;
      color: #2c2f38;
      border: none;
      padding: 12px 25px;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <!-- Actual logo placed here -->
    <img src="https://i.postimg.cc/2StQVLn5/IMG-4853.jpg" alt="Italia Construction Logo" />
    <h1>Italia Construction</h1>
    <p>Transforming Spaces with Quality and Precision</p>
    <a href="#contact" class="btn">Get a Free Quote</a>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>
      At Italia Construction, we bring years of experience in transforming residential and commercial spaces across the Lower Mainland, BC. Whether it's renovations, painting, tiling, or flooring — our team delivers excellence in every project.
    </p>
  </section>

  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="card">
      <h3>Renovations</h3>
      <p>Renovations from old to modern — complete transformation services.</p>
    </div>
    <div class="card">
      <h3>Painting</h3>
      <p>Residential and non-residential painting — interior & exterior.</p>
    </div>
    <div class="card">
      <h3>Tile Installations</h3>
      <p>Expert tile installations for kitchens, bathrooms, floors, and walls.</p>
    </div>
    <div class="card">
      <h3>Flooring</h3>
      <p>Professional hardwood, laminate, vinyl, and other flooring solutions.</p>
    </div>
    <div class="card">
      <h3>Cleaning</h3>
      <p>Domestic and commercial post-construction cleaning services.</p>
    </div>
    <div class="card">
      <h3>Gazebo Installations</h3>
      <p>Custom gazebo installation for outdoor living spaces.</p>
    </div>
  </section>

  <section id="why-us">
    <h2>Why Choose Us?</h2>
    <ul>
      <li>✅ Quality Workmanship</li>
      <li>✅ Timely Delivery</li>
      <li>✅ Competitive Pricing</li>
      <li>✅ Customer Satisfaction Guaranteed</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 236‑632‑4812</p>
    <p><strong>Email:</strong> italiaconstructionbc@gmail.com</p>
    <form class="contact-form" action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Project details…" required></textarea>
      <button type="submit" class="btn-secondary">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Italia Construction – Serving the Lower Mainland, BC</p>
    <p><small>Website by [Your Name]</small></p>
  </footer>

</body>
</html>
