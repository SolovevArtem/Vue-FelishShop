<template>
  <div class="aboutUsComp">
    <div class="container">
      <div class="aboutUsComp__row">
        <div class="aboutUsComp__body">
          <div class="aboutUsComp__title pgTitle">About Us</div>
          <div class="aboutUsComp__body">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
          </div>
          <div class="aboutUsComp__readmore "><a class="smlButton">READ MORE</a></div>
        </div>
        <div class="aboutUsComp__img">
          <img class="aboutUsImg" src="../assets/MaskGroup2.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutUSComp",
};
</script>

<style scoped>
.aboutUsComp {
    margin-top: 250px;
}
.container {
}
.aboutUsComp__row {
    display:flex;
}
.aboutUsComp__body {

    margin-right: 40px;


  font-family: "Helvetica";
  font-style: normal;
  font-weight: 300;
  font-size: 27px;
  line-height: 158.9%;
  /* or 43px */

  text-transform: lowercase;
}
.aboutUsComp__title {
}
.aboutUsComp__readmore {
    margin-top: 150px;
    text-transform: uppercase;
}
.smlButton {
}
.aboutUsComp__img {
}
.aboutUsImg {
}
</style>
