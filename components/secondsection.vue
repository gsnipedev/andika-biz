<template>
  <section class="second-section">
    <div class="wrapper pb-5">
      <div class="container py-4">
        <div class="big-title patua">Apa yang diperlukan untuk menggunakan jasa kami?</div>
      </div>

      <div class="container text-center">
        <div class="floating-div p-3">
          <div class="row">
            <div class="col-12 col-lg-4">
              <p class="req-title patua">Sudah memiliki materi🔥</p>
              <img src="/images/idea.png" alt="" width="200" />
              <p class="res-title mt-4 heebo">Kirimkan konten/materi website yang telah disusun kepada tim kami.</p>
            </div>
            <div class="col-12 col-lg-4 mid">
              <p class="req-title patua">Punya materi yang lain</p>
              <img src="/images/Lidea.png" alt="" width="200" />
              <p class="res-title mt-4 heebo">
                Tim kami akan bantu aplikasikan konten dari brosur / materi lain yang telah Anda miliki ke dalam
                aplikasi.
              </p>
            </div>
            <div class="col-12 col-lg-4">
              <p class="req-title patua">Belum memiliki materi</p>
              <img src="/images/Nidea.png" alt="" width="200" />
              <p class="res-title mt-4 heebo">
                Jangan khawatir, tim kami juga dapat membantu menulis dan memberi ide konten untuk software yang akan
                dibuat.
              </p>
            </div>
          </div>

          <div class="text-center">
            <button class="cme-button patua">Hubungi kami sekarang</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.floating-div {
  background-color: $green;
  border-radius: 5px;
}
.cme-button {
  padding-inline: 2em;
  padding-block: 0.5em;
  border: none;
  border-radius: 5px;
  background-color: $altdark;
  color: white;

  &:hover {
    color: $green;
  }
}
.big-title {
  text-align: center;
  color: white;
  font-size: 24px;
  text-decoration: underline;
}
.second-section {
  background-color: $altdark;
}

.req-title {
  color: $altdark;
  font-size: 18px;
}

.res-title {
  color: $altdark;
  font-weight: 500;
}

.mid {
  border-left: 0px solid gray;
  border-right: 0px solid gray;
}

@media screen and (min-width: 992px) {
  .mid {
    border: none;
    border-left: 1px solid gray;
    border-right: 1px solid gray;
  }
}
</style>
