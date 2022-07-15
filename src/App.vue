<template>
  <div id="app">
    <!-- Header with Jumbotron -->
    <TopHeader />
    <JumbotronHome />
    <!-- Main -->
    <main>
      <!-- Services -->
      <ServicesSection />
      <!-- About -->
      <AboutSection />
      <!-- Projects -->
      <ProjectSection />
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
import ServicesSection from "./components/ServicesSection.vue";
import AboutSection from "./components/AboutSection.vue";
import ProjectSection from "./components/ProjectSection.vue";
export default {
  name: "App",
  components: {
    TopHeader,
    JumbotronHome,
    ServicesSection,
    AboutSection,
    ProjectSection,
  },
};
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
