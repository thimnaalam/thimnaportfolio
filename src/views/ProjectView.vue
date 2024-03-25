<template>
    <div class="container " id="Bproj">
<div class="row">
    <h2 class="display-2" id="heading">Projects</h2>
    <div class="row grid gap-3" id="rows">
  <div class="p-2 g-col-6 card w-25 ">
    <div class="card-body">
      <img src="../assets/T & J (2).png" class="card-img-top" alt="netflix">
      <h5 class="card-title text-dark ">Node_EOMP</h5>
      <a href="https://github.com/niyaazdaniels/NODE_EOMP.git" class="btn btn-outline-dark" target="_blank" >Github</a>
      <a href="https://nodeeomp-7c094.web.app" class="btn btn-outline-dark" target="_blank">Firebase</a>
    </div>
  </div>
  <div class=" p-2 g-col-6 card w-25 "> 
    <div class="card-body">
      <img src="../assets/download (12).jpg" class="card-img-top" alt="E.Commerce">
      <h5 class="card-title text-dark">Khanyle's ecommerce</h5>
      <a href=" https://github.com/thimnaalam/Khanyile.js.git" class="btn btn-outline-dark" target="_blank">GitHub</a>
      <a href="https://khanyiles.netlify.app/" class="btn btn-outline-dark" target="_blank">Netify</a>
    </div>
  </div>
  <div class=" p-2 g-col-6 card w-25 "> 
    <div class="card-body">
  <img src="../assets/bTA.jpg" class="card-img-top" alt="Keyboard">
  <h5 class="card-title text-dark">Bootstrap Portfolio</h5>
  <a href="https://github.com/thimnaalam/BootstrapProject.git" class="btn btn-outline-dark" target="_blank">GitHub</a>
  <a href="https://bootstrapthimna.netlify.app/" class="btn btn-outline-dark" target="_blank">Netify</a>
</div>
  </div>
</div>
<div class="row grid gap-3 pt-4 " id="rows">
  <div class="p-2   g-col-6 card w-25  ">
    <div class="card-body">
      <img src="../assets/calc.png" class="card-img-top" alt="Calculator">
      <h5 class="card-title text-dark">Calculator</h5>
      <a href="https://github.com/thimnaalam/projectCalculator.git" class="btn btn-outline-dark" target="_blank">Github</a>
      <a href="#" class="btn btn-outline-dark" target="_blank">Netify</a>
    </div>
  </div>
  <div class=" p-2 g-col-6 card w-25 "> 
    <div class="card-body">
      <img src="../assets/keyboard.webp" class="card-img-top" alt="Keyboard">
      <h5 class="card-title text-dark">Keyboard</h5>
      <a href="#" class="btn btn-outline-dark" target="_blank">GitHub</a>
      <a href="#" class="btn btn-outline-dark" target="_blank">Netify</a>
    </div>
</div>
<div class=" p-2 g-col-6 card w-25 "> 
  <div class="card-body">
      <img src="../assets/mobi.png" class="card-img-top" alt="MobiCare">
      <h5 class="card-title text-dark">MobiCare</h5>
      <a href="https://github.com/thimnaalam/MobiCare_week1.git" class="btn btn-outline-dark" target="_blank">GitHub</a>
      <a href="#" class="btn btn-outline-dark" target="_blank">Netify</a>
    </div>
</div>
</div>
    </div>
    </div>
    <div class="containerD">
    <div class="dots-container">
      <div v-for="(dot, index) in dots" :key="index" :style="{ animationDelay: index * delay + 'ms' }" class="dot"></div>
    </div>
  </div>
</template>

<script>
    export default {
  data() {
    return {
      dots: 50, // Number of dots
      delay: 100 // Delay between each dot animation
    };
  }
};
        
    
</script>

<style scoped>
.card{
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}
.btn{
  background-color: gray;
  border-color: white;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}
.containerD {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.dots-container {
  position: relative;
  width: 1000px; /* Adjust as needed */
  height: 200px; /* Adjust as needed */
}

.dot {
  position: absolute;
  width: 8px; /* Dot size */
  height: 8px; /* Dot size */
  border-radius: 50%; /* Make it round */
  background-color: #000; /* Dot color */
  animation: spiral 3s infinite ;
}

@keyframes spiral {
  0% {
    top: 0;
    left: 0;
  }
  100% {
    top: 100%;
    left: 100%;
  }
}
</style>