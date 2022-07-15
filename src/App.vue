<template>
  <div id="app">
    <!-- Header with Jumbotron -->
    <TopHeader />
    <JumbotronHome />
    <!-- Main -->
    <main>
      <!-- Services -->
      <!-- About -->
      <!-- Projects -->
      <!-- Results -->
      <!-- Contact form -->
    </main>
    <!-- Footer -->
    <footer></footer>
  </div>
</template>

<script>
import TopHeader from "./components/TopHeader.vue";
import JumbotronHome from "./components/JumbotronHome.vue";
export default {
  name: "App",
  components: { TopHeader, JumbotronHome },
};
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
