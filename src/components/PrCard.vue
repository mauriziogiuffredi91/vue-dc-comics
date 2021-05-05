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

    .box-fumetto{
        margin-right: 10px;
    }
    .box-fumetto img{
        height: 184px;
        width: 184px;
        
    }
        
        

    .box-fumetto h5{
        color: floralwhite;
        text-transform: uppercase;
        width: 184px;
        padding: 10px 0;
        font-weight: 400;
    }

</style>