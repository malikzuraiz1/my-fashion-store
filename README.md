# my-fashion-store
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Luxury Fashion</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f8f9fa;
    }
    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #222;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    .hero {
      background: #ddd;
      text-align: center;
      padding: 60px 20px;
    }
    .categories {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .category {
      background: white;
      padding: 10px;
      border: 1px solid #ccc;
      text-align: center;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Luxury Fashion</h1>
    <p>Clothing for Men, Women, Boys, Girls, and Children</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Men</a>
    <a href="#">Women</a>
    <a href="#">Boys</a>
    <a href="#">Girls</a>
    <a href="#">Contact</a>
  </nav>
  <div class="hero">
    <h2>Discover Your Style</h2>
    <p>Modern, Elegant, Comfortable</p>
  </div>
  <div class="categories">
    <div class="category"><h3>Men</h3></div>
    <div class="category"><h3>Women</h3></div>
    <div class="category"><h3>Boys</h3></div>
    <div class="category"><h3>Girls</h3></div>
    <div class="category"><h3>Kids</h3></div>
  </div>
  <footer>
    &copy; 2025 Luxury Fashion. All rights reserved.
  </footer>
</body>
</html>