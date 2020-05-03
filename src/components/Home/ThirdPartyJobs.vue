<template>
  
    <v-row justify="center" class="mt-12">
        <v-col md="8">
            <img class="mb-n2" src="https://img.icons8.com/color/34/000000/search.png"/>
            <span class="headline font-weight-medium">Try our third party job search</span>
            <span  class="d-block font-weight-regular mt-5 mb-2 subtitle-1">Still did not find a job matching your needs? We are partnering with some of the most important job search engines to help you find the right position. Use the form below to filter through hundreds of Vue.js related openings:</span>
            <v-row>
                <v-col md="12">
                    <v-row align="center" class="bg">
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
                        <v-col md="1">
                            <span class="job-title text-uppercase blue-grey lighten-4 px-3 py-3 br-a">Ft</span>
                        </v-col>
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
                        <v-col md="1">
                            <span class="job-title text-uppercase blue-grey lighten-4 px-3 py-3 br-a">Ft</span>
                        </v-col>
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
</template>

<script>
export default {

}
</script>

<style>

</style>