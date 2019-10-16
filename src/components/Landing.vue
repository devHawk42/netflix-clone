<template>
  <div class="landing-container">
    <div class="header-container">
      <img class="logo" src="/netflix-logo.png"/>
      <button class="header-button">Sign in</button>
    </div>
    <h1>Unlimited movies, TV shows, and more.</h1>
    <h2>Watch anywhere. Cancel anytime.</h2>
    <button class="landing-button">try it now</button>
  </div>
</template>

<script>
export default {
  name: 'Landing',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.landing-container {
  background-image: url('/landing-bk.jpg');
  background-size: cover;
  height: 100vh;
}

.header-container {
  display: flex;
  justify-content: space-between;
}

.logo {
  width: 108px;
  height: 40px;
}
</style>
