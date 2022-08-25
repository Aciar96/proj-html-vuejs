<template>
  <div>
    <MainHeader></MainHeader>
    <MainJumbotron></MainJumbotron>
    <TheMain></TheMain>
    <TheSection></TheSection>
    <VideoSection></VideoSection>
  </div>
</template>

<script>

import MainHeader from "./components/MainHeader.vue"
import MainJumbotron from "./components/MainJumbotron.vue";
import TheMain from "./components/TheMain.vue";
import  TheSection  from "./components/TheSection.vue"
import VideoSection from "./components/VideoSection.vue";

export default {
  name: "App",
  data() {
  },
  components: {
    MainHeader,
    MainJumbotron,
    TheMain,
    TheSection,
    VideoSection,
    
},
};
  

</script>

<style >
  
</style>
