<template>
  <header class="HeaderComp">
    <div class="container">
      <div class="HeaderComp__row">
        <nav class="HeaderComp__nav_left nav">
          <a class="nav__item shopnow">SHOP NOW</a>
          <a class="nav__item lookbook">LOOKBOOK</a>
        </nav>
        <div class="nav__brand">Felis</div>
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
.HeaderComp__container {
}
.HeaderComp__row {
  display: flex;
  justify-content: space-between;
}
.HeaderComp__nav_left {
   
    
    
}
.HeaderComp__nav_left > .lookbook {
   margin-left: 15px;
  
    
}
.nav {
}
.nav__item {
    
}
.nav__brand {
  font-family: "Selna";
  font-style: normal;
  font-weight: 400;
  font-size: 52.9025px;
  line-height: 90px;
  display: flex;
  align-items: center;
  text-align: center;
  margin-right: 388px;
  margin-left: 363px;
}
.HeaderComp__nav_right {
}

.HeaderComp__nav_right > .search{
   margin-right: 30px;
}
</style>
