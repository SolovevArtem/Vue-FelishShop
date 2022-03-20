<template>
  <div class="TitleComp">
    <div class="TitleComp__row">
      <div class="TitleComp__Col1">
        <img class="bigImg" src="../assets/Rectangle1.png" alt="" />
      </div>
      <div class="TitleComp__Col2">
        <img class="star" src="../assets/Polygon2.svg" alt="" />
        <div class="TitleComp__title">
          NEW WEEK.<br />
          NEW ARRIVALS
        </div>

        <div class="TitleComp__shopnow"><a>SHOP NOW</a></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TitleComp",
};
</script>

<style scoped>
.TitleComp {
}
.TitleComp__row {
  display: flex;
  flex-direction: row;
}
.TitleComp__Col1 {
  flex: 0 0 50%;
}
.TitleComp__Col2 {
  display: flex;
  flex-direction: column;
  flex: 1 1 50%;
  align-items: center;
  /* justify-content: center; */
}
.TitleComp__title {
  font-family: sel;
  font-style: normal;
  font-weight: 400;
  font-size: 62.844px;
  line-height: 80px;
  text-align: center;
  margin-top: 26px;
}
.TitleComp__shopnow {
  margin-top: 38px;
  text-decoration: underline;
  font-family: proxima-nova, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 20.1783px;
  line-height: 25px;

  display: flex;
  align-items: center;
  text-align: center;
}

.bigImg {
  height: 800px;
  width: 720px;
  max-height: 100%;
}

.star {
  margin-top: 197px;
}
</style>
