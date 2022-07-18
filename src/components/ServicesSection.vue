<template>
  <section>
    <div class="container">
      <!-- Services introduction -->
      <h5>OUR BUSINESS AREAS</h5>
      <H3>Excellence in <span class="highlighted_green">Services</span></H3>
      <div class="d-flex justify-content-between">
        <p class="intro_p">
          We are leaders in providing consultancy services with a set of
          cutting-edge technologies and a team of experienced and renowned
          professionals. These are some options that you can hire.
        </p>
        <div><a href="#" class="ms_btn btn_green">SEE ALL</a></div>
      </div>
      <!-- Services grid -->
      <div class="row">
        <div class="col-4 my-3">
          <div class="services_card">
            <div class="d-flex justify-content-between green_icons">
              <div><a href="#">Icona</a></div>
              <div>
                <a href="#"><i class="fa-solid fa-arrow-right"></i></a>
              </div>
            </div>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="services_card">
            <span>Icona</span>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="services_card">
            <span>Icona</span>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="services_card">
            <span>Icona</span>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="services_card">
            <span>Icona</span>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
        <div class="col-4 my-3">
          <div class="services_card">
            <span>Icona</span>
            <h4>Audit & Assurance</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ServicesSection",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";

section {
  background-color: #eef4ed;
  color: #848486;
  height: 800px;
  display: flex;
  align-items: center;
}
h3,
h4 {
  color: black;
}
.intro_p {
  width: 70%;
}
.ms_btn {
  width: 90px;
}
.services_card {
  background-color: white;
  border-radius: 15px;
  padding: 2.5rem;
}
.green_icons a {
  color: #058283;
  text-decoration: none;
}
</style>
