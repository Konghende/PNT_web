<template>
  <div class="body">
    <div class="text">
      <h3>Ask us anything</h3>
      <div class="center">
        <nuxt-link class="cta" to="contacts">
          <b-button pill>Contact Us</b-button>
        </nuxt-link>
      </div>
      <p>
        Fill in the following form, and you'll be contacted by our customer
        service.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.body {
  background: linear-gradient(rgba(46, 96, 105, 0.7), rgba(46, 96, 105, 0.7)),
    url('../assets/images/Customer-Support-Pages-1920-732.png') no-repeat;
  @include media-breakpoint-up(lg) {
    background: linear-gradient(92deg, transparent, rgb(46, 96, 105, 1) 55%),
      url('../assets/images/Customer-Support-Pages-1920-732.png') no-repeat;
    background-size: cover;
    height: 459px;
  }
}
.text {
  padding: 1rem;
  @include media-breakpoint-up(lg) {
    margin-left: 50%;
  }
}
h3 {
  text-align: center;
  padding-top: 96px;
  color: #fff;
  font-weight: 300;
}
.center,
p {
  text-align: center;
  padding-top: 20px;
  color: #fff;
  font-weight: 300;
}
.btn {
  background-color: #fff;
  color: #2e6069;
  width: 167px;
  font-size: 15px;
  padding: 1rem;
}
</style>
