<template>
    <div class="bg_image">
        <div class="bg-logo">
            <div class="container">
                <div class="row">
                    <div class="col">
                    <h3>dc comics</h3>
                    <ul>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                    </ul>
                    <h3>Shop</h3>
                    <ul>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                        <li>Lorem, ipsum dolor.</li>
                    </ul>
                    </div>
                    <div class="col">
                        <h3>dc</h3>
                            <ul>
                                <li>Lorem, ipsum dolor.</li>
                                <li>Lorem, ipsum dolor.</li>
                                <li>Lorem, ipsum dolor.</li>
                                <li>Lorem, ipsum dolor.</li>
                                <li>Lorem, ipsum dolor.</li>
                                <li>Lorem, ipsum dolor.</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>sites</h3>
                        <ul>
                            <li>Lorem, ipsum dolor.</li>
                            <li>Lorem, ipsum dolor.</li>
                            <li>Lorem, ipsum dolor.</li>
                            <li>Lorem, ipsum dolor.</li>
                            <li>Lorem, ipsum dolor.</li>
                            <li>Lorem, ipsum dolor.</li>
                        </ul>
                    </div>

                    <div class="col">
                        <img src="" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>

    
export default {
  name: 'FooterComponent',
 
}
</script>

<style lang="scss" scoped>
    .bg_image{
        background-image: url("@/assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        height: 100%;
        
    }

    .row{
        padding: 2.5rem 0 2.5rem;
        margin-left: 2rem;
    }


    .bg-logo{
        background-image: url("@/assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-size: cover;
        background-size: 550px;
        background-position: right; 
        margin-right: 2rem;
    }

    h3{
        
        color: white;
        text-transform: uppercase;
        margin: 1rem 0 1rem;
    }

    .col{
        margin-right: 3rem;
    }

     ul{
        li{
            list-style: none;
            color: #959595;
           
        }
    }


</style>