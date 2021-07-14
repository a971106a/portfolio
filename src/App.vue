<template>
  <v-app>
    <v-app-bar app color="white" elevate-on-scroll dark height="70px">
      <v-container>
        <v-row>
          <a href="#home">
            <div class="app-title">Lee.YW</div>
          </a>

          <v-spacer></v-spacer>

          <a href="#about">
            <div class="header-btn">
              <div class="header-btn-text">ABOUT</div>
            </div>
          </a>
          <div class="header-btn">
            <div class="header-btn-text">SKILLS</div>
          </div>
          <div class="header-btn">
            <div class="header-btn-text">ARCHIVING</div>
          </div>
          <div class="header-btn">
            <div class="header-btn-text">PROJECTS</div>
          </div>
        </v-row>
      </v-container>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",

  data: () => ({
    //
  }),
});
</script>

<style>
@font-face {
  font-family: "Nexon";
  src: url("./assets/fonts/NEXON Lv1 Gothic OTF.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: "NexonBold";
  src: url("./assets/fonts/NEXON Lv1 Gothic OTF Bold.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}
#app {
  font-family: "Nexon";
  text-decoration: none;
}
a:link {
  text-decoration: none !important;
}
@media (min-width: 1281px) {
  .app-title {
    font-size: 24px;
    letter-spacing: 4px;
    color: #777;
    font-family: "NexonBold";
  }
  .header-btn:hover .header-btn-text {
    transition: all 0.3s;
    color: #1fc7ff;
  }
  .header-btn-text {
    color: #777;
  }
  .header-btn {
    margin-left: 10px;
    padding-top: 8px;
    cursor: pointer;
  }
}
@media (min-width: 768px) and (max-width: 1280px) {
  .header-btn:hover,
  .header-btn {
    transition: all 0.3s;
    color: #1fc7ff;
  }
}
@media (max-width: 767px) {
}
</style>