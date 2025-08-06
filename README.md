<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>One Piece</title>
  <link href="https://fonts.googleapis.com/css2?family=Pirata+One&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #111;
      padding: 10px;
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      z-index: 1000;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .menu-button {
      position: absolute;
      left: 10px;
      background: none;
      border: none;
      color: white;
      font-size: 20px;
      cursor: pointer;
    }

    .title {
      font-family: 'Pirata One', cursive;
      font-size: 32px;
      color: gold;
      text-align: center;
    }

    nav {
      position: fixed;
      top: 60px;
      left: 0;
      background-color: #222;
      padding: 15px;
      width: 200px;
      height: 100%;
      overflow-y: auto;
      display: none;
      flex-direction: column;
      z-index: 999;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 10px 0;
      display: block;
      font-size: 16px;
    }

    .search-bar {
      margin-top: 80px;
      text-align: center;
    }

    .search-bar input {
      padding: 8px;
      width: 60%;
      max-width: 400px;
      border-radius: 5px;
      border: none;
      font-size: 16px;
    }

    section {
      padding: 100px 20px 40px 20px;
      text-align: center;
      max-width: 800px;
      margin: 0 auto;
    }

    h2 {
      font-family: 'Pirata One', cursive;
      color: orange;
      margin-bottom: 10px;
    }

    ul {
      list-style-type: disc;
      text-align: left;
      margin: 0 auto;
      display: inline-block;
    }

    li {
      margin: 5px 0;
    }
  </style>
</head>
<body>

  <header>
    <button class="menu-button" onclick="toggleMenu()">☰ Menu</button>
    <div class="title">One Piece</div>
  </header>

  <nav id="menu">
    <a href="#" onclick="history.back()">← Back</a>
    <a href="#strawhat">Straw Hat Crew</a>
    <a href="#sea">Sea & Monsters</a>
    <a href="#bounty">Bounty</a>
    <a href="#ships">Ships</a>
  </nav>

  <div class="search-bar">
    <input type="text" placeholder="Search One Piece World...">
  </div>

  <section id="strawhat">
    <h2>Straw Hat Crew</h2>
    <p>The Straw Hat Pirates are led by Monkey D. Luffy, the future Pirate King. His loyal crew includes Zoro the swordsman, Nami the navigator, Sanji the cook, Usopp the sniper, Chopper the doctor, Robin the archaeologist, Franky the shipwright, Brook the musician, and Jinbe the helmsman. Together, they sail the Grand Line chasing dreams, freedom, and adventure.</p>
  </section>

  <section id="sea">
    <h2>Sea & Monsters</h2>
    <p>The world of One Piece is divided by massive oceans and mysterious seas like the Grand Line and the Calm Belt. These waters are home to monstrous Sea Kings, unpredictable weather, and mythical islands. Navigating these seas requires skill, courage, and a bit of luck.</p>
  </section>

  <section id="bounty">
    <h2>Bounty</h2>
    <p>Bounties are issued by the World Government to rank the threat level of pirates. The higher the bounty, the greater the danger they pose. Luffy's current bounty is among the highest in the world, making him one of the most wanted pirates alive.</p>
  </section>

  <section id="ships">
    <h2>Ships</h2>
    <p>Some of the strongest and most legendary ships in the world of One Piece include:</p>
    <ul>
      <li><strong>Thousand Sunny</strong> – Owned by the Straw Hat crew, built by Franky from Adam Wood. It’s fast, powerful, and equipped with special weapons like the Gaon Cannon.</li>
      <li><strong>Moby Dick</strong> – Whitebeard’s iconic whale-shaped ship, feared across the seas.</li>
      <li><strong>Queen Mama Chanter</strong> – Big Mom’s living ship, animated by her Soul-Soul Fruit powers.</li>
    </ul>
    <p>These ships reflect the power and identity of their owners — symbols of freedom, fear, and adventure on the high seas.</p>
  </section>

  <script>
    function toggleMenu() {
      const menu = document.getElementById('menu');
      menu.style.display = (menu.style.display === 'flex') ? 'none' : 'flex';
    }
  </script>

</body>
</html>
