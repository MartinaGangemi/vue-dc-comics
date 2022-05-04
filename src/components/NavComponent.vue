<template>
    <nav>
        <ul>
            <li v-for="(list, index) in listMenu" :key="index" :class="list.text==='Comics' ? 'active' : ''" >
                 <a :href="src"> {{ list.text }}</a> 
            </li>
        </ul>
    </nav>
</template>

<script>
    export default {
  name: 'NavComponent',
    data () {
        return  { 
            listMenu : [
                { 
                    id: 1,
                    href: "#",
                    text : "Characters",
                },
                { 
                    id: 2,
                    href: "#",
                    text : "Comics",
                },
                { 
                    id: 3,
                    href: "#",
                    text : "Movies",
                },
                { 
                    id: 4,
                    href: "#",
                    text : "tv" ,
                },
                { 
                    id: 5,
                    href: "#",
                    text : "games", 
                },
                { 
                    id: 6,
                    href: "#",
                    text : "collectibles",
                },
                { 
                    id: 7,
                    href: "#",
                    text : "videos",
                },
                { 
                    id: 8,
                    href: "#",
                    text : "fans",
                },
                { 
                    id: 8,
                    href: "#",
                    text : "news",
                },
                { 
                    id: 8,
                    href: "#",
                    text : "shop",
                }
            ]
        }

    }
}
</script>

<style lang="scss" scoped>
    ul{
        li{
            list-style: none;
            display: inline-block;
            margin-right: 1rem;
            text-transform: uppercase;
            font-size: 0.8rem;
            font-weight: bold;
            color: #1C1C1C ;
            position: relative;
            cursor: pointer;
        }
        li:hover:after, .active:after{
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