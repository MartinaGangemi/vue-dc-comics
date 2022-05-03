<template>
    <div class="bg_blue">
        <div class="container">
            <div class="row">
                <div class="col">prova</div>
                <div class="col">prova</div>
                <div class="col">prova</div>
                <div class="col">prova</div>
                <div class="col">prova</div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
  name: 'MenuComponent',
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