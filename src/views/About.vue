<template>
<v-container fluid class="pa-0">
    <v-row class="about-container-bg pb-12 mb-12">
      <v-col md="12">
        <Appbar />
        <v-row class="mt-12 pb-12" justify="center">
              <v-col md="10" class="mt-10 text-center white--text pb-12">
                <span class="main-heading d-block white--text">Meet the VueJobs project</span>
                <span class="secondary-text white--text d-block pb-12">Support Vue.js development by posting a job with us!</span>
              </v-col>
            </v-row>
          </v-col>
        </v-row>

        <v-row justify="center" class="pb-12">
          <v-col md="10" class="text-center px-12">
            <span class="d-block headline mt-8 mb-5">Get to know who's behind VueJobs</span>
            <span class="d-block regular">VueJobs has been developed by Vue.js and Laravel enthusiasts whose aim is to contribute to the growing community by helping companies find Vue.js talent around the world. When you register with Vue.js jobs, companies will be able to list jobs and developers will have the chance to apply for those jobs.</span>
          </v-col>

            <v-row justify="space-around" class="mt-5">

              <v-col md="4" offset-lg="1" class="pa-0">
                <v-card raised>
                  <v-row>
                    <v-col md="2" class="py-0">
                      <img class="img-rad mb-n2" width="150px" src="../assets/jim.png" alt="">
                    </v-col>
                    <v-col md="10" class="pl-6">
                      <span class="d-block subtitle-1">Jilson Thomas</span>
                      <span class="regular">I'm a frontend/backend developer and UI designer. I have a deep interest in pixel perfect, user-centric design with a special focus on the user experience.</span>
                    </v-col>
                  </v-row>
                </v-card>            
              </v-col>

              <v-col md="4" class="pa-0">
                <v-card raised>
                  <v-row>
                    <v-col md="2" class="py-0">
                      <img class="img-rad mb-n2" width="150px" src="../assets/is.jpg" alt="">
                    </v-col>
                    <v-col md="10" class="pl-6">
                      <span class="d-block subtitle-1">Jilson Thomas</span>
                      <span class="regular">I'm a frontend/backend developer and UI designer. I have a deep interest in pixel perfect, user-centric design with a special focus on the user experience.</span>
                    </v-col>
                  </v-row>
                </v-card>            
              </v-col>
            </v-row>
        </v-row>

        <v-row justify="center" >
          <v-col md="10">
            <v-row justify="center" align="center">
              <v-col md="2">
                <span class="display-1 txt-grey">3 Benifits of Posting with Us</span>
              </v-col>

              <v-col md="7" offset-lg="1">

                <v-card shaped color="#34495E" class="outline pr-5">
                  <v-row class="px-2" align="center">
                  <v-col md="1" class="display-2 txt-grey">1</v-col>
                  <v-col md="11" class="white">
                    <span class="d-block headline pa-2">We are a Vue.js niche</span>
                    <span >Our Vue.js job board is a niche job site. We provide job listings for the Vue.js market so we can ensure most of our job seekers are matching 100% of your main job requirement, Vue.js knowledge.</span>
                  </v-col>
                </v-row>
                </v-card>

                <v-card shaped color="#34495E" class="outline pr-5 my-6">
                  <v-row class="px-2" align="center">
                  <v-col md="1" class="display-2 txt-grey">2</v-col>
                  <v-col md="11" class="white">
                    <span class="d-block headline pa-2">Help the Vue.js community</span>
                    <span>We like to play closely with the Vue.js community. We donate part of our incomes (in different forms) to sponsor local Vue.js communities to help them promote and share experiences using Vue.js.</span>
                  </v-col>
                </v-row>
                </v-card>

                <v-card shaped color="#34495E" class="outline pr-5">
                  <v-row class="px-2" align="center">
                  <v-col md="1" class="display-2 txt-grey">3</v-col>
                  <v-col md="11" class="white">
                    <span class="d-block headline pa-2">Sponsoring Vue.js development</span>
                    <span>VueJobs has been a sponsoring Vue.js development via Evan's Patreon Campaign since we started. Posting a job with us will ensure that this sponsorship last forever.</span>
                  </v-col>
                </v-row>
                </v-card>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
        
        <v-row justify="center">
          <v-col md="10">
            <v-row align="center">
              <v-col md="6">
                <span class="d-block headline py-6">Hire Vue.js developers</span>
                <span  class="d-block pb-2">Post a job with us and let us help you find the Vue.js talent that you are looking for. All postings include:</span>
                <span class="d-block my-2">
                <img src="../assets/good.jpg">
                <span class="pl-2">List your job in our social media and leading partners.</span>
                </span>

                <span class="d-block mb-2">
                <img src="../assets/good.jpg">
                <span class="pl-2">Contribute to Vue.js development and its community.</span>
                </span>

                <span class="d-block mb-2">
                <img src="../assets/good.jpg">
                <span class="pl-2">Sponsor Vue.js related meetups.</span>
                </span>

                <span class="d-block mb-2">
                <img src="../assets/good.jpg">
                <span class="pl-2">Include your job in our weekly newsletter.</span>
                </span>

                <span class="d-block pt-3">And much more! Check out our pricing to discover:</span>

                <v-btn dark color="#34495E" class="text-capitalize my-4" large><v-icon left>arrow_forward</v-icon>See Pricing Options</v-btn>

              </v-col>
              <v-col md="6">
                <v-row justify="space-around">
                  <v-col md="3"><img width="100%" src="../assets/twitter-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                  <v-col md="3"><img width="100%" src="../assets/linkedin-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                  <v-col md="3"><img width="100%" src="../assets/facebook-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                </v-row>

                <v-row justify="space-around">
                  <v-col md="3"><img width="100%" src="../assets/vuejs-feed-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                  <v-col md="3"><img width="100%" src="../assets/vue-newsletter-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                  <v-col md="3" class="text-center"><img width="38%" src="../assets/vuejs-developers-logo.png" alt=""><span class="d-block caption text-center">Our twitter Profile</span></v-col>
                </v-row>

              </v-col>

            </v-row>

          </v-col>
        </v-row>


</v-container>






</template>

<script>
import Appbar from "../components/Appbar";

export default {
    name: 'About',
  components: {
        Appbar
  }

}
</script>

<style>

</style>