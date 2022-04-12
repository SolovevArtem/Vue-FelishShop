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
            <input
              v-model="email"
              @click="cssChange"
              @blur="lostFocus"
              type="email"
              class="email smlButton inactive"
              id="email"
              name="email"
            />
            <input
              class="signUp__subscribe smlButton"
              type="submit"
              value="Subscribe"
            />
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "SignUpComp",
  data() {
    return {
      email: "Enter your email",
    };
  },
  methods: {
    cssChange() {
      if (this.email == "Enter your email") {
        this.email = "";
        
      }
    },
    lostFocus() {
      if (this.email == "" || this.email == undefined) {
        this.email = "Enter your email";
      }
    },
  },
};
</script>

<style scoped>
.SignUpComp {
  margin-top: 50px;
  margin-bot: 180px;
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
  margin-top: 200px;
}
.signUp__title {
}
.signUp__emailbox {
  margin-top: 143px;
}
.signUp__email {
}
#email {
  text-transform: uppercase;
  text-decoration: none;
  color: rgba(29, 27, 25, 0.5);
  width: 380px;
}
.signUp__subscribe {
  text-transform: uppercase;
  text-decoration: none;
}

.inactive {
}

.active {
}
</style>
