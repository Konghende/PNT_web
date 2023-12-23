<template>
  <div class="container text-center py-4">
    <b-form-group label="Choose a color here...">
      <b-form-input v-model="color" type="color" />
    </b-form-group>
    <div class="row" :style="{ color }">
      <div class="col-6 col-md-3 col-lg-2">
        <IconAwesomeCheck />
        <p>IconAwesomeCheck</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconArrowRight />
        <p>IconArrowRight</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconCheck />
        <p>IconCheck</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronDown />
        <p>IconChevronDown</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronLeft />
        <p>IconChevronLeft</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronsDown />
        <p>IconChevronsDown</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconFacebook />
        <p>IconFacebook</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconSearch />
        <p>IconSearch</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconAwesomeYoutube />
        <p>IconAwesomeYoutube</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronRight />
        <p>IconChevronRight</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronUp />
        <p>IconChevronUp</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronsLeft />
        <p>IconChevronsLeft</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronsRight />
        <p>IconChevronsRight</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconChevronsUp />
        <p>IconChevronsUp</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconExternalLink />
        <p>IconExternalLink</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconInstagram />
        <p>IconInstagram</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconLinkedin />
        <p>IconLinkedin</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconMenuClose />
        <p>IconMenuClose</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconMenu />
        <p>IconMenu</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconPhone />
        <p>IconPhone</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconTwitter />
        <p>IconTwitter</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconYoutube />
        <p>IconYoutube</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconAttachment />
        <p>IconAttachment</p>
      </div>
      <div class="col-6 col-md-3 col-lg-2">
        <IconCalendar />
        <p>IconCalendar</p>
      </div>
    </div>
  </div>
</template>

<script>
import {
  IconAwesomeCheck,
  IconArrowRight,
  IconCheck,
  IconChevronDown,
  IconChevronLeft,
  IconChevronsDown,
  IconFacebook,
  IconSearch,
  IconAwesomeYoutube,
  IconChevronRight,
  IconChevronUp,
  IconChevronsLeft,
  IconChevronsRight,
  IconChevronsUp,
  IconExternalLink,
  IconInstagram,
  IconLinkedin,
  IconMenuClose,
  IconMenu,
  IconPhone,
  IconTwitter,
  IconYoutube,
  IconAttachment,
  IconCalendar,
} from '../../components/icons/icons'

export default {
  components: {
    IconAwesomeCheck,
    IconArrowRight,
    IconCheck,
    IconChevronDown,
    IconChevronLeft,
    IconChevronsDown,
    IconFacebook,
    IconSearch,
    IconAwesomeYoutube,
    IconChevronRight,
    IconChevronUp,
    IconChevronsLeft,
    IconChevronsRight,
    IconChevronsUp,
    IconExternalLink,
    IconInstagram,
    IconLinkedin,
    IconMenuClose,
    IconMenu,
    IconPhone,
    IconTwitter,
    IconYoutube,
    IconAttachment,
    IconCalendar,
  },
  data() {
    return {
      color: 'currentColor',
    }
  },
}
</script>

<style scoped>
.b-icon {
  font-size: 3rem;
  margin-bottom: 10px;
}

p {
  color: gray;
}
</style>
