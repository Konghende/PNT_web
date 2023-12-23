<template>
  <div id="index-page">
    <NavBarSection />
    <NavServices />
    <BannerSection />
    <AboutUsSection />
    <OurVisionSection />
    <OurAchievements />
    <OurClientsSection />
    <OurPartners />
    <AskUsSection />
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
#index-page {
  .navbar {
    @include media-breakpoint-up(lg) {
      background-color: #2e6069;
      color: white;
    }
  }
}
</style>
