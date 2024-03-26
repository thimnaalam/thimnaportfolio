<template>
    <nav class="container-fluid navbar navbar-expand-lg custom-navbar ">
   <div class="container-fluid">
    <RouterLink to="/">
     <img class="img-fluid" loading="lazy" src="../assets/TA.png" alt="logo">
    </RouterLink>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
       <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
         <li class="nav-item">
           <RouterLink to="/" class="nav-link  text-white">
             Home
           </RouterLink>
         </li>
         <li class="nav-item">
           <RouterLink to="/about" class="nav-link  text-white">
           About
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/resume" class="nav-link  text-white">
                 Resume
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/project" class="nav-link  text-white">
                 Projects
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/testimonials" class="nav-link  text-white">
                 Testimonials
           </RouterLink>
         </li>
         <li class="nav-item">
             <RouterLink to="/contact" class="nav-link active text-white">
                 Contact
           </RouterLink>
         </li>
       </ul>  
     </div>
   </div>
 </nav> 
 
 </template>
 
 <script>
     export default {
         name:'NavBarComp',
     }
 </script>
 
 <style scoped>
 .nav-item{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: large;
 }
 .nav-item:hover .nav-link,
  .nav-item:focus .nav-link,
  .nav-item:active .nav-link {
    color: #ffffff; 
    background-color: #b77004;
    border-radius: 30px;
  }

 </style>