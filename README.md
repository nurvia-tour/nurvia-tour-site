<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NURVIA Tour — Arzon aviachipta va sayohatlar</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">NURVIA <span>Tour</span></div>
    <nav>
      <ul>
        <li><a href="#">Bosh sahifa</a></li>
        <li><a href="#">Arzon reyslar</a></li>
        <li><a href="#">Sayohat paketlari</a></li>
        <li><a href="#">Biz haqimizda</a></li>
        <li><a href="#">Bog‘lanish</a></li>
      </ul>
    </nav>
    <div class="lang-switch">
      <button>UZ</button>
      <button>RU</button>
      <button>EN</button>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Eng arzon aviachipta va sayohat paketlari shu yerda</h1>
    <form class="search-form">
      <input type="text" placeholder="Qayerdan" />
      <input type="text" placeholder="Qayerga" />
      <input type="date" />
      <button type="submit">Qidirish</button>
    </form>
  </section>

  <!-- Arzon reyslar -->
  <section class="cheap-flights">
    <h2>Arzon reyslar</h2>
    <div class="flights-list">
      <!-- Reyslar dinamik ko‘rinadi -->
      <div class="flight-card">Toshkent — Istanbul<br><strong>$250</strong></div>
      <div class="flight-card">Toshkent — Dubai<br><strong>$220</strong></div>
      <div class="flight-card">Toshkent — Kuala Lumpur<br><strong>$310</strong></div>
    </div>
  </section>

  <!-- Sayohat paketlari -->
  <section class="packages">
    <h2>Sayohat paketlari</h2>
    <div class="package-list">
      <div class="package-card">
        <img src="images/istanbul.jpg" alt="Istanbul" />
        <h3>Istanbul</h3>
        <p>7 kunlik tur — $450</p>
      </div>
      <div class="package-card">
        <img src="images/dubai.jpg" alt="Dubai" />
        <h3>Dubay</h3>
        <p>5 kunlik tur — $500</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 NURVIA Tour. Barcha huquqlar himoyalangan.</p>
    <div class="socials">
      <a href="#">Telegram</a> | <a href="#">Instagram</a> | <a href="#">Facebook</a>
    </div>
  </footer>
</body>
</html>
