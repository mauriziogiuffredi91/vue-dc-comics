<template>
    <section class="current-comics">
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

    .current-comics{
        background-color: #1c1c1c;
        padding: 54px 0;

    }

    .current-comics .main-box{
        display: flex;
        flex-wrap: wrap;

        
    }


    



</style>