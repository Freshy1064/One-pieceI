<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>One Piece Devil Fruits</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #000;
      color: #fff;
    }

    header {
      background-color: #111;
      padding: 20px 30px;
      text-align: center;
      font-size: 32px;
      font-weight: bold;
      border-bottom: 3px solid #e91e63;
    }

    .container {
      padding: 30px;
      max-width: 1200px;
      margin: auto;
    }

    #searchBox {
      width: 100%;
      max-width: 400px;
      padding: 12px 20px;
      margin-bottom: 30px;
      font-size: 18px;
      border-radius: 25px;
      border: none;
      outline: none;
      box-shadow: 0 0 8px #e91e63;
      background-color: #222;
      color: #fff;
      transition: box-shadow 0.3s ease;
    }

    #searchBox:focus {
      box-shadow: 0 0 15px #ff4081;
    }

    .devil-fruit-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .devil-fruit {
      background-color: #1e1e1e;
      border: 2px solid #e91e63;
      border-radius: 12px;
      padding: 15px;
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .devil-fruit:hover {
      transform: scale(1.08);
      box-shadow: 0 0 12px #e91e63;
      background-color: #2c2c2c;
    }

    .devil-fruit img {
      width: 140px;
      height: 140px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 15px;
      border: 3px solid #e91e63;
      background: #000;
    }

    .devil-fruit h3 {
      margin: 0 0 10px 0;
      color: #e91e63;
      font-size: 20px;
    }

    .devil-fruit p {
      font-size: 14px;
      color: #ccc;
      margin: 0;
      flex-grow: 1;
    }

    /* Responsive for smaller screens */
    @media (max-width: 600px) {
      .devil-fruit-list {
        grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      }
      .devil-fruit img {
        width: 120px;
        height: 120px;
      }
    }
  </style>
</head>
<body>

<header>
  Devil Fruits of One Piece
</header>

<div class="container">
  <input type="text" id="searchBox" placeholder="Search Devil Fruits..." />

  <div class="devil-fruit-list" id="devilFruitList">

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Gomu Gomu no Mi">
      <img src="https://via.placeholder.com/140?text=Gomu+Gomu+no+Mi" alt="Gomu Gomu no Mi" />
      <h3>Gomu Gomu no Mi</h3>
      <p>Luffy's fruit gives his body rubber-like properties.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Mera Mera no Mi">
      <img src="https://via.placeholder.com/140?text=Mera+Mera+no+Mi" alt="Mera Mera no Mi" />
      <h3>Mera Mera no Mi</h3>
      <p>Controls fire; once eaten by Ace.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Hie Hie no Mi">
      <img src="https://via.placeholder.com/140?text=Hie+Hie+no+Mi" alt="Hie Hie no Mi" />
      <h3>Hie Hie no Mi</h3>
      <p>Ice powers to freeze anything instantly.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Pika Pika no Mi">
      <img src="https://via.placeholder.com/140?text=Pika+Pika+no+Mi" alt="Pika Pika no Mi" />
      <h3>Pika Pika no Mi</h3>
      <p>Grants the ability to move at light speed.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Gura Gura no Mi">
      <img src="https://via.placeholder.com/140?text=Gura+Gura+no+Mi" alt="Gura Gura no Mi" />
      <h3>Gura Gura no Mi</h3>
      <p>Causes powerful shockwaves, earthquakes.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Ope Ope no Mi">
      <img src="https://via.placeholder.com/140?text=Ope+Ope+no+Mi" alt="Ope Ope no Mi" />
      <h3>Ope Ope no Mi</h3>
      <p>Allows surgeon-like spatial manipulation.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Ito Ito no Mi">
      <img src="https://via.placeholder.com/140?text=Ito+Ito+no+Mi" alt="Ito Ito no Mi" />
      <h3>Ito Ito no Mi</h3>
      <p>Creates and controls threads.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Yami Yami no Mi">
      <img src="https://via.placeholder.com/140?text=Yami+Yami+no+Mi" alt="Yami Yami no Mi" />
      <h3>Yami Yami no Mi</h3>
      <p>Darkness powers that absorb anything.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Zoan Model Tiger">
      <img src="https://via.placeholder.com/140?text=Zoan+Model+Tiger" alt="Zoan Model Tiger" />
      <h3>Zoan Model Tiger</h3>
      <p>Allows transformation into a saber-toothed tiger.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Neko Neko no Mi">
      <img src="https://via.placeholder.com/140?text=Neko+Neko+no+Mi" alt="Neko Neko no Mi" />
      <h3>Neko Neko no Mi</h3>
      <p>Grants the power to transform into a leopard.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Hito Hito no Mi">
      <img src="https://via.placeholder.com/140?text=Hito+Hito+no+Mi" alt="Hito Hito no Mi" />
      <h3>Hito Hito no Mi</h3>
      <p>Allows Zoan users to transform into a human.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Horo Horo no Mi">
      <img src="https://via.placeholder.com/140?text=Horo+Horo+no+Mi" alt="Horo Horo no Mi" />
      <h3>Horo Horo no Mi</h3>
      <p>Creates and controls ghosts.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Kilo Kilo no Mi">
      <img src="https://via.placeholder.com/140?text=Kilo+Kilo+no+Mi" alt="Kilo Kilo no Mi" />
      <h3>Kilo Kilo no Mi</h3>
      <p>Allows changing body weight at will.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Bomu Bomu no Mi">
      <img src="https://via.placeholder.com/140?text=Bomu+Bomu+no+Mi" alt="Bomu Bomu no Mi" />
      <h3>Bomu Bomu no Mi</h3>
      <p>Makes body parts explode on contact.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Magu Magu no Mi">
      <img src="https://via.placeholder.com/140?text=Magu+Magu+no+Mi" alt="Magu Magu no Mi" />
      <h3>Magu Magu no Mi</h3>
      <p>Allows user to create and control magma.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Suke Suke no Mi">
      <img src="https://via.placeholder.com/140?text=Suke+Suke+no+Mi" alt="Suke Suke no Mi" />
      <h3>Suke Suke no Mi</h3>
      <p>Grants invisibility.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Hana Hana no Mi">
      <img src="https://via.placeholder.com/140?text=Hana+Hana+no+Mi" alt="Hana Hana no Mi" />
      <h3>Hana Hana no Mi</h3>
      <p>Allows user to sprout body parts anywhere.</p>
    </div>

    <div class="devil-fruit" onclick="location.href='https://freshy1064.github.io/One-pieceI/'" data-name="Tori Tori no Mi">
      <img src="https://via.placeholder.com/140?text=Tori+Tori+no+Mi" alt="Tori Tori no Mi" />
      <h3>Tori Tori no Mi</h3>
      <p>Allows transformation into a phoenix.</p>
    </div>

  </div>
</div>

<script>
  const searchBox = document.getElementById('searchBox');
  const devilFruitList = document.getElementById('devilFruitList');
  const devilFruits = devilFruitList.getElementsByClassName('devil-fruit');

  searchBox.addEventListener('input', function () {
    const query = this.value.toLowerCase();

    for (let fruit of devilFruits) {
      const name = fruit.getAttribute('data-name').toLowerCase();
      const description = fruit.querySelector('p').textContent.toLowerCase();
      if (name.includes(query) || description.includes(query)) {
        fruit.style.display = '';
      } else {
        fruit.style.display = 'none';
      }
    }
  });
</script>

</body>
</html>
