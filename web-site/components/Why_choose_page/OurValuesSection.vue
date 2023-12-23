<template>
  <div class="body">
    <h1>OUR VALUES</h1>
    <div class="container">
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/transparency.png" />
        </div>
        <div class="text">
          <p>Transparency</p>
        </div>
      </div>
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/secret-file.png" />
        </div>
        <div class="text">
          <p>Confidentiality</p>
        </div>
      </div>
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/skill-development.png" />
        </div>
        <div class="text">
          <p>Integrity</p>
        </div>
      </div>
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/innovation.png" />
        </div>
        <div class="text">
          <p>Innovation</p>
        </div>
      </div>
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/decentralized.png" />
        </div>
        <div class="text">
          <p>Dynamism</p>
        </div>
      </div>
      <div class="cards">
        <div class="items">
          <img src="../../assets/images/followers.png" />
        </div>
        <div class="text">
          <p>Friendliness</p>
        </div>
      </div>
    </div>
    <OurPartners id="our-partners" />
  </div>
</template>

<script>
import OurPartners from '../OurPartners.vue'

export default {
  components: { OurPartners },
}
</script>

<style lang="scss" scoped>
.body {
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url('../../assets/images/iStock-826217148-1920x1281.png') no-repeat;
  background-position: top;
  background-size: cover;
}
.container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-auto-rows: auto;
  grid-gap: 16px;
  text-align: center;
  justify-content: center;
  cursor: pointer;
  @include media-breakpoint-up(lg) {
    grid-template-columns: repeat(3, 1fr);
    width: 500px;
  }
}
.container > .cards {
  background: #fff;
  border-radius: 5px;
}
img {
  padding: 1rem;
  width: 75px;
  @include media-breakpoint-up(lg) {
    margin: 69px 102px 53px;
  }
}
.text {
  @include media-breakpoint-up(lg) {
    padding-bottom: 58px;
  }
}
h1 {
  font-size: 35px;
  text-align: center;
  color: #fff;
  padding-top: 50px;
  @include media-breakpoint-up(lg) {
    padding: 68px 0 49px;
  }
}
</style>
