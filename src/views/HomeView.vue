<script setup>
import SearchBar from '../components/SearchBar.vue';
import NavBar from '../components/NavBar.vue';
</script>

<template>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<div class="home-page">
  <NavBar></NavBar>

<div class="search-container">
  <h1 id="title">You are the storyteller</h1>
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
.search-container{
  margin-top: 200px;
}

#search-bar{
  margin: auto;
}

.search-container #title{
  text-align: center;
  padding: 25px;
  margin-bottom: 30px;
  color: #fff;
  font-family: 'Pacifico', cursive;
  word-spacing: 2;
  letter-spacing: 1px;
  font-size: 48px;
}

</style>
