<template>

  <div id=" App">
    <headerPage />
    <HomePage />
    <FooterPage />
  </div>

</template>

<script>
import headerPage  from "./components/Page/Homepage/Header.vue"
import FooterPage  from "./components/Page/Homepage/Footer.vue"
import HomePage  from "./components/Page/Homepage/Homepage.vue"
export default {
  name: 'App',
  components: {
    headerPage,
    FooterPage,
    HomePage
  }
}
</script>
