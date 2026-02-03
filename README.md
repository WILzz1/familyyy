<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Keluarga Hangat</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
  <h1>Keluarga</h1>
  <ul>
    <li><a href="#p1">Awal</a></li>
    <li><a href="#p2">Makna</a></li>
    <li><a href="#p3">Foto</a></li>
    <li><a href="#p4">Cerita</a></li>
    <li><a href="#p5">Momen</a></li>
    <li><a href="#p6">Cinta</a></li>
  </ul>
</nav>

<section id="p1" class="panel hero-love parallax">
  <h2>Keluarga Adalah Rumah</h2>
  <p>Tempat paling hangat untuk pulang ❤️</p>
</section>

<section id="p2" class="panel fade">
  <h2>Makna Keluarga</h2>
  <p>
    Keluarga adalah cinta yang tumbuh setiap hari  
    lewat perhatian kecil dan kebersamaan.
    💞 Makna Keluarga

Keluarga adalah tempat di mana hati merasa aman,
di mana kita diterima apa adanya,
dan dicintai tanpa syarat.

🏡 Tentang Kehangatan

Kehangatan keluarga tidak diukur dari kemewahan,
tetapi dari kebersamaan, perhatian kecil,
dan doa yang selalu menyertai.

❤️ Tentang Cinta

Cinta keluarga adalah cinta yang paling tulus,
yang tetap ada saat kita lelah, jatuh,
dan sedang tidak sempurna.

🌸 Tentang Kebersamaan

Dalam keluarga, tawa sederhana menjadi kenangan,
dan kebersamaan kecil menjadi kebahagiaan besar.

🤍 Tentang Arti Pulang

Sejauh apa pun kita pergi,
keluarga selalu menjadi tempat pulang
yang paling menenangkan.

🌷 Kalimat Pendek (Elegan)

Keluarga adalah rumah bagi hati.

Cinta keluarga tidak pernah habis.

Bersama keluarga, segalanya terasa cukup.

Keluarga adalah kekuatan dalam diam.
  </p>
</section>

<!-- FOTO KELUARGA -->
<section id="p3" class="panel soft zoom">
  <h2>Foto Keluarga</h2>

  <div class="family-gallery">
    <div class="family-photo">
      <img src="d:\Ernanda\Family\Foto\WhatsApp_Image_2022-10-18_at_12.53.57-removebg-preview (2).png" alt="Keluarga bahagia 1">
    </div>
    <div class="family-photo">
      <img src="d:\Ernanda\Family\Foto\WhatsApp_Image_2022-10-18_at_12.53.57-removebg-preview.png" alt="Keluarga bahagia 2">
    </div>
    <div class="family-photo">
      <img src="d:\Ernanda\Family\Foto\Mix\WhatsApp Image 2023-01-28 at 19.57.09.jpeg" alt="Keluarga bahagia 3">
    </div>
    <div class="family-photo">
      <img src="d:\Ernanda\Family\Foto\Mix\WhatsApp Image 2022-11-07 at 08.16.59.jpeg" alt="Keluarga bahagia 4">
    </div>
  </div>

  <p class="caption">Empat momen sederhana, satu cinta yang sama ❤️</p>
</section>

<section id="p4" class="panel fade">
  <h2>Cerita Sehari-hari</h2>
  <p>
    Makan bersama, berbagi cerita,  
    dan tertawa tanpa alasan.Kebersamaan yang seru tanpa memikirkan apapun
  </p>
</section>

<section id="p5" class="panel dark zoom">
  <h2>Momen Berharga</h2>
  <div class="cards">
    <div class="card">👨‍👩‍👧‍👦</div>
    <div class="card">🏡</div>
    <div class="card">❤️</div>
  </div>
</section>

<section id="p6" class="panel hero-love small parallax">
  <h2>Cinta Hangat Dan Penuh Kasih Sayang</h2>
  <p>Keluarga adalah segalanya</p>
</section>

<footer>
  <p>© 2026 Keluarga Hangat • Dibuat dengan ❤️</p>
</footer>

<script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
  font-family: 'Segoe UI', sans-serif;
}

body {
  color: #333;
}

/* NAV */
nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba(255,255,255,0.95);
  padding: 15px 40px;
  display: flex;
  justify-content: space-between;
  z-index: 100;
}

nav h1 { color: #ff6f91; }

nav ul {
  list-style: none;
  display: flex;
  gap: 18px;
}

nav a {
  text-decoration: none;
  color: #333;
}

nav a:hover { color: #ff6f91; }

/* PANEL */
.panel {
  min-height: 100vh;
  padding: 120px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.panel h2 {
  font-size: 2.6rem;
  margin-bottom: 20px;
}

/* HERO LOVE BACKGROUND */
.hero-love {
  color: #fff;
  background-color: #ffb6c1;
  background-image:
    radial-gradient(#ff6f91 10%, transparent 11%),
    radial-gradient(#ff6f91 10%, transparent 11%);
  background-size: 60px 60px;
  background-position: 0 0, 30px 30px;
}

/* VARIATION */
.soft { background: #fff0f5; }

.dark {
  background: #2a2a2a;
  color: #fff;
}

.hero-love.small {
  min-height: 70vh;
}

/* FOTO KELUARGA */
.family-photo {
  margin: 30px 0;
  max-width: 420px;
  border-radius: 30px;
  overflow: hidden;
  box-shadow: 0 20px 40px rgba(0,0,0,0.25);
  /* GALLERY FOTO KELUARGA */
.family-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
  margin-top: 30px;
  max-width: 900px;
  width: 100%;
}

.family-photo {
  border-radius: 26px;
  overflow: hidden;
  box-shadow: 0 18px 35px rgba(0,0,0,0.25);
  transition: 0.5s;
}

.family-photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.family-photo:hover {
  transform: scale(1.08) rotate(1deg);
}

}

.family-photo img {
  width: 100%;
  display: block;
}

.caption {
  margin-top: 10px;
  font-style: italic;
  color: #555;
}

/* CARDS */
.cards {
  display: flex;
  gap: 25px;
  margin-top: 30px;
}

.card {
  width: 160px;
  height: 160px;
  background: #ff6f91;
  border-radius: 24px;
  font-size: 3rem;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 0.4s;
}

.card:hover {
  transform: scale(1.1) rotate(4deg);
}

/* ANIMATION */
.fade, .zoom {
  opacity: 0;
  transform: translateY(60px);
  transition: 1s ease;
}

.zoom { transform: scale(0.85); }

.show {
  opacity: 1;
  transform: none;
}

/* PARALLAX */
.parallax {
  background-attachment: fixed;
}

/* FOOTER */
footer {
  background: #111;
  color: #aaa;
  text-align: center;
  padding: 20px;
}
const animated = document.querySelectorAll('.fade, .zoom');

function onScroll() {
  const trigger = window.innerHeight * 0.85;
  animated.forEach(el => {
    if (el.getBoundingClientRect().top < trigger) {
      el.classList.add('show');
    }
  });
}

window.addEventListener('scroll', onScroll);
onScroll();

