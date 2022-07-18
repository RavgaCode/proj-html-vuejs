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
      <ResultSection />
      <!-- Contact form -->
      <GetInTouchSection />
    </main>
    <!-- Footer -->
    <footer>
      <BotFooter />
    </footer>
  </div>
</template>

<script>
import TopHeader from "./components/TopHeader.vue";
import JumbotronHome from "./components/JumbotronHome.vue";
import ServicesSection from "./components/ServicesSection.vue";
import AboutSection from "./components/AboutSection.vue";
import ProjectSection from "./components/ProjectSection.vue";
import ResultSection from "./components/ResultSection.vue";
import GetInTouchSection from "./components/GetInTouchSection.vue";
import BotFooter from "./components/BotFooter.vue";
export default {
  name: "App",
  components: {
    TopHeader,
    JumbotronHome,
    ServicesSection,
    AboutSection,
    ProjectSection,
    ResultSection,
    GetInTouchSection,
    BotFooter,
  },
};
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
