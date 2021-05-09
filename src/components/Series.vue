<template>
    <section class="current-comics">


        <div class="banner-blue">
            <h2>Current Series</h2>
        </div>
        <div class="main-box">

            <!-- test sui riquadri box iniettato da altra pagina -->
            <!-- <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div> -->
            <PrCard 
                v-for="(product, index) in products" 
                :key="index" 
                :specifies="product"
            />


            
        </div>
        <div class="last-box">

            <div class="button-blue-bottom">
                <h5>Load More</h5>
            </div>
        </div>

    </section>
</template>

<script>
import PrCard from '@/components/PrCard.vue';
import ItemsProd from '@/data/itemsProd.js';
export default {
    name: 'Series',
    components:{
        PrCard,
    },
    data(){
        return{
            products: ItemsProd,
        };
    },
}
</script>

<style scoped>


    .banner-blue{
        position: absolute;
        top: 475px;
        left: 255px;
        height: 52px;
        width: 247px;
        background-color: dodgerblue;
        padding: 10px;

    }

    .banner-blue h2{
        color: white;
        text-transform: uppercase;
        text-align: center;
    }
    .current-comics{
        background-color: #1c1c1c;
        padding: 54px 0;

    }

    .current-comics .main-box{
        display: flex;
        flex-wrap: wrap;

        
    }

    .last-box{
        display: flex;
        align-items: center;
        justify-content: center;
        padding-top: 20px;
    }
    .button-blue-bottom{
        color: white;
        text-transform: uppercase;
        padding: 10px;
        background-color: dodgerblue;
        width: 180px;
        height: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;


    }

    .button-blue-bottom:hover,
    .button-blue-bottom:active{
        background-color: rgb(10, 104, 199);
    }

    



</style>