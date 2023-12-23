<template>
  <div class="body">
    <div class="tittle-text">
      <h1>CONTACT US</h1>
      <p>
        Fill in the following form, and you'll be contacted by our customer
        service.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.body {
  background: linear-gradient(
      rgba(255, 255, 255, 0.7),
      rgba(255, 255, 255, 0.7)
    ),
    url('../../assets/images/pntec customer sevice.png') no-repeat;
  background-size: cover;
  background-position: center;

  @include media-breakpoint-up(lg) {
    height: 379px;
  }
}
.tittle-text {
  text-align: center;
  padding: 1rem;

  @include media-breakpoint-up(lg) {
    padding: 76px 380px 152px 381px;
  }
}
.tittle-text > h1 {
  font-size: 30px;
  font-weight: 400;
  color: #2e6069;
  padding-top: 40px;

  @include media-breakpoint-up(lg) {
    font-size: 50px;
  }
}
.tittle-text > p {
  font-size: 18px;
  font-weight: 300;
  color: #555757;
}
</style>
