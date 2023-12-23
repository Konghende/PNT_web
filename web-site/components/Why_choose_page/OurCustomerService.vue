<template>
  <div class="body">
    <img
      src="../../assets/images/Customer-Support-Pages-1920-731 - Copy.png"
      class="d-block d-lg-none illustration"
      alt="Cuatomer Service Illustration"
      height="200"
    />
    <div class="text">
      <h1>OUR CUSTOMER SERVICE</h1>
      <p>
        We provide our customers with a hotline to respond to the concerns of
        our precious customers.
      </p>
      <p>
        It allows us to act quickly and efficiently to best meet the
        requirements of our customers.
      </p>
      <div class="contact">
        <h3>AVAILABLE 7/7 DAYS TO SERVE YOU.</h3>
        <a class="nav-item-icon">
          <IconPhone />
          (+237) 681 629 775
        </a>
      </div>
    </div>
    <img src="../../assets/images/Group 462.png" />
  </div>
</template>

<script>
import { IconPhone } from '../icons/icons'

export default {
  components: {
    IconPhone,
  },
}
</script>

<style lang="scss" scoped>
.body {
  background-repeat: no-repeat;

  @include media-breakpoint-up(lg) {
    background: linear-gradient(270deg, transparent 400px, #fff 800px),
      url('./assets/images/Customer-Support-Pages-1920-731 - Copy.png');
    background-size: cover;
    padding-top: 82px;
  }
}
.text {
  padding: 1rem;
  top: 200px;

  @include media-breakpoint-up(lg) {
    top: 82px;
    margin-right: 34%;
    margin-left: 120px;
  }
}
h1 {
  font-size: 30px;
  font-weight: 400;
  color: #2e6069;
  padding-bottom: 30px;
}
p {
  font-size: 20px;
  color: rgb(80, 82, 83);
}
.contact {
  color: #2e6069;
  text-align: center;
  line-height: 0cm;
  padding-top: 68px;
}
h3 {
  font-size: 15px;
  font-weight: 400;
  text-align: center;
  color: #2e6069;

  @include media-breakpoint-up(lg) {
    font-size: 23px;
  }
}
.nav-item-icon {
  font-size: 36px;
  font-weight: 300;
  color: #2e6069;

  @include media-breakpoint-up(lg) {
    font-size: 56px;
  }
}
img {
  width: 100px;

  @include media-breakpoint-up(lg) {
    width: 160px;
  }
}

.illustration {
  width: 100%;
  height: 200px;
  object-fit: cover;
  object-position: center;
}
</style>
