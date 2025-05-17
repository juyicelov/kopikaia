<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kopi Kaia - Rasa Laut, Jiwa Kopi</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Inter:wght@400;500&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #F5F1E9;
      color: #333;
      scroll-behavior: smooth;
    }

    header {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 60px 20px 30px;
      animation: fadeInDown 1s ease-out;
    }

    header img {
      width: 120px;
      margin-bottom: 20px;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.8em;
      margin: 0;
    }

    header p {
      font-style: italic;
      font-size: 1.2em;
    }

    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeInUp 1s ease-in;
    }

    .section h2 {
      color: #5D3A1A;
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      margin-bottom: 20px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: space-between;
    }

    .product-card {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      flex: 1 1 calc(33% - 20px);
      transition: transform 0.3s ease;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card h3 {
      margin-top: 0;
      color: #003366;
    }

    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    a {
      color: #003366;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      .product-card {
        flex: 1 1 100%;
      }

      header h1 {
        font-size: 2em;
      }
    }

    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://drive.google.com/file/d/1a0IuV9lvcWlTw5ZXCbIuonYFpozS6hEL/view?usp=sharing" alt="Logo Kopi Kaia">
    <h1>Kopi Kaia</h1>
    <p>Oleh Erik Astaman (60900123033)</p>
  </header>

  <section class="section" id="tentang">
    <h2>Tentang Kopi Kaia</h2>
    <p>
      Kopi Kaia adalah rebranding dari Kapal Api, membawa warisan sejak 1927 ke dalam identitas baru yang lebih modern dan premium. Filosofi nama “Kaia” yang berarti laut merepresentasikan kekuatan, ketenangan, dan kedalaman rasa dalam setiap tegukan kopi kami.
    </p>
  </section>

  <section class="section" id="produk">
    <h2>Menu Unggulan</h2>
    <div class="products">
      <div class="product-card">
        <h3>Ocean Mist Latte</h3>
        <p>Latte dengan infused sea salt caramel, disajikan dengan taburan bubuk kayu manis di atas microfoam. Terinspirasi dari udara pantai dan rasa manis-garam yang elegan.</p>
      </div>
      <div class="product-card">
        <h3>Drift Cold Brew</h3>
        <p>Cold brew 18 jam dengan infused jeruk bali dan rosemary. Rasa segar, kompleks, seperti mengarungi laut di pagi hari.</p>
      </div>
      <div class="product-card">
        <h3>Bubuk Kopi Toraja Deep Roast</h3>
        <p>Kopi Toraja dengan profil bold, earthy, dan rempah-rempah.Cocok untuk espresso dan black coffee.</p>
      </div>
    </div>
  </section>

  <section class="section" id="kontak">
    <h2>Hubungi Kami</h2>
    <p>
      📍 Makassar, Indonesia<br>
      📧 <a href="mailto:erikastaman7@gmail.com">kopikaia@example.com</a><br>
      📱 <a href="https://instagram.com/kopi.kaia" target="_blank">@kopi.kaia</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Kopi Kaia. All rights reserved.</p>
  </footer>

</body>
</html>
