<template>
  <v-app>

    <v-container fluid class="container-bg">
<v-app-bar color="rgba(255, 0, 0, 0)" flat>
 <v-row>

   <v-col cols="2">
   <span class="px-4 logo-text">Logo Here</span>
   </v-col>
   <v-col cols="6">
   <span class="px-4 white--text subtitle-1">Hire Developers</span>
   <span class="px-4 white--text subtitle-1">Developer Profile</span>
  <span class="px-4 white--text subtitle-1">About</span>
  <span class="px-4 white--text subtitle-1">Pricing</span>
   </v-col>

   <v-col cols="3" offset="1">
  <span class=" pa-2 mr-2 white--text subtitle-1 outlined ">POST A JOB</span>
  <span class="px-4 white--text subtitle-1">Login</span>
  <span class="pl-4 white--text subtitle-1">Register</span>

   </v-col>

 </v-row>
  
</v-app-bar>

      <v-row class="mt-12">
        <v-col cols="12" class="mt-10 text-center white--text">
          <span class="main-heading d-block white--text mb-3">Hire expert <span class="font-weight-medium"> Vue.js developers</span> & <span class="font-weight-medium">find Vue.js jobs</span></span>
          <span class="secondary-text white--text d-block">Sign up and <span class="tab tab4 mx-1"> Post a job </span>or create your <span class="tab tab4">Developer profile.</span><br/> <span class="mt-1 d-block"> We will find offers / candidates for you!</span></span>
        </v-col>
      </v-row>
      <v-row class="text-center mb-12">
        <v-col class="mb-12">
          <v-btn width="259" height="42" class="btn white--text text-capitalize font-weight-regular mr-5" color="#536eec">Create a Developer Profile</v-btn>
          <v-btn width="181" height="42" class="btn white--text text-capitalize font-weight-regular " color="#42b983">Post a Vue.js Job</v-btn>

        </v-col>
      </v-row>
     
    </v-container>
<template>

    <v-tabs
    width="70%" class="mid mt-n12 "
      v-model="tab"
      centered
      dark      
      background-color="rgba(255, 0, 0, 0)"
    >
      <v-tab
        v-for="item in items"
        :key="item.tab"
        ripple
        class="text-capitalize tab2"
        active-class="tab"
        
      >
        {{ item.tab }}
      </v-tab>
    </v-tabs>

    <v-tabs-items v-model="tab">
      <v-tab-item
        v-for="item in items"
        :key="item.tab"
        
      >
        <v-row  class="bg" justify="center">
          <v-col md="8">
           <v-row class="section-yellow  pl-2 py-1  my-8">
            <v-col cols="1"><img width="42" height="10" src="./assets/joblogo.png" alt=""></v-col>
            <v-col cols="11 ">
              <span class="job-title">Senior JavaScript Developer (Nuxt & Node)</span>
              <span class="job-category font-weight-regular badge">Full-time</span>
              <span class="d-block job-category">at <span class="font-weight-bold">Nacelle</span> - <span>Remote</span></span>
              <span class="job-category">Senior Javascript Developer (Vue) - UNITED STATES ONLY Who We Are Nacelle is an eCommerce Web Service for JAMStack developers. By taking care of complex back-end infrastructure, we...</span>
            </v-col>
          </v-row>
         
          <v-row class="section-white  pl-2 py-1  my-8 ">
            <v-col cols="1"><img width="42" height="10" src="./assets/joblogo.png" alt=""></v-col>
            <v-col cols="11 ">
              <span class="job-title">Senior JavaScript Developer (Nuxt & Node)</span>
              <span class="job-category font-weight-regular badge">Full-time</span>
              <span class="d-block job-category">at <span class="font-weight-bold">Nacelle</span> - <span>Remote</span></span>
              <span class="job-category">Senior Javascript Developer (Vue) - UNITED STATES ONLY Who We Are Nacelle is an eCommerce Web Service for JAMStack developers. By taking care of complex back-end infrastructure, we...</span>
            </v-col>
          </v-row>          
        </v-col>
        </v-row>

        <v-row justify="center">
            <v-col md="8" class="paddding-0">
              <v-icon class="font-weight-bold black--text mb-1 pb-1">search</v-icon>
              <span class="headline font-weight-medium">Try our third party job search</span>
              <span  class="d-block font-weight-regular my-2 subtitle-1">Still did not find a job matching your needs? We are partnering with some of the most important job search engines to help you find the right position. Use the form below to filter through hundreds of Vue.js related openings:</span>
              <v-row>
                <v-col md="12">
                  <v-row align="center">
                    <v-col md="5">
                      <span class="subtitle-1 d-block">Keywords</span>
                      <v-text-field dense outlined color="blue" placeholder="Freelance, node..."></v-text-field>
                    </v-col>
                    <v-col md="5">
                      <span class="subtitle-1 d-block" >Location</span>
                      <v-text-field dense outlined color="blue" placeholder="UK, USA, Canada..."></v-text-field>
                    </v-col>
                    <v-col md="2">
                      <v-btn color="#F5315C" dark class="text-capitalize btn font-weight-regular">Search</v-btn>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>

                <v-row justify="center">
                  <v-col md="12">
                    
                    <v-row align="center">
                    <v-col md="1"><span class="job-title text-uppercase blue-grey lighten-4 px-3 py-3 br-a">Ft</span></v-col>
                    <v-col md="11">
                      <v-row>
                        <v-col md="10">
                          <span class="job-title py-1">Senior Front-End Engineer (JavaScript, Vue.js, Vuex)</span>
                          <span class="d-block job-category">at <span class="font-weight-bold">Fin-Tech Startup </span> - <span>Manhattan, NY</span></span>
                        </v-col>
                        <v-col md="2">
                          <span class="job-category text--secondary d-block mt-4">1 week ago</span>
                        </v-col>
                      </v-row>
                    </v-col>
                  </v-row>
            
                  <v-divider light></v-divider>
                  
                    <v-row align="center">
                    <v-col md="1"><span class="job-title text-uppercase blue-grey lighten-4 px-3 py-3 br-a">Ft</span></v-col>
                    <v-col md="11">
                      <v-row>
                        <v-col md="10">
                          <span class="job-title py-1">Senior Front-End Engineer (JavaScript, Vue.js, Vuex)</span>
                          <span class="d-block job-category">at <span class="font-weight-bold">Fin-Tech Startup </span> - <span>Manhattan, NY</span></span>
                        </v-col>
                        <v-col md="2">
                          <span class="job-category text--secondary d-block mt-4">1 week ago</span>
                        </v-col>
                      </v-row>
                    </v-col>
                  </v-row>
            
                  <v-divider light></v-divider>

                  

            </v-col>
          </v-row>


                  </v-col>
                </v-row>
      </v-tab-item>
    </v-tabs-items>
</template>




  </v-app>
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
style <style lang="less">
@import "less/global.less";

.logo-text{

  font-family: "Open Sans", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 24px;
  line-height: 18.4px;
  letter-spacing: normal;
  font-weight: bold;
  color: aqua;
}

.btn{

  font-size: 16px !important;
  line-height: 24px;
  text-align: center;
  letter-spacing: normal;
  color: #ffffff;
}

.outlined{
  border:1px solid white;
  border-radius: 5px;
}

.main-heading{
  font-size: 2.25rem;
    font-weight: 300;
    

}

.secondary-text{

  font-size: 1.25rem;
    font-weight: 400;
}

.btn-profile{

  background-color: #536eec;

}

.container-bg{
  background:url('./assets/header.jpg');
  background-size: cover;
  font-family: "Open Sans", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";

}

.mid
{
  margin: 0 auto;
}

.tab{

  background-color: white;
  color: black !important;
  
}

.theme--dark.v-tabs > .v-tabs-bar .v-tab:not(.v-tab--active){
  color: white !important;
}

.tab4{
  border-radius: 5px;
  padding: 5px;
}

.section-yellow{
  background-color: #fff4d3;
  border: 1px solid #ffe7a0;
  border-radius: 5px;
  position: relative;
}

.section-white{
  background-color:white;
  border: 1px solid #eef0f1;
  border-radius: 5px;
  position: relative;
}

.job-title{
    font-size: 18px;
    font-weight: 600 !important;
    line-height: 27px;
    color: #34495e;
}

.job-category{
font-size: 14px;
line-height: 22px;
font-weight: 400;
color: #34495e;
}

.badge{

    background: rgba(255, 193, 7, 0.5);
    position: absolute;
    top: 0;
    font-size: 0.875rem;
    right: 0;
    padding: 3px 10px;
    border-bottom-left-radius: 4px;
    border-top-right-radius: 4px;
    }

  .bg{
      background-color: #fafafa;
  }

  .br-a{

    border-radius: 3px;
  }
</style>
