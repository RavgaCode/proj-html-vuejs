<template>
  <section>
    <div class="container">
      <!-- Section Introduction and Project Selection Bar -->
      <div class="row d-flex justify-items-center text-center">
        <h5>WE DO MORE FOR EVERYONE</h5>
        <h3>Actions & <span>Projects</span></h3>
        <ul class="d-flex justify-content-center">
          <li>ALL</li>
          <li>INSTITUTIONAL</li>
          <li>SOCIAL</li>
          <li>EVENTS</li>
          <li>INNOVATION</li>
          <li>ENVIRONMENT</li>
          <li>TECHNOLOGY</li>
        </ul>
      </div>
      <!-- Projects Grid -->
      <div class="row">
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4>Academic Professional Program in Social Media</h4>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ProjectSection",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";

section {
  height: 120vh;
  background-color: coral;
}
li {
  margin-inline: 2rem;
}
img {
  width: 200px;
}
</style>
