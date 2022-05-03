<template>
    <div class="bg_image">
        <div class="col bg-logo">
        <div class="container">
            <div class="row">
                <div class="col">
                <h3>dc comics</h3>
                <ul>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                </ul>
                <h3>Shop</h3>
                <ul>
                    <li>a</li>
                    <li>a</li>
                    <li>a</li>
                </ul>
                </div>
                <div class="col">
                    <h3>dc comics</h3>
                        <ul>
                            <li>a</li>
                            <li>a</li>
                            <li>a</li>
                            <li>a</li>
                            <li>a</li>
                            <li>a</li>
                            <li>a</li>
                    </ul>
                </div>
                <div class="col">
                    <h3>prova</h3>
                    <ul>
                        <li>a</li>
                        <li>a</li>
                        <li>a</li>
                        <li>a</li>
                        <li>a</li>
                        <li>a</li>
                        <li>a</li>
                    </ul>
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
        padding-top: 3rem;
        padding-bottom: 3rem;
    }


    .bg-logo{
        background-image: url("@/assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: right; 
    }

    h3{
        color: white;
    }

    .col{
        margin-right: 3rem;
    }


</style>