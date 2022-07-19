<template>
  <section>
    <div class="container h-100">
      <div class="row h-100">
        <!-- Left Col - Form Col -->
        <div class="col-8">
          <div class="form_card">
            <h5>SEND A MESSAGE</h5>
            <H3>Get in <span class="highlighted_green">Touch</span></H3>
            <p>We will respond to your message as soon as possible</p>
            <div>
              <div class="row d-flex justify-content-between">
                <!-- Name -->
                <div class="col-6">
                  <input type="text" placeholder="Name" />
                </div>
                <!-- Email -->
                <div class="col-6">
                  <input type="email" placeholder="Email" />
                </div>
                <!-- Phone -->
                <div class="col-6">
                  <input type="tel" placeholder="Phone" />
                </div>
                <!-- More Info -->
                <div class="col-6">
                  <input type="text" placeholder="More Info" />
                </div>
                <div class="col">
                  <input type="text-area" class="text_form" />
                </div>
              </div>
            </div>
            <input type="submit" class="ms_btn btn_green" value="SEND" />
          </div>
        </div>
        <!-- Right Col - Contact info Col -->
        <div class="col-4">
          <div class="info_card">
            <h4>Example Inc.</h4>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            <p>
              Deleniti magnam fugit aliquam, minima nostrum omnis dolores
              reiciendis quos vero dolor
            </p>
            <ul>
              <li>
                <span class="green_circle"
                  ><i class="fa-solid fa-phone"></i
                ></span>
                +1(305) 1234-5678
              </li>
              <li>
                <span class="green_circle"
                  ><i class="fa-solid fa-envelope"></i
                ></span>
                hello@example.com
              </li>
              <li>
                <span class="green_circle"
                  ><i class="fa-solid fa-location-dot"></i
                ></span>
                Main Avenue, 987
              </li>
            </ul>
            <div><a href="#" class="ms_btn btn_whitebg">VIEW MAP</a></div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GetInTouchSection",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";
section {
  height: 80vh;
  color: #c0c3d0;
}
h3,
h4 {
  color: black;
}
.form_card {
  padding-top: 12rem;
}
.info_card {
  padding-top: 12rem;

  p {
    margin-block: 1.5rem;
  }
}
input {
  width: 100%;
  height: 40px;
  margin-block: 0.5rem;
  background-color: #ececec;
  border: 1px solid #ececec;
  padding-inline: 0.5rem;
  border-radius: 7px;
}
.text_form {
  height: 200px;
}
.ms_btn {
  width: 100px;
  border: 1px solid #058283;
}
li {
  color: #058283;
  font-size: 23px;
  margin-block: 1.5rem;
}
.btn_whitebg {
  width: 150px;
  margin-top: 2rem;
}
</style>
