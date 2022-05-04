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
                text: "Dc Merchandise",
            },
            {
                src: "/img/buy-comics-subscriptions.png",
                text: "Subscription",
            },
            {
                src: "/img/buy-comics-shop-locator.png",
                text: "Comics shop location",
            },
            {
                src: "/img/buy-dc-power-visa.svg",
                text: "dc power visa",
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
        color: white;
        text-transform: uppercase;
        font-size: 0.9rem;
        display: flex;
        align-items: center;
        flex-grow: 1;
    }

    img{
        height: 50px;
        margin-right: 1rem;
    }
   
</style>