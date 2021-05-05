<template>
    <section class="current-comics">
        <div class="main-box">

            <!-- test sui riquadri -->
            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>

            <div class="box-fumetto">
                <img src="" alt="">

                <h5>Action Comics</h5>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'Series',
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


    .box-fumetto img{
        /*test riquadri*/ 
        background-color: gray;
        height: 180px;
        width: 180px;
        margin: 10px;
        
    }

    .box-fumetto h5{
        color: floralwhite;
        text-transform: uppercase;
        padding-left: 10px;
    }



</style>