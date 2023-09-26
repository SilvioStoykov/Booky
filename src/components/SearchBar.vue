<template>
    <div class="search-container">
        <input id="search-bar" type="text">
        <button id="submit-btn" role="button">Submit</button>
    </div>
</template>

<script setup>

</script>

<style scoped>
#search-bar{
    width: 75%;
    height: 50px;
    outline: none;
    border: none;
    border-radius: 15px;
    font-size: 20px;
}

.search-container{
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0px;
}

#submit-btn{
    margin: 10px;
    width: 100px;
    height: 20px;
    border-radius: 10px;
    outline: none;
    border: none;
    background-color: #21A3EC;
    color: #fff;
    font-weight: 600;
}

/* CSS */
#submit-btn {
  align-items: center;
  background-image: linear-gradient(135deg, #432bd9 40%, #ef3838);
  border: 0;
  border-radius: 10px;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  display: flex;
  flex-direction: column;
  font-family: "Codec cold",sans-serif;
  font-size: 16px;
  font-weight: 700;
  height: 54px;
  justify-content: center;
  letter-spacing: .4px;
  line-height: 1;
  max-width: 100%;
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 3px;
  text-decoration: none;
  text-transform: uppercase;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

#submit-btn:active {
  outline: 0;
}

#submit-btn:hover {
  outline: 0;
}

#submit-btn span {
  transition: all 200ms;
}

#submit-btn:hover span {
  transform: scale(.9);
  opacity: .75;
}

@media screen and (max-width: 991px) {
  #submit-btn {
    font-size: 15px;
    height: 50px;
  }

  #submit-btn span {
    line-height: 50px;
  }
}
</style>