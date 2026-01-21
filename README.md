# fugglerstore
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Fuggler Blue Store 🧸</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root {
  --blue: #2563eb;
  --soft-blue: #e0ecff;
  --dark: #0f172a;
}

* {
  box-sizing: border-box;
  font-family: 'Poppins', system-ui, sans-serif;
}

body {
  margin: 0;
  background: linear-gradient(to bottom, #f5f9ff, #e6f0ff);
  color: var(--dark);
}

/* NAVBAR */
nav {
  position: sticky;
  top: 0;
  background: white;
  padding: 15px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 10px 30px rgba(0,0,0,.08);
  z-index: 99;
}

nav h1 {
  color: var(--blue);
  font-size: 1.5rem;
}

nav a {
  text-decoration: none;
  color: var(--dark);
  margin-left: 20px;
  font-weight: 500;
}

nav a:hover {
  color: var(--blue);
}

/* HERO */
header {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  padding: 80px 60px;
  align-items: center;
}

header h2 {
  font-size: 3rem;
  color: var(--blue);
}

header p {
  font-size: 1.1rem;
  margin: 20px 0;
}

header button {
  background: var(--blue);
  color: white;
  border: none;
  padding: 14px 30px;
  border-radius: 40px;
  font-size: 1rem;
  cursor: pointer;
}

header button:hover {
  background: #1d4ed8;
}

header img {
  width: 100%;
  animation: float 4s ease-in-out infinite;
}

@keyframes float {
  0%,100% { transform: translateY(0); }
  50% { transform: translateY(-15px); }
}

/* SECTION */
section {
  padding: 80px 60px;
}

section h3 {
  font-size: 2rem;
  text-align: center;
  margin-bottom: 50px;
}

/* PRODUCTS */
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 35px;
}

.card {
  background: white;
  border-radius: 25px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 20px 40px rgba(0,0,0,.1);
  transition: .4s;
}

.card:hover {
  transform: translateY(-15px) scale(1.02);
}

.card img {
  width: 100%;
  border-radius: 20px;
}

.price {
  color: var(--blue);
  font-weight: 700;
}

/* ABOUT + CONTACT */
.box {
  background: var(--soft-blue);
  border-radius: 30px;
  padding: 50px;
  max-width: 900px;
  margin: auto;
  text-align: center;
}

/* TESTI */
.testi {
  display: flex;
  gap: 20px;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
}

.testi div {
  background: white;
  padding: 30px;
  border-radius: 20px;
  min-width: 280px;
  scroll-snap-align: start;
}

/* FOOTER */
footer {
  background: var(--blue);
  color: white;
  text-align: center;
  padding: 40px 20px;
}

/* WHATSAPP FLOAT */
.wa {
  position: fixed;
  bottom: 25px;
  right: 25px;
  background: #22c55e;
  color: white;
  padding: 15px 20px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: bold;
  box-shadow: 0 15px 30px rgba(0,0,0,.2);
}
</style>
</head>

<body>

<nav>
  <h1>Fuggler 🧸</h1>
  <div>
    <a href="#produk">Produk</a>
    <a href="#tentang">Tentang</a>
    <a href="#kontak">Kontak</a>
  </div>
</nav>

<header>
  <div>
    <h2>Fuggler Blue Store</h2>
    <p>Boneka jelek-lucu yang setia nemenin kamu pas lagi kangen orang yang salah.</p>
    <button>Belanja Sekarang</button>
  </div>
  <img src="images/fuggler-blue-1.jpg">
</header>

<section id="produk">
  <h3>🧸 Produk Unggulan</h3>
  <div class="products">
    <div class="card">
      <img src="images/fuggler-blue-1.jpg">
      <h4>Fuggler Devil Blue</h4>
      <p class="price">Rp 249.000</p>
    </div>
    <div class="card">
      <img src="images/fuggler-blue-2.jpg">
      <h4>Fuggler Overthinking</h4>
      <p class="price">Rp 229.000</p>
    </div>
    <div class="card">
      <img src="images/fuggler-blue-3.jpg">
      <h4>Fuggler Pura-Pura Kuat</h4>
      <p class="price">Rp 269.000</p>
    </div>
  </div>
</section>

<section id="tentang">
  <div class="box">
    <h3>Tentang Kami</h3>
    <p>
      Fuggler Blue Store adalah tempat pelarian terbaik dari rasa sepi.
      Mukanya aneh, tapi jujur. Jelek, tapi setia.
    </p>
  </div>
</section>

<section>
  <h3>💬 Testimoni</h3>
  <div class="testi">
    <div>“Sejak beli Fuggler, aku berhenti nunggu chat dia.”</div>
    <div>“Mukanya nyebelin, tapi gak ninggalin.”</div>
    <div>“Lebih konsisten dari mantanku.”</div>
  </div>
</section>

<section id="kontak">
  <div class="box">
    <h3>📍 Kontak</h3>
    <p>Jl. Kenangan No.17, Indonesia</p>
    <p>📞 0812-3456-7890</p>
    <p>📧 fugglerbluestore@gmail.com</p>
  </div>
</section>

<footer>
  © 2026 Fuggler Blue Store • Made with 💙 & sedikit 💔
</footer>

<a class="wa" href="https://wa.me/6281234567890">WhatsApp</a>

</body>
</html>



