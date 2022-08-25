<template>
  <div class="container">
   <img class="shape" src="../assets/img/artist-shape-02.png" alt="">
   <img class="dots" src="../assets/img/artist-shape-03.png" alt="">
   <img class="square" src="../assets/img/artist-hero-image-02.jpg" alt="">
   <img class="ape" src="../assets/img/artist-hero-image-01.jpg" alt="">
   <img class="hero" src="../assets/img/artist-hero-image-03.png" alt="">
   <img class="shap" src="../assets/img/artist-shape-01.png" alt="">
   <h2  class="hello">helo,Im Matin </h2>
   <h3 class="pres">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et magnam dist</h3>
   <button>get started today</button>
   <img class="leaf" src="../assets/img/artist-shape-04.png" alt="">
   <img class="stain" src="../assets/img/artist-shape-05.png" alt="">
   <img class="boy" src="../assets/img/artist-hero-image-04.jpg" alt="">
  </div>
</template>

<script>


export default {
  name: "MainJumbotron",
  data() {
  },

};
  

</script>

<style lang="scss">
 .container{
  margin: 0 -10px;
  max-width: 1400px;
  background-color: #FBF9F6;
  height: 31.25rem;
  position: relative;
 }
 .shape {
    width: 50%;
    height: 21.25rem;
 }
 .dots{
     width: 20%;
    height: 22.813rem;
    position: absolute;
    top: 5rem;
    left: 0;
 }
.square{
       width: 18%;
    height: 18.75rem;
    position: relative;
    top: 0.313rem;
    right: 29.063rem;
}
.ape{
     width: 12%;
    height: 9.375rem;
    position: relative;
    top: 6.875rem;
    right: 52.875rem;
    }
    .hero{
    width: 16%;
    height: 15.625rem;
    position: relative;
    top: 10.625rem;
    right: 47.5rem;
    }
    .shap{
    width: 37%;
    height: 23.438rem;
    position: absolute;
    bottom: 7.813rem;
    right: 7.813rem;
    }
    .leaf{
    
    position: absolute;
    bottom: 15.938rem;
    right: 8.313rem;
    height: 14.063rem;
    
    }
    .boy{
    position: absolute;
    bottom: 4.938rem;
    right: 11.25rem;
    height: 16.875rem;
    
    }
   .stain{
     position: absolute;
    bottom: 4.063rem;
    right: 1.25rem;
    }
   

    //central text
    .hello{
    position: absolute;
    bottom: 16.75rem;
    left: 38.75rem;
    }
    .pres{
    text-align: center;
    position: absolute;
    bottom: 13.125rem;
    width: 21rem;
    left: 32.5rem;
      }
      button{
    position: absolute;
    text-align: center;
    bottom: 8.75rem;
    width: 9rem;
    left: 37.5rem ;

      }
      
 </style>