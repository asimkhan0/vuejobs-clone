<template>
    <v-container fluid class="pricing-container-bg ">
        <Appbar />
        <v-row class="mt-12">
            <v-col cols="12" class="mt-10 text-center white--text">
                <span class="main-heading d-block white--text mb-3">Pricing plans for everyone</span>
                <span class="secondary-text white--text d-block mb">Select the plan that fits your needs and reach out to up to 150k+ Vue.js developers.</span>
            </v-col>
        </v-row>
    </v-container>
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