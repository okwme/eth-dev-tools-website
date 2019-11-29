<template>
  <div class="home">
    <logo id="logo" />
    <h2>Eth Dev Tools</h2>
    <!-- <h2>⚒️ Eth Dev Tools ⚒️</h2> -->
    <!-- <a href="https://github.com">github</a><br> -->
    (Coming Soon)<br>
    <a target="_blank" href="/img/1.jpeg">
      <img class="demo" src="/img/1.jpeg" />
    </a>
    <!-- <a href="/img/2.jpeg"><img class="demo" src="/img/2.jpeg" /></a> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Logo from "@/assets/logo.vue";
export default {
  name: "home",
  components: {
    Logo
  }
};
</script>
<style scoped>
#logo {
  width: 60px;
  height: 60px;
  /* -webkit-filter: drop-shadow(3px 3px 2px rgba(0, 0, 0, 0.7));
  filter: drop-shadow(3px 3px 2px rgba(0, 0, 0, 0.7)); */
  color: #27ae60;
}
.demo {
  max-width: 100vw;
  max-height: calc(100vh - 200px);
}
</style>
