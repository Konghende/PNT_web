<template>
  <nav class="navbar navbar-light">
    <a href="/" class="navbar-toggle-icon">
      <img src="../assets/images/Pntec Logo.png" alt="logo"
    /></a>
    <div class="container_fliud">
      <ul class="nav_links ml-auto"></ul>
      <a class="nav-item-icon">
        <IconFacebook />
      </a>
      <a class="nav-item-icon">
        <IconTwitter />
      </a>
      <a class="nav-item-icon">
        <IconInstagram />
      </a>
      <a class="nav-item-icon">
        <IconYoutube />
      </a>
      <a class="nav-item-icon">
        <IconLinkedin />
      </a>
      <a class="language-selector d-none d-lg-inline">
        EN
        <IconChevronsDown />
      </a>
      <b-button variant="outline-dark" class="cta" to="why-choose-us">
        WHY CHOOSE US?
      </b-button>
      <nuxt-link class="nav-item-icon" to="icon-menu">
        <IconMenu />
      </nuxt-link>
    </div>
  </nav>
</template>

<script>
import {
  IconFacebook,
  IconTwitter,
  IconInstagram,
  IconYoutube,
  IconLinkedin,
  IconChevronsDown,
  IconMenu,
} from './icons/icons'

export default {
  components: {
    IconFacebook,
    IconTwitter,
    IconInstagram,
    IconYoutube,
    IconLinkedin,
    IconChevronsDown,
    IconMenu,
  },
}
</script>

<style lang="scss" scoped>
.navbar {
  background-color: white;
  padding-top: 6px;
  padding-bottom: 6px;
  padding-left: 15px;

  &.open {
    background-color: black;
    color: white;
  }

  @include media-breakpoint-up(lg) {
    justify-content: space-between;
    padding-top: 6px;
    padding-bottom: 5px;
    padding-left: 50px;
  }
}
.container_fliud {
  padding-bottom: 10px;
  cursor: pointer;
}
.cta {
  margin-left: 20px;
  margin-right: 20px;
  background-color: transparent;
  padding: 7px 23px;
  border: 2px solid currentColor;
  border-radius: 100px;
  cursor: pointer;
  display: none;
  color: inherit;

  @include media-breakpoint-up(lg) {
    display: inline-block;
  }
}
.language {
  color: inherit;
  text-decoration: none;
  display: none;
  @include media-breakpoint-up(lg) {
    display: inline;
  }
  .menu {
    background-color: #2e6069;
    @include media-breakpoint-up(lg) {
      display: none;
    }
  }
}

.nav-item-icon {
  color: inherit;
  font-size: 20px;
  vertical-align: middle;
  margin-right: 5px;
  @include media-breakpoint-up(lg) {
    margin-right: 24px;
  }
}

.language-selector {
  font-size: 18px;
  margin-left: 5px;
  color: inherit;
  vertical-align: middle;
  text-decoration: none;
}
</style>
