<template>
<body>
  <div id="app">
    <div class="name">
     <h1>参加団体アプリ</h1>
    </div>
    <div class="login">
     <h2>Log In</h2>
    </div>
    <img class="homepic" src="./assets/homepic.png">
  </div>
</body>
</template>

<script>

</script>

<style>
body{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.name{
  margin: 0px;
  color: aliceblue;
  background-color: black;
  flex-flow: column;
  padding: 15px;
}
.login{
  margin: 0px;
  color: aliceblue;
  background-color: black;
  text-align: end;
  padding: 15px;
}
.homepic{
  width: 100%;
}
</style>
