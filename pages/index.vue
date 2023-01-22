<template>
  <section class="top-banner">
    <div class="container py-5">
      <h1 class="big-title secular">Jasa Pembuatan Website, Aplikasi Android & Desktop.</h1>
      <p class="sub-title heebo">
        Kami adalah tim yang bergerak di bidang jasa yang meliputi: Pembuatan Website, Aplikasi Android, Database
        Design, Aplikasi Desktop, Office Software, dan lain sebagainya.
      </p>

      <button class="contact-button patua">Hubungi Kami</button>
    </div>
  </section>

  <Secondsection />
  <Thirdsection />
</template>

<style scoped lang="scss">
.top-banner {
  background-color: $dark;
  color: white;
}

.top-banner {
  background-image: linear-gradient(to left, rgba(245, 246, 252, 0.52), rgba($altdark, 0.8)), url("/images/banner.jpg");
  background-size: cover;
  background-position-y: center;
}

.big-title {
  word-wrap: break-word;
  max-width: 20ch;
  font-size: 30px;
}

.contact-button {
  padding-inline: 2em;
  padding-block: 0.75em;
  border-radius: 5px;
  border: 2px solid $green;
  outline: none;
  cursor: pointer;
  background-color: $altdark;
  color: $green;
}

.sub-title {
  word-wrap: break-word;
  max-width: 50ch;
}

@media screen and (min-width: 992px) {
  .big-title {
    font-size: 50px;
  }
}
</style>
