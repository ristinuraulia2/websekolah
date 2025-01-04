<template>
  <div class="container py-5">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="jurusan-card">
          <img src="assets/img/tkj.jpeg" alt="TJKT" />
          <h3>Teknik Jaringan Komputer dan Telekomunikasi</h3>
          <p>Program keahlian yang mempelajari tentang jaringan komputer, sistem telekomunikasi, dan keamanan jaringan.
          </p>
        </div>
      </div>

      <div class="col-md-4">
        <div class="jurusan-card">
          <img src="assets/img/rpl.jpeg" alt="RPL" />
          <h3>Pengembangan Perangkat Lunak dan Gim</h3>
          <p>Program keahlian yang fokus pada pengembangan aplikasi, pemrograman,membuat dan mengembangkan gim (game
            development)..</p>
        </div>
      </div>

      <div class="col-md-4">
        <div class="jurusan-card">
          <img src="assets/img/dkv.jpeg" alt="DKV" />
          <h3>Desain Komunikasi Visual</h3>
          <p>Program keahlian yang mempelajari tentang desain grafis, multimedia, dan komunikasi visual.</p>
        </div>
      </div>
      <div class="col-md-4 mb-5">
        <div class="jurusan-card">
          <img src="assets/img/tbsm.jpeg" alt="TSM" />
          <h3>Teknik Sepeda Motor</h3>
          <p>Program keahlian yang mempelajari tentang otomotif motor</p>
        </div>
      </div>
      <div class="col-md-4 mb-5">
        <div class="jurusan-card">
          <img src="assets/img/toi.jpeg" alt="TOI" />
          <h3>Teknik Otomasi Industri</h3>
          <p>Program keahlian yang mempelajari tentang elektronika</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 10%;
}

h1 {
  color: #333;
  font-size: 2rem;
}

.desc-text {
  color: #666;
  max-width: 800px;
  margin: 0 auto;
}

.jurusan-card {
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  padding: 15px;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  min-height: 320px;
  margin-top: 5%;
}

.jurusan-card img {
  width: 120px;
  /* Lebar gambar 120px */
  height: 120px;
  /* Tinggi gambar 120px */
  object-fit: cover;
  border-radius: 50%;
  /* Membuat gambar berbentuk bulat */
  border: 3px solid #ddd;
  /* Menambahkan border tipis */
  margin-bottom: 15px;
}

.jurusan-card h3 {
  color: #444;
  font-size: 1.2rem;
  margin-bottom: 10px;
}

.jurusan-card p {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.5;
  text-align: justify;
}

/* Grid untuk card */
.row {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  /* 3 kolom di layar besar */
  gap: 20px;
}

/* 2 kolom di layar sedang */
@media (max-width: 992px) {
  .row {
    grid-template-columns: repeat(2, 1fr);
  }

  .jurusan-card img {
    width: 100px;
    height: 100px;
  }
}

/* 1 kolom di layar kecil */
@media (max-width: 576px) {
  .row {
    grid-template-columns: 1fr;
  }

  .container {
    padding: 10px;
  }

  h1 {
    font-size: 1.8rem;
  }

  .jurusan-card img {
    width: 80px;
    height: 80px;
  }
}
</style>