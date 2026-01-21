# fugglerstore
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Fuggler Blue Store 🧸</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      box-sizing: border-box;
      font-family: 'Poppins', Arial, sans-serif;
    }

    body {
      margin: 0;
      background: #eef6ff;
      color: #1e2a38;
    }

    header {
      background: linear-gradient(135deg, #4facfe, #00f2fe);
      color: white;
      padding: 70px 20px;
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
      max-width: 1200px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 40px;
      color: #0b5ed7;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card img {
      width: 100%;
      border-radius: 15px;
    }

    .card h3 {
      margin: 15px 0 5px;
    }

    .price {
      color: #0d6efd;
      font-weight: bold;
      font-size: 1.1rem;
    }

    button {
      background: #0d6efd;
      border: none;
      color: white;
      padding: 10px 22px;
      border-radius: 30px;
      cursor: pointer;
      margin-top: 10px;
    }

    button:hover {
      background: #084298;
    }

    .info-box {
      background: #dbeafe;
      border-radius: 25px;
      padding: 40px;
      margin-top: 40px;
    }

    footer {
      background: #0d6efd;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
  </style>
</head>

<body>

<header>
  <h1>Fuggler Blue Store 🧸</h1>
  <p>Boneka jelek-lucu yang setia. Gak kayak dia.</p>
</header>

<section>
  <h2>🛍 Produk Unggulan</h2>

  <div class="products">
    <div class="card">
      <img src="images/fuggler-blue-1.jpg" alt="Fuggler Biru 1">
      <h3>Fuggler Blue Devil</h3>
      <p class="price">Rp 249.000</p>
      <button>Beli Sekarang</button>
    </div>

    <div class="card">
      <img src="images/fuggler-blue-2.jpg" alt="Fuggler Biru 2">
      <h3>Fuggler Sad Blue</h3>
      <p class="price">Rp 229.000</p>
      <button>Beli Sekarang</button>
    </div>

    <div class="card">
      <img src="images/fuggler-blue-3.jpg" alt="Fuggler Biru 3">
      <h3>Fuggler Overthinking</h3>
      <p class="price">Rp 269.000</p>
      <button>Beli Sekarang</button>
    </div>
  </div>
</section>

<section class="info-box">
  <h2>📖 Tentang Kami</h2>
  <p>
    Fuggler Blue Store adalah toko boneka unik dengan karakter aneh,
    lucu, dan jujur. Kami percaya boneka gak harus sempurna,
    yang penting nemenin kamu pas lagi kangen orang yang salah.
  </p>
</section>

<section class="info-box">
  <h2>📍 Alamat & Kontak</h2>
  <p><strong>Alamat:</strong> Jl. Kenangan No. 17, Kota kita, Indonesia</p>
  <p><strong>WhatsApp:</strong> 0812-3456-7890</p>
  <p><strong>Email:</strong> fugglerbluestore@gmail.com</p>
  <p><strong>Instagram:</strong> @fugglerblue.store</p>
</section>

<footer>
  <p>© 2026 Fuggler Blue Store</p>
  <p>Made with 💙 & sedikit 💔</p>
</footer>

</body>
</html>



