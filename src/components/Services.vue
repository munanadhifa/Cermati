<template>
  <div>
    <h1 class="service">How Can I Help You?</h1>
    <p class="txt-service">
      Our work then targeted, best practices outcomes social innovation synergy.
      <br />Venture philanthropy, revolutionary inclusive policymaker relief. User-centered
      <br />program areas scale.
    </p>

    <v-row>
      <v-col>
        <v-card  id="card-1" class="mx-auto"  outlined>
          <v-row>
            <v-col>
              <p class="name-1">Consult</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-1">mdi-wechat</v-icon>
            </v-col>
          </v-row>

          <p class="txt-1">
            Co-create, design thinking; strengthen insfrastructure resist
            <br />granular. Revolation circular, movement or framework
            <br />social impact low-hanging fruit. Save the worl
            <br />compelling revolutionary progress.
          </p>
        </v-card>
      </v-col>

      <v-col>
        <v-card id="card-2" class="mx-auto"  outlined>
          <v-row>
            <v-col>
              <p class="name-2">Design</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-2">mdi-marker</v-icon>
            </v-col>
          </v-row>

          <p class="txt-2">
            Revolutionary circular, movements a or impact framework
            <br />social impect low-hanging. Save the compelling
            <br />revolutionary inspire progress. Collective impacts and
            <br />challenges for opportunities of thought provoking.
          </p>
        </v-card>
      </v-col>

      <v-col>
        <v-card id="card-3" class="mx-auto"  outlined>
          <v-row>
            <v-col>
              <p class="name-3">Develop</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-3">mdi-view-grid</v-icon>
            </v-col>
          </v-row>

          <p class="txt-3">
            Policymaker collaborates collective impact humanitarian
            <br />shared value vocabulary inspire issue outcomes agile
            <br />Overcame injustice deep dive agile issue outcomes vibrant
            <br />boots on the ground sustainable.
          </p>
        </v-card>
      </v-col>
    </v-row>

    <v-row>
      <v-col>
        <v-card id="card-4" class="mx-auto"  outlined>
          <v-row>
            <v-col>
              <p class="name-4">Marketing</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-4">mdi-volume-medium</v-icon>
            </v-col>
          </v-row>

          <p class="txt-4">
            Peaceful; vibrant paradigm, collaborative cities. Shared
            <br />vocabulary agile, replicable, effective altruism youth.
            <br />Mobilize commitment to overcome injustice resilient, uplift
            <br />social transparent effective.
          </p>
        </v-card>
      </v-col>

      <v-col>
        <v-card id="card-5" class="mx-auto" outlined>
          <v-row>
            <v-col>
              <p class="name-5">Manage</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-5">mdi-server</v-icon>
            </v-col>
          </v-row>

          <p class="txt-5">
            Change-makers innovation or shared unit of analysis.
            <br />Overcome injustice outcomes strategize vibrant boots on
            <br />the ground sustainable. Optimism, effective altruism
            <br />invest optimsm corporate social.
          </p>
        </v-card>
      </v-col>

      <v-col>
        <v-card id="card-6" class="mx-auto"  outlined>
          <v-row>
            <v-col>
              <p class="name-6">Evolve</p>
            </v-col>

            <v-col>
              <v-icon large class="icon-6">mdi-chart-line</v-icon>
            </v-col>
          </v-row>

          <p class="txt-6">
            Activate cataylyze and impact contextualize humanitarian.
            <br />Unit of analysis overcome injustice storytelling altruism.
            <br />Thoght leadership mass incarceration. Outcomes big
            <br />data, fairness, social game-changer.
          </p>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media (min-width: 1281px) {
  .service {
    text-align: center;
    margin-top: 40px;
  }
  .txt-service {
    text-align: center;
    margin-left: 10px;
  }
  .txt-1,
  .txt-2,
  .txt-3,
  .txt-4,
  .txt-5,
  .txt-6 {
    font-size: 12px;
    width: 350px;
    margin-left: 15px;
  }

  .name-1,
  .name-2,
  .name-3,
  .name-4,
  .name-5,
  .name-6 {
    margin-left: 15px;
  }

  .icon-1,
  .icon-2,
  .icon-3,
  .icon-4,
  .icon-5,
  .icon-6 {
    margin-left: 100px;
  }
  #card-1,
  #card-2,
  #card-3,
  #card-4,
  #card-5,
  #card-6{
    max-width:344px;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
   .service {
    text-align: center;
    margin-top: 40px;
  }
  .txt-service {
    text-align: center;
    margin-left: 10px;
  }
  .txt-1,
  .txt-2,
  .txt-3,
  .txt-4,
  .txt-5,
  .txt-6 {
    font-size: 12px;
    width: 350px;
    margin-left: 15px;
  }

  .name-1,
  .name-2,
  .name-3,
  .name-4,
  .name-5,
  .name-6 {
    margin-left: 15px;
  }

  #card-1,
  #card-2,
  #card-3,
  #card-4,
  #card-5,
  #card-6{
    max-width:344px;
  }

  .icon-1,
  .icon-2,
  .icon-3,
  .icon-4,
  .icon-5,
  .icon-6 {
    margin-left: 100px;
  }
}


@media only screen and (max-width: 800px) {
   .service {
    text-align: center;
    margin-top: 40px;
  }
  .txt-service {
    text-align: center;
    width: 300px;
    margin-left: 40px;
  }
  .txt-1,
  .txt-2,
  .txt-3,
  .txt-4,
  .txt-5,
  .txt-6 {
    font-size: 12px;
    width: 350px;
    margin-left: 15px;
  }

  .name-1,
  .name-2,
  .name-3,
  .name-4,
  .name-5,
  .name-6 {
    margin-left: 15px;
  }

  .icon-1,
  .icon-2,
  .icon-3,
  .icon-4,
  .icon-5,
  .icon-6 {
    margin-left: 100px;
  }

   #card-1,
  #card-2,
  #card-3,
  #card-4,
  #card-5,
  #card-6{
    max-width:344px;
  }

}

@media only screen and (device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2) {
   .service {
    text-align: center;
    margin-top: 40px;
  }
  .txt-service {
    text-align: center;
    width: 300px;
    margin-left: 10px;
  }
  .txt-1,
  .txt-2,
  .txt-3,
  .txt-4,
  .txt-5,
  .txt-6 {
    font-size: 10px;
    width: 350px;
    margin-left: 15px;
  }

  .name-1,
  .name-2,
  .name-3,
  .name-4,
  .name-5,
  .name-6 {
    margin-left: 15px;
  }

  .icon-1,
  .icon-2,
  .icon-3,
  .icon-4,
  .icon-5,
  .icon-6 {
    margin-left: 100px;
  }

   #card-1,
  #card-2,
  #card-3,
  #card-4,
  #card-5,
  #card-6{
    max-width:300px;
  }
}

</style>