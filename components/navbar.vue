<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand patua fs-1 text-light" href="#">NetHeve</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse patua local-navbar" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link" aria-current="page" href="#">Beranda</a>
          <a class="nav-link" href="#">Produk & Layanan</a>
          <a class="nav-link" href="#">Pembayaran</a>
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
      color: $dark;
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
