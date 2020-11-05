<template>
<div class="home">
  <h1>Welcome our new user to <span>WizHubb</span></h1>
  <img src="../assets/bg.svg" />
</div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.home {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.home>h1 {
  font-size: 46px;
}

.home>h1>span {
  color: rgba(255, 0, 157, 0.877);
}

.home>img {
  width: 700px;
}
</style>
