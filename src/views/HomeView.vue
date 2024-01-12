<template>
  <div class="homePage">
   
   
    <h1 class="display-2" id="typewriter">
      I am an aspiring Full-stack Dev
      <span id="name"></span>
    </h1>
  
</div>

  </template>
<script>

export default {
  name: 'homePage',
  mounted(){
    this.typeWriter('name', 'Thimna Alam');
  },
  methods:{
    typeWriter(targetId, text, speed =100){
      const targetElement = document.getElementById(targetId);
  if (targetElement) {
    let i = 0;
    const typeWriterInterval = setInterval(() => {
      if (i < text.length) {
        targetElement.innerHTML += text.charAt(i);
        i++;
      } else {
        clearInterval(typeWriterInterval);
      }
    }, speed);
  }
},
},

    }
  

</script>
