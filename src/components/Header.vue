<template>
    <header>
        <div class="logo-box">
            <a href="/">
                <img src="../assets/img/dc-logo.png" alt="">
            </a>

        </div>

        

        <nav>
            <ul>
                <li>
                    <a href=""><h4>characters</h4></a>
                    <a href=""><h4>comics</h4></a>
                    <a href=""><h4>movies</h4></a>
                    <a href=""><h4>tv</h4></a>
                    <a href=""><h4>games</h4></a>
                    <a href=""><h4>collectibles</h4></a>
                    <a href=""><h4>videos</h4></a>
                    <a href=""><h4>fans</h4></a>
                    <a href=""><h4>news</h4></a>
                    <a href=""><h4>shop</h4></a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        max-width: 1100px;
        margin: 0 auto;

    }
    
    nav ul li{
        display: inline-block;
        list-style: none;
        


    }

    nav ul li a{
        text-decoration: none;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.835);
    }
</style>