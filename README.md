<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Adobe Data Plan</title>
  <style>
    :root {
      --bg: #0d0d0d;
      --purple: #8e44ad;
      --green: #2ecc71;
      --white: #f0f0f0;
      --black: #000;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--white);
      line-height: 1.7;
    }

    header {
      background-color: var(--purple);
      text-align: center;
      padding: 3rem 1rem;
      color: white;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background-color: var(--black);
    }

    nav a {
      color: var(--green);
      text-decoration: none;
      font-weight: bold;
      text-transform: uppercase;
    }

    nav a:hover {
      color: var(--purple);
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    section h2 {
      font-size: 2rem;
      color: var(--purple);
      margin-bottom: 1rem;
      border-bottom: 2px solid var(--green);
      display: inline-block;
    }

    .bundle-group {
      margin-bottom: 2rem;
    }

    .bundle {
      background-color: #1a1a1a;
      border-left: 5px solid var(--green);
      margin: 1rem 0;
      padding: 1rem;
      border-radius: 8px;
    }

    .bundle h3 {
      color: var(--green);
    }

    footer {
      background-color: var(--purple);
      text-align: center;
      padding: 2rem 1rem;
      color: white;
      margin-top: 3rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      nav {
        flex-direction: column;
        gap: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Adobe Data Plan</h1>
    <p>Affordable Internet Bundles for Every Budget</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#bundles">Bundles</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About the Bundles</h2>
    <p>Welcome to Adobe Data Plan — your go-to destination for affordable, fast, and flexible data plans in Nigeria. Whether you're browsing, streaming, or working online, we’ve got a plan that fits your budget.</p>
  </section>

  <section id="bundles">
    <h2>Data Plan Bundles Available</h2>

    <div class="bundle-group">
      <h3 style="color: var(--white); margin-top: 2rem;">Daily Data Plans</h3>
      <div class="bundle">
        <h3>₦100 – 100MB for 1 Day</h3>
        <p>Perfect for quick browsing and messaging.</p>
      </div>
      <div class="bundle">
        <h3>₦200 – 250MB for 1 Day</h3>
        <p>Stay connected with social media and news.</p>
      </div>
    </div>

    <div class="bundle-group">
      <h3 style="color: var(--white); margin-top: 2rem;">Weekly Data Plans</h3>
      <div class="bundle">
        <h3>₦500 – 1GB for 7 Days</h3>
        <p>Stream music, videos, and more throughout the week.</p>
      </div>
      <div class="bundle">
        <h3>₦1000 – 2.5GB for 7 Days</h3>
        <p>Ideal for work, video calls, and content uploads.</p>
      </div>
    </div>

    <div class="bundle-group">
      <h3 style="color: var(--white); margin-top: 2rem;">Monthly Data Plans</h3>
      <div class="bundle">
        <h3>₦2000 – 4GB for 30 Days</h3>
        <p>Balanced usage for light-to-medium users.</p>
      </div>
      <div class="bundle">
        <h3>₦5000 – 12GB for 30 Days</h3>
        <p>Stream, chat, and work without limits.</p>
      </div>
      <div class="bundle">
        <h3>₦10,000 – 25GB for 30 Days</h3>
        <p>Power users rejoice. Full-speed connectivity all month.</p>
      </div>
    </div>

    <div class="bundle-group">
      <h3 style="color: var(--white); margin-top: 2rem;">Yearly Data Plans</h3>
      <div class="bundle">
        <h3>₦30,000 – 80GB for 12 Months</h3>
        <p>Budget-friendly plan for long-term users.</p>
      </div>
      <div class="bundle">
        <h3>₦90,000 – 250GB for 12 Months</h3>
        <p>Peace of mind all year round.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Info</h2>
    <p>Need help or want to subscribe? Contact us today:</p>
    <p><strong>Adobe Stores:</strong> 0703457394</p>
  </section>

  <footer>
    <p>&copy; 2025 Adobe Data Plan. All rights reserved.</p>
  </footer>

</body>
</html>
