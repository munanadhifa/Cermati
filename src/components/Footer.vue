<template>
  <div>
    <v-footer color="indigo darken-4" id="footer">
      <v-row>
        <v-col>
          <v-card class="card-msg" outlined>
            <v-icon class="close">mdi-close</v-icon>
            <h3 class="txt-1">Get latest updates in web technologies</h3>
            <p class="txt-2">
              I write articles relates to web technologies, such as design trends, development 
              tools, UI/UX case studies and reviews, and more.<br> Sign up to my newsletter to get 
              them all.
            </p>

            <v-row>
              <v-col>
            <v-text-field
            label="Email"
            solo
            style="margin-left:30px"
            class="email"
          ></v-text-field>
            </v-col>

            <v-col>
              <v-btn color="orange lighten-2" class="btn-msg">Count me in</v-btn>
            </v-col>
          </v-row>

           

           
          </v-card>
        </v-col>
        <v-col class="text-center">
          <p class="txt-footer">n Monos. All rights reserved.</p>
        </v-col>
      </v-row>
    </v-footer>
  </div>
</template>

<script>
export default {
  data: () => ({
    sheet: false,
  }),
};
</script>

<style scoped>
@media (min-width: 1281px) {
  #footer {
    margin-top: 60px;
  }
  .txt-footer {
    color: white;
    margin-left: -690px;
    margin-top: 50px;
  }
  .card-msg{
    margin-top: -120px;
    margin-left: -20px;
    width: 550px;
    margin-bottom: -20px;
     background: rgba(13, 71, 161, 0.6);
    /* background:#1E88E5;
    opacity: 0.6; */
    
   
  }
  .close{
    color: white;
    margin-left: 500px;
  }
  .txt-1,
  .txt-2{
    color: white;
    margin-left: 30px;
  }
  .email{
    width: 300px;
  }
  .btn-msg{
    margin-top: 5px;
  }
}
@media (min-width: 768px) and (max-width: 1024px) {
  #footer {
    margin-top: 100px;
  }
}

@media only screen and (max-width: 800px){
  #footer {
    margin-top: 100px;
  }
  
  .card-msg{
   margin-left: -20px;
    width: 450px;
    margin-bottom: -75px;
    background: rgba(13, 71, 161, 0.6);
  }
  .close{
    color: white;
    margin-left: 330px;
  }
  .txt-1,
  .txt-2{
    margin-top: 10px;
    color: white;
    margin-left: 30px;
    width: 320px;
  }
  .email{
    width: 300px;
    margin-left: 30px;
  }
  .btn-msg{
   margin-left: 30px;
   width: 300px;
   margin-top: -40px;
   color: white;
  }
}


@media only screen and (device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2) {
    #footer {
    margin-top: 100px;
  }
  
  .card-msg{
   margin-left: -20px;
    width: 380px;
    margin-bottom: -75px;
    background: rgba(13, 71, 161, 0.6);
  }
  .close{
    color: white;
    margin-left: 270px;
  }
  .txt-1,
  .txt-2{
    margin-top: 10px;
    color: white;
    margin-left: 20px;
    font-size: 13px;
    width: 300px;
  }
  .email{
    width: 250px;
    margin-left: -10px;
  }
  .btn-msg{
   margin-left: 30px;
   width: 250px;
   margin-top: -40px;
   color: white;
  }
}



</style>