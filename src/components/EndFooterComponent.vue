<template>
    <div class="end-footer">
        <div class="container">
            <div class="row">
                <!-- sign up -->
                <div class="col">
                    <button> sign-up now!</button>
                </div>
                <!-- follow us -->
                <div class=" row col social">
                    <div>follow us </div>
                    <img src="@/assets/img/footer-facebook.png" alt="">
                    <img src="@/assets/img/footer-twitter.png" alt="">
                    <img src="@/assets/img/footer-youtube.png" alt="">
                    <img src="@/assets/img/footer-pinterest.png" alt="">
                    <img src="@/assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
  name: 'EndFooterComponent',
}
</script>

<style lang="scss" scoped>
.end-footer{
    background-color:#303030 ;
    text-transform: uppercase;
    color: #0282F9;
    font-size: 1.2rem;
}

.row{
    justify-content:space-between;
    padding: 2rem 0 2rem;
    align-items: center;
}

button{
    border: solid 2px $dc-primary;
    background-color: transparent ;
    color: $dc-white;
    text-transform: uppercase;
    padding: 1rem;
    font-size: 1.2rem;
    cursor: pointer;
}

.social{
    gap: 1rem;
}

</style>