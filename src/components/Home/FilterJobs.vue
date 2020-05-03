<template>
  <v-container fluid class="pa-0">
        <v-tabs width="70%" class="mid mt-n12 " v-model="tab" centered dark background-color="rgba(255, 0, 0, 0)">
            <v-tab v-for="item in items" :key="item.tab" ripple class="text-capitalize tab2" active-class="tab">
                {{ item.tab }}
            </v-tab>
        </v-tabs>

        <v-tabs-items v-model="tab">
            <v-tab-item v-for="item in items" :key="item.tab">
            </v-tab-item>
        </v-tabs-items>

        <v-row  class="bg">
            <v-col md="7" offset-md="2">
                <v-row class="mt-2">
                    <v-col md="12">
                        <img src="https://img.icons8.com/material-two-tone/22/000000/search-in-list.png"/>
                        <span class="font-weight-medium headline px-2">Filter by</span>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col md="11">
                        <v-text-field dense outlined color="blue" placeholder="Keywords, Locations, Job type..."></v-text-field>
                    </v-col>
                    <v-col md="1">
                        <v-btn color="success" depressed height="40" dark class="text-capitalize btn font-weight-regular ml-n13">Search <img class="ml-1" src="https://img.icons8.com/ios/20/ffffff/search--v1.png"/></v-btn>
                    </v-col>
                </v-row>
        
                <v-row class="section-yellow  pl-2 py-1  mb-8">
                    <v-col cols="1">
                        <img width="42" height="10" src="../../assets/joblogo.png" alt="">
                    </v-col>
                    <v-col cols="11 ">
                        <span class="job-title">Senior JavaScript Developer (Nuxt & Node)</span>
                        <span class="job-category font-weight-regular badge">Full-time</span>
                        <span class="d-block job-category">at <span class="font-weight-bold">Nacelle</span> - <span>Remote</span></span>
                        <span class="job-category">Senior Javascript Developer (Vue) - UNITED STATES ONLY Who We Are Nacelle is an eCommerce Web Service for JAMStack developers. By taking care of complex back-end infrastructure, we...</span>
                    </v-col>
                </v-row>
                
                <v-row class="section-white  pl-2 py-1  my-8 ">
                    <v-col cols="1">
                        <img width="42" height="10" src="../../assets/joblogo.png" alt="">
                    </v-col>
                    <v-col cols="11 ">
                        <span class="job-title">Senior JavaScript Developer (Nuxt & Node)</span>
                        <span class="job-category font-weight-regular badge">Full-time</span>
                        <span class="d-block job-category">at <span class="font-weight-bold">Nacelle</span> - <span>Remote</span></span>
                        <span class="job-category">Senior Javascript Developer (Vue) - UNITED STATES ONLY Who We Are Nacelle is an eCommerce Web Service for JAMStack developers. By taking care of complex back-end infrastructure, we...</span>
                    </v-col>
                </v-row>          
            </v-col>
            <v-col md="2" >
                <a href=""><img class="card-pos ml-4 mt-6" width="120" height="175" src="../../assets/ad.jpg" alt=""></a>
            </v-col>

        </v-row>
  </v-container>
</template>

<script>
export default {
     data () {
      return {
        tab: null,
        items: [
          { tab: 'All Jobs', content: 'Tab 1 Content' },
          { tab: 'Full Time', content: 'Tab 2 Content' },
          { tab: 'Part Time', content: 'Tab 3 Content' },
          { tab: 'Freelance', content: 'Tab 4 Content' },
          { tab: 'Temporary', content: 'Tab 5 Content' },
          { tab: 'Internship', content: 'Tab 6 Content' },
          { tab: 'remote', content: 'Tab 7 Content' },
          
        ],
      }
    },

}
</script>

<style>

</style>