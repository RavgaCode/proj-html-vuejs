<template>
  <footer>
    <div class="footer_columns">
      <section class="top_footer">
        <div class="container">
          <div class="card_columns">
            <!-- Col Info -->
            <div class="col-3">
              <div class="info_card">
                <img src="../assets/img/logo.png" alt="logo nexgen" />
                <p>A Functional HTML Template for Corporate & Business.</p>
                <ul>
                  <li>
                    <span
                      ><i class="fa-solid fa-phone"></i>+1(305) 1234-5678</span
                    >
                  </li>
                  <li>
                    <span><i class="fa-solid fa-envelope"></i></span
                    >hello@example.com
                  </li>
                  <li>
                    <span><i class="fa-solid fa-location-dot"></i></span> Main
                    Avenue, 987
                  </li>
                </ul>
              </div>
              <div>
                <a href="#" class="ms_btn btn_transparent">GET IN TOUCH</a>
              </div>
            </div>
            <!-- Col About -->
            <div class="col-3">
              <div class="card_footer">
                <h3>About</h3>
                <ul>
                  <li v-for="(item, index) in categories.about" :key="index">
                    <span><i class="fa-solid fa-chevron-right"></i></span
                    >{{ item }}
                  </li>
                </ul>
              </div>
            </div>
            <!-- Col Services -->
            <div class="col-3">
              <div class="card_footer">
                <h3>Services</h3>
                <ul>
                  <li v-for="(item, index) in categories.services" :key="index">
                    <span><i class="fa-solid fa-chevron-right"></i></span
                    >{{ item }}
                  </li>
                </ul>
              </div>
            </div>
            <!-- Col Support -->
            <div class="col-3">
              <div class="card_footer">
                <h3>Support</h3>
                <ul>
                  <li v-for="(item, index) in categories.support" :key="index">
                    <span><i class="fa-solid fa-chevron-right"></i></span
                    >{{ item }}
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="bot_footer">
        <div class="container">
          <div class="footer_credits">
            <div>
              Enjoy the low price. We are tacking any intention of piracy.
            </div>
            <div>
              &copy; 2020 NEXGEN is Proudly Powered by
              <span class="green_text">Codings</span>
            </div>
          </div>
        </div>
      </section>
    </div>
  </footer>
</template>

<script>
export default {
  name: "BotFooter",
  data() {
    return {
      categories: {
        about: [
          "The Company",
          "Institutional",
          "Social & Events",
          "Innovation",
          "Enviroment",
          "Technology",
        ],
        services: [
          "Audit & Assurance",
          "Financial Advisory",
          "Analytics M&A",
          "Middle Marketing",
          "Legal Consulting",
          "Regulatory Risk",
        ],
        support: [
          "Responsability",
          "Terms of Use",
          "About Cookies",
          "Privacy Policy",
          "Accessibility",
          "Information",
        ],
      },
    };
  },
};
</script>

<style lang="scss">
@import "../style/style.scss";
footer {
  color: #c0c3d0;
  height: 60vh;
  background-color: #111117;
}
.bot_footer {
  background-color: black;
  height: 8vh;
  display: flex;
  align-items: center;
}
.footer_credits {
  background-color: black;
  display: flex;
  justify-content: space-between;
}
.footer_columns {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100%;
  padding-top: 4rem;
}
.card_columns {
  display: flex;
  justify-content: space-between;
  margin-right: -1.5rem;
  background-color: #111117;
}
.info_card {
  margin-right: 1.5rem;

  * {
    padding-block: 0.3rem;
  }
  img {
    height: 60px;
  }
}
.ms_btn {
  margin-top: 2rem;
}
.card_footer {
  background-color: #19191f;
  border-radius: 15px;
  padding: 2rem;
  margin-right: 1.5rem;
}
ul {
  padding-left: 2rem;
}
li {
  padding-block: 0.3rem;

  * {
    margin-right: 0.3rem;
  }
}
h3 {
  color: white;
}
.green_text {
  color: #09524d;
}
</style>
