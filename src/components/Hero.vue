<template>
    <section class="main-box">
        <ul>
            <li v-for="(object, index) in links" :key="index" >
                <!-- <img :src="`object.img`" alt="">
                 :src per inserire immagine dinamica da js ci vogliono backtik `` e inserimento 
                <a href="/">{{object.text}}</a> 
                -->
            </li>

            
        </ul>

    </section>
</template>

<script>
export default {
    name: 'Hero',
    data() {
        return {
            links:[
                {text: 'digital comics', url: '/digitalComics/page', current: false, img:'../assets/img/buy-comics-digital-comics.png'},
                {text: 'dc merchandise', url: '/dcMerchandise/page', current: false, img: '../assets/img/buy-comics-merchandise.png'},
                {text: 'subscription', url: '/subScription/page', current: false, img: '../assets/img/buy-comics-subscriptions.png'},
                {text: 'comic shop locator', url: '/comicShopLocator/page', current: false, img: '../assets/img/buy-comics-shop-locator.png'},
                {text: 'dc power visa', url: '/dcPowerVisa/page', current: false, img: '../assets/img/buy-dc-power-visa.png'},
                
                
                
            ],
        };
    },
    methods: {},
}
</script>

<style scoped>

</style>