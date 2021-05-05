<template>
    <div class="box-fumetto">
        <img :src="specifies.thumb" alt="">

        <h5 >{{specifies.series}}</h5>
    </div>
</template>

<script>
export default {
    name: 'PrCard',
    props: ['specifies'],
    /*Qui abbiamo usato la specifica props per far 
    prendere in considerazione attributo custom in un'altra scheda*/
}
</script>

<style scoped>

    .box-fumetto img{
        margin: 10px;
        height: 184px;
        width: 184px;
        
    }
        

    .box-fumetto h5{
        color: floralwhite;
        text-transform: uppercase;
        padding-left: 10px;
    }

</style>