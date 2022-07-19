<template>
  <main>
    <section class="numbers_section">
      <div class="row text-center d-flex align-content-center h-100">
        <h5>WHAT ARE WE DOING</h5>
        <h3><span class="highlighted_white">Results</span> in Numbers</h3>
        <!-- Numbers Ul -->
        <ul class="d-flex justify-content-center">
          <li>
            <div class="number">128</div>
            <div class="result_item">Certifications</div>
          </li>
          <li>
            <div class="number">230</div>
            <div class="result_item">Employees</div>
          </li>
          <li>
            <div class="number">517</div>
            <div class="result_item">Customers</div>
          </li>
          <li>
            <div class="number">94</div>
            <div class="result_item">Countries Served</div>
          </li>
        </ul>
      </div>
    </section>
    <section class="img_section">
      <div class="container">
        <ul>
          <li>
            <img src="../assets/img/logo-4.png" alt="logo jQuery" />
          </li>
          <li>
            <img src="../assets/img/logo-5.png" alt="logp less" />
          </li>
          <li>
            <img src="../assets/img/logo-1.png" alt="logo woocommercee" />
          </li>
          <li>
            <img src="../assets/img/logo-2.png" alt="logo wordpress" />
          </li>
          <li>
            <img src="../assets/img/logo-3.png" alt="logo pingdom" />
          </li>
          <li>
            <img src="../assets/img/logo-4.png" alt="logo jQuery" />
          </li>
        </ul>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "ResultSection",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";
.numbers_section {
  background-image: url(../assets/img/bg-7.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  color: white;
  height: 50vh;
}
.img_section {
  background-color: #111117;
  height: 20vh;
  display: flex;
  align-items: center;
}
ul {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
li {
  margin-inline: 2rem;
}
img {
  filter: brightness(400%);
  height: 25px;
}
h3 {
  padding-block: 2rem;
}
.number {
  color: #00a6a6;
  font-size: xx-large;
  font-weight: 800;
  padding-block: 2rem;
}
.result_item {
  font-size: x-large;
  font-weight: 800;
}
</style>
