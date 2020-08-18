<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
  *{
    padding: 0;
    margin: 0;
  }
  body {
    padding: 0px;
    font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
    background-color: #350230;
    height: 100%;
    margin: 0;
    color: #CCC;
    line-height: 140%;
    font-size: 0.95em;
  }
  #app{
    width: 100%;
    background-color: #350230;
    background-image: url(http://www.sekhem.com.au/templates/sekhem/images/bg.png);
    background-repeat: repeat-x;
    height: 100vh;
    left: 0;
    margin: auto;
    min-height: 100%;
    position: relative;
    text-align: center;
    top: 0;
  }
</style>
