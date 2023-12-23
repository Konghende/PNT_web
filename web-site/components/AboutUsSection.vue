<template>
  <div class="about-us">
    <div class="about-us-text">
      <h6>About Us</h6>
      <p>
        Our company has been in business for over 5 years. We have participated
        in many projects from different horizons, involving several
        technologies. These achievements have consolidated our know-how and our
        team spirit, making us want to take on even greater challenges in the
        future.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about-us {
  background: white url('../assets/images/about-us-bg.jpg') no-repeat;
  background-size: cover;

  @include media-breakpoint-up(lg) {
    padding: 125px 60px;
  }
}
h6 {
  color: #2e6069;
}
p {
  color: #545555;
}

.about-us-text {
  background-color: rgba(255, 255, 255, 0.9);
  padding: 2rem;

  @include media-breakpoint-up(lg) {
    width: 50%;
    background-color: rgb(255, 255, 255);
    padding: 2rem;
  }
}
</style>
