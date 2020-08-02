<template>
  <v-app>
    <v-app-bar app color="white" hide-on-scroll dense dark  class="header">
      <div class="privacy">
        <p>
          By accessing and using this website, you acknowledge you have read and
          <br />understand our
          <a>Cookie Policy</a>,
          <a>Privacy Policy</a>, and our
          <a>Terms of Service</a>.
        </p>
      </div>

      <div class="btn">
        <div class="my-2">
          <v-btn color="primary">Got It</v-btn>
        </div>
      </div>
    </v-app-bar>

    <v-main>
      <Page />
      <Services />
    </v-main>

    <Footer />
  </v-app>
</template>

<script>
import Page from "./components/Page";
import Services from "./components/Services";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Page,
    Services,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
@media (min-width: 1281px) {
  .privacy {
    color: black;
    font-size: 14px;
    margin-top: 15px;
    margin-left: 300px;
  }

  .btn {
    margin-left: 40px;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  .privacy {
    color: black;
    font-size: 9px;
    margin-top: 15px;
    margin-left: 190px;
  }

  .btn {
    margin-left: 40px;
  }
}

@media only screen and (max-width: 800px){
   .privacy {
    color: black;
    font-size: 8px;
    margin-top: 20px;
    width: 300px;
  }

  .btn {
    margin-left: 40px;
  }

  .header{
    height: 60px;
  }
}
@media only screen and (device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2) {
   .privacy {
    color: black;
    font-size: 8px;
    width: 200px;
  }

  .btn {
    margin-left: 40px;
  }

  .header{
    height: 60px;
  }
}
</style>
