<template>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  font-family: "Montserrat", sans-serif;
  color: #000;
  padding: 16px;
  background-color: #f4f4f0;
}

@media (min-width: 576px) {
  #app {
    padding: 32px;
  }
}

@media (min-width: 768px) {
  #app {
    padding: 64px;
  }
}
</style>
