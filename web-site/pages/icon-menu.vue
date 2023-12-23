<template>
  <div id="icon-menu">
    <NavBarSection />
    <MenuPage />
  </div>
</template>

<style lang="scss" scoped>
#icon-menu {
  .navbar {
    display: none;
    @include media-breakpoint-up(lg) {
      display: flex;
      background-color: #000;
      color: #fff;
    }
  }
}
</style>
