<template>
    <section class="main-box">
        <ul>
            <li v-for="(object, index) in links" :key="index" >
                <img src="`./assets/img/${object.img}.png`" alt="">
                <!-- :src per inserire immagine dinamica da js ci vogliono backtik `` e inserimento dinamico -->
                <a href="/">{{object.text}}</a>
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
                {text: 'digital comics', url: '/digitalComics/page', current: false, img:'buy-comics-digital-comics'},
                {text: 'dc merchandise', url: '/dcMerchandise/page', current: false, img: 'buy-comics-merchandise'},
                {text: 'subscription', url: '/subScription/page', current: false, img: 'buy-comics-subscriptions'},
                {text: 'comic shop locator', url: '/comicShopLocator/page', current: false, img: 'buy-comics-shop-locator'},
                {text: 'dc power visa', url: '/dcPowerVisa/page', current: false, img: 'buy-dc-power-visa'},
                
                
                
            ],
        };
    },
    methods: {},
}
</script>

<style scoped>

</style>