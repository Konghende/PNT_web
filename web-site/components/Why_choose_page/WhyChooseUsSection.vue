<template>
  <div class="banner">
    <div class="text">
      <h1>WHY CHOOSE US?</h1>
      <p>
        Lorem ipsum dolor sit, elit. Adipisci, error ab architecto officia
        fugit.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.banner {
  background: linear-gradient(
      rgba(255, 255, 255, 0.5),
      rgba(255, 255, 255, 0.5)
    ),
    url('./assets/images/it_specialist_1920.png') no-repeat;
  background-size: cover;
  background-position: center;
  padding: 1.5rem;
  @include media-breakpoint-up(sm) {
    padding: 125px 60px;
  }
}
.text {
  text-align: center;
  font-weight: 300;
}
p {
  font-size: 18px;
}
h1 {
  font-size: 30px;
  font-weight: 400;
  color: #2e6069;
  @include media-breakpoint-up(sm) {
    font-weight: 400;
    font-size: 50px;
  }
}
</style>
