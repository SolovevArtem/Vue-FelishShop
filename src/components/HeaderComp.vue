<template>
  <header class="HeaderComp">
    <div class="container">
      <div class="HeaderComp__row">
        <nav class="HeaderComp__nav_left nav">
          <a class="nav__item shopnow">SHOP NOW</a>
          <a class="nav__item lookbook">LOOKBOOK</a>
        </nav>
        <div class="nav__brand">FELIS</div>
        <nav class="HeaderComp__nav_right nav">
          <a class="nav__item search">SEARCH</a>
          <a class="nav__item cart">CART</a>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComp",
};
</script>

<style scoped>
.HeaderComp {
  
}

.HeaderComp__row {
  display: flex;
  justify-content: center;
  
}
.HeaderComp__nav_left {
  margin-top: 39px;
  margin-bottom: auto;
  flex-wrap: nowrap;
}

.HeaderComp__nav_left > .lookbook {
  margin-left: 20px;
}
.nav {
}
.nav__item {
}
.nav__brand {
  font-family: sel;
  font-style: normal;
  font-weight: 400;
  font-size: 52.9025px;
  line-height: 90px;
  display: flex;
  align-items: center;
  text-align: center;
  padding-right: 388px;
  padding-left: 320px;
}
.HeaderComp__nav_right {
  margin-top: 39px;
  margin-bottom: auto;
}

.HeaderComp__nav_right > .search {
  margin-right: 30px;
}
</style>
