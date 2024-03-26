<template>

  <div class="homePage">
    <h1 class="display-2" id="typewriter">
      I am an aspiring <span id="mainTitle"> Full-stack Dev </span>
           <span id="name"></span>
    </h1>
  </div>
</template>

<script>
export default {
  name: 'homePage',
  mounted() {
    this.typeWriter('name', 'Thimna Alam');
    this.typeMainTitle();
  },
  methods: {
    typeWriter(targetId, text, speed = 100) {
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
    typeMainTitle() {
      const mainTitleElement = document.getElementById('mainTitle');
      const titles = ['Full-stack Dev', 'Graphic Designer', 'Radio Producer'];
      let currentIndex = 0;
      setInterval(() => {
        mainTitleElement.textContent = titles[currentIndex];
        currentIndex = (currentIndex + 1) % titles.length;
      }, 2000);
    },
  },
};
</script>

<style scoped>
h1{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

  
</style>

