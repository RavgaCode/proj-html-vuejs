<template>
  <header>
    <!-- TopHeader -->
    <div class="top_header">
      <div class="container h-100">
        <div class="row d-flex justify-between align-items-center h-100">
          <!-- Left Col -->
          <div class="col-6">
            <div class="h-100">
              <span><i class="fa-solid fa-clock"></i></span> Open Hours:
              Mon-Sat-9:00-18:00
            </div>
          </div>
          <!-- Right Col -->
          <div class="col-6 d-flex justify-content-end">
            <ul>
              <li>
                <span><i class="fa-solid fa-phone"></i></span>+1(305) 1234-5678
              </li>
              <li>
                <span><i class="fa-solid fa-envelope"></i></span
                >hello@example.com
              </li>
              <li>
                <span
                  ><a href="#"><i class="fa-brands fa-facebook-f"></i></a
                ></span>
              </li>
              <li>
                <span
                  ><a href="#"><i class="fa-brands fa-twitter"></i></a
                ></span>
              </li>
              <li>
                <span
                  ><a href="#"><i class="fa-brands fa-linkedin-in"></i></a
                ></span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "TopHeader",
};
</script>

<style lang="scss" scoped>
@import "../style/style.scss";
.top_header {
  height: 60px;
  background-color: #21333e;
  color: #c0c3d0;
}
ul {
  height: 100%;
  display: flex;
  margin-right: -1.5rem;
  align-items: center;
}
li {
  height: 100%;
  padding-right: 1.5rem;
}
</style>
