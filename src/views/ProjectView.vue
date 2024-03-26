<template>
  <div class="container" id="Bproj">
    <h2 class="display-2" id="heading">Projects</h2>
    <div class="row grid gap-3" id="rows">
      <div v-for="(project, index) in projects" :key="index" class="p-2 g-col-6 card w-25" :class="{ 'slide-from-left': index % 2 === 0, 'slide-from-right': index % 2 !== 0 }">
        <div class="card-body">
          <img :src="project.image" class="card-img-top" :alt="project.title">
          <h5 class="card-title text-dark">{{ project.title }}</h5>
          <a :href="project.github" class="btn btn-outline-dark" target="_blank">GitHub</a>
          <a :href="project.netlify" class="btn btn-outline-dark" target="_blank">Netlify</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          title: "Node_EOMP",
          image: "https://i.ibb.co/84LHFpN/T-J-2.png",
          github: "https://github.com/niyaazdaniels/NODE_EOMP.git",
          netlify: "https://nodeeomp-7c094.web.app"
        },
        {
          title: "Khanyle's ecommerce",
          image: "https://i.ibb.co/Jr5jJgP/download-12.jpg",
          github: "https://github.com/thimnaalam/Khanyile.js.git",
          netlify: "https://khanyiles.netlify.app/"
        },
        {
          title: "Bootstrap Portfolio",
          image: "https://i.ibb.co/TMMjCmc/1000-F-474835440-XYky-AZj-LECO54-WGb-BDAu3-Ar9-Bm23kh9-Q.jpg",
          github: "https://github.com/thimnaalam/BootstrapProject.git",
          netlify: "https://bootstrapthimna.netlify.app/"
        },
        {
          title: "Calculator",
          image: "https://i.ibb.co/nB4mJP0/download-4.png",
          github: "https://github.com/thimnaalam/projectCalculator.git"
        },
        {
          title: "Keyboard",
          image: "https://i.ibb.co/GT5XJ48/5fd7cf7f78a5740019a15561.webp"
        },
        {
          title: "MobiCare",
          image: "https://i.ibb.co/B6LX3Vq/download-5.png",
          github: "https://github.com/thimnaalam/MobiCare_week1.git"
        }
      ]
    };
  }
};
</script>

<style scoped>
.card {
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
  height: 300px;
  width: 300px;
}
img{
  height: 200px;
}
.btn {
  background-color: gray;
  border-color: white;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.slide-from-left {
  animation: slideFromLeft 1s ease-in-out;
}

.slide-from-right {
  animation: slideFromRight 1s ease-in-out;
}

@keyframes slideFromLeft {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(0);
  }
}
</style>
