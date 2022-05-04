<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteMenu />
    <SiteFooter />
    <EndFooter />
  </div>
</template>

<script>

import SiteMain from "./components/MainComponent.vue"
import SiteHeader from "./components/HeaderComponent.vue"
import SiteMenu from "./components/MenuComponent.vue"
import SiteFooter from "./components/FooterComponent.vue"
import EndFooter from "@/components/EndFooterComponent"
export default {
  name: 'App',
  components: {
   SiteHeader,
   SiteMain,
   SiteMenu,
   SiteFooter,
   EndFooter,
  }
}
</script>

<style lang="scss">
  @import '@/assets/scss/style.scss';

</style>
