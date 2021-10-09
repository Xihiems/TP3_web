<template>

  <div id=" App">
    <headerPage />
    <BaseLayout>
      <HomePage />
    </BaseLayout>

    <FooterPage />
  </div>

</template>

<script>
import headerPage  from "./components/Page/Homepage/Header.vue"
import FooterPage  from "./components/Page/Homepage/Footer.vue"
import HomePage  from "./components/Page/Homepage/Homepage.vue"
import BaseLayout from "./components/Page/Homepage/BaseLayout";
export default {
  name: 'App',
  components: {
    headerPage,
    FooterPage,
    HomePage,
    BaseLayout
  }
}
</script>
