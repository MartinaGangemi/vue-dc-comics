<template>
    <div class="bg_blue">
        <div class="container">
            <div class="row">
                <div class="col" v-for="(list, index) in listItem" :key="index"><img :src="list.src" alt=""> {{list.text}}</div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
  name: 'MenuComponent',
    data () {
       return  { 
          listItem : [
            {
                src: "@/assets/img/buy-comics-digital-comics.png",
                text: "Digital comics",
            },

            {
                src: "@/assets/img/buy-comics-digital-comics.png",
                text: "DC Merchandise",
            },

            {
                src: "@/assets/img/buy-comics-digital-comics.png",
                text: "Subscrition",
            },

            {
                src: "@/assets/img/buy-comics-digital-comics.png",
                text: "Comics Shop Locator",
            },

            {
                src: "@/assets/img/buy-comics-digital-comics.png",
                text: "Dc power Visa",
            },
        ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .bg_blue{
        background-color:#0282F9 ;
    }

    .row{
        align-items: center;
        padding: 2rem;
    }
    
    .col{
        flex-grow: 1;
    }
</style>