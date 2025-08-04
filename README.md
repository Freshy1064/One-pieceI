<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Devil Fruits – One Piece</title>
  <style>
    body {
      background-color: #111;
      color: #fff;
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      padding: 0;
    }

    nav li {
      display: inline;
    }

    nav a {
      color: #ccc;
      text-decoration: none;
      font-weight: bold;
    }

    nav a.active {
      color: #ffcc00;
      border-bottom: 2px solid #ffcc00;
    }

    h3 {
      color: #ff9900;
      margin-top: 30px;
    }

    li {
      margin-bottom: 10px;
    }

    strong {
      color: #00ffff;
    }

    p {
      margin-top: 30px;
      font-style: italic;
      color: #ccc;
    }

    #menu-button {
      display: none;
    }

    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        display: none;
        background-color: #222;
        padding: 10px;
      }
      nav ul.active {
        display: flex;
      }
      #menu-button {
        display: block;
        background: #ff9900;
        color: #000;
        padding: 10px;
        border: none;
        margin-bottom: 10px;
        font-weight: bold;
      }
    }
  </style>
</head>
<body>
  <button id="menu-button">☰ Menu</button>
  <nav>
    <ul id="menu-items">
      <li><a href="https://freshy1064.github.io/Fresh/">Home</a></li>
      <li><a href="devilfruits.html" class="active">Devil Fruits</a></li>
      <li><a href="crew.html">Straw Hat Crew</a></li>
    </ul>
  </nav>

  <section>
    <h3>Most Powerful Devil Fruits</h3>
    <ul>
      <li><strong>Magu Magu no Mi</strong> – Overwhelmingly hot magma powers (Akainu).</li>
    </ul>

    <h3>Other Known Fruits</h3>
    <ul>
      <li><strong>Suna Suna no Mi</strong> – Crocodile: Sand and dehydration control.</li>
      <li><strong>Doku Doku no Mi</strong> – Magellan: Generates and resists deadly poison.</li>
      <li><strong>Noro Noro no Mi</strong> – Foxy: Slows people and attacks with photons.</li>
      <li><strong>Soru Soru no Mi</strong> – Big Mom: Controls souls and animates objects.</li>
      <li><strong>Hobi Hobi no Mi</strong> – Sugar: Turns people into toys and erases them from memory.</li>
      <li><strong>Buki Buki no Mi</strong> – Baby 5: Turns body parts into weapons.</li>
      <li><strong>Mato Mato no Mi</strong> – Vander Decken: Targets objects that chase people.</li>
    </ul>

    <p>Devil Fruits are rare, powerful, and mysterious — and the deeper the sea, the more secrets they hold. But every user must sacrifice their ability to swim forever.</p>
  </section>

  <script>
    const menuButton = document.getElementById('menu-button');
    const menuItems = document.getElementById('menu-items');
    menuButton.addEventListener('click', () => {
      menuButton.classList.toggle('active');
      menuItems.classList.toggle('active');
    });
    menuButton.addEventListener('keydown', e => {
      if(e.key === 'Enter' || e.key === ' ') {
        e.preventDefault();
        menuButton.click();
      }
    });
  </script>
</body>
</html>
