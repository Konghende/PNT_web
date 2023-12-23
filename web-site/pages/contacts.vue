<template>
  <div>
    <NavBarSection />
    <ContactSection />
    <HeadOfficeSection />
    <FormSection />
  </div>
</template>

<script>
import NavBarSection from '../components/NavBarSection.vue'
import ContactSection from '../components/Contac_us_page/ContactSection.vue'
import HeadOfficeSection from '../components/Contac_us_page/HeadOfficeSection.vue'
import FormSection from '../components/Contac_us_page/FormSection.vue'

export default {
  components: { NavBarSection, ContactSection, HeadOfficeSection, FormSection },
}
</script>
