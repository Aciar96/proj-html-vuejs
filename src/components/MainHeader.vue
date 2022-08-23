<template>
  <header >
    <img src="../assets/img/dark-logo.png" alt="logo">
    <ul>
        <li>home</li>
        <li>pages</li>
        <li>courses</li>
        <li>features</li>
        <li>blog</li>
        <li>shop</li>
    </ul>
    <ul>
      <li><font-awesome-icon icon="fa-brands fa-twitter" /></li>
      <li><i class="fa-brands fa-facebook-f"></i></li>
      <li></li>
      <li></li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "MainHeader"
  }
</script>

<style lang="scss" >
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
} 
img{
  height: 50px;
    width: 150px;
   
}
ul{
  display: flex;
}
li{
 list-style-type: none;
 padding:  1rem; 
}
</style>