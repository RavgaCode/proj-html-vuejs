<template>
  <main>
    <section class="numbers_section">
      <div class="row text-center d-flex align-content-center h-100">
        <h5>WHAT ARE WE DOING</h5>
        <h3><span>Results</span> in Numbers</h3>
        <!-- Numbers Ul -->
        <ul class="d-flex justify-content-center">
          <li>
            <div>128</div>
            <div>Certifications</div>
          </li>
          <li>
            <div>230</div>
            <div>Employees</div>
          </li>
          <li>
            <div>517</div>
            <div>Customers</div>
          </li>
          <li>
            <div>94</div>
            <div>Countries Served</div>
          </li>
        </ul>
      </div>
    </section>
    <section class="img_section">
      <ul class="d-flex justify-content-center">
        <li>
          <img src="../assets/img/logo-1.png" alt="logo-1" />
        </li>
        <li>
          <img src="../assets/img/logo-1.png" alt="" />
        </li>
        <li>
          <img src="../assets/img/logo-1.png" alt="" />
        </li>
        <li>
          <img src="../assets/img/logo-1.png" alt="" />
        </li>
        <li>
          <img src="../assets/img/logo-1.png" alt="" />
        </li>
        <li>
          <img src="../assets/img/logo-1.png" alt="" />
        </li>
      </ul>
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
}
li {
  margin-inline: 2rem;
}
</style>
