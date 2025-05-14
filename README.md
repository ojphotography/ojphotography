<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OJ Photography | Nairobi</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background: #111;
      padding: 1em 2em;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: gold;
      text-decoration: none;
      margin-left: 1.5em;
      font-weight: bold;
    }
    .hero {
      background: url('https://via.placeholder.com/1500x900') center/cover no-repeat;
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      color: gold;
      margin-bottom: 0.5em;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
    }
    .cta {
      margin-top: 1.5em;
      padding: 0.8em 1.5em;
      background: gold;
      color: #000;
      border: none;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }
    section {
      padding: 4em 2em;
    }
    .about, .contact {
      text-align: center;
    }
    .portfolio-preview {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5em;
      margin-top: 2em;
    }
    .portfolio-preview img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #111;
      padding: 2em;
      text-align: center;
      color: gold;
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="LOGO.jpg" alt="OJ Photography Logo">
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>OJ Photography</h1>
    <p>Capturing moments with creativity and professionalism. Based along Thika Road, Nairobi.</p>
    <a href="https://wa.me/254703599340" target="_blank"><button class="cta">Book a Session</button></a>
  </div>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>Based in Nairobi along Thika Road, OJ Photography specializes in capturing your most cherished moments with creativity and professionalism. With years of experience in the industry, we pride ourselves on delivering high-quality images that tell your unique story.</p>
  </section>

  <section id="portfolio">
    <h2 style="text-align:center; color:gold;">Portfolio Preview</h2>
    <div class="portfolio-preview">
      <img src="/mnt/data/WhatsApp Image 2025-05-14 at 14.32.09_c69acefe.jpg" alt="Model 1">
      <img src="/mnt/data/WhatsApp Image 2025-05-14 at 15.02.43_15f523f6.jpg" alt="Model 2">
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:credoojijo99@gmail.com">credoojijo99@gmail.com</a></p>
    <p>Phone/WhatsApp: <a href="tel:+254703599340">+254 703 599 340</a></p>
    <p>TikTok: <a href="https://www.tiktok.com/@heavyoj24" target="_blank">@heavyoj24</a></p>
  </section>

  <footer>
    <p>&copy; 2025 OJ Photography. All rights reserved.</p>
  </footer>
</body>
</html>
