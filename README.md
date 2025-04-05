<!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wallpaper Finder</title>
  <link rel="stylesheet" href="style.css"> <!-- External CSS linked here -->

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #333;
      color: white;
      padding: 1em;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      background: #444;
      padding: 10px;
    }

    nav a 
{
      margin: 0 15px;
      text-decoration: none;
      color: white;
      font-size: 18px;
      padding: 10px;
      <a href="categories.html">Categories</a>
<a href="about.html">About Us</a>

    }

    nav a:hover {
      background: #007BFF;
      border-radius: 5px;
    }

    .search-bar {
      display: flex;
      justify-content: center;
      margin: 20px auto;
      width: 80%;
    }

    .search-bar input[type="text"] {
      width: 100%;
      max-width: 500px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px 0 0 5px;
      font-size: 16px;
    }

    .search-bar button {
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 0 5px 5px 0;
      cursor: pointer;
    }

    .search-bar button:hover {
      background-color: #0056b3;
    }

    .container {
      text-align: center;
      padding: 30px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 5px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .wallpaper-table {
      width: 90%;
      margin: 20px auto;
      border-collapse: collapse;
      background: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .wallpaper-table th,
    .wallpaper-table td {
      padding: 10px;
      text-align: center;
      border: 1px solid #ddd;
    }

    .wallpaper-table th {
      background: #333;
      color: white;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Wallpaper Finder</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Trending</a>
    <a href="#">Categories</a>
    <a href="#">Popular</a>
    <a href="#">Latest</a>
    <a href="#">Contact</a>
  </nav>

  <div class="search-bar">
    <input type="text" placeholder="Search for wallpapers...">
    <button>Search</button>
  </div>

  <div class="container">
    <h2>Find your perfect Wallpaper</h2>
    <p>Explore a wide collection of high-quality Wallpapers.</p>
  </div>

  <div class="gallery">
    <img src="https://via.placeholder.com/600x400?text=Nature+Bliss" alt="Wallpaper 1">
    <img src="https://via.placeholder.com/600x400?text=City+Lights" alt="Wallpaper 2">
    <img src="https://via.placeholder.com/600x400?text=Abstract+Art" alt="Wallpaper 3">
    <img src="https://via.placeholder.com/600x400?text=Ocean+Vibes" alt="Wallpaper 4">
    <img src="https://via.placeholder.com/600x400?text=Mountainscape" alt="Wallpaper 5">
    <img src="https://via.placeholder.com/600x400?text=Sunset+Glow" alt="Wallpaper 6">
    <img src="https://via.placeholder.com/600x400?text=Galaxy" alt="Wallpaper 7">
    <img src="https://via.placeholder.com/600x400?text=Minimal+Design" alt="Wallpaper 8">
  </div>

  <table class="wallpaper-table">
    <tr>
      <th>Wallpaper Name</th>
      <th>Categories</th>
      <th>Resolution</th>
    </tr>
    <tr>
      <td>Nature Bliss</td>
      <td>Nature</td>
      <td>1920x1080</td>
    </tr>
    <tr>
      <td>City Lights</td>
      <td>Urban</td>
      <td>2560x1440</td>
    </tr>
    <tr>
      <td>Abstract Art</td>
      <td>Abstract</td>
      <td>3840x2160</td>
    </tr>
    <tr>
      <td>Ocean Vibes</td>
      <td>Nature</td>
      <td>1920x1200</td>
    </tr>
    <tr>
      <td>Mountainscape</td>
      <td>Nature</td>
      <td>2560x1600</td>
    </tr>
    <tr>
      <td>Sunset Glow</td>
      <td>Landscape</td>
      <td>1920x1080</td>
    </tr>
    <tr>
      <td>Galaxy</td>
      <td>Space</td>
      <td>3840x2160</td>
    </tr>
    <tr>
      <td>Minimal Design</td>
      <td>Abstract</td>
      <td>2560x1440</td>
    </tr>
  </table>

  <footer>
    © 2025 Wallpaper Finder. All rights reserved.
  </footer>

</body>
</html>
