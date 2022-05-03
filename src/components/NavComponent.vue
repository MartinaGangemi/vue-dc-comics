<template>
    <nav>
        <ul>
            <li v-for="(list, index) in listMenu" :key="index" :class="active" > {{ list }} </li>
        </ul>
    </nav>
</template>

<script>
    export default {
  name: 'NavComponent',
  data () {
       return  { 
          listMenu : ["Character","Comics","Movies", "tv" , "games","collectibles","videos","fans","news","shop",]
      
  }
    }
}


</script>

<style lang="scss" scoped>

    ul{
        li{
            list-style: none;
            display: inline-block;
            margin: 1rem;
            text-transform: uppercase;
            font-size: 0.8rem;
            font-weight: bold;
            color: #1C1C1C ;
            position: relative;
            cursor: pointer;
        }

        .active:after{
            border-bottom: solid 4px #0282F9;
            content: '';
            position: absolute;
            left: 0;
            right: 0;
            width: 100%;
            top: 59px;
            margin: 0 auto;
        }
    }
</style>