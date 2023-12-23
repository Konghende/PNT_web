<template>
  <div class="body">
    <a class="item d-lg-none" href="/">
      <IconMenuClose />
    </a>
    <div class="list">
      <h1>
        News Feeds<a class="item">
          <IconChevronsRight />
        </a>
      </h1>
      <h1>Achievements</h1>
      <h1>Contact</h1>
    </div>
    <div class="center">
      <button type="button" class="btn btn-secondary">ASK FOR A QUOTE</button>
    </div>
    <div class="news">
      <p>LATEST NEWS FEEDS</p>
      <div class="container">
        <img src="../../assets/images/Camtel Logo - Copy.png" />
        <p>
          LOREM IPSUM DOLOR SIT; ELIT DOLOR SIT, ADIPISCI ERROR AB ARCHITECTO
          OFFICIA FUGIT.ADIPISCI, ERROR ADIPISCI ARCHITECTO OFFICIA FUGIT
        </p>
        <p>29 MARCH 2021</p>
      </div>
      <div class="container">
        <img src="../../assets/images/Camtel Logo - Copy.png" />
        <p>
          LOREM IPSUM DOLOR SIT; ELIT DOLOR SIT, ADIPISCI ERROR AB ARCHITECTO
          OFFICIA FUGIT.ADIPISCI, ERROR ADIPISCI ARCHITECTO OFFICIA FUGIT
        </p>
        <p>29 MARCH 2021</p>
      </div>
    </div>
  </div>
</template>

<script>
import { IconChevronsRight, IconMenuClose } from '../icons/icons'

export default {
  components: {
    IconChevronsRight,
    IconMenuClose,
  },
}
</script>

<style lang="scss" scoped>
.body {
  background-color: #000000;
  background-image: url('../../assets/images/Intersection 3.png');
  background-size: 300px;
  background-repeat: no-repeat;
  background-position: bottom right;
  height: 896px;

  @include media-breakpoint-up(lg) {
    height: 768px;
    background-size: 500px;
  }
}
.body > .item {
  margin-left: 85%;
  cursor: pointer;
}
.item {
  font-size: 30px;
  color: #fff;
  padding-left: 18px;
}
.list {
  display: grid;
  grid-gap: 28px;
  color: #fff;
  font-size: 50px;
  padding: 0 65px 40px 20px;

  @include media-breakpoint-up(lg) {
    padding: 140px 65px 40px 20px;
  }
}
h1 {
  border-left-style: solid;
  border-left-width: 6px;
  border-left-color: #2e6069;

  @include media-breakpoint-up(lg) {
    margin-left: 129px;
  }
}
.center {
  padding: 0 0 40px 19px;
  @include media-breakpoint-up(lg) {
    margin-left: 150px;
  }
}
.btn {
  background-color: #2e6069;
  font-size: 15px;
  color: #fff;
  border-radius: 100px;
  padding: 16px 32px;
}
p {
  color: #fff;
  padding-left: 20px;
  font-size: 18px;
}
.container {
  backdrop-filter: blur(30px);
  border-radius: 10px;
  padding-top: 0px;
  margin-top: 24px;
}
.container img {
  margin-top: 16px;
  position: absolute;
  width: 42px;
}
.container p {
  padding-left: 56px;
}
.news {
  @include media-breakpoint-up(lg) {
    padding: 8rem;
    position: absolute;
    left: 44%;
    top: 0px;
  }
}
</style>
