<template>
  <div id="content">
    
    <div>
      <img src="./assets/2-end.png" alt="logo" class="logo">
      <img src="./assets/Software-Development.png" alt="" class="sublogo">
      
    </div>
    <img src="./assets/impact.png" alt="" id="impact">
    <Home />
    <Main/>

  </div>
</template>

<script>
import Main from './components/Main.vue'
import Home from './components/Home.vue';
export default {
  name: 'App',
  components: {
    Home,
    Main
}
}
</script>

<style>


*{
  color: #FFF;
}

/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/

.logo {

position: absolute;
width: 173.89px;
height: 62.1px;
left: 92.23px;
top: 44px;

}

.sublogo{
  position: absolute;
  width: 173.89px;
  height: 12.42px;
  left: 92.23px;
  top: 117.58px;
}

body {
  background: linear-gradient(116.66deg, #115357 -5.89%, #05593B 100%);
}

#content {
/* /* position: absolute;
width: 1440px;
height: 3000px; */
/* left: 0px;
top: 0px; 
display: block; */
background: linear-gradient(116.66deg, #115357 -5.89%, #05593B 100%);
}

.navbar {
  color: #fff;
  margin: 400px;
}

#impact {

  box-sizing: border-box;

position: absolute;
width: 404px;
height: 392.35px;
left: 908px;
top: 270px;
border-radius: 272px;
}

h3 {
  text-transform: uppercase;
  margin-top: 100px;
  font-family: 'Nunito Sans';
  font-weight: 900;
  font-size: 24px;
}



</style>
