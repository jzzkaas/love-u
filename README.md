<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Untuk Bunga 💙</title>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

      body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(to bottom, #021428, #06243a);
        color: #e0e8f0;
      }

      .container {
        max-width: 900px;
        margin: 40px auto;
        background: rgba(255, 255, 255, 0.05);
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 16px;
        box-shadow: 0 0 30px rgba(0, 0, 0, 0.3);
        overflow: hidden;
      }

      header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 40px;
      }

      header h1 {
        font-size: 1.4rem;
      }

      header span {
        color: #ffb8d2;
      }

      nav a {
        color: #b8c5d9;
        margin-left: 20px;
        text-decoration: none;
        transition: 0.3s;
      }

      nav a:hover {
        color: white;
      }

      section {
        padding: 20px 40px;
        border-top: 1px solid rgba(255, 255, 255, 0.05);
      }

      .hero {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 30px;
        align-items: center;
      }

      .hero-text h2 {
        font-size: 2rem;
        font-weight: 600;
      }

      .hero-text span {
        color: #ffb8d2;
      }

      .hero-text p {
        color: #aab7c4;
      }

      .buttons a {
        display: inline-block;
        margin-top: 16px;
        margin-right: 12px;
        padding: 10px 18px;
        border-radius: 999px;
        border: 1px solid #ffb8d2;
        color: #ffb8d2;
        background: rgba(255, 184, 210, 0.15);
        text-decoration: none;
        transition: 0.3s;
      }

      .buttons a:hover {
        background: rgba(255, 184, 210, 0.3);
      }

      .photo-card {
        background: linear-gradient(to bottom right, #08253a, #063048);
        border-radius: 12px;
        padding: 16px;
        text-align: center;
        border: 1px solid rgba(255, 255, 255, 0.05);
      }

      .photo {
        background: linear-gradient(to bottom right, #0e2c45, #072335);
        border-radius: 8px;
        height: 200px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: #b0c4d2;
        font-size: 0.9rem;
      }

      .facts {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
        gap: 20px;
        margin-top: 20px;
      }

      .fact {
        background: rgba(255, 255, 255, 0.04);
        border-radius: 10px;
        padding: 16px;
      }

      .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        gap: 10px;
        margin-top: 20px;
      }

      .gallery div {
        height: 150px;
        background: rgba(255, 255, 255, 0.05);
        border-radius: 8px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: #a8b5c6;
        font-size: 0.85rem;
      }

      blockquote {
        background: linear-gradient(to bottom right, #042635, #083044);
        border-left: 4px solid #ffb8d2;
        padding: 20px;
        border-radius: 8px;
        color: #ccd6e0;
        line-height: 1.6;
      }

      footer {
        text-align: center;
        font-size: 0.8rem;
        color: #a0b1c1;
        padding: 16px;
        border-top: 1px solid rgba(255, 255, 255, 0.05);
      }
    </style>
  </head>
  <body>
    <div class="container">
      <header>
        <h1>for <span>Bunga</span></h1>
        <nav>
          <a href="#about">About</a>
          <a href="#gallery">Gallery</a>
          <a href="#note">Love Note</a>
        </nav>
      </header>

      <section class="hero">
        <div class="hero-text">
          <h2>
            untuk kamu, <span>Bunga</span> —<br />
            sedikit manis untuk hari-harimu
          </h2>
          <p>
            Ini halaman kecil yang kubuat supaya kamu tahu seberapa sering aku
            ingat tawa dan cerita kita. Simpan sebagai kenangan, atau buka kalau
            kangen — aku juga bakal kangen tiap kali kamu buka halaman ini 💌
          </p>
          <div class="buttons">
            <a href="#note">Baca Love Note</a>
            <a href="#gallery">Lihat Foto</a>
          </div>
        </div>

        <div class="photo-card">
          <div class="photo">photo placeholder<br /><small>(ganti dengan foto kalian berdua)</small></div>
          <p style="font-size: 0.8rem; margin-top: 10px; color: #b8c5d9;">
            Kenangan: telepon larut, tuker cerita, kamu bilang 'bebe' • Favorit aku: suaramu
          </p>
        </div>
      </section>

      <section id="about">
        <h3>sedikit tentang kita</h3>
        <div class="facts">
          <div class="fact">
            <h4>Panggilan manja</h4>
            <p>kamu selalu panggil aku 'bebe' — jadi kebiasaan manis</p>
          </div>
          <div class="fact">
            <h4>Cerita larut</h4>
            <p>obrol panjang sampai lupa waktu, cerita-cerita yang bikin ketawa</p>
          </div>
          <div class="fact">
            <h4>Janji kecil</h4>
            <p>janji untuk selalu jadi pendengar ketika kamu butuh</p>
          </div>
        </div>
      </section>

      <section id="gallery">
        <h3>galeri kecil</h3>
        <p>foto-foto favorit — nanti tinggal kamu ganti dengan gambar asli kalian 💙</p>
        <div class="gallery">
          <div>Foto 1</div>
          <div>Foto 2</div>
          <div>Foto 3</div>
          <div>Foto 4</div>
        </div>
      </section>

      <section id="note">
        <h3>love note</h3>
        <blockquote>
          <p>Bunga,</p>
          <p>
            setiap kali aku ingat suaramu, aku tersenyum. setiap pesanmu adalah alasan
            aku nahan rindu sedikit lagi. terima kasih sudah jadi tempat cerita dan
            alasan senyumku. kalau suatu hari aku kurang sabar atau sering salah,
            tolong ingatkan aku dengan cara kamu sendiri — yang lembut itu.
          </p>
          <p>selalu, yang manggil kamu bebe 💙</p>
        </blockquote>
      </section>

      <footer>
        dibuat dengan 💙 oleh bebe untuk Bunga — <span id="year"></span>
      </footer>
    </div>

    <script>
      document.getElementById("year").textContent = new Date().getFullYear();
    </script>
  </body>
</html>
