<template>
  <section>
    <!-- Team Img -->
    <img src="../assets/img/bg-parallax.png" alt="Team Img" class="team_img" />
    <!-- Navbar -->
    <div class="container">
      <div class="row d-flex justify-between align-items-center py-3">
        <!-- Logo img -->
        <div class="col-6">
          <img
            src="../assets/img/logo.png"
            alt="Logo nexgen"
            class="jumbo_logo"
          />
        </div>
        <!-- Navbar -->
        <div class="col-6 d-flex justify-content-end align-content-center">
          <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">SERVICES</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">PROJECTS</a></li>
            <li><a href="#">RESULTS</a></li>
            <li><a href="#" class="ms_btn btn_green">GET IN TOUCH</a></li>
          </ul>
          <div class="ms_btn btn_size"></div>
        </div>
      </div>
    </div>
    <!-- Slogan Claim -->
    <div
      class="slogan h-100 d-flex flex-column justify-content-center align-items-center text-center"
    >
      <h2>Ready <span class="highlighted_green">Team</span></h2>
      <p>
        No matter what your company needs, we will be ready to assist you in the
        best possible way.
      </p>
      <div class="d-flex">
        <a href="#" class="ms_btn btn_green">GET IN TOUCH</a>
        <a href="#" class="ms_btn btn_whitebg">READ MORE</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "JumbotronHome",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";
section {
  background-image: url(../assets/img/squares-background.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  height: 90vh;
  position: relative;
}

ul {
  display: flex;
  z-index: 2;
}
li {
  margin-left: 3rem;
  display: flex;
  align-items: center;

  a {
    text-decoration: none;
    color: #657178;
    font-weight: 500;
  }
}
.ms_btn {
  margin-inline: 0.5rem;
  z-index: 2;
}
.btn_green {
  width: 140px;
}
.team_img {
  position: absolute;
  top: 48%;
  left: -5%;
  height: 946px;
  margin-top: -500px;
  margin-left: -500px;
  z-index: 1;
  display: block;
}
.jumbo_logo {
  height: 40px;
}
h2 {
  font-weight: 800;
  font-size: 70px;
}
.slogan p {
  width: 380px;
  color: #8c969b;
  padding-block: 1rem;
}
</style>
