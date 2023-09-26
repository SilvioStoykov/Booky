<script setup>
import SearchBar from '../components/SearchBar.vue';
import NavBar from '../components/NavBar.vue';
</script>

<template>
<div class="home-page">
  <NavBar></NavBar>
  <div class="search-box">
    <SearchBar id="search-bar"></SearchBar>
  </div>
</div>
</template>

<style scoped>
.home-page{
  background: url('../public/blob-scene-haikei.svg');
  width: 100vw;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
}

.search-box{
  padding-top: 20%;
  padding-left: 20%;
}

</style>
