<template>
  <div class="body">
    <h3>Head Office</h3>
    <div class="image">
      <img
        src="../../assets/images/christian-gabi-fLBAwYeSKHA-unsplash.png"
        alt="Heat Office Illustration"
      />
    </div>
    <div class="text">
      <p>Montée Chapelle Obili Yaoundé, Cameroun B.P. 10123</p>
      <br />(+237) 242 016 500 <br />660 111 239 <br />656 709 220 <br />681 629
      775
      <p>contact@pntec-ltd.com</p>
    </div>
    <div class="map">
      <p>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3980.6428534778124!2d11.50090101474189!3d3.886497749261035!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x108bcfcda15c8a05%3A0x5cb4f2a59f837c59!2sPNTEC%20Ltd!5e0!3m2!1sen!2scm!4v1627460254014!5m2!1sen!2scm"
          width="100%"
          height="233px"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
        ></iframe>
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.body > h3 {
  padding: 1rem;
  font-size: 22px;
  font-weight: 300;
}
.image {
  text-align: center;
}
.image > img {
  width: 90%;
  height: 207px;

  @include media-breakpoint-up(lg) {
    height: 463px;
  }
}
.text {
  padding: 20px;
  text-align: center;
  line-height: 1;
  font-size: 22px;

  @include media-breakpoint-up(lg) {
    padding-top: 10%;
    padding-right: 50%;
  }
}
.text > p {
  margin-top: 14px;
}
.map {
  padding: 20px;

  @include media-breakpoint-up(lg) {
    padding: 0 0 0 50%;
    position: relative;
    top: -284px;
    padding-right: 60px;
  }
}
.map > p > iframe {
  @include media-breakpoint-up(lg) {
    height: 364px;
  }
}
</style>
