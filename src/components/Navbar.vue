<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary custom-navbar">
   <div class="container-fluid">
    <RouterLink to="/">
     <img class="img-fluid" loading="lazy" src="../assets/TA.png" alt="logo">
    </RouterLink>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
       <ul class="navbar-nav me-auto mb-2 mb-lg-0">
         <li class="nav-item">
           <RouterLink to="/" class="nav-link active">
             Home
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/about" class="nav-link active">
                 About
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/resume" class="nav-link active">
                 Resume
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/project" class="nav-link active">
                 Projects
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/testimonials" class="nav-link active">
                 Testimonials
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/contact" class="nav-link active">
                 Contact
           </RouterLink>
         </li>
       </ul>  
     </div>
   </div>
 </nav> <div>
 
     </div>
 </template>
 
 <script>
     export default {
         name:'NavBarComp',
     }
 </script>
 
 <style scoped>
 
 </style>