<script>
export default {
  props: {
    title: String,
    subTitle: String,
  },
};
</script>

<template>
  <div class="container wrapper p-4 mt-5">
    <div class="row">
      <div class="col-12 col-lg-9">
        <p class="sub-title m-0 heebo">{{ title }}</p>
        <p class="big-title fs-1 patua m-0">{{ subTitle }}</p>
      </div>
      <div class="col-12 col-lg-3 d-flex align-items-center justify-content-center">
        <button class="order-button patua">Pesan Sekarang</button>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.wrapper {
  width: 100%;
  background-color: $green;
  border-radius: 10px;
}

.sub-title {
  color: $altdark;
  font-weight: 500;
  text-decoration: underline;
  text-align: center;
}

.big-title {
  text-align: center;
}

.order-button {
  border: none;
  background-color: $altdark;
  color: white;
  padding-block: 1em;
  padding-inline: 1.5em;
  border-radius: 9999px;
  border: 2px solid transparent;
  transition: 0.2s all;
  margin-top: 40px;

  &:hover {
    background-color: $green;
    color: $altdark;
    border: 2px solid $altdark;
  }
}

@media screen and (min-width: 992px) {
  .wrapper {
    width: 80%;
  }
  .big-title {
    text-align: left;
  }
  .sub-title {
    text-align: left;
  }

  .order-button {
    margin-top: 0;
  }
}
</style>
