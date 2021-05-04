<template>
    <header>
        
        <a href="/">
            <img src="../assets/img/dc-logo.png" alt="">
        </a>

        

        

        <nav>
            <ul>
                <li>
                    <a href="/"><h5>characters</h5></a>
                    
                </li>

                <li>
                    <a href="/"><h5>comics</h5></a>
                </li>

                <li>
                    <a href="/"><h5>movies</h5></a>
                </li>

                <li>
                    <a href="/"><h5>tv</h5></a>
                </li>

                <li>
                    <a href="/"><h5>games</h5></a>
                </li>

                <li>
                    <a href="/"><h5>collectibles</h5></a>
                </li>
                    
                <li>
                    <a href="/"><h5>videos</h5></a>
                </li>
                    
                <li>
                    <a href="/"><h5>fans</h5></a>
                </li>    
                    
                <li>
                    <a href="/"><h5>news</h5></a>
                </li>
                
                <li>
                    <a href="/"><h5>shop</h5></a>
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
        padding: 1rem;

    }
        
        
    nav ul{
        padding-top: 2rem;
    }
    nav ul li{
        list-style: none;
        display: inline-block;
        margin-right: 20px;
    }
    
    nav ul li:last-child{
        margin-right: 0;
    }


        

    nav ul li a{
        text-decoration: none;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.835);
    }
        
</style>