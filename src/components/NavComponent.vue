<template>
    <nav>
        <ul>
            <li>Characters</li>
            <li class="active">Comics</li>
            <li>Movies</li>
            <li>Tv</li>
            <li>Games</li>
            <li>Collectibles</li>
            <li>Videos</li>
            <li>Fans</li>
            <li>News</li>
            <li>Shop</li>
        </ul>
    </nav>
</template>

<script>
    export default {
  name: 'NavComponent',
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