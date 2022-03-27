<template>
  <div class="SectionsComp">
    <div class="container">
      <div class="SectionsComp__row">
        <div class="SectionsComp__Col1">
          <img src="../assets/image3.png" alt="" class="img" />
        </div>
        <div class="SectionsComp__Col2">
          
          <ul>
            <li class="sections">Sections</li>
            <li>JEWLERY</li>
            <li>HANDBAGS</li>
            <li>SWEATERS</li>
            <li>EYEWEAR</li>
            <li>SHIRTS</li>
          </ul>
        </div>
        <div class="SectionsComp__Col3">
          <img src="../assets/image4.png" alt="" class="img" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionsComp",
};
</script>

<style scoped>
.SectionsComp {
    margin-top: 103px;
}
.container {
}
.SectionsComp__row {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
.SectionsComp__Col1 {
   
}
.img {
  width: 332px;
  /* height: 463px; */
  
}
.SectionsComp__Col2 {
  font-family: "Selna";
  font-style: normal;
  font-weight: 400;
  font-size: 56.377px;
  line-height: 96px;
  display: flex;
  align-items: center;
  text-align: center;
  text-transform: uppercase;
  
  margin-top: 127px;
}
.SectionsComp__Col3 {
    margin-top: 271px;
}
.sections {
  margin-top: -170px;
  margin-bottom: 170px;
}
</style>
