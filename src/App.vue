<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>

#app {
  font-family: 'Poppins', sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}

body::-webkit-scrollbar {
  display: none;
}
</style>
