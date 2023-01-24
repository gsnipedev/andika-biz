<template>
  <section class="payinfo-section">
    <div class="container py-5">
      <div class="patua text-center big-title">Pembayaran</div>
      <div class="patua text-center fs-5 sub-title text-light">
        Kami menerima berbagai bentuk pembayaran, tunai
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            style="width: 24px; height: 24px"
            class="green-svg"
          >
            <title>cash</title>
            <path
              fill="currentColor"
              d="M3,6H21V18H3V6M12,9A3,3 0 0,1 15,12A3,3 0 0,1 12,15A3,3 0 0,1 9,12A3,3 0 0,1 12,9M7,8A2,2 0 0,1 5,10V14A2,2 0 0,1 7,16H17A2,2 0 0,1 19,14V10A2,2 0 0,1 17,8H7Z"
            />
          </svg>
        </span>
        maupun non tunai

        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            style="height: 24px; width: 24px"
            class="text-warning"
          >
            <title>bitcoin</title>
            <path
              fill="currentColor"
              d="M14.24 10.56C13.93 11.8 12 11.17 11.4 11L11.95 8.82C12.57 9 14.56 9.26 14.24 10.56M11.13 12.12L10.53 14.53C11.27 14.72 13.56 15.45 13.9 14.09C14.26 12.67 11.87 12.3 11.13 12.12M21.7 14.42C20.36 19.78 14.94 23.04 9.58 21.7C4.22 20.36 .963 14.94 2.3 9.58C3.64 4.22 9.06 .964 14.42 2.3C19.77 3.64 23.03 9.06 21.7 14.42M14.21 8.05L14.66 6.25L13.56 6L13.12 7.73C12.83 7.66 12.54 7.59 12.24 7.53L12.68 5.76L11.59 5.5L11.14 7.29C10.9 7.23 10.66 7.18 10.44 7.12L10.44 7.12L8.93 6.74L8.63 7.91C8.63 7.91 9.45 8.1 9.43 8.11C9.88 8.22 9.96 8.5 9.94 8.75L8.71 13.68C8.66 13.82 8.5 14 8.21 13.95C8.22 13.96 7.41 13.75 7.41 13.75L6.87 15L8.29 15.36C8.56 15.43 8.82 15.5 9.08 15.56L8.62 17.38L9.72 17.66L10.17 15.85C10.47 15.93 10.76 16 11.04 16.08L10.59 17.87L11.69 18.15L12.15 16.33C14 16.68 15.42 16.54 16 14.85C16.5 13.5 16 12.7 15 12.19C15.72 12 16.26 11.55 16.41 10.57C16.61 9.24 15.59 8.53 14.21 8.05Z"
            />
          </svg>
        </span>

        .
      </div>
    </div>

    <div class="container">
      <p class="m-0 text-light patua fs-5">
        <u>1. E-Wallet (IDR & USD)</u>
      </p>
      <br />

      <p class="m-0 text-light rslab">Kami menerima pembayaran melalui E-Wallet, dengan mata uang Dollar dan Rupiah.</p>

      <br />

      <ul class="text-light rslab">
        <li>
          <img src="/images/paypal.png" alt="" width="64" class="bg-light p-1" /> Paypal - andikawpb211@gmail.com ($USD)
        </li>
        <li><img src="/images/dana.jpg" alt="" width="64" /> DANA - +62 823 8287 8591 (IDR)</li>
        <li><img src="/images/gopay.png" alt="" width="64" class="bg-light" /> Gopay (IDR)</li>
        <li><img src="/images/ovo.png" alt="" width="64" class="bg-light p-1" /> Ovo (IDR)</li>
      </ul>

      <br />

      <p class="m-0 text-light patua fs-5">
        <u>
          <span> 2. Bank (IDR) - </span>

          <span class="text-danger">Unavailable</span>
        </u>
      </p>
      <br />

      <p class="m-0 text-light patua fs-5">
        <u>3. Blockchain (Cryptocurrency)</u>
      </p>
      <br />

      <p class="m-0 text-light rslab">
        Kami menerima pembayaran melalui Blockxhain, dengan mata uang digital (BTC & BUSD)
      </p>

      <br />

      <ul class="text-light rslab">
        <li>
          bc1qn6vrmn8gdfpnkyg0l2vnqccq3gvf37w24e04w5 (BTC)

          <span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              style="height: 24px; width: 24px"
              class="text-warning"
            >
              <title>bitcoin</title>
              <path
                fill="currentColor"
                d="M14.24 10.56C13.93 11.8 12 11.17 11.4 11L11.95 8.82C12.57 9 14.56 9.26 14.24 10.56M11.13 12.12L10.53 14.53C11.27 14.72 13.56 15.45 13.9 14.09C14.26 12.67 11.87 12.3 11.13 12.12M21.7 14.42C20.36 19.78 14.94 23.04 9.58 21.7C4.22 20.36 .963 14.94 2.3 9.58C3.64 4.22 9.06 .964 14.42 2.3C19.77 3.64 23.03 9.06 21.7 14.42M14.21 8.05L14.66 6.25L13.56 6L13.12 7.73C12.83 7.66 12.54 7.59 12.24 7.53L12.68 5.76L11.59 5.5L11.14 7.29C10.9 7.23 10.66 7.18 10.44 7.12L10.44 7.12L8.93 6.74L8.63 7.91C8.63 7.91 9.45 8.1 9.43 8.11C9.88 8.22 9.96 8.5 9.94 8.75L8.71 13.68C8.66 13.82 8.5 14 8.21 13.95C8.22 13.96 7.41 13.75 7.41 13.75L6.87 15L8.29 15.36C8.56 15.43 8.82 15.5 9.08 15.56L8.62 17.38L9.72 17.66L10.17 15.85C10.47 15.93 10.76 16 11.04 16.08L10.59 17.87L11.69 18.15L12.15 16.33C14 16.68 15.42 16.54 16 14.85C16.5 13.5 16 12.7 15 12.19C15.72 12 16.26 11.55 16.41 10.57C16.61 9.24 15.59 8.53 14.21 8.05Z"
              />
            </svg>
          </span>
        </li>

        <li>
          0x36b8B3f4c278C6eb805E3c5217413328C237149a (BUSD)

          <img src="/images/busd.png" alt="Binance Logo" width="24" />
        </li>
      </ul>

      <div class="m-0 alert alert-warning rslab mt-5" data-bs-theme="dark">
        <h4 class="alert-heading">Perhatian!</h4>
        Setelah melakukan pembayaran non-tunai, mohon untuk melakukan konfirmasi ke kami dengan cara yang telah kami
        sediakan.
      </div>
    </div>

    <div class="py-5 container">
      <Contactbar title="Tunggu apalagi?" sub-title="Hubungi kami, dan pesan sekarang!" />
    </div>
  </section>
</template>

<style scoped lang="scss">
.payinfo-section {
  background-color: $dark;
}

.big-title {
  color: $green;
  text-decoration: underline;
  font-size: 50px;
}

.green-svg {
  color: $green;
}
</style>
