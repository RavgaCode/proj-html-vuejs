<template>
  <section>
    <div class="container h-100">
      <div class="row h-100">
        <!-- Left Col - Form Col -->
        <div class="col-6">
          <div class="form_card">
            <h5>SEND A MESSAGE</h5>
            <H3>Get in <span>Touch</span></H3>
            <p>We will respond to your message as soon as possible</p>
            <div>
              <h3>Form</h3>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Distinctio consectetur magnam fugit eius suscipit omnis similique,
              quidem officiis delectus adipisci maiores explicabo debitis
              accusantium, dolorem voluptatibus tempora dignissimos? Recusandae,
              vitae!
            </div>
            <button>SEND</button>
          </div>
        </div>
        <!-- Right Col - Contact info Col -->
        <div class="col-6">
          <div class="info_card">
            <h4>Example Inc.</h4>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            <p>
              Deleniti magnam fugit aliquam, minima nostrum omnis dolores
              reiciendis quos vero dolor
            </p>
            <ul>
              <li>
                <span><i class="fa-solid fa-phone"></i></span> +1(305) 1234-5678
              </li>
              <li>
                <span><i class="fa-solid fa-envelope"></i></span>
                hello@example.com
              </li>
              <li>
                <span><i class="fa-solid fa-location-dot"></i></span> Main
                Avenue, 987
              </li>
            </ul>
            <button>VIEW MAP</button>
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
}
.form_card {
  padding-top: 12rem;
}
.info_card {
  padding-top: 12rem;
}
</style>
