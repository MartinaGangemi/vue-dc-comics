<template>
    <div class="col-2" >
        <div class="card"> 
            <div class="box-img">
                <img :src="img" alt="">
            </div> 
            <div class="title">{{ title }}</div>
        </div>
    </div>
</template>


<script>


export default {
    name:"ComicsComponent",
    props:{
        img:String,
        title:String,
    },
}
</script>


<style lang="scss" scoped >
.row{
    gap: 1rem;
}
.col-2{
    width: calc(100% / 12 )*2;
}

.card{
    display: flex;
    flex-direction: column;
    align-items: center;
}

.box-img{
    width: 100%;
    margin-top: 2rem;
    
}

img{
    width: 100%;
    object-fit: cover;
        aspect-ratio: 1 / 1;
        padding: 1rem;
        object-position: top;
}

.title{
    color: $dc-white;
    text-transform: uppercase;
    padding: 1rem;
}
</style>

