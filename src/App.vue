<template>
  <link rel="stylesheet" href="https://use.typekit.net/hpa7jym.css" />

  <div class="wrapper">
    <HeaderComp class="HeaderComp"> </HeaderComp>
    <TitleComp class="TitleComp"></TitleComp>
    <FavourComp class="FavourComp"></FavourComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import TitleComp from "./components/TitleComp.vue";
import FavourComp from "./components/FavourComp";

export default {
  name: "App",
  components: {
    HeaderComp,
    TitleComp,
    FavourComp,
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
  max-width: 1350px;
  margin: auto auto;
}

.wrapper {
  min-height: 100%;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}
/* COMPONENTS */

/* BLOCKS CSS STYLES */
.pgTitle {
  font-family: "Selna";
  font-style: normal;
  font-weight: 400;
  font-size: 50px;
  line-height: 85px;
  text-transform: uppercase;
}

.smlButton {
  font-family: "Helvetica";
  font-style: normal;
  font-weight: 100;
  font-size: 20.1783px;
  line-height: 23px;
  align-items: center;
  text-align: center;
  text-decoration: underline;
}
</style>
