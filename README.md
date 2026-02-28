<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Radha Krishna Veg Court</title>

  <link href="https://fonts.googleapis.com/css2?family=Kaushan+Script&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #fffaf0;
      color: #333;
    }

    /* HEADER */
    header {
      background: linear-gradient(135deg, #8B0000, #B22222);
      color: white;
      text-align: center;
      padding: 25px 20px;
    }

    header h1 {
      font-family: 'Kaushan Script', cursive;
      font-size: 3em;
      margin: 0;
    }

    header p {
      font-size: 1.2em;
      margin-top: 8px;
      color: #ffeb99;
    }

    /* NAVIGATION */
    nav {
      background: #222;
      text-align: center;
      padding: 12px 0;
    }

    nav a {
      color: white;
      margin: 0 18px;
      text-decoration: none;
      font-weight: 500;
      font-size: 16px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ffd700;
    }

    /* HERO */
    .hero {
      width: 100%;
      height: 550px;
      background-image:
        linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url('https://i.ibb.co/YFckT7DZ/Enhance-the-uploaded.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
    }

    .hero h2 {
      font-family: 'Kaushan Script', cursive;
      font-size: 3em;
      background: rgba(0, 0, 0, 0.4);
      padding: 15px 25px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
      text-align: center;
    }

    /* SECTION */
    section {
      padding: 50px 20px;
      text-align: center;
    }

    /* MENU SECTIONS */
    .menu {
      display: grid;
      gap: 25px;
      margin-bottom: 50px;
    }

    .menu-main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }

    .menu-small {
      display: grid;
      grid-template-columns: 1fr;
      gap: 20px;
    }

    .menu-box {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      text-align: left;
    }

    .menu-box:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
    }

    .menu-box h3 {
      color: #8B0000;
      text-align: center;
      font-size: 1.5em;
      margin-bottom: 15px;
      position: relative;
    }

    .menu-box h3::after {
      content: "";
      display: block;
      width: 50px;
      height: 3px;
      background: #ffd700;
      margin: 8px auto 0 auto;
      border-radius: 3px;
    }

    /* GALLERY */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    /* BUTTON */
    button {
      padding: 14px 28px;
      background: linear-gradient(45deg, #ff6600, #ffcc00);
      border: none;
      cursor: pointer;
      font-size: 16px;
      border-radius: 8px;
      font-weight: bold;
      color: #222;
      transition: 0.3s;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }

    button:hover {
      background: linear-gradient(45deg, #ffd700, #ff8c00);
      color: white;
      transform: translateY(-2px);
    }

    /* FOOTER */
    footer {
      background: #222;
      color: #ffd700;
      text-align: center;
      padding: 25px 15px;
      font-weight: bold;
    }

    /* PEACOCK FEATHER ACCENT */
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://i.ibb.co/ZL1VpH4/peacock-feather.png') no-repeat;
      background-position: top right;
      background-size: 150px;
      opacity: 0.05;
      pointer-events: none;
    }
  </style>
</head>

<body>

  <header>
    <h1>Radha Krishna Veg Court</h1>
    <p>Pure Veg Family Restaurant</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Welcome to Radha Krishna Veg Court</h2>
  </section>

  <!-- MENU SECTION -->
  <section id="menu">
    <h2>Our Full Menu</h2>

    <!-- MAIN COURSE -->
    <div class="menu menu-main">
      <div class="menu-box">
        <h3>Main Course</h3>
        <p>Veg. Special</p>
        <p>Veg. Green Garden</p>
        <p>Veg. Hungama</p>
        <p>Veg. Peshawari</p>
        <p>Paneer Roll Curry</p>
        <p>Paneer Amritsari — ₹255.00</p>
        <p>Paneer Butter Masala — ₹200.00</p>
        <p>Paneer Mushroom Masala — ₹220.00</p>
        <p>Veg. Patiyala — ₹230.00</p>
        <p>Chilly Milly Subzi — ₹220.00</p>
        <p>Subzi Bahar — ₹220.00</p>
        <p>Veg. Do Pyaaza — ₹185.00</p>
        <p>Kaju Khoya — ₹240.00</p>
        <p>Paneer Lahori Masala — ₹220.00</p>
        <p>Mushroom Baby Corn Masala — ₹210.00</p>
        <p>Veg. Maratha — ₹170.00</p>
        <p>Sev Bhaji — ₹170.00</p>
        <p>Sev Tomato — ₹170.00</p>
        <p>Paneer Kolhapuri — ₹210.00</p>
        <p>Kaju Makhaniwala — ₹220.00</p>
        <p>Green Peas Masala — ₹150.00</p>
        <p>Veg. Jaipuri — ₹160.00</p>
        <p>Paneer Masala</p>
        <p>Dal Fry</p>
        <p>Butter Dal Fry</p>
        <p>Dal Kolhapuri</p>
        <p>Dal Hariyali</p>
        <p>Bhendi Masala — ₹160.00</p>
        <p>Veg. Kolhapuri — ₹160.00</p>
      </div>

      <!-- RK KITCHEN MAIN COURSE -->
      <div class="menu-box">
        <h3>RK Kitchen Main Course</h3>
        <p>Channa Masala — ₹150.00</p>
        <p>Aloo Mutter — ₹150.00</p>
        <p>Aloo Palak — ₹150.00</p>
        <p>Green Peas Palak — ₹150.00</p>
        <p>Aloo Gobi — ₹150.00</p>
        <p>Bhendi Fry — ₹170.00</p>
        <p>Tomato Bhartha — ₹170.00</p>
        <p>Paneer Palak — ₹200.00</p>
        <p>Stuff Tomato — ₹170.00</p>
        <p>Stuff Simla — ₹170.00</p>
        <p>Veg. Makhanwala — ₹180.00</p>
        <p>Methi Malai Mutter — ₹220.00</p>
        <p>Veg. Jalfrazie — ₹180.00</p>
        <p>Veg. Bhuna Masala — ₹200.00</p>
        <p>Veg. Hyderabadi — ₹195.00</p>
        <p>Dum Aloo Punjabi — ₹180.00</p>
        <p>Veg. Kheema — ₹190.00</p>
        <p>Paneer Mutter — ₹200.00</p>
        <p>Dum Aloo Kashmiri — ₹210.00</p>
      </div>

      <!-- COMBO MEALS -->
      <div class="menu-box">
        <h3>Combo Meals</h3>
        <p>Channa Masala Combo — ₹260.00</p>
        <p>Mix Veg. Combo — ₹270.00</p>
        <p>Paneer Masala Combo — ₹280.00</p>
        <p>Paneer Makhanwala Combo — ₹280.00</p>
        <p>Veg. Kolapuri Combo — ₹270.00</p>
        <p>Veg. Manchurian Combo — ₹270.00</p>
        <p>Veg. Hong Kong Combo — ₹270.00</p>
      </div>
    </div>

    <!-- SMALL SECTIONS -->
    <div class="menu menu-small">

      <div class="menu-box">
        <h3>South Indian</h3>
        <p>Idli Sambar - ₹50</p>
        <p>Vada Sambar - ₹50</p>
        <p>Plain Dosa - ₹60</p>
        <p>Masala Dosa - ₹80</p>
      </div>

      <div class="menu-box">
        <h3>Punjabi</h3>
        <p>Paneer Butter Masala - ₹200</p>
        <p>Veg Kolhapuri - ₹160</p>
        <p>Dal Tadka - ₹140</p>
        <p>Butter Naan - ₹30</p>
      </div>

      <div class="menu-box">
        <h3>Chinese</h3>
        <p>Veg Fried Rice - ₹120</p>
        <p>Hakka Noodles - ₹130</p>
        <p>Manchurian - ₹140</p>
      </div>

      <div class="menu-box">
        <h3>Snacks</h3>
        <p>Paneer Pakoda — ₹170.00</p>
        <p>Cheese Pakoda — ₹240.00</p>
        <p>Misal Pav — ₹70.00</p>
        <p>Dahi Misal Pav — ₹85.00</p>
        <p>Usal — ₹50.00</p>
        <p>Puri Bhaji — ₹550.90</p>
        <p>Extra Puri</p>
      </div>

      <div class="menu-box">
        <h3>Upwas Items</h3>
        <p>Potato Chips</p>
        <p>Sabudana Wada — ₹80.00</p>
      </div>

      <div class="menu-box">
        <h3>Sandwiches</h3>
        <p>Bread Butter — ₹45.00</p>
        <p>Bread Butter Jam — ₹50.00</p>
        <p>Chatni Sandwich — ₹50.00</p>
        <p>Toast Butter — ₹60.00</p>
        <p>Toast Jam — ₹65.00</p>
        <p>Veg. Sandwich — ₹70.00</p>
        <p>Veg. Cheese Sandwich — ₹120.00</p>
        <p>Tomato Omelette Sandwich — ₹110.00</p>
        <p>Toast Omelette Sandwich — ₹120.00</p>
        <p>Cheese Sandwich — ₹125.00</p>
        <p>Toast Cheese Sandwich — ₹135.00</p>
        <p>Club Sandwich — ₹160.00</p>
      </div>

      <div class="menu-box">
        <h3>Pav Bhaji</h3>
        <p>Pav Bhaji — ₹140.00</p>
        <p>Jain Pav Bhaji — ₹145.00</p>
        <p>Khada Pav Bhaji — ₹150.00</p>
        <p>Cheese Pav Bhaji — ₹180.00</p>
        <p>Special Pav Bhaji — ₹190.00</p>
      </div>

      <div class="menu-box">
        <h3>Soups</h3>
        <p>Veg. Schezwan Soup — ₹140.00</p>
        <p>Baby Corn Soup — ₹140.00</p>
        <p>Cream Of Veg. Soup — ₹125.00</p>
        <p>Cream & Palak Soup — ₹125.00</p>
        <p>Cream Of Mushroom Soup — ₹135.00</p>
        <p>Veg. Clear Soup — ₹115.00</p>
        <p>Vegetable Soup — ₹125.00</p>
        <p>Lemon Coriander Soup — ₹140.00</p>
      </div>

      <div class="menu-box">
        <h3>Kadai Items</h3>
        <p>Veg. Kadai — ₹195.00</p>
        <p>Paneer Kadai — ₹220.00</p>
        <p>Mushroom Kadai — ₹215.00</p>
      </div>

      <div class="menu-box">
        <h3>Handi Items</h3>
        <p>Veg. Handi — ₹200.00</p>
      </div>

      <div class="menu-box">
        <h3>Tawa Items</h3>
        <p>Veg. Tawa — ₹220.00</p>
        <p>Paneer Tawa — ₹240.00</p>
        <p>Mushroom Paneer Tawa — ₹245.00</p>
        <p>Mushroom Baby Corn Tawa — ₹245.00</p>
      </div>

      <div class="menu-box">
        <h3>Pizza Department</h3>
        <p>Veg. Cheese Pizza — ₹160.00</p>
        <p>Jain Pizza — ₹170.00</p>
        <p>Only Cheese Pizza — ₹170.00</p>
        <p>Cheese Capsicum Pizza — ₹175.00</p>
        <p>Corn Pizza — ₹175.00</p>
        <p>Mushroom Pizza — ₹180.00</p>
        <p>Paneer Pizza — ₹190.00</p>
        <p>Baby Corn Pizza — ₹185.00</p>
        <p>Special Pizza — ₹210.00</p>
        <p>Spicy Indian Pizza — ₹210.00</p>
      </div>

    </div>
    <!-- END MENU -->

    <!-- GALLERY -->
    <section id="gallery">
      <h2>Restaurant Gallery</h2>
      <div class="gallery">
        <img src="https://i.ibb.co/RktNJ1cr/pic4.png" alt="Gallery Image 1">
        <img src="https://i.ibb.co/Q3BpZ3Gn/pic3.png" alt="Gallery Image 2">
        <img src="https://i.ibb.co/FvGd5C6/PIc-1.png" alt="Gallery Image 3">
        <img src="https://i.ibb.co/L26Fvwv/pic-2.png" alt="Gallery Image 4">
        <img src="https://i.ibb.co/N00cTMQ/pic5.png" alt="Gallery Image 5">
        <img src="https://i.ibb.co/Rkf32nBK/pic6.png" alt="Gallery Image 6">
        <img src="https://i.ibb.co/BVr1GPL6/pic8.png" alt="Gallery Image 7">
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p>📞 8055515661 / 8055515662</p>
      <br>
      <button onclick="orderNow()">Order on WhatsApp</button>
    </section>

    <footer>
      © 2026 Radha Krishna Veg Court | All Rights Reserved
    </footer>

    <script>
      function orderNow() {
        window.open("https://wa.me/918055515661", "_blank");
      }
    </script>

</body>

</html>
