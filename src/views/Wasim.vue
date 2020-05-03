<template>
  <v-container fluid class="pa-0">

    <!-- HEADER -->
    <Header />

    <!-- PRICING TABLE -->
    <PricingTables />

    <!-- 350 COMPANIES -->
    <Testemonials />

    <!-- OPEN SOURCE -->
    <OpenSourceProject  />

    <!-- FOOTER -->
    <Footer />

  </v-container>

</template>

<script>
import Header from "../components/Pricing/Header";
import PricingTables from "../components/Pricing/PricingTables";
import Testemonials from "../components/Pricing/Testemonials";
import OpenSourceProject from "../components/Pricing/OpenSourceProject";
import Footer from "../components/Home/Footer";


export default {
  name: 'Wasim',
  components: {
        Footer,
        Header,
        PricingTables,
        Testemonials,
        OpenSourceProject
  }

}
</script>

<style>

</style>