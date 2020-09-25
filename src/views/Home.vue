<template>
  <div class="home">
    <div class="wrapper">
      <div class="left-panel">
        <h3>ChatUP</h3>
      </div>
      <div class="chat-main"></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home"
};
</script>

<style>
 body {
   margin: 0;
   padding: 0;
   box-sizing: 0;
   font-family: 'Montserrat', sans-serif;
 }
  .wrapper {
    width: 100%;
    display: grid;
    grid-template-columns: 2fr 8fr;
    height: 100vh;
  }
  .left-panel {
    width: 100%;
    height: 100%;
    padding: 15px;
  }
  .chat-main {
    width: 100%;
    height: 100%;
  }
</style>
