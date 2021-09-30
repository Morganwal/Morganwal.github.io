<template>
  <div class="wrapper">
    <div class="background1">
    </div>
    <div class="background2">
      <div class="header"> 
      <img alt="company-logo" src="./assets/logo1.svg" id="logo">
      <img alt="company-name" src="./assets/companyName1.svg" id="companyName">
    </div>
    </div> 
  </div>
</template>

<script lang="ts">




</script>

<style>
#app {
  position: relative;
  width: 100%;
  height: 6857px;

  background: rgba(255, 255, 255, 0.96);
  }

@media only screen and  (max-width: 440px){
  .wrapper {
    position: relative;
    width: 100%;
    height: 9200px;
    background: rgba(255, 255, 255, 0.96);
  }

    .background1 {
      position: absolute;
      width: 3000px;
      height: 20%;
      left: -800px;
      top: -100px;      
      background: #FFF632;
      transform : skewY(-5deg);
      z-index: 0;
    }
    
    .background2{
      position: relative;
      width: 3000px;
      height: 19.75%;
      left: -800px;
      top: -100px;
      background: #89E1FD;
      transform : skewY(-5deg); 
      z-index: 1  
    }
    .header {
      z-index: 2;
    }

    #logo {
      position: relative;
      width: 300px;
      height: 200px;
      left: 875px;
      top: 175px;
      transform : skewY(5deg);
      filter: drop-shadow(3px 4px 10px rgba(0, 0, 0, 0.25));
    }

    #companyName {
      position: absolute;
      width: 700px;
      height: 90px;
      left: 1110px;
      top: 275px;
      transform : skewY(5deg);
      filter: drop-shadow(3px 4px 10px rgba(0, 0, 0, 0.25));
    }
   
  }
</style>
