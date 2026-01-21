# fugglerstore
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Fuggler Blue Store 🧸</title>
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

/* PRODUCTS */
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
  transition:.4s;
}

.card:hover{
  transform:translateY(-12px);
}

.card img{
  width:100%;
  border-radius:20px;
}

.price{
  color:var(--blue);
  font-weight:700;
}

/* FEATURES */
.features{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
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

form button{
  background:var(--blue);
  color:white;
  border:none;
  padding:14px;
  border-radius:30px;
  cursor:pointer;
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
  <h1>Fuggler Store 🧸</h1>
  <div>
    <a href="#produk">Produk</a>
    <a href="#kategori">Kategori</a>
    <a href="#tentang">Tentang</a>
    <a href="#kontak">Kontak</a>
  </div>
</nav>

<header>
  <div>
    <h2>Fuggler Blue Store</h2>
    <p>Toko boneka karakter unik dengan desain lucu, aneh, dan penuh ekspresi. Cocok untuk koleksi, hadiah, atau teman dekorasi.</p>
    <button>Lihat Koleksi</button>
  </div>
  <img src="https://i.imgur.com/1sJk7wD.png">
</header>

<section id="kategori">
  <h3>🗂 Kategori Produk</h3>
  <div class="features">
    <div class="feature">🧸 Classic Fuggler</div>
    <div class="feature">😈 Monster Series</div>
    <div class="feature">🌈 Color Edition</div>
    <div class="feature">🎁 Limited Edition</div>
  </div>
</section>

<section id="produk">
  <h3>⭐ Produk Unggulan</h3>
  <div class="products">
    <div class="card">
      <img src="https://i.imgur.com/1sJk7wD.png">
      <h4>Fuggler Devil</h4>
      <p class="price">Rp 249.000</p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/9RZ6ZQb.png">
      <h4>Fuggler Red</h4>
      <p class="price">Rp 229.000</p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/4YF8nXa.png">
      <h4>Fuggler Brown</h4>
      <p class="price">Rp 269.000</p>
    </div>
  </div>
</section>

<section>
  <h3>📦 Kenapa Pilih Kami</h3>
  <div class="features">
    <div class="feature">✔ Material berkualitas</div>
    <div class="feature">✔ Desain original</div>
    <div class="feature">✔ Aman untuk koleksi</div>
    <div class="feature">✔ Pengiriman rapi</div>
  </div>
</section>

<section id="tentang">
  <div class="box">
    <h3>Tentang Fuggler Store</h3>
    <p>
      Fuggler Store menghadirkan boneka karakter dengan ekspresi unik
      dan detail yang berbeda dari boneka pada umumnya.
      Setiap produk dibuat untuk memberi kesan lucu, berani, dan berkarakter.
    </p>
  </div>
</section>

<section>
  <h3>💬 Testimoni Pelanggan</h3>
  <div class="testi">
    <div>“Kualitasnya bagus dan detailnya lucu.”</div>
    <div>“Cocok buat pajangan dan koleksi.”</div>
    <div>“Pengiriman cepat dan rapi.”</div>
  </div>
</section>

<section id="kontak">
  <div class="box">
    <h3>📍 Hubungi Kami</h3>
    <p>Alamat: Jl. Kreatif No.17, Indonesia</p>
    <p>WhatsApp: 0812-3456-7890</p>
    <p>Email: fugglerstore@gmail.com</p>

    <form>
      <input type="text" placeholder="Nama">
      <input type="email" placeholder="Email">
      <textarea rows="4" placeholder="Pesan"></textarea>
      <button>Kirim Pesan</button>
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




