<template>
    <section >

        <div class="main-box">
            <ul>
                <li class="box" v-for="(object, index) in links" :key="index" >
                    <img :src="object.img" alt="`${object.text}`">
                        <!-- mancava il require -->
                    <a href="/">{{object.text}}</a> 
                    
                </li>

                
            </ul>

        </div>

    </section>
</template>

<script>
export default {
    name: 'Hero',
    data() {
        return {
            links:[
                {
                    text: 'digital comics', 
                    url: '/digitalComics/page', 
                    current: false, 
                    img: require ('../assets/img/buy-comics-digital-comics.png'),
                },
                {
                    text: 'dc merchandise',
                    url: '/dcMerchandise/page', 
                    current: false, 
                    img: require( '../assets/img/buy-comics-merchandise.png'),
                },
                {   text: 'subscription', 
                    url: '/subScription/page', 
                    current: false, 
                    img: require( '../assets/img/buy-comics-subscriptions.png'),
                },
                {
                    text: 'comic shop locator',
                    url: '/comicShopLocator/page', 
                    current: false, 
                    img: require( '../assets/img/buy-comics-shop-locator.png'),
                },
                {
                    text: 'dc power visa',
                    url: '/dcPowerVisa/page', 
                    current: false, 
                    img: require( '../assets/img/buy-dc-power-visa.svg'),
                },
                
                
                
            ],
        };
    },
    methods: {},
}
</script>

<style scoped>
    section{
        background-color: #1e80ff;
    }
    .main-box{
        padding: 40px;
    }
        
        

    .main-box ul{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }



    .main-box ul li{
        display: flex;
        align-items: center;
        list-style: none;
        
    }
        
        
        
        

    

    .main-box ul li a{
        text-transform: uppercase;
        color: ghostwhite;
        text-decoration: none;
        font-size: 15px;
        

    }

    ul li img{
        width: 45px;
        height: 60px;
        margin-right: 10px;
        
    }

</style>