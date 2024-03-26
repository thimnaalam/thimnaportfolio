<template>
  <div class="about">
    <h1 class="display-2" id="heading">About</h1>

   
    <div class="flex-container">
    
      <div class="image-container">
        <img class="img-fluid" loading="lazy" src="../assets/thimna.jpg" alt="Your Image">
      </div>
      <div class="para-container text-black">
        <p>Reside: Cape Town - Khayelitsha</p>
        <p>Born: 16/10/2002</p>
        <p>Hobbies:</p>
        <p>Reading</p>
        <p>Exercise</p>
        <p>Gardening</p>
        <p>Graphic design</p>
      </div>

      <a href="/path/to/your/cv.pdf" download="your_cv_name.pdf" class="btn btn-primary">Download CV</a>

      <div class="paragraph-container text-black">
        <p class="container t">
          My name is Thimna Alam born and raised in Cape Town. I obtained my matric certificate at the Centre Of Science And Technology in 2020. During that period, I was also part of the Children's Radio Foundation doing a radio production course. In 2019, I also took part in a coding and robotics bootcamp at UCT under Code Space. After that, I went to False Bay college and did nated electrical engineering but I did not finish.
        </p>
        <p class="container">
          After high school, I went to work part-time at Khanyile's Bakery at that time it was still opening. I did everything from baking to cashiering, which is where I am currently working at on weekends as an administrator. In 2023 January to June, I worked at Alpha Konnect as a lead generator - outbound calls and now I am currently a student at Life Choices Academy doing a course in web development.
        </p>
      </div>
    </div>
  </div>
</template>
<div></div>
<script>
export default {
  name: 'AboutPage',
};
</script>

<style scoped>
h1{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
p{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: large;
}
.paragraph-container{
  width: 500px;
  position: absolute;
  left: 63%;
  top:40%;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}
img{
  margin-left: 18%;
margin-top: 30%;
box-shadow: 20px 7px 40px rgba(0, 0, 0, 0.1);
}
.para-container{
  position: absolute;
  left:45%;
  top:60%;
  font-size: 20px;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
 
}
.btn{
  position: absolute;
  left:50%;
  top:800px;
  background-color: gray;
  border-color: #b77004;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}
</style>
