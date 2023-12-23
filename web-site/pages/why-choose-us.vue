<template>
  <div>
    <NavBar />
    <WhyChooseUsSection />
    <OurTeamSection />
    <OurCustomerService />
    <OurValuesSection />
    <AskUsSection />
  </div>
</template>

<script>
import NavBar from '../components/Why_choose_page/NavBar.vue'
import OurTeamSection from '../components/Why_choose_page/OurTeamSection.vue'
import OurCustomerService from '../components/Why_choose_page/OurCustomerService.vue'
import OurValuesSection from '../components/Why_choose_page/OurValuesSection.vue'
import AskUsSection from '../components/AskUsSection.vue'

export default {
  components: {
    NavBar,
    OurTeamSection,
    OurCustomerService,
    OurValuesSection,
    AskUsSection,
  },
}
</script>

<style></style>
