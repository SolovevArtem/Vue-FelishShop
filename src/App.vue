<template>
  <div class="wrapper">
    <HeaderComp> </HeaderComp>
    <TitleComp></TitleComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import TitleComp from "./components/TitleComp.vue";

export default {
  name: "App",
  components: {
    HeaderComp,
    TitleComp
},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html{
  margin: -7px -10px;
}


* {
  background: #f1eae4;
}

.container {
  max-width: 1200px;
  margin: auto auto;
  border: 2px solid black;
  
}

.wrapper {
  min-height: 100%;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  
}
</style>
