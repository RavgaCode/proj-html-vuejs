<template>
  <section>
    <!-- Navbar -->
    <div class="container">
      <div class="row d-flex justify-between">
        <!-- Logo img -->
        <div class="col-6">
          <p>Logo Nexgen</p>
        </div>
        <!-- Navbar -->
        <div class="col-6 d-flex justify-content-end">
          <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">SERVICES</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">PROJECTS</a></li>
            <li><a href="#">RESULTS</a></li>
          </ul>
          <button>GET IN TOUCH</button>
        </div>
      </div>
    </div>
    <!-- Slogan Claim -->
    <div
      class="slogan h-100 d-flex flex-column justify-content-center align-items-center"
    >
      <h2>Ready <span>Team</span></h2>
      <p>
        No matter what your company needs, we will be ready to assist you in the
        best possible way.
      </p>
      <div class="d-flex">
        <button>GET IN TOUCH</button>
        <button>READ MORE</button>
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
  background-image: url(../assets/img/bg-parallax.png);
  background-size: contain;
  background-repeat: no-repeat;
  height: 90vh;
}
ul {
  display: flex;
}
li {
  margin-left: 3rem;
}
button {
  margin-left: 3rem;
}
</style>
