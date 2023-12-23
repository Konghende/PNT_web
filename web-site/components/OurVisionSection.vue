<template>
  <div class="our-vision">
    <div class="text">
      <h6>OUR VISION & MISSION</h6>
      <p>
        We aspire to be a benchmark company in the field of ICT in Central
        Africa and Cameroon in particular.
      </p>

      <p>
        This is why we make it a point of honor to provide a global solution
        that meets the specific needs of the companies with which we work and at
        affordable costs.
      </p>
      <p>
        More than a job, IT is a passion that we pass on in each of the projects
        we carry out.
      </p>
    </div>
    <div class="center">
      <nuxt-link class="cta" to="why-choose-us">
        <button type="button" class="btn btn-secondary">Read More</button>
      </nuxt-link>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.our-vision {
  @include media-breakpoint-up(lg) {
    background-image: url('../assets/images/Mask Group 2 - Copy.png');
    height: 82vh;
    background-size: 454px;
    background-repeat: no-repeat;
    background-position: left;
  }
}
.text {
  background-color: rgba(255, 255, 255, 0.9);
  padding: 10px 20px;

  @include media-breakpoint-up(lg) {
    width: 50%;
    background-color: rgb(255, 255, 255);
    margin-top: 80px;
    margin-left: 46%;
  }
  p {
    color: #545555;
    padding: 0.5rem;
  }
  h6 {
    padding: 0.5rem;
    color: #2e6069;
  }
}
.center {
  text-align: center;
}
button {
  border-radius: 24px;
  width: 160px;
  padding: 11px;
  background-color: white;
  border-color: #2e6069;
  color: #2e6069;
  @include media-breakpoint-up(lg) {
    margin-left: 130px;
  }
}
</style>
