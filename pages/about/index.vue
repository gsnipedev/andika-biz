<template>
  <section class="chill-section">
    <div class="container py-5">
      <div class="patua text-center big-title">Hai, Calon Pelanggan Kami!</div>
      <div class="patua text-center fs-5 sub-title text-light">
        Jika masih ada yang kurang dan masih memiliki pertanyaan lebih lanjut, silahkan hubungi kami.
      </div>
    </div>
  </section>
  <section class="about-section py-5">
    <div class="container">
      <div class="row p-5 rounded all-container">
        <div class="col-12 col-lg-6 text-center mb-3">
          <img src="/images/tom.jpg" alt="our picture" class="nml-img" />
        </div>
        <div class="col-12 col-lg-6">
          <div class="text-light heebo fw-bold">Tentang Kami</div>
          <div class="text-light patua h2">NetHeve.com</div>
          <div class="text-light heebo">
            NetHeve - merupakan sebuah tim yang fokus bergerak di bidang <strong>Perangkat Lunak</strong> yang sudah
            bergerak sejak tahun 2020. Tujuan kami adalah untuk memudahkan konsumen kami dalam menjalankan
            bisnis/pekerjaan nya.
          </div>
          <br />
          <div class="text-light heebo">
            Kepuasan konsumen adalah prioritas kami, kami akan terus melayani konsumen sampai mereka benar benar puas
            dengan hasil yang kami berikan.
          </div>
          <div class="ma-button mt-3">
            <button class="patua">Pesan Sekarang</button>
          </div>
        </div>
      </div>

      <div class="row p-5 rounded all-container mt-1">
        <div class="col-12 col-lg-6 mb-3">
          <div class="text-light heebo fw-bold">Trust Us</div>
          <div class="text-light patua h2">Percayakan Dengan Kami</div>
          <div class="text-light heebo">
            Tim kami sudah berpengalaman selama 3+ tahun di bidangnya, ada banyak hal yang telah kami lewati yang mana
            hal hal tersebut yang membuat kami semakin profesional.
          </div>
          <br />
          <div class="text-light heebo">
            Kami akan memastikan bahwa konsumen sudah benar benar puas dengan hasil yang kami berikan.
          </div>
        </div>
        <div class="col-12 col-lg-6 text-center">
          <img src="/images/tom.jpg" alt="our picture" class="nml-img" />
        </div>
      </div>
    </div>

    <div class="container">
      <Contactbar title="Percayakan ke kami" sub-title="Hubungi kami sekarang!" />
    </div>
  </section>
</template>

<style scoped lang="scss">
.about-section {
  background-color: $dark;
}

.chill-section {
  background-color: $dark;
}

button {
  border: none;
  border-radius: 5px;
  background-color: $green;
  color: $altdark;
  padding: 0.5em;
}

.ma-button {
  margin-top: auto;
  height: 100px;
}
.big-title {
  color: $green;
  text-decoration: underline;
  font-size: 50px;
}

.nml-img {
  width: 100%;
  object-fit: cover;
  max-height: 400px;
}
</style>
