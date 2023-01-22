<template>
  <div class="third-section py-5">
    <div class="container">
      <div class="big-title text-center patua py-4">Kenapa harus menggunakan jasa kami?</div>
      <div class="big-sub-title text-center heebo">
        Kami adalah tim yang bergerak di bidang Software dengan 3+ tahun pengalaman di bidangnya, kami handal dalam
        menggunakan teknologi/framework terkini dan juga mahir menggunakan teknologi yang ada sebelumnya.
      </div>
    </div>

    <div class="container mt-5">
      <div class="row">
        <div class="col-12 col-lg-4">
          <div class="text-center svg-icon">
            <svg style="width: 100px; height: 100px" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M20 22L16.14 20.45C16.84 18.92 17.34 17.34 17.65 15.73L20 22M7.86 20.45L4 22L6.35 15.73C6.66 17.34 7.16 18.92 7.86 20.45M12 2C12 2 17 4 17 12C17 15.1 16.25 17.75 15.33 19.83C15 20.55 14.29 21 13.5 21H10.5C9.71 21 9 20.55 8.67 19.83C7.76 17.75 7 15.1 7 12C7 4 12 2 12 2M12 12C13.1 12 14 11.1 14 10C14 8.9 13.1 8 12 8C10.9 8 10 8.9 10 10C10 11.1 10.9 12 12 12Z"
              />
            </svg>
          </div>
          <p class="sub-title patua text-center">Cepat</p>
          <p class="sub-title mt-4 heebo text-center">
            Daftarkan pesanan anda, lakukan pembayaran beserta data data yang lengkap, Aplikasi anda akan langsung kami
            kerjakan.
          </p>
        </div>
        <div class="col-12 col-lg-4 mid">
          <div class="text-center svg-icon">
            <svg style="width: 100px; height: 100px" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M20.5,11H19V7C19,5.89 18.1,5 17,5H13V3.5A2.5,2.5 0 0,0 10.5,1A2.5,2.5 0 0,0 8,3.5V5H4A2,2 0 0,0 2,7V10.8H3.5C5,10.8 6.2,12 6.2,13.5C6.2,15 5,16.2 3.5,16.2H2V20A2,2 0 0,0 4,22H7.8V20.5C7.8,19 9,17.8 10.5,17.8C12,17.8 13.2,19 13.2,20.5V22H17A2,2 0 0,0 19,20V16H20.5A2.5,2.5 0 0,0 23,13.5A2.5,2.5 0 0,0 20.5,11Z"
              />
            </svg>
          </div>
          <p class="sub-title patua text-center">Kreatif & Professional</p>
          <p class="sub-title mt-4 heebo text-center">
            Kualitas aplikasi yang kami produksi sangat inovatif dan profesional, karena dikerjakan oleh tenaga ahli
            yang berpengalaman di bidangnya.
          </p>
        </div>
        <div class="col-12 col-lg-4">
          <div class="text-center svg-icon">
            <svg style="width: 100px; height: 100px" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M18.72,14.76C19.07,13.91 19.26,13 19.26,12C19.26,11.28 19.15,10.59 18.96,9.95C18.31,10.1 17.63,10.18 16.92,10.18C13.86,10.18 11.15,8.67 9.5,6.34C8.61,8.5 6.91,10.26 4.77,11.22C4.73,11.47 4.73,11.74 4.73,12A7.27,7.27 0 0,0 12,19.27C13.05,19.27 14.06,19.04 14.97,18.63C15.54,19.72 15.8,20.26 15.78,20.26C14.14,20.81 12.87,21.08 12,21.08C9.58,21.08 7.27,20.13 5.57,18.42C4.53,17.38 3.76,16.11 3.33,14.73H2V10.18H3.09C3.93,6.04 7.6,2.92 12,2.92C14.4,2.92 16.71,3.87 18.42,5.58C19.69,6.84 20.54,8.45 20.89,10.18H22V14.67H22V14.69L22,14.73H21.94L18.38,18L13.08,17.4V15.73H17.91L18.72,14.76M9.27,11.77C9.57,11.77 9.86,11.89 10.07,12.11C10.28,12.32 10.4,12.61 10.4,12.91C10.4,13.21 10.28,13.5 10.07,13.71C9.86,13.92 9.57,14.04 9.27,14.04C8.64,14.04 8.13,13.54 8.13,12.91C8.13,12.28 8.64,11.77 9.27,11.77M14.72,11.77C15.35,11.77 15.85,12.28 15.85,12.91C15.85,13.54 15.35,14.04 14.72,14.04C14.09,14.04 13.58,13.54 13.58,12.91A1.14,1.14 0 0,1 14.72,11.77Z"
              />
            </svg>
          </div>
          <p class="sub-title patua text-center">Dukungan Pelanggan</p>
          <p class="sub-title mt-4 heebo text-center">
            Jika Anda mengalami kendala dalam meng-edit aplikasi anda, maka team support kami akan sedia membantu anda.
          </p>
        </div>
      </div>
    </div>

    <div class="container">
      <Contactbar />
    </div>
  </div>
</template>

<style scoped lang="scss">
.third-section {
  background-color: $dark;
}

.big-title {
  color: white;
  font-size: 40px;
}

.big-sub-title {
  color: white;
}

.sub-title {
  color: white;
}

.svg-icon {
  color: $green;
}
</style>
