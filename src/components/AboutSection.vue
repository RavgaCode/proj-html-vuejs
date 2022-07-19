<template>
  <section>
    <img
      src="../assets/img/bullets.png"
      alt="green bullets"
      class="top_bullets"
    />
    <img
      src="../assets/img/bullets.png"
      alt="green bullets"
      class="bottom_bullets"
    />
    <div class="container">
      <div class="row">
        <!-- Left Col - Text-->
        <div class="col-6 d-flex align-items-center">
          <div class="about_card">
            <h5 class="my-3">ABOUT THE NETWORK</h5>
            <h3 class="my-3">
              <span class="highlighted_white">The</span> Company
            </h3>
            <p>
              For 12 years we have been providing audit and warranty, financial
              advice, risk advice, taxes and related services to select clients.
            </p>
            <!-- About Info Cards -->
            <div class="row">
              <div class="col-6 my-3">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
            </div>
            <!-- Buttons -->
            <div class="d-flex">
              <div><a href="#" class="ms_btn btn_green">GET IN TOUCH</a></div>
              <div>
                <a href="#" class="ms_btn btn_transparent">READ MORE</a>
              </div>
            </div>
          </div>
        </div>

        <!-- Right-Col - Img -->
        <div class="col-6">
          <img src="../assets/img/about-4.jpg" alt="About-img" />
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "AboutSection",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";
section {
  background-color: #111117;
  color: white;
  height: 80vh;
  position: relative;
}
p {
  color: #b1bbcd;
}
img {
  max-width: 80vh;
}
.ms_btn {
  margin-right: 1rem;
  margin-top: 2rem;
}
.top_bullets {
  position: absolute;
  height: 100px;
  top: -48px;
  left: 50%;
  margin-left: -35px;
}
.bottom_bullets {
  position: absolute;
  width: 100px;
  bottom: -53px;
  left: 50%;
  margin-left: -35px;
}
</style>
