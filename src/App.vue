<template>
  <div class="wrapper">
    <HeaderComp> </HeaderComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";

export default {
  name: "App",
  components: {
    HeaderComp,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

* {
  background: #f1eae4;
}

.container {
  max-width: 1307px;
  margin: -1px auto;
  
  
}

.wrapper {
  min-height: 100%;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  
}
</style>
