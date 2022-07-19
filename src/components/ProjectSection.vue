<template>
  <section class="d-flex align-items-center">
    <div class="container">
      <!-- Section Introduction and Project Selection Bar -->
      <div class="row d-flex justify-items-center text-center">
        <h5 class="my-3">WE DO MORE FOR EVERYONE</h5>
        <h3 class="my-3">
          Actions & <span class="highlighted_green">Projects</span>
        </h3>
        <ul class="d-flex justify-content-center my-3">
          <li><a href="#" class="highlighted_green">ALL</a></li>
          <li><a href="#">INSTITUTIONAL</a></li>
          <li><a href="#">SOCIAL</a></li>
          <li><a href="#">EVENTS</a></li>
          <li><a href="#">INNOVATION</a></li>
          <li><a href="#">ENVIRONMENT</a></li>
          <li><a href="#">TECHNOLOGY</a></li>
        </ul>
      </div>
      <!-- Projects Grid -->
      <div class="row">
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-1.jpg" alt="Project 1 Img" />
            <h4 class="front_card_name">
              Academic Professional Program in Social Media
            </h4>
            <div class="hover_card">
              <h4>Academic Professional Program in Social Media</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-2.jpg" alt="Project 2 Img" />
            <h4 class="front_card_name">
              President's speech at the annual meeting
            </h4>
            <div class="hover_card">
              <h4>President's speech at the annual meeting</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-3.jpg" alt="Project 3 Img" />
            <h4 class="front_card_name">
              International business trip in Shanghai
            </h4>
            <div class="hover_card">
              <h4>International business trip in Shanghai</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-4.jpg" alt="Project 4 Img" />
            <h4 class="front_card_name">
              Technology workshop with education theme
            </h4>
            <div class="hover_card">
              <h4>Technology workshop with education theme</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-5.jpg" alt="Project 5 Img" />
            <h4 class="front_card_name">
              Donation of clothes and food to the partner NGO
            </h4>
            <div class="hover_card">
              <h4>Donation of clothes and food to the partner NGO</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="project_card">
            <img src="../assets/img/project-6.jpg" alt="Project 6 Img" />
            <h4 class="front_card_name">
              Confraternization of the procurement team
            </h4>
            <div class="hover_card">
              <h4>Confraternization of the procurement team</h4>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
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
}
li {
  margin-inline: 2rem;

  a {
    color: #88838b;
    text-decoration: none;
    font-size: large;
  }
}
img {
  width: 350px;
  border-radius: 10px;
  filter: brightness(60%);
}
h3 {
  color: black;
}
h4 {
  color: white;
  text-align: center;
  max-width: 350px;
}
p {
  color: white;
  text-align: center;
  max-width: 350px;
}
.project_card {
  position: relative;
}
.front_card_name {
  position: absolute;
  bottom: 0;
  left: 0;
}
li:hover a {
  color: #058283;
}

.hover_card {
  display: none;
  position: absolute;
  bottom: 0;
  left: 0;
}
.project_card:hover .hover_card {
  display: block;
}
.project_card:hover .front_card_name {
  display: none;
}
.project_card:hover img {
  filter: blur(3px) brightness(60%);
}
</style>
