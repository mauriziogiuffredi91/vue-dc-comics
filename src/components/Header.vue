<template>
    <header class="main-box">

        
        
        <a href="/">
            <img src="../assets/img/dc-logo.png" alt="">
        </a>

        

        

        <nav>
            <ul>
                <li :class="{ active: link.current }" v-for="(link, index) in links" :key="index">
                    <a :class="{ active: link.current }" :href="link.url"><h5>{{link.oggetto}}</h5></a>
                    
                </li>

                
                    
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            links:[
                {oggetto: 'characters', url: '/characters/page', current: false},
                {oggetto: 'comics', url: '/comics/page', current: true},
                {oggetto: 'movies', url: '/movies/page', current: false},
                {oggetto: 'tv', url: '/tv/page', current: false},
                {oggetto: 'games', url: '/games/page', current: false},
                {oggetto: 'collectibles', url: '/collectibles/page', current: false},
                {oggetto: 'videos', url: '/videos/page', current: false},
                {oggetto: 'fans', url: '/fans/page', current: false},
                {oggetto: 'news', url: '/news/page', current: false},
                {oggetto: 'shop', url: '/shop/page', current: false},
                
                
            ],
        };
    },
    methods: {},
}
</script>

<style lang="scss" scoped>
    header{
        display: flex;
        justify-content: space-between;
        padding-top: 1rem;

    }
        
        
        
    nav ul{
        padding-top: 2rem;
    }
    nav ul li{
        list-style: none;
        display: inline-block;
        margin-right: 20px;
        height: 5rem;
    }
    
    nav ul li:last-child{
        margin-right: 0;
    }

    nav ul li:hover,
    nav ul li.active{
        border-bottom: 8px solid dodgerblue;
    }
        

    nav ul li a{
        text-decoration: none;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.835);
        transition: color .2s;
        
    }

    nav ul li a:hover,
    nav ul li a.active{
        color: dodgerblue;
        
    }
        
</style>