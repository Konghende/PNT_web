<template>
  <div class="our-client">
    <div class="client-text">
      <h3>What Our Clients Say</h3>
      <h1>"</h1>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Adipisci,
        error ab architecto officia fug lorem ipsum dolor sit amet, consetetur
        sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
        dolore magna aliquyam erat, sed diam voluptua.
      </p>
      <div class="client">
        <img src="../assets/images/c1.png" style="height: 53px; opacity: 0.5" />
        <div class="text">
          <h5>SANDY</h5>
          <h6>Director</h6>
        </div>
        <img src="../assets/images/c2.png" style="z-index: 2" />
        <div class="text">
          <h5>JOHN DEO</h5>
          <h6>Director</h6>
        </div>
        <img src="../assets/images/c3.png" style="height: 53px; opacity: 0.5" />
        <div class="text">
          <h5>JANE</h5>
          <h6>UI/UX Designer</h6>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
h3 {
  text-align: center;
  font-size: 17px;
}
h1 {
  font-weight: 900;
  font-family: 'arial';
  text-align: center;
  font-size: 600%;
}
p {
  text-align: center;
  color: rgb(36, 33, 33);
  padding: 1rem;
}
.our-client {
  @include media-breakpoint-up(lg) {
    background-image: url('../assets/images/Mask Group 9 - Copy.png');
    height: 86vh;
    background-size: 415px;
    background-repeat: no-repeat;
    background-position: center right;
  }
}
.client-text {
  padding: 1rem;
  @include media-breakpoint-up(lg) {
    width: 60%;
    margin-left: 20%;
  }
}
.client {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  @include media-breakpoint-up(lg) {
    flex-wrap: nowrap;
  }
}
h5 {
  color: #2e6069;
  text-align: start;
  font-size: 12px;
}
h6 {
  font-size: 11px;
}
.text {
  padding-right: 10%;
  color: #929292;
  z-index: 2;
}
</style>
