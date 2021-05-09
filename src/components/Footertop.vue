<template>
    <section>
        <div class="main-box">

            <div class="text-container">

                <ul>
                    <li>
                        <h3>Dc comics</h3>

                    </li>

                    <li class="options" 
                        v-for="items in dcComics" 
                        :key="items.oggetto"
                    >
                    <a href="/">{{items.oggetto}}</a>

                    </li>

                    <li>
                        <h3>Shop</h3>
                    </li>

                    <li class="options" 
                        v-for="items in shop" 
                        :key="items.oggetto"
                    >
                    <a href="/">{{items.oggetto}}</a>

                    </li>
                </ul>
                <ul>
                    <li>
                        <h3>Dc</h3>
                    </li>
                    <li class="options" 
                        v-for="items in dc" 
                        :key="items.oggetto"
                    >
                    <a href="/">{{items.oggetto}}</a>

                    </li>
                </ul>
                <ul>
                    <li>
                        <h3>Sites</h3>
                    </li>

                    <li class="options" 
                        v-for="items in sites" 
                        :key="items.oggetto"
                    >
                    <a href="/">{{items.oggetto}}</a>

                    </li>
                </ul>
            </div>


            <div class="logo-container">
                <img src="../assets/img/dc-logo-bg.png" alt="dc logo grande">
            </div>
        </div>

          
    </section>
</template>

<script>
export default {
    name: 'Footertop',
    data() {
        return {
            dcComics:[
                {oggetto: 'Characters', url: '/characters/page'},
                {oggetto: 'Comics', url: '/comics/page'},
                {oggetto: 'Movies', url: '/movies/page'},
                {oggetto: 'TV', url: '/tv/page'},
                {oggetto: 'Games', url: '/games/page'},
                {oggetto: 'Videos', url: '/videos/page'},
                {oggetto: 'News', url: '/news/page'},
                
            ],
            
            shop:[
                
                {oggetto: 'Shop Dc', url: '/shop/page'},
                {oggetto: 'Shop Dc Collectibles', url: '/dcCollectibles/page'},
                
            ],

            dc:[
                {oggetto: 'Terms Of Use', url: '/termsOfUse/page'},
                {oggetto: 'Privacy policy (New)', url: '/policy/page'},
                {oggetto: 'Ad Choices', url: '/choicheAd/page'},
                {oggetto: 'Advertising', url: '/advertising/page'},
                {oggetto: 'Jobs', url: '/jobs/page'},
                {oggetto: 'Subscriptions', url: '/subscriptions/page'},
                {oggetto: 'Talent Workshops', url: '/talentWorkshop/page'},
                {oggetto: 'CPSC Certificates', url: '/CPSC/page'},
                {oggetto: 'Ratings', url: '/ratings/page'},
                {oggetto: 'Shop Help', url: '/shop/page'},
                {oggetto: 'Contact Us', url: '/contact/page'},
                
            ],
            sites:[
                {oggetto: 'DC', url: '/dc/page'},
                {oggetto: 'MAD Magazine', url: '/MADmagazine/page'},
                {oggetto: 'DC Kids', url: '/dcKids/page'},
                {oggetto: 'DC Universe', url: '/DcUniverse/page'},
                {oggetto: 'DC Power Visa', url: '/powerVisa/page'},
                
                
            ],
                
        };
    },
    methods: {},
}
</script>

<style scoped>

    section{
        position: relative;
        background-image: url('../assets/img/footer-bg.jpg');
        padding: 20px;
        background-size: cover;
    }

    .main-box{
        display: flex;
        justify-content: space-between;
    }

    .main-box .text-container{
        display: flex;
        justify-content: space-between;

    }

    .text-container ul{
        width: 200px;
        padding: 30px;
    }
    .text-container ul li{
        margin-right: 20px;
        list-style: none;
        text-decoration: none;
        
    }

    
        


    .text-container ul li h3{
        color: ghostwhite;
        text-transform: uppercase;
        margin: 10px 0;

    }

    .text-container ul li a{
        text-decoration: none;
        color: #959595;
        width: 200px;
        display: inline-block;
        font-size: 12px;
    }

    .text-container ul li a:hover{
        color: white;
    }
        
    .logo-container img{
        position: absolute;
        overflow: hidden;
        top: -20%;
        right: 18%;
        

    }
        

    

</style>