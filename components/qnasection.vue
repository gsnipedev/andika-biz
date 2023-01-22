<template>
  <section class="py-5 qna-section">
    <div class="container">
      <p class="m-0 text-light patua text-center fs-2">Pertanyaan Seputar Dunia Jasa Pembuatan Aplikasi</p>

      <div class="accordion-container">
        <div class="accordion accordion-flush mt-5" id="qna_accordion">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button patua"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#qna1"
                aria-expanded="true"
                aria-controls="qna1"
              >
                Apa itu Software?
              </button>
            </h2>
            <div
              id="qna1"
              class="accordion-collapse collapse"
              aria-labelledby="headingOne"
              data-bs-parent="#qna_accordion"
            >
              <div class="accordion-body heebo">
                Perangkat lunak atau software adalah bagian dari komputer yang terdiri dari beberapa perintah di mana
                pengoperasiannya di lakukan melalui mesin komputer. Dengan kata lain, software adalah perangkat yang
                tidak punya wujud fisik. Software memiliki fungsi dalam mengatur hardware/perangkat keras yang ada pada
                komputer. Dengan begitu, komputer yang digunakan dapat bekerja dengan baik sesuai pekerjaan apa yang
                dibutuhkan
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button patua"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#qna2"
                aria-expanded="true"
                aria-controls="qna2"
              >
                Mengapa harus memiliki website?
              </button>
            </h2>
            <div
              id="qna2"
              class="accordion-collapse collapse"
              aria-labelledby="headingOne"
              data-bs-parent="#qna_accordion"
            >
              <div class="accordion-body heebo">
                Agar bisnis Anda bisa sukses di era Revolusi Industri 4.0, mempunyai website adalah sebuah kewajiban
                bagi para pebisnis. Baik dari skala bisnis menengah ke atas hingga yang paling kecil sekalipun. Sebab,
                jika bisnis Anda tidak berada di internet, kesempatan meraih kesuksesan di era Revolusi Industri 4.0
                tinggal sebuah angan-angan.
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button patua"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#qna3"
                aria-expanded="true"
                aria-controls="qna3"
              >
                Apakah saya bisa berjualan dan melakukan transaksi dengan website?
              </button>
            </h2>
            <div
              id="qna3"
              class="accordion-collapse collapse"
              aria-labelledby="headingOne"
              data-bs-parent="#qna_accordion"
            >
              <div class="accordion-body heebo">
                Tentu saja bisa! Anda bisa memulainya dengan memilih beberapa tema yang kami sediakan, sesuai dengan
                kebutuhan Anda. Kami juga memiliki beberapa panduan untuk Anda mengelola produk Anda di dalam website,
                karena siapapun dapat berjualan dengan website. Bikin website murah tidak pernah semudah ini!
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button patua"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#qna4"
                aria-expanded="true"
                aria-controls="qna4"
              >
                Apakah aplikasi saya bisa diakses di mana saja, kapan saja, dan tidak hanya terbatas lewat komputer
                saja?
              </button>
            </h2>
            <div
              id="qna4"
              class="accordion-collapse collapse"
              aria-labelledby="headingOne"
              data-bs-parent="#qna_accordion"
            >
              <div class="accordion-body heebo">
                Sangat bisa! Produk (Website) yang kami berikan harus sudah mobile-friendly, sehingga website Anda bisa
                tampil secara maksimal menggunakan perangkat apapun, poin ini diberikan pengecualian terhadap produk
                non-website.
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button patua"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#qna5"
                aria-expanded="true"
                aria-controls="qna5"
              >
                Bagaimana jika saya menemukan kesulitan saat mengelola aplikasi? Apakah saya akan dibantu?
              </button>
            </h2>
            <div
              id="qna5"
              class="accordion-collapse collapse"
              aria-labelledby="headingOne"
              data-bs-parent="#qna_accordion"
            >
              <div class="accordion-body heebo">
                Ya. Untuk produk jasa bikin software instan ini kami akan memberikan panduan kepada Anda baik berupa
                panduan digital berupa artikel, video, bahkan panduan secara langsung kepada Anda.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.accordion {
  width: 100%;
  border-radius: 10px;
}

.accordion-container {
  display: flex;
  justify-content: center;
}
.qna-section {
  background-color: $altdark;
}

.accordion-item {
  background-color: $dark;
  color: white;
}

.accordion-button {
  &:not(.collapsed)::after {
    background-image: url("/svgs/minus.svg");
  }

  background-color: $dark;
  box-shadow: none;
  color: $green;

  &::after {
    background-image: url("/svgs/plus.svg");
  }
}

@media screen and (min-width: 992px) {
  .accordion {
    width: 80%;
  }
}
</style>
