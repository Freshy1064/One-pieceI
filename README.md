<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Devil Fruits - One Piece</title>
  <link href="https://fonts.googleapis.com/css2?family=Pirata+One&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; }
    body {
      background-color: #121212;
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
    }
    nav {
      background: linear-gradient(90deg, #0b0b0b, #1a1a1a);
      box-shadow: 0 4px 8px rgba(0,0,0,0.7);
      padding: 12px 20px;
      position: relative;
      z-index: 100;
    }
    .menu-button {
      width: 35px;
      height: 28px;
      cursor: pointer;
      position: relative;
      display: inline-block;
    }
    .menu-button span {
      background: white;
      display: block;
      height: 4px;
      width: 100%;
      border-radius: 2px;
      position: absolute;
      left: 0;
      transition: 0.3s ease;
    }
    .menu-button span:nth-child(1) { top: 0; }
    .menu-button span:nth-child(2) { top: 12px; }
    .menu-button span:nth-child(3) { top: 24px; }
    .menu-button.active span:nth-child(1) {
      transform: rotate(45deg); top: 12px;
    }
    .menu-button.active span:nth-child(2) {
      opacity: 0;
    }
    .menu-button.active span:nth-child(3) {
      transform: rotate(-45deg); top: 12px;
    }
    .menu-items {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.4s ease;
      text-align: center;
    }
    .menu-items.active { max-height: 500px; }
    .menu-items a {
      display: block;
      padding: 12px 0;
      color: #eee;
      text-decoration: none;
      font-weight: 600;
      font-size: 20px;
      border-bottom: 1px solid rgba(255,255,255,0.1);
      transition: color 0.3s ease;
    }
    .menu-items a:hover {
      color: #f9d71c;
      text-shadow: 0 0 6px #f9d71c;
    }
    .menu-items a.active {
      color: #f9d71c;
      font-weight: 700;
      text-shadow: 0 0 8px #f9d71c;
      border-bottom: 2px solid #f9d71c;
      padding-bottom: 4px;
    }
    @media (min-width: 700px) {
      .menu-button { display: none; }
      .menu-items {
        max-height: none !important;
        display: flex;
        justify-content: center;
        overflow: visible;
        text-align: initial;
      }
      .menu-items a {
        border: none;
        margin: 0 25px;
        font-size: 18px;
        padding: 0;
        line-height: 1;
      }
      .menu-items a.active {
        border-bottom: 2px solid #f9d71c;
        padding-bottom: 6px;
      }
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
      text-align: center;
    }

    #devil-fruits {
      max-width: 800px;
      margin: 40px auto;
      text-align: left;
      padding: 0 20px;
    }

    #devil-fruits h2 {
      font-family: 'Pirata One', cursive;
      font-size: 2.5em;
      color: #f9d71c;
      text-align: center;
      margin-bottom: 20px;
    }

    #devil-fruits h3 {
      color: #f9d71c;
      margin-top: 30px;
      font-size: 1.6em;
    }

    #devil-fruits p {
      font-size: 1.2em;
      line-height: 1.6;
      color: #eee;
      margin-bottom: 15px;
    }

    #devil-fruits ul {
      list-style-type: square;
      padding-left: 20px;
      margin-bottom: 30px;
    }

    #devil-fruits li {
      font-size: 1.1em;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <nav>
    <div class="menu-button" id="menu-button" aria-label="Toggle menu" role="button" tabindex="0">
      <span></span><span></span><span></span>
    </div>
    <div class="menu-items" id="menu-items">
      <a href="index.html">Home</a>
      <a href="devil-fruit.html" class="active">Devil Fruit</a>
      <a href="character.html">Character</a>
      <a href="story.html">Story</a>
    </div>
  </nav>

  <div class="container">
    <h1>All About Devil Fruits</h1>
    <p>Discover the mysterious fruits that grant extraordinary powers at the cost of the ability to swim.</p>

    <section id="devil-fruits">
      <h2>Types of Devil Fruits</h2>

      <h3>1. Paramecia</h3>
      <p>Grants superhuman abilities, altering body or surroundings.</p>
      <ul>
        <li><strong>Gomu Gomu no Mi (Hito Hito no Mi, Model: Nika)</strong> – Luffy: Rubber body and Sun God awakening.</li>
        <li><strong>Bara Bara no Mi</strong> – Buggy: Split body into floating pieces.</li>
        <li><strong>Ope Ope no Mi</strong> – Law: Spatial operations, teleportation, immortality surgery.</li>
        <li><strong>Mochi Mochi no Mi</strong> – Katakuri: Control over mochi with high-level haki.</li>
        <li><strong>Ito Ito no Mi</strong> – Doflamingo: Create and control sharp threads.</li>
      </ul>

      <h3>2. Zoan</h3>
      <p>Grants transformation into animals or hybrids. Mythical and Ancient Zoans are rarer.</p>
      <ul>
        <li><strong>Hito Hito no Mi</strong> – Chopper: Gain human intelligence and form.</li>
        <li><strong>Tori Tori no Mi, Model: Phoenix</strong> – Marco: Phoenix regeneration and flight.</li>
        <li><strong>Uo Uo no Mi, Model: Seiryu</strong> – Kaido: Turns user into a powerful dragon.</li>
        <li><strong>Hito Hito no Mi, Model: Daibutsu</strong> – Sengoku: Golden Buddha form with shockwaves.</li>
        <li><strong>Ushi Ushi no Mi</strong> – Dalton: Transforms into a powerful bison.</li>
      </ul>

      <h3>3. Logia</h3>
      <p>Control over elements and intangibility.</p>
      <ul>
        <li><strong>Mera Mera no Mi</strong> – Ace/Sabo: Fire powers.</li>
        <li><strong>Pika Pika no Mi</strong> – Kizaru: Become and control light.</li>
        <li><strong>Goro Goro no Mi</strong> – Enel: Lightning control with godlike speed.</li>
        <li><strong>Hie Hie no Mi</strong> – Aokiji: Ice generation and manipulation.</li>
        <li><strong>Magu Magu no Mi</strong> – Akainu: Magma powers, extreme destruction.</li>
        <li><strong>Yami Yami no Mi</strong> – Blackbeard: Gravity-like darkness that absorbs everything and cancels powers.</li>
      </ul>

      <h3>Most Powerful Devil Fruits</h3>
      <ul>
        <li><strong>Yami Yami no Mi</strong> – Gravity and power nullification.</li>
        <li><strong>Gura Gura no Mi</strong> – World-shaking earthquake powers (Whitebeard).</li>
        <li><strong>Ope Ope no Mi</strong> – Can grant immortality through special operation.</li>
        <li><strong>Hito Hito no Mi, Model: Nika</strong> – Luffy’s true awakened power of freedom and imagination.</li>
        <li><strong>Uo Uo no Mi, Model: Seiryu</strong> – Massive destructive dragon power (Kaido).</li>
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
  </div>

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
