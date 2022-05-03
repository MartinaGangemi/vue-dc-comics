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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container{
   max-width: 1300px;
  margin: 0 auto;
}

img{
  max-height: 100%;
}

 .row{
        display: flex;
    }
</style>
