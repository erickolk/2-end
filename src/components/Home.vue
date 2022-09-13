<template>
    <div id="home-content">
        <nav class="navbar">
        <ul>
            <a href=""><li>Quem somos</li></a>
            <a href=""><li>Serviços</li></a>
            <a href=""><li>Contato</li></a>
        </ul>
        </nav>
        <!--<div class="line-container"><div class="linha"></div></div>-->
        <h2 class="slogan">Desenvolvemos além do <span>Software</span>, encontramos a <span>solução</span> que você precisa!</h2>
        
        

    </div>
</template>

<script>
    export default {
        name: 'Home',
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,200;0,300;0,400;0,600;1,200;1,300;1,400&display=swap');
    h2{
        color: #FFF;
        position: absolute;
    width: 694px;
    height: 282px;
    left: 40px;
    top: 331px;
    font-family: 'Nunito Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 48px;
    line-height: 125.5%;

    /* or 60px */
    letter-spacing: 0.045em;
    }
    span{
        color: #02FF86;
    }

    

    ul {
        display: flex;
        position: absolute;
        right: 95px;
        top: 58px;
        list-style: none;
        font-family: 'Nunito Sans';
        font-size: 18px;
        font-weight: 700;

    }

    ul li {
        padding-right: 64px;
    }

    ul a {
        text-decoration: none;
        color: #FFF;

    }

    ul a:hover {
        color: #02FF86;

    }

    .linha {
        height: 2px;
        background-color: #02FF86;
        width: 1210px;
        position: absolute;
        top: 200px;
    }

    .line-container {
        display: flex;
        justify-content: center;
    }

    #home-content {
        display: block;
        background-color: black;
        margin-bottom: 800px;
    }

    .slogan {
        text-align: center;
        margin-top: 60px;
    }
</style>