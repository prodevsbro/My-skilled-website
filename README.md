# My-skilled-website
#This is my first code to show my skills via creating websites in html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CodeDevs | Build Smarter</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #0f172a;
      color: #f1f5f9;
      line-height: 1.6;
    }

    header {
      background: #1e293b;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    header h1 {
      font-size: 2rem;
      color: #38bdf8;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #f1f5f9;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: auto;
    }

    .btn {
      display: inline-block;
      margin-top: 30px;
      padding: 12px 24px;
      background: #38bdf8;
      color: #0f172a;
      font-weight: bold;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #0ea5e9;
    }

    footer {
      background: #1e293b;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 0.9rem;
      color: #94a3b8;
    }
  </style>
</head>
<body>

  <header>
    <h1>CodeDevs</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Projects</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>We Build Code That Powers the Future</h2>
    <p>At CodeDevs, we help turn ideas into clean, fast, and scalable code — whether it’s a website, app, or startup solution.</p>
    <a href="#" class="btn">Get Started</a>
  </section>

  <footer>
    &copy; 2025 CodeDevs. All rights reserved.
  </footer>

</body>
</html>
