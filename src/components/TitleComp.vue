<template>
  <div class="TitleComp">
    <div class="TitleComp__row">
      <div class="TitleComp__Col1">
        <img class="bigImg" src="../assets/Rectangle1.png" alt="" />
      </div>
      <div class="TitleComp__Col2">
        <div class="TitleComp__title">NEW WEEK. NEW ARRIVALS</div>
        <div class="TitleComp__shopnow"><a>Shop Now</a></div>
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
  border: 1px solid black;
}
.TitleComp__Col2 {
}
.TitleComp__title {
}
.TitleComp__shopnow {
}

.bigImg{
    height: 800px;
    width: 720px;
}
</style>
