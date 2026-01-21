<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Fuggler Blue Store</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --blue:#2563eb;
  --soft:#eaf2ff;
  --dark:#0f172a;
  --gray:#64748b;
}

*{
  box-sizing:border-box;
  font-family:'Poppins',system-ui,sans-serif;
}

body{
  margin:0;
  background:linear-gradient(#f7fbff,#e6f0ff);
  color:var(--dark);
}

/* NAVBAR */
nav{
  position:sticky;
  top:0;
  background:white;
  padding:16px 40px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  box-shadow:0 8px 25px rgba(0,0,0,.08);
  z-index:99;
}

nav h1{
  color:var(--blue);
  font-size:1.5rem;
}

nav a{
  text-decoration:none;
  color:var(--dark);
  margin-left:24px;
  font-weight:500;
}

nav a:hover{color:var(--blue);}

/* HERO */
header{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:40px;
  padding:90px 60px;
  align-items:center;
}

header h2{
  font-size:3rem;
  color:var(--blue);
}

header p{
  font-size:1.1rem;
  color:var(--gray);
  margin:20px 0;
}

header button{
  background:var(--blue);
  color:white;
  border:none;
  padding:14px 32px;
  border-radius:40px;
  font-size:1rem;
  cursor:pointer;
}

header img{
  width:100%;
  max-width:420px;
  animation:float 4s ease-in-out infinite;
}

@keyframes float{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-15px);}
}

/* SECTION */
section{
  padding:90px 60px;
}

section h3{
  text-align:center;
  font-size:2.2rem;
  margin-bottom:50px;
}

/* GRID PRODUCT */
.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:35px;
}

.card{
  background:white;
  border-radius:25px;
  padding:20px;
  text-align:center;
  box-shadow:0 20px 40px rgba(0,0,0,.1);
  transition:.3s;
}

.card:hover{
  transform:translateY(-10px);
}

.card img{
  width:100%;
  height:230px;
  object-fit:cover;
  border-radius:18px;
}

.price{
  color:var(--blue);
  font-weight:700;
  margin:8px 0;
}

/* FEATURES */
.features{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:30px;
}

.feature{
  background:var(--soft);
  padding:30px;
  border-radius:25px;
  text-align:center;
}

/* INFO BOX */
.box{
  background:var(--soft);
  border-radius:30px;
  padding:50px;
  max-width:1000px;
  margin:auto;
  text-align:center;
}

/* TESTI */
.testi{
  display:flex;
  gap:20px;
  overflow-x:auto;
  scroll-snap-type:x mandatory;
}

.testi div{
  min-width:300px;
  background:white;
  padding:30px;
  border-radius:20px;
  scroll-snap-align:start;
  box-shadow:0 10px 30px rgba(0,0,0,.1);
}

/* FORM */
form{
  display:grid;
  gap:15px;
  max-width:600px;
  margin:30px auto 0;
}

input,textarea{
  padding:14px;
  border-radius:15px;
  border:1px solid #cbd5e1;
}

/* FOOTER */
footer{
  background:var(--blue);
  color:white;
  padding:50px 30px;
  text-align:center;
}

/* WHATSAPP */
.wa{
  position:fixed;
  right:25px;
  bottom:25px;
  background:#22c55e;
  color:white;
  padding:15px 22px;
  border-radius:50px;
  text-decoration:none;
  box-shadow:0 15px 30px rgba(0,0,0,.2);
}
</style>
</head>

<body>

<nav>
  <h1>Fuggler Store</h1>
  <div>
    <a href="#home">Home</a>
    <a href="#kategori">Kategori</a>
    <a href="#produk">Produk</a>
    <a href="#tentang">Tentang</a>
    <a href="#kontak">Kontak</a>
  </div>
</nav>

<header id="home">
  <div>
    <h2>Fuggler Blue Store</h2>
    <p>
      Toko boneka karakter unik dengan desain ekspresif dan detail yang kuat.
      Cocok untuk koleksi, hadiah, dan dekorasi.
    </p>
    <button onclick="document.getElementById('produk').scrollIntoView()">Lihat Koleksi</button>
  </div>

  <!-- GANTI FOTO DI SINI -->
  <img src="images/fuggler1.jpg" alt="Fuggler">
</header>

<section id="kategori">
  <h3>🗂 Kategori</h3>
  <div class="features">
    <div class="feature">🧸 Classic Series</div>
    <div class="feature">😈 Monster Series</div>
    <div class="feature">🎨 Color Edition</div>
    <div class="feature">🎁 Limited Item</div>
  </div>
</section>

<section id="produk">
  <h3>⭐ Produk Unggulan</h3>
  <div class="products">

    <!-- PRODUK 1 -->
    <div class="card">
      <img src="images/fuggler1.jpg">
      <h4>Fuggler Classic Blue</h4>
      <p class="price">Rp 249.000</p>
      <p>Material lembut dan detail karakter kuat.</p>
    </div>

    <!-- PRODUK 2 -->
    <div class="card">
      <img src="images/fuggler2.jpg">
      <h4>Fuggler Monster</h4>
      <p class="price">Rp 269.000</p>
      <p>Desain unik dengan ekspresi khas.</p>
    </div>

    <!-- PRODUK 3 -->
    <div class="card">
      <img src="images/fuggler3.jpg">
      <h4>Fuggler Color Edition</h4>
      <p class="price">Rp 229.000</p>
      <p>Warna cerah untuk koleksi dekoratif.</p>
    </div>

  </div>
</section>

<section>
  <h3>📦 Kenapa Pilih Kami</h3>
  <div class="features">
    <div class="feature">✔ Kualitas terjaga</div>
    <div class="feature">✔ Desain original</div>
    <div class="feature">✔ Aman untuk koleksi</div>
    <div class="feature">✔ Pengemasan rapi</div>
  </div>
</section>

<section id="tentang">
  <div class="box">
    <h3>Tentang Fuggler Store</h3>
    <p>
      Fuggler Store menyediakan boneka karakter dengan pendekatan desain yang unik,
      menggabungkan unsur lucu, ekspresif, dan berani.
      Kami berkomitmen menghadirkan produk yang menarik dan berkualitas.
    </p>
  </div>
</section>

<section>
  <h3>💬 Testimoni</h3>
  <div class="testi">
    <div>“Detailnya rapi dan sesuai foto.”</div>
    <div>“Cocok untuk pajangan.”</div>
    <div>“Kualitasnya bagus.”</div>
  </div>
</section>

<section id="kontak">
  <div class="box">
    <h3>📍 Kontak Kami</h3>
    <p>Alamat: Jl. Kreatif No.17, Indonesia</p>
    <p>WhatsApp: 0812-3456-7890</p>
    <p>Email: fugglerstore@gmail.com</p>

    <form>
      <input type="text" placeholder="Nama">
      <input type="email" placeholder="Email">
      <textarea rows="4" placeholder="Pesan"></textarea>
      <button style="background:#2563eb;color:white;border:none;border-radius:30px;padding:14px;">
        Kirim Pesan
      </button>
    </form>
  </div>
</section>

<footer>
  <p>© 2026 Fuggler Blue Store</p>
  <p>Unique Plush • Creative Design • Trusted Store</p>
</footer>

<a class="wa" href="https://wa.me/6281234567890">WhatsApp</a>

</body>
</html>




