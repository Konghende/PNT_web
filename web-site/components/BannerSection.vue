<template>
  <div class="banner">
    <div class="text">
      <h3>STATE OF THE ART</h3>
      <div class="arrow">
        <img src="../assets/images/XMLID_341_.png" />
      </div>
      <div class="pics">
        <img
          src="../assets/images/joshua-rawson-harris-KRELIShKxTM-unsplash.png"
        />
        <div class="center">
          <nuxt-link class="cta" to="ask-a-quote">
            <button type="button" class="btn btn-secondary">
              Ask For A Quote
            </button>
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.banner {
  background: linear-gradient(
      rgba(255, 255, 255, 0.9),
      rgba(255, 255, 255, 0.9)
    ),
    url('../assets/images/a-black-man-sitting-at-a-computer-coding-away-computer-programming-diversity-in-stem.png')
      no-repeat;
  background-color: #fff;
  background-size: cover;
  padding: 40px 20px;
}
.center {
  text-align: center;
}
button {
  background-color: #2e6069;
  border-radius: 100px;
  padding: 2% 5%;
  @include media-breakpoint-up(lg) {
    display: none;
  }
}
.pics {
  text-align: center;
}
.pics img {
  width: 100%;
  left: 20px;
  margin-bottom: 70px;
  @include media-breakpoint-up(lg) {
    margin-left: 17%;
    width: 81%;
  }
}
h3 {
  color: #2e6069;
  margin-bottom: 7.75px;
  font-weight: 700;
  margin-top: 91px;
  font-size: 100.76%;
  @include media-breakpoint-up(lg) {
    margin-left: 50px;
    font-size: 239.76%;
    margin-top: 200px;
  }
}
.arrow {
  margin-left: 48px;
  top: 556px;
  position: absolute;
  display: none;
  @include media-breakpoint-up(lg) {
    display: inline-block;
  }
}
</style>
