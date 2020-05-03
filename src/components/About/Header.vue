<template>
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

</template>

<script>
import Appbar from "../../components/Home/Appbar";

export default {
  name: 'Home',
  components: {
        Appbar
  }

}
</script>

<style>

</style>