<template>
  <div class="FavourComp">
    <div class="container">
      <div class="FavourComp__row">
        <div class="FavourComp_header">
          <div class="FavourComp__title pgTitle">OUR FAVOURITES</div>
          <a class="FavourComp__seeall smlButton">SEE ALL</a>
        </div>
        <div class="FavourComp__line1">
          <div class="FavourComp__card1 card">
            <div class="card__img1 img">
              <img class="img1" src="../assets/Rectangle2.png" alt="" />
            </div>

            <div class="card__itemName">7 Gold Rings Lari</div>
            <div class="card__itemPrice">490$</div>
          </div>
          <div class="FavourComp__card2 card">
            <div class="card__img2 img">
              <img class="img2" src="../assets/Rectangle5.png" alt="" />
            </div>
            <div class="card__itemName">White Shirt Dali</div>
            <div class="card__itemPrice">399$</div>
          </div>
        </div>
        <div class="FavourComp__line2">
          <div class="FavourComp__card3 card">
            <div class="card__img3 img">
              <img class="img3" src="../assets/MaskGroup.png" alt="" />
            </div>
            <div class="card__itemName">Shitra Handbag</div>
            <div class="card__itemPrice">299$</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FavourComp",
};
</script>

<style>
.FavourComp {
  margin-top: 100px;
}
.container {
}
.FavourComp__row {
}
.FavourComp_header {
  flex-direction: row;
  display: inline-flex;
  margin-bottom: 71px;
}
.FavourComp__title {
  display: flex;
  flex: 1 1 auto;
  margin-right: 850px;
}

.FavourComp__seeall {
  justify-self: flex-end;
  align-self: flex-end;
  margin-bottom: 25px;
}

.FavourComp__line1 {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.FavourComp__card1 {
}
.card {
}
.card__img1 {
}

.img1 {
}
.card__itemName {
}
.card__itemPrice {
}
.FavourComp__card2 {
}
.card__img2 {
}
.img2 {
}
.FavourComp__line2 {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.FavourComp__card3 {
}
.card__img3 {
}
.img3 {
}
</style>
