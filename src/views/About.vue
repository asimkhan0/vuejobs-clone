<template>
<v-container fluid class="pa-0">

  <!-- HEADER -->
  <Header />

  <!-- WHO BEHIND VUE JOBS -->
  <Team />

  <!-- 3 BENIFITS OF POSTING WITH US -->
  <Benifits />
        
  <!-- HIRE VUE.JS DEVELOPERS -->
  <HireDevelopers />

  <!-- VUE.JS MEETUP -->
  <VueMeetup />

  <!-- FOOTER -->
  <Footer />


</v-container>
</template>

<script>
import Appbar from "../components/Home/Appbar";
import Footer from "../components/Home/Footer";
import Header from "../components/About/Header";
import Team from "../components/About/Team";
import Benifits from "../components/About/Benifits";
import HireDevelopers from "../components/About/HireDevelopers";
import VueMeetup from "../components/About/VueMeetup";

export default {
    name: 'About',
  components: {
        Appbar,
        Footer,
        Header,
        Team,
        Benifits,
        HireDevelopers,
        VueMeetup
  }

}
</script>

<style>

</style>