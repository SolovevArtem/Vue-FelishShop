<template>
  <link rel="stylesheet" href="https://use.typekit.net/hpa7jym.css" />

  <div class="wrapper">
    <HeaderComp class="HeaderComp"> </HeaderComp>
    <TitleComp class="TitleComp"></TitleComp>
    <FavourComp class="FavourComp"></FavourComp>
    <SectionsComp class="SectionsComp"></SectionsComp>
    <AboutUsComp class="AboutUsComp"></AboutUsComp>
    <SignUpComp class="SignUpComp"></SignUpComp>
    <div id="line"><hr /></div>
    <InstagramComp class="InstagramComp"></InstagramComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import TitleComp from "./components/TitleComp.vue";
import FavourComp from "./components/FavourComp";
import SectionsComp from "./components/SectionsComp";
import AboutUsComp from "./components/AboutUsComp.vue";
import SignUpComp from "./components/SignUpComp.vue";
import InstagramComp from "./components/InstagramComp.vue";
export default {
  name: "App",
  components: {
    HeaderComp,
    TitleComp,
    FavourComp,
    SectionsComp,
    AboutUsComp,
    SignUpComp,
    InstagramComp,
  },
};
</script>

<style>
/*Обнуление*/
* {
  padding: 0;
  margin: 0;
  border: 0;
}
*,
*:before,
*:after {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
:focus,
:active {
  outline: none;
}
a:focus,
a:active {
  outline: none;
}
nav,
footer,
header,
aside {
  display: block;
}
html,
body {
  height: 100%;
  width: 100%;
  font-size: 100%;
  line-height: 1;
  font-size: 14px;
  -ms-text-size-adjust: 100%;
  -moz-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
input,
button,
textarea {
  font-family: inherit;
}
input::-ms-clear {
  display: none;
}
button {
  cursor: pointer;
}
button::-moz-focus-inner {
  padding: 0;
  border: 0;
}
a,
a:visited {
  text-decoration: none;
}
a:hover {
  text-decoration: none;
}
ul li {
  list-style: none;
}
img {
  vertical-align: top;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}
/*--------------------*/

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

.img > * {
  height: 524px;
  width: 422px;
}

#line {
  display: flex;
  align-items: center;
  justify-items: center;
  
}
hr {
  width: 35%;
  background-color: black;
  height: 1px;
  margin: 0 auto;
}
</style>
