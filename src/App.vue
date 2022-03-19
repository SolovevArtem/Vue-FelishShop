<template>
  <div class="wrapper">
    <HeaderComp class="HeaderComp"> </HeaderComp>
    <TitleComp class="TitleComp"></TitleComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import TitleComp from "./components/TitleComp.vue";

export default {
  name: "App",
  components: {
    HeaderComp,
    TitleComp,
  },
};
</script>

<style>
/* GENERAL */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html {
  margin: -7px -10px;
}

* {
  background: #f1eae4;
}

.container {
  max-width: 1200px;
  margin: auto auto;
}

.wrapper {
  min-height: 100%;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}
/* COMPONENTS */
.HeaderComp {
  display: flex;

  width: 100%;
}
</style>
