<template>
    <div class="bg_blue">
        <div class="container">
            <div class="row">
                <div class="col" v-for="(list, index) in listItem" :key="index">
                    <img :src="require(`@/assets${list.src}`)"> {{list.text}}
                </div>
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
                src: "/img/buy-comics-digital-comics.png",
                text: "Digital comics",
            },

            {
                src: "/img/buy-comics-merchandise.png",
                text: "Digital comics",
            },
            {
                src: "/img/buy-comics-subscriptions.png",
                text: "Digital comics",
            },
            {
                src: "/img/buy-comics-shop-locator.png",
                text: "Digital comics",
            },
            {
                src: "/img/buy-dc-power-visa.svg",
                text: "Digital comics",
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
        padding: 3rem;
        gap: 2rem;
    }
    
    .col{
        flex-grow: 1;
        color: white;
        text-transform: uppercase;
        font-size: 0.9rem;
        display: flex;
        align-items: center;
        
    }

    img{
        height: 60px;
        margin-right: 1rem;
    }
   
</style>