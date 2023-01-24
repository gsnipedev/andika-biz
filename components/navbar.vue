<template>
  <nav class="navbar navbar-expand-lg sticky-top">
    <div class="container the-nav">
      <a class="navbar-brand patua fs-1 text-light" href="/">NetHeve</a>
      <button
        class="navbar-toggler text-light"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <svg style="width: 24px; height: 24px" viewBox="0 0 24 24">
          <path
            fill="currentColor"
            d="M22 13C22 14.11 21.11 15 20 15H4C2.9 15 2 14.11 2 13S2.9 11 4 11H13L15.5 13L18 11H20C21.11 11 22 11.9 22 13M12 3C3 3 3 9 3 9H21C21 9 21 3 12 3M3 18C3 19.66 4.34 21 6 21H18C19.66 21 21 19.66 21 18V17H3V18Z"
          />
        </svg>
      </button>
      <div class="collapse navbar-collapse patua local-navbar" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link" aria-current="page" href="/">Beranda</a>
          <a class="nav-link" href="/product">Produk & Layanan</a>
          <a class="nav-link" href="/payment">Pembayaran</a>
          <a class="nav-link" href="#">Kontak</a>
          <a class="nav-link" href="#">Tentang</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped lang="scss">
.navbar {
  background-color: $altdark;
}
.local-navbar {
  justify-content: left;
}

.navbar-nav {
  > a {
    color: white;
    font-size: 18px;
    margin-inline: 10px;

    &:hover {
      color: $green;
    }
  }
}

@media screen and (min-width: 992px) {
  .local-navbar {
    justify-content: right;
  }

  .navbar-nav {
    > a {
      margin-inline: 0px;
    }
  }
}
</style>
