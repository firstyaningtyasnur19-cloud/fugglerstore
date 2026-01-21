# fugglerstore
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Fuggler Store 🧸</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    * {
      box-sizing: border-box;
      font-family: 'Comic Sans MS', 'Poppins', sans-serif;
    }

    body {
      margin: 0;
      background: #fff3f8;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #ff9ecb, #ffc6e2);
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: #fff;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      transition: transform 0.3s;
      text-align: center;
    }

    .card:hover {
      transform: translateY(-10px) rotate(-1deg);
    }

    .card img {
      width: 100%;
      border-radius: 15px;
    }

    .card h3 {
      margin: 15px 0 5px;
    }

    .price {
      color: #ff5fa2;
      font-weight: bold;
      font-size: 1.1rem;
    }

    .about, .testi {
      background: #ffe4f1;
      border-radius: 25px;
      padding: 40px;
      margin-top: 40px;
    }

    footer {
      background: #ff9ecb;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    button {
      background: #ff5fa2;
      border: none;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      cursor: pointer;
      margin-top: 10px;
    }

    button:hover {
      background: #ff3f90;
    }
  </style>
</head>

<body>

<header>
  <h1>Fuggler Store 🧸</h1>
  <p>Boneka jelek-lucu yang tetap setia, unlike your ex.</p>
</header>

<section>
  <h2>🛍 Produk Kami</h2>
  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/300x300?text=Fuggler+1">
      <h3>Fuggler Ngambek</h3>
      <p class="price">Rp 199.000</p>
      <button>Beli Sekarang</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x300?text=Fuggler+2">
      <h3>Fuggler Overthinking</h3>
      <p class="price">Rp 229.000</p>
      <button>Beli Sekarang</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x300?text=Fuggler+3">
      <h3>Fuggler Pura-Pura Kuat</h3>
      <p class="price">Rp 249.000</p>
      <button>Beli Sekarang</button>
    </div>

  </div>
</section>

<section class="about">
  <h2>📖 Tentang Kami</h2>
  <p>
    Fuggler Store hadir untuk kamu yang butuh teman lucu, aneh,
    dan gak ninggalin tanpa kejelasan.  
    Mereka jelek, tapi jujur.
  </p>
</section>

<section class="testi">
  <h2>💬 Testimoni</h2>
  <p>“Sejak beli Fuggler, aku gak nungguin chat dia lagi.”</p>
  <p>“Mukanya jelek, tapi setia.”</p>
</section>

<footer>
  <p>© 2026 Fuggler Store | Made with 🤡 & 💔</p>
</footer>

</body>
</html>
