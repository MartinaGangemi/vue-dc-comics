<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
  </div>
</template>

<script>

import SiteMain from "./components/MainComponent.vue"
import SiteHeader from "./components/HeaderComponent.vue"
export default {
  name: 'App',
  components: {
   SiteHeader,
   SiteMain
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
</style>
