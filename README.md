<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aryavart Eyes</title>
  <style>
    body { margin:0; font-family: Arial; background:#f4f4f4; }
    header { background:#c62828; color:white; padding:15px; text-align:center; font-size:28px; font-weight:bold; }

    nav { background:#333; display:flex; justify-content:center; flex-wrap:wrap; }
    nav a, .dropdown { color:white; padding:12px 15px; text-decoration:none; position:relative; }
    nav a:hover, .dropdown:hover { background:#555; }

    .dropdown-content {
      display:none;
      position:absolute;
      background:#fff;
      color:#000;
      top:40px;
      left:0;
      min-width:200px;
      max-height:300px;
      overflow:auto;
      box-shadow:0 2px 5px rgba(0,0,0,0.3);
      z-index:1;
    }

    .dropdown-content a {
      display:block;
      padding:8px;
      color:black;
    }

    .dropdown:hover .dropdown-content { display:block; }

    .container { display:flex; margin:20px; }
    .main-news { flex:3; margin-right:20px; }
    .sidebar { flex:1; background:white; padding:10px; border-radius:5px; }

    .news-card {
      background:white; padding:15px; margin-bottom:15px; border-radius:5px;
      box-shadow:0 2px 5px rgba(0,0,0,0.1);
    }

    .news-card img { width:100%; border-radius:5px; }

    footer { background:#222; color:white; text-align:center; padding:10px; }
  </style>
</head>
<body>

<header>Aryavart Eyes</header>

<nav>
  <a href="#">Home</a>

  <div class="dropdown">NATIONAL
    <div class="dropdown-content">
      <a href="#">Andhra Pradesh</a>
      <a href="#">Arunachal Pradesh</a>
      <a href="#">Assam</a>
      <a href="#">Bihar</a>
      <a href="#">Chhattisgarh</a>
      <a href="#">Goa</a>
      <a href="#">Gujarat</a>
      <a href="#">Haryana</a>
      <a href="#">Himachal Pradesh</a>
      <a href="#">Jharkhand</a>
      <a href="#">Karnataka</a>
      <a href="#">Kerala</a>
      <a href="#">Madhya Pradesh</a>
      <a href="#">Maharashtra</a>
      <a href="#">Manipur</a>
      <a href="#">Meghalaya</a>
      <a href="#">Mizoram</a>
      <a href="#">Nagaland</a>
      <a href="#">Odisha</a>
      <a href="#">Punjab</a>
      <a href="#">Rajasthan</a>
      <a href="#">Sikkim</a>
      <a href="#">Tamil Nadu</a>
      <a href="#">Telangana</a>
      <a href="#">Tripura</a>
      <a href="#">Uttar Pradesh</a>
      <a href="#">Uttarakhand</a>
      <a href="#">West Bengal</a>
    </div>
  </div>

  <a href="#">INTERNATIONAL</a>
  <a href="#">POLITICAL</a>
  <a href="#">Tech</a>
  <a href="#">Viral</a>
  <a href="#">Religion</a>
  <a href="#">Sports</a>
  <a href="#">Entertainment</a>
</nav>

<div class="container">
  <div class="main-news">

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400">
      <h3>Top National News</h3>
      <p>Latest updates from across all Indian states.</p>
    </div>

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400">
      <h3>Political Headlines</h3>
      <p>Major political developments and debates.</p>
    </div>

    <div class="news-card">
      <img src="https://via.placeholder.com/800x400">
      <h3>Tech & Viral</h3>
      <p>Trending technology and viral content online.</p>
    </div>

  </div>

  <div class="sidebar">
    <h3>Trending</h3>
    <p>• Breaking political news</p>
    <p>• International crisis update</p>
    <p>• Viral video trending</p>
    <p>• Sports highlights</p>
  </div>
</div>

<footer>
  © 2026 Aryavart Eyes | All Rights Reserved
</footer>

</body>
</html>
