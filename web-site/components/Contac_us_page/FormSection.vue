<template>
  <div class="container">
    <div class="heading">
      <h3>Leave Us A Message</h3>
    </div>
    <form class="form">
      <div class="form-control">
        <input type="text" placeholder="First Name*" />
      </div>
      <div class="form-control">
        <input type="text" placeholder="Last Name*" />
      </div>
      <div class="form-control">
        <input type="text" placeholder="Company Name" />
      </div>
      <div class="form-control">
        <input type="text" placeholder="Phone*" />
      </div>
      <div class="form-control">
        <input type="text" placeholder="Email*" />
      </div>
      <div class="form-control">
        <input type="text" placeholder="Attachment" />
      </div>
    </form>
    <div class="message-form">
      <input type="text" placeholder="Message*" />
    </div>
    <div class="center">
      <button type="button" class="btn btn-secondary">Send Message</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.heading {
  padding-left: 10px;
}
.heading > h3 {
  font-size: 22px;
  font-weight: 400;
}
.form-control {
  padding-bottom: 60px;
  border: none;
}
.form-control > input {
  height: 50px;
  width: 100%;
  background: #f5f5f5 0% 0% no-repeat padding-box;
  border: 1px solid #2e606999;
  border-radius: 5px;
  font-size: 15px;
}
.message-form {
  padding-top: 40px;
}
.message-form > input {
  height: 229px;
  width: 100%;
  background: #f5f5f5 0% 0% no-repeat padding-box;
  border: 1px solid #2e606999;
  border-radius: 5px;
  font-size: 15px;
  text-align: center;
}
.form {
  @include media-breakpoint-up(lg) {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-auto-rows: auto;
    grid-gap: 20px;
  }
}
.center {
  text-align: center;
  padding-top: 20px;
}
.center > button {
  background-color: #2e6069;
  border-radius: 100px;
  padding: 11px;
  width: 160px;
  margin: 10px;
}
</style>
