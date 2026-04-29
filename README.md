<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aryavart Eyes</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }
    header {
      background: #c62828;
      color: white;
      padding: 15px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffcc00;
    }
    .container {
      display: flex;
      margin: 20px;
    }
    .main-news {
      flex: 3;
      margin-right: 20px;
    }
    .sidebar {
      flex: 1;
      background: white;
      padding: 10px;
      border-radius: 5px;
    }
    .news-card {
      background: white;
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .news-card img {
      width: 100%;
      border-radius: 5px;
    }
    .news-card h3 {
      margin: 10px 0;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>Aryavart Eyes</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Politics</a>
  <a href="#">National</a>
  <a href="#">International</a>
  <a href="#">Sports</a>
  <a href="#">Entertainment</a>
</nav>

<div class="container">
  <div class="main-news">

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400" alt="news">
      <h3>Breaking News Headline</h3>
      <p>Stay updated with the latest breaking news from across the country and the world.</p>
    </div>

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400" alt="news">
      <h3>Political Update</h3>
      <p>Latest political developments and analysis from top leaders.</p>
    </div>

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400" alt="news">
      <h3>Sports Highlights</h3>
      <p>Catch all the action from cricket, football, and more.</p>
    </div>

  </div>

  <div class="sidebar">
    <h3>Trending News</h3>
    <p>• Big political announcement today</p>
    <p>• Stock market updates</p>
    <p>• Celebrity news</p>
    <p>• Weather updates</p>
  </div>
</div>

<footer>
  © 2026 Aryavart Eyes | All Rights Reserved
</footer>

</body>
</html>
