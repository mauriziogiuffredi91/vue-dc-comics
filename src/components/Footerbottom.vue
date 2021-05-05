<template>
    <section>
        <div class="main-box">

            <div class="box-left">
                <button>
                    <h3>
                        Sign-up now!
                    </h3>
                </button>
            </div>
            <div class="boxright">
                <h3>Follow Us</h3>

                <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a>

                <a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a>

                <a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a>

                <a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a>

                <a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a>

                
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'Footerbottom',
}
</script>

<style scoped>
    section{
        background-color: #303030;
        padding: 33px;
        position: relative;
    }

    .main-box{
        display: flex;
        justify-content: space-between;
        align-items: center;

    }

    .main-box .boxright{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 30%;
    }
</style>