<template>
  <div class="text">
    <h3>OUR PARTNERS</h3>
    <div class="container">
      <div class="logos">
        <img src="../assets/images/Camtel Logo.png" />
      </div>
      <div class="logos">
        <img src="../assets/images/MTN Logo.png" />
      </div>
      <div class="logos">
        <img src="../assets/images/Nexttel Logo.png" />
      </div>
      <div class="logos">
        <img src="../assets/images/Orange Logo.png" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.text {
  color: #2e6069;
  text-align: center;
  padding: 1rem;
}
h3 {
  padding-top: 50px;
  font-size: 15px;
  @include media-breakpoint-up(lg) {
    text-align: start;
    padding-top: 60px;
    position: absolute;
    font-size: 15px;
    margin-left: 120px;
  }
}
.container {
  width: 100%;
  display: grid;
  grid-template-columns: auto auto;
  grid-gap: 10px;
  justify-items: center;
  justify-content: center;
  @include media-breakpoint-up(lg) {
    grid-gap: 100px;
    justify-content: end;
    grid-template-columns: auto auto auto auto;
  }
}
.logos {
  padding: 10px;
  transition: all 700ms ease-in;
  filter: grayscale(1) opacity(0.8);
  cursor: pointer;
  @include media-breakpoint-down(xs) {
    &:not(:last-child) {
      border-bottom: 1px solid #d8d6d6d7;
    }
  }
  img {
    width: 80px;
  }

  /* @include media-breakpoint-up(sm) {
    &:not(:last-child) {
      border-right: 1px solid #d8d6d6d7;
    }
  }*/
}
.logos:hover {
  filter: grayscale(0) opacity(1);
}
</style>
