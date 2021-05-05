<template>
    <section>
        <div class="main-box">

            <div class="text-container">

                <ul>
                    <li>
                        <h4>Dc comics</h4>
                    </li>

                    <li>
                        <h4>Shop</h4>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h4>Dc</h4>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h4>Sites</h4>
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
}
</script>

<style scoped>

    section{
        background-image: url('../assets/img/footer-bg.jpg');
        padding: 20px;
    }

    .main-box{
        display: flex;
        justify-content: space-between;
    }

    

    

</style>