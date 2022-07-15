<template>
  <div id="app">
    <!-- Header with Jumbotron -->
    <TopHeader />
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
export default {
  name: "App",
  components: { TopHeader },
};
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
