<template>
  <v-img
    dark
    :src="require('../assets/work-desk__dustin-lee.jpg')"
    gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
    class="image"
  >
    <v-img dark :src="require('../assets/y-logo-white.png')" class="logo" />

    <div class="txt">
      <h1>Hello! I'm Yuan Monos</h1>
      <h2>Consult, Design, and Develop Website</h2>
      <p class="txt-main">
        Have something great in mind? Feel free to contact me.
        <br />I'll help you to make it happen.
      </p>
      <v-btn class="ma-2" outlined color="white">Let's Make Contact</v-btn>
    </div>
  </v-img>
</template>

<script>
export default {};
</script>

<style scoped>
@media (min-width: 1281px) {
  .logo {
    width: 40px;
    margin-left: 20px;
    margin-top: 10px;
  }
  .txt {
    text-align: center;
    margin-top: 100px;
  }
  .image{
    height:500px;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  .logo {
    width: 40px;
    margin-left: 20px;
    margin-top: 10px;
  }
  .txt {
    text-align: center;
    margin-top: 100px;
  }
  .image{
    height:500px;
  }
}

@media only screen and (max-width: 800px){
  .logo {
    width: 40px;
    margin-left: 20px;
    margin-top: 10px;
  }
  .txt {
    text-align: center;
    margin-top: 100px;
  }
  .image{
    height:500px;
  
  }
}

@media only screen and (device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2) {
   .logo {
    width: 40px;
    margin-left: 20px;
    margin-top: 10px;
  }
  .txt {
    text-align: center;
    margin-top: 100px;
  }
  .image{
    height:500px;
  }
  .txt-main{
    font-size: 15px;
  }
}
</style>