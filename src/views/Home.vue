<template>
  <v-container class="pa-0" fluid>

    <Header />

    <FilterJobs />

    <ThirdPartyJobs />

    <JobsByLocation />

    <LookingForJob/>

    <PostAJob/>

    <Footer />

  </v-container>

</template>

<script>
// @ is an alias to /src
import Footer from "../components/Home/Footer";
import Header from "../components/Home/Header";
import FilterJobs from "../components/Home/FilterJobs";
import ThirdPartyJobs from "../components/Home/ThirdPartyJobs";
import JobsByLocation from "../components/Home/JobsByLocation";
import LookingForJob from "../components/Home/LookingForJob";
import PostAJob from "../components/Home/PostAJob"

export default {
  name: 'Home',
  components: {
        Footer,
        Header,
        FilterJobs,
        ThirdPartyJobs,
        JobsByLocation,
        LookingForJob,
        PostAJob
  }
}
</script>
