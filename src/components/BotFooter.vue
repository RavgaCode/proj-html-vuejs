<template>
  <footer>
    <div class="container">
      <div class="row">
        <!-- Col Info -->
        <div class="col-3">
          <img src="../assets/img/logo.png" alt="logo nexgen" />
          <p>A Functional HTML Template for Corporate & Business.</p>
          <ul>
            <li>
              <span><i class="fa-solid fa-phone"></i>+1(305) 1234-5678</span>
            </li>
            <li>
              <span><i class="fa-solid fa-envelope"></i></span>hello@example.com
            </li>
            <li>
              <span><i class="fa-solid fa-location-dot"></i></span> Main Avenue,
              987
            </li>
          </ul>
          <button>GET IN TOUCH</button>
        </div>
        <!-- Col About -->
        <div class="col-3">
          <div class="card_footer">
            <h3>About</h3>
            <ul>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
            </ul>
          </div>
        </div>
        <!-- Col Services -->
        <div class="col-3">
          <div class="card_footer">
            <h3>Services</h3>
            <ul>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
            </ul>
          </div>
        </div>
        <!-- Col Support -->
        <div class="col-3">
          <div class="card_footer">
            <h3>Support</h3>
            <ul>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
              <li>
                <span><i class="fa-solid fa-chevron-right"></i></span>The
                Company
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "BotFooter",
};
</script>

<style lang="scss">
@import "../style/style.scss";
footer {
  background-color: black;
  color: white;
}

.card_footer {
  background-color: lightgray;
  border-radius: 15px;
}
</style>
