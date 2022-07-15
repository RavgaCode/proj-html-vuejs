<template>
  <section>
    <div class="container">
      <div class="row">
        <!-- Left Col - Text-->
        <div class="col-6 d-flex align-items-center">
          <div class="about_card">
            <h5>ABOUT THE NETWORK</h5>
            <h3><span>The</span> Company</h3>
            <p>
              For 12 years we have been providing audit and warranty, financial
              advice, risk advice, taxes and related services to select clients.
            </p>
            <!-- About Info Cards -->
            <div class="row">
              <div class="col-6">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
              <div class="col-6">
                <h4><span>Logo </span>Tradition</h4>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
              </div>
            </div>
            <!-- Buttons -->
            <div class="d-flex">
              <button>GET IN TOUCH</button>
              <button>READ MORE</button>
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
  background-color: #000000;
  color: white;
  height: 80vh;
}
img {
  max-height: 80vh;
}
</style>
