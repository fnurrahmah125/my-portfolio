<template>
  <div class="container-fluid">
    <NavbarComp />
    <div class="row justify-content-center px-2">
      <div class="col-lg-8">
        <div class="name">
          <img src="../assets/hand-wave.png" alt="hand wave icon" />
          <span class="fs-4 fw-bolder">Halo, saya Fatrini Nurrahmah.</span>
        </div>

        <p>
          Saya tinggal di kota Bandung, lebih tepatnya di daerah Dago. Sejak di bangku sekolah saya sudah tertarik dengan bidang IT. Saya pun mencoba untuk masuk jurusan Teknik Informatika di Universitas dan Politeknik Negeri. Namun rezeki
          saya ternyata bukan di jurusan itu tapi di Teknik Telekomunikasi.
        </p>

        <p>
          Saat kuliah, ketertarikan saya terhadap bidang IT sempat menghilang, lalu muncul kembali setelah lulus kuliah. Melihat banyaknya peluang untuk bekerja di bidang IT, saya pun mencoba untuk mempelajarinya dari berbagai sumber di
          internet. Lalu saya memilih Frontend Development karena relatif lebih mudah untuk dipelajari dan sumber belajarnya sudah sangat banyak.
        </p>

        <p>
          Saya menghabiskan beberapa bulan untuk mempelajarinya, dimulai dari belajar HTML, CSS dan Javascript. Saat ini saya sudah bisa membuat web sederhana seperti landing page dan aplikasi web sederhana. Saya masih dan akan terus
          mengeksplorasi berbagai teknologi untuk membangun sebuah website. Sambil terus mengasah kemampuan, saya pun mencoba untuk mendapatkan pekerjaan di bidang Frontend Development. CV yang sudah saya buat bisa didownload di bawah ini.
        </p>

        <p>Terima kasih sudah membaca cerita singkat tentang saya.</p>

        <div class="btn-preview mt-5">
          <a class="btn btn-front" href="/CV_Fatrini_Nurrahmah.pdf" download>Download CV</a>
          <a href="" class="btn btn-back">Download CV</a>
        </div>
      </div>
    </div>
  </div>
  <FooterComp />
</template>

<script>
import NavbarComp from "../components/NavbarComp.vue";
import FooterComp from "../components/FooterComp.vue";

export default {
  name: "AboutPage",
  components: {
    NavbarComp,
    FooterComp,
  },
};
</script>

<style scoped>
.container-fluid {
  border: 0.0625rem solid #000;
  border-radius: 0.25rem;
  background-color: #fff;
}

.name {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 16px;
}
img {
  width: 25px;
}
.row {
  padding: 35px 0 54px 0;
}
.btn-preview {
  position: relative;
}
.btn {
  border-radius: 0.25rem;
  background-color: #000;
}
.btn-front {
  position: absolute;
  z-index: 2;
  color: #fff;
  transition: 0.35s;
}
.btn-back {
  position: relative;
  color: #000;
  background-color: #000;
}
.btn-front:hover {
  color: #000;
  border: 1px solid #000;
  background-color: #ff90e8;
  transform: translate(-5px, -5px);
}
</style>
