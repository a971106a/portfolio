<template>
  <div>
    <div class="first-sec" id="home">
      <v-container pa-0>
        <div class="first-content">
          <div class="profile-name">이영우</div>
          <img
            class="profile-img"
            src="@/assets/imgs/profile.png"
            alt="profile"
          />
          <div class="first-content-block">
            <div class="first-content-text">Web Developer Portfolio</div>
            <div class="first-content-text">
              신기술 연구가 취미인 저는, 웹 개발자 이영우 입니다.
            </div>
          </div>
          <a href="#about">
            <v-btn rounded color="white" style="margin-top: 50px">
              더 보기
              <v-icon style="padding-left: 5px">mdi-chevron-double-down</v-icon>
            </v-btn>
          </a>
        </div>
      </v-container>
    </div>
    <div class="sec-sec" id="about">
      <v-container pa-0>
        <div class="first-content">
          <div class="sec-title">About Me</div>
          <v-container class="sec-content">
            <v-row class="sec-detail">
              <v-col xs="12" sm="12" md="6">
                <v-row align="center" justify="center">
                  <v-col cols="3">
                    <v-icon x-large color="black"> mdi-account </v-icon>
                  </v-col>
                  <v-col style="text-align: left"> 이영우 </v-col>
                </v-row>
              </v-col>
              <v-col xs="12" sm="12" md="6">
                <v-row align="center" justify="center">
                  <v-col cols="3">
                    <v-icon x-large color="black"> mdi-calendar </v-icon>
                  </v-col>
                  <v-col style="text-align: left"> 97.11.06 </v-col>
                </v-row>
              </v-col>
            </v-row>
            <v-row class="sec-detail">
              <v-col xs="12" sm="12" md="6">
                <v-row align="center" justify="center">
                  <v-col cols="3">
                    <v-icon x-large color="black"> mdi-phone </v-icon>
                  </v-col>
                  <v-col style="text-align: left"> 010-3757-1106 </v-col>
                </v-row>
              </v-col>
              <v-col xs="12" sm="12" md="6">
                <v-row align="center" justify="center">
                  <v-col cols="3">
                    <v-icon x-large color="black"> mdi-email </v-icon>
                  </v-col>
                  <v-col style="text-align: left">
                    zestlee1106@gmail.com
                  </v-col>
                </v-row>
              </v-col>
            </v-row>
          </v-container>
        </div>
      </v-container>
    </div>
    <div class="third-sec" id="home">
      <v-container pa-0>
        <div class="first-content">
          <div class="sec-title">Skills</div>
          <v-container fluid>
            <v-row dense>
              <v-col xs="12" sm="12" md="4">
                <v-card class="mx-auto">
                  <v-card-text>
                    <p class="text-h4 text--primary">Front-end</p>
                    <div class="text--primary">
                      <img
                        src="@/assets/imgs/htmlSkill.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/vue.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/vuex.png"
                        style="width: 100px"
                        alt=""
                      />
                      <img
                        src="@/assets/imgs/router.png"
                        style="width: 100px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/vuetify.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/NuxtJS.svg"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/php.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/jquery-logo.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/axios.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/ionic.png"
                        style="width: 200px"
                        alt=""
                      />
                    </div>
                  </v-card-text>
                </v-card>
              </v-col>
              <v-col xs="12" sm="12" md="4">
                <v-card class="mx-auto">
                  <v-card-text>
                    <p class="text-h4 text--primary">Back-end</p>
                    <div class="text--primary">
                      <img
                        src="@/assets/imgs/python.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/flask.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/mysql.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/lambda.svg"
                        style="width: 200px"
                        alt=""
                      />
                    </div>
                  </v-card-text>
                </v-card>
              </v-col>
              <v-col xs="12" sm="12" md="4">
                <v-card class="mx-auto">
                  <v-card-text>
                    <p class="text-h4 text--primary">Development</p>
                    <div class="text--primary">
                      <img
                        src="@/assets/imgs/aws.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/ubuntu.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/iis.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/apache.png"
                        style="width: 200px"
                        alt=""
                      />
                    </div>
                  </v-card-text>
                </v-card>
              </v-col>
              <v-col xs="12" sm="12" md="4">
                <v-card class="mx-auto">
                  <v-card-text>
                    <p class="text-h4 text--primary">Version Control</p>
                    <div class="text--primary">
                      <img
                        src="@/assets/imgs/gitlab.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/github.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/bitbucket.png"
                        style="width: 200px"
                        alt=""
                      />
                    </div>
                  </v-card-text>
                </v-card>
              </v-col>
              <v-col xs="12" sm="12" md="4">
                <v-card class="mx-auto">
                  <v-card-text>
                    <p class="text-h4 text--primary">Try</p>
                    <div class="text--primary">
                      <img
                        src="@/assets/imgs/react.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/reactNative.png"
                        style="width: 200px"
                        alt=""
                      />
                      <br />
                      <img
                        src="@/assets/imgs/typescript.png"
                        style="width: 200px"
                        alt=""
                      />
                    </div>
                  </v-card-text>
                </v-card>
              </v-col>
            </v-row>
          </v-container>
        </div>
      </v-container>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Home",

  components: {},
});
</script>

<style scoped>
@media (min-width: 1281px) {
  .first-sec {
    background-color: #01caff;
    height: 731px;
  }
  .sec-sec {
    background-color: #f4f4f4;
    height: 360px;
  }
  .third-sec {
    background-color: white;
    height: 1000px;
  }
  .first-content {
    align-content: center;
    text-align: center;
    padding-top: 59px;
  }
  .profile-img {
    height: 250px;
    margin-top: 25px;
  }
  .profile-name {
    font-size: 73px;
    font-family: "NexonBold";
    letter-spacing: 5px;
  }
  .sec-title {
    font-family: "NexonBold";
    font-size: 40px;
  }
  .first-content-text {
    font-size: 28px;
  }
  .first-content-block {
    margin-top: 20px;
  }
  .sec-detail {
    width: 738px;
    margin-left: auto;
    margin-right: auto;
  }
  .sec-content {
    margin-top: 30px;
  }
}
@media (min-width: 768px) and (max-width: 1280px) {
}
@media (max-width: 767px) {
}
</style>
