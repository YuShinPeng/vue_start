<!-- JavaScript -->
<script setup>
import HeaderView from "./components/Header.vue";
import FooterView from "./components/Footer.vue";
import HomeView from "./view/Home.vue";
import ButtonView from "./components/ButtonView.vue";
// import CardView from "./components/CardView.vue";
</script>

<!-- HTML -->
<template>
  <div class="container">
    <HeaderView />
    <HomeView />
    <ButtonView />
    <FooterView />

  </div>

  <!-- <div class="app">
    <h1>這是App.vue檔案</h1>
    <CardView />
    <ButtonView />
  </div> -->
</template>

<!-- CSS -->
<style scoped>
  .container{
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  /* .app{
    width: 300px;
    background-color: lightskyblue;
  } */
</style>
