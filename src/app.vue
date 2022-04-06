<template>
  <section class="app-container main-layout">
    <app-header />
    <!-- This will be a router view rendering cmps dynamically in a proper app -->
    <landing-page />
    <app-footer />
  </section>
</template>

<script >
import appHeader from './cmps/app-header.vue'
import landingPage from './pages/landing-page.vue'
import appFooter from './cmps/app-footer.vue'

export default {
  components: {
    appHeader,
    landingPage,
    appFooter
  }
}
</script>

<style>
</style>
