<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GM KENT AUTO DIAGNOSTIC AND REPAIR CENTER LTD</title>
  <style>
    /* Global Styles */
    body { 
      font-family: Arial, sans-serif; 
      margin: 0; 
      padding: 0; 
      line-height: 1.6;
      color: #333;
    }
    a { text-decoration: none; color: inherit; }
    h1, h2, h3 { margin: 0 0 15px; }
    p { margin: 0 0 20px; }
    /* Header */
    header {
      background: url('garage-bg.jpg') no-repeat center center/cover;
      height: 100vh;
      color: #fff;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }
    header a.btn {
      padding: 12px 25px;
      background: #007BFF;
      color: #fff;
      border-radius: 5px;
      transition: background 0.3s;
    }
    header a.btn:hover {
      background: #0056b3;
    }
    /* Navigation */
    nav {
      background: #333;
      text-align: center;
    }
    nav a {
      color: #fff;
      display: inline-block;
      padding: 15px 20px;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #555;
    }
    /* Sections */
    section {
      padding: 60px 20px;
    }
    section#about, section#contact { background: #f9f9f9; }
    /* Cards Layout */
    .services, .shop {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .card {
      border: 1px solid #ddd;
      padding: 20px;
      width: 300px;
      text-align: center;
      border-radius: 5px;
      background: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-bottom: 10px;
      color: #007BFF;
    }
    .card button {
      padding: 10px 15px;
      background: #333;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .card button:hover {
      background: #555;
    }
    /* Forms */
    form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, select, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }
    button[type="submit"] {
      padding: 12px;
      background: #007BFF;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button[type="submit"]:hover {
      background: #0056b3;
    }
    /* Footer */
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    /* Responsive */
    @media (max-width: 768px) {
      header h1 { font-size: 2.5em; }
      nav a { padding: 10px 15px; }
      .services, .shop { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header id="home">
    <h1>GM KENT AUTO DIAGNOSTIC AND REPAIR CENTER LTD</h1>
    <p>Expert Diagnostics & Repair Services | Online Booking & Sales</p>
    <a href="#booking" class="btn">Book Your Appointment</a>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#booking">Booking</a>
    <a href="#shop">Shop</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>At GM KENT, we combine advanced diagnostic technology with expert repair services. Our experienced team is dedicated to ensuring your vehicle receives the highest quality care. We pride ourselves on transparency, efficiency, and customer satisfaction.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Advanced Diagnostics</h3>
        <p>Utilizing state‑of‑the‑art diagnostic tools to accurately identify your vehicle's issues.</p>
      </div>
      <div class="card">
        <h3>Repair & Maintenance</h3>
        <p>Comprehensive repair services, from routine maintenance to major repairs, ensuring longevity and performance.</p>
      </div>
      <div class="card">
        <h3>Engine & Transmission</h3>
        <p>Expert servicing for engines and transmissions, using quality parts and precise techniques.</p>
      </div>
      <div class="card">
        <h3>Electrical Systems</h3>
        <p>Advanced troubleshooting and repair of modern vehicle electrical and electronic systems.</p>
      </div>
    </div>
  </section>

  <!-- Booking Section -->
  <section id="booking">
    <h2>Online Booking</h2>
    <p>Schedule your service appointment easily with our online booking system.</p>
    <form id="bookingForm">
      <input type="text" id="name" name="name" placeholder="Your Name" required>
      <input type="email" id="email" name="email" placeholder="Your Email" required>
      <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>
      <input type="date" id="date" name="date" required>
      <select id="service" name="service" required>
        <option value="">Select a Service</option>
        <option value="diagnostics">Advanced Diagnostics</option>
        <option value="repair">Repair & Maintenance</option>
        <option value="engine">Engine & Transmission</option>
        <option value="electrical">Electrical Systems</option>
      </select>
      <textarea id="message" name="message" placeholder="Additional Information (Optional)"></textarea>
      <button type="submit">Book Appointment</button>
    </form>
  </section>

  <!-- Shop Section -->
  <section id="shop">
    <h2>Online Shop</h2>
    <div class="shop">
      <div class="card">
        <h3>Quality Auto Parts</h3>
        <p>Premium parts to keep your vehicle running smoothly.</p>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <h3>Service Packages</h3>
        <p>Convenient service bundles for regular maintenance and repairs.</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have any questions or need further assistance? Get in touch!</p>
    <form id="contactForm">
      <input type="text" id="contactName" name="contactName" placeholder="Your Name" required>
      <input type="email" id="contactEmail" name="contactEmail" placeholder="Your Email" required>
      <textarea id="contactMessage" name="contactMessage" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 GM KENT AUTO DIAGNOSTIC AND REPAIR CENTER LTD. All rights reserved.</p>
  </footer>

  <!-- JavaScript for Simple Form Interactions -->
  <script>
    document.getElementById('bookingForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Booking submitted! We will contact you shortly.');
      this.reset();
    });
    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Message sent! We will get back to you soon.');
      this.reset();
    });
  </script>
</body>
</html> 👋 Hi, I’m @Gytis0321
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Gytis0321/Gytis0321 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
