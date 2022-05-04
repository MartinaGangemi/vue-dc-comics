<template>
  <header class="container">
      <div class="row">
          <!-- logo img -->
        <div class="col-4">
            <img src="@/assets/img/dc-logo.png" alt=""> 
        </div>
        <!-- nav -->
        <div class="col-8">
            <SiteNav />
        </div>
      </div>
  </header>
</template>

<script>
import SiteNav from "@/components/NavComponent"

export default {
  name: 'HeaderComponent',
  components: {
      SiteNav
  }
}
</script>

<style lang="scss" scoped>
    header{
        background-color: white;
        padding: 1rem 0 1rem;
    }

    .row{
        align-items: center;
    }

    .col-4{
        width: calc(100% / 12)*4;
        height: 80px;
    }

    .col-8{
        width: calc(100% / 12)*8;
        text-align: right;
    }
</style>