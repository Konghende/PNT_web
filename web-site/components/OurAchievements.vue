<template>
  <div class="achievements">
    <h3>Our Achievements</h3>
    <div class="container">
      <div class="bank">
        <img src="../assets/images/pic 1.png" />
        <div class="text">
          <p>WEB DEVELOPMENT</p>
          <h4>CCEI BANK GE</h4>
        </div>
      </div>
      <div class="sport">
        <img src="../assets/images/pic 2.png" />
        <div class="text">
          <p>WEB DEVELOPMENT</p>
          <h4>CCEI BANK GE</h4>
        </div>
      </div>
      <div class="socec">
        <img src="../assets/images/pic 3.png" />
        <div class="text">
          <p>WEB DEVELOPMENT</p>
          <h4>CCEI BANK GE</h4>
        </div>
      </div>
    </div>
    <div class="center">
      <button type="button" class="btn btn-secondary">See More</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
h3 {
  margin: 30px 0 20px;
  text-align: center;
  @media screen and (min-width: 991px) {
    margin: -110px 0 20px;
  }
}
.container {
  width: 100%;
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
}
img {
  margin: 3px;
  width: 97%;
}
@media screen and (max-width: 991px) {
  .container {
    flex-direction: column;
  }
}
.text {
  width: 100%;
  position: relative;
  padding: 20px;
  margin-top: -30%;
  text-align: start;
  background: linear-gradient(#ffffff 0% 0%);
  height: 101px;
  opacity: 0.9;
  @media screen and (min-width: 449px) {
    height: 207px;
  }
  @media screen and (min-width: 992px) {
    height: 111px;
  }
}
p {
  color: #2e6069;
  margin-bottom: -1%;
  font-weight: 700;
  z-index: 2;
}
.center {
  text-align: center;
}
button {
  background-color: #2e6069;
  border-radius: 100px;
  padding: 11px;
  width: 160px;
  margin: 10px;
}
</style>
