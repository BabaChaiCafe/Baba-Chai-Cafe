# Baba-Chai-Cafe
Baba Chai Cafe 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Baba Chai Cafe</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #fffaf5;
      color: #3e2723;
    }

    header {
      background-color: #4e342e;
      padding: 1.5rem;
      text-align: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      color: #f1c40f;
      letter-spacing: 2px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #6d4c41;
      padding: 1rem 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
      padding: 0.5rem 1rem;
      transition: background 0.3s ease;
      border-radius: 5px;
    }

    nav a:hover {
      background-color: #a1887f;
    }

    .section {
      padding: 3rem 2rem;
      text-align: center;
      max-width: 900px;
      margin: auto;
    }

    .section h2 {
      font-size: 2rem;
      color: #4e342e;
      margin-bottom: 1rem;
    }

    .section p {
      font-size: 1.1rem;
      line-height: 1.6;
      color: #5d4037;
    }

    footer {
      background-color: #3e2723;
      color: #fbe9e7;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      margin-top: 2rem;
    }

    .card {
      background-color: #fff;
      padding: 2rem;
      margin-top: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      nav {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Baba Chai Cafe</h1>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#order">Order History</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="section" id="about">
    <div class="card">
      <h2>About Baba Chai Cafe</h2>
      <p>At Baba Chai Cafe, we believe every sip of tea should feel like home. From traditional masala chai to modern kulhad flavors, we bring soul, warmth, and nostalgia in every cup. Our vision is to blend roots with richness — and give you India’s most premium chai experience.</p>
    </div>
  </section>

  <section class="section" id="order">
    <div class="card">
      <h2>Order History</h2>
      <p>Thousands of customers across India trust us every day. Whether it’s a morning energizer or an evening unwind, your chai memories are safe with us. We proudly serve love in kulhads.</p>
    </div>
  </section>

  <section class="section" id="services">
    <div class="card">
      <h2>Our Services</h2>
      <p>✨ Premium Chai Bar <br>
         ✨ Franchise Opportunities <br>
         ✨ Event Catering <br>
         ✨ Herbal Blends & Chai Packs <br>
         ✨ Instagrammable Cafe Experience</p>
    </div>
  </section>

  <section class="section" id="contact">
    <div class="card">
      <h2>Contact & Location</h2>
      <p>📍 Kanpur, Uttar Pradesh <br>
         📞 +91 98765 43210 <br>
         ✉️ info@babachaicafe.com</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Baba Chai Cafe. Designed with ❤️ in India. <br>
    All Rights Reserved.
  </footer>

</body>
</html>
