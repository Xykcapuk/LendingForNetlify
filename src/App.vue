<template>
  <div class="wrapper">
    <Header></Header>
    <div class="text">
      <span>Моя любовь</span>
    </div>
  </div>
</template>

<script>

import Header from "./components/Header";
export default {
  name: 'App',
  components: {Header}
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
body {
  height: 100vh;
}
.wrapper {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20px;
  flex-direction: column;
}
.text {
  margin-top: 30px;
  font-size: 40px;
}
</style>
