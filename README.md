<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delicious Bites Restaurant</title>
  <style>
    /* Basic reset */
    * {margin:0; padding:0; box-sizing:border-box; font-family: Arial, sans-serif;}
    body {background-color: #fffbe6; color: #333;}

    /* Header */
    header {background-color: #ff6f61; color: white; padding: 20px; text-align: center;}
    header h1 {font-size: 2em; margin-bottom: 5px;}
    header p {font-size: 1.1em;}

    /* Banner Image */
    .banner {width: 100%; max-height: 300px; overflow: hidden;}
    .banner img {width: 100%; object-fit: cover;}

    /* Menu */
    .menu {padding: 20px;}
    .menu h2 {text-align: center; margin-bottom: 20px; color: #ff6f61;}
    .menu-section {margin-bottom: 30px;}
    .menu-section h3 {color: #333; margin-bottom: 10px; text-decoration: underline;}
    .menu-item {display:flex; justify-content: space-between; padding: 8px 0; border-bottom: 1px dotted #ccc;}
    
    /* WhatsApp button */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: white;
      padding: 15px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 2px 5px rgba(0,0,0,0.3);
      z-index: 1000;
    }
    .whatsapp:hover {background-color: #1ebe5d;}

    /* Footer */
    footer {text-align: center; padding: 15px; background-color: #ff6f61; color: white; margin-top: 20px;}
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Delicious Bites</h1>
    <p>Your favorite food, delivered fresh!</p>
    <p>Call / WhatsApp: 8307927400</p>
  </header>

  <!-- Banner -->
  <div class="banner">
    <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1500&q=80" alt="Delicious Food Banner">
  </div>

  <!-- Menu -->
  <div class="menu">
    <h2>Our Menu</h2>

    <div class="menu-section">
      <h3>Veg</h3>
      <div class="menu-item"><span>Paneer Butter Masala</span><span>₹180</span></div>
      <div class="menu-item"><span>Veg Biryani</span><span>₹150</span></div>
      <div class="menu-item"><span>Mix Veg</span><span>₹120</span></div>
      <div class="menu-item"><span>Dal Tadka</span><span>₹100</span></div>
      <div class="menu-item"><span>Butter Naan</span><span>₹20</span></div>
    </div>

    <div class="menu-section">
      <h3>Non-Veg</h3>
      <div class="menu-item"><span>Chicken Biryani</span><span>₹220</span></div>
      <div class="menu-item"><span>Chicken Curry</span><span>₹200</span></div>
      <div class="menu-item"><span>Egg Curry</span><span>₹120</span></div>
    </div>
  </div>

  <!-- WhatsApp Button -->
  <a href="https://wa.me/918307927400?text=Hi%20Delicious%20Bites,%20I%20want%20to%20place%20an%20order." class="whatsapp" target="_blank">Order on WhatsApp</a>

  <!-- Footer -->
  <footer>
    &copy; 2026 Delicious Bites Restaurant | Made with ❤️
  </footer>

</body>
</html>
