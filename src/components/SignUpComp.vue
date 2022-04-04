<template>
  <div class="SignUpComp">
    <div class="container">
      <div class="signUp__row">
        <div class="signUp__star">
          <img class="star" src="../assets/Polygon2.svg" alt="" />
        </div>
        <div class="signUp__title pgTitle">SIGN UP FOR OUR NEWSLETTER</div>
        <div class="signUp__emailbox">
          <form action="/action_page.php">
            <label for="email">Enter your email:</label>
            <input type="email" id="email" name="email" />
            <input type="submit" />
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "SignUpComp",
};
</script>

<style scoped>
.SignUpComp {
  margin-top: 50px;
}
.container {
}
.signUp__row {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.signUp__star {
}
.star {
  margin-top: 152px;
}
.signUp__title {
}
.signUp__emailbox {
}
.signUp__email {
}
.signUp__subscribe {
}
</style>
