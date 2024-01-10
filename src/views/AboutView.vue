<template>
  <div class="about">
    <h1 class="display-2" id="heading">About</h1>

    <!-- Using flex container for layout -->
    <div class="flex-container">
      <!-- Image on the left -->
      <div class="image-container">
        <img class="img-fluid" loading="lazy" src="../assets/profileDemo.jpg" alt="Your Image">
      </div>

      <!-- Paragraphs on the right -->
      <div class="paragraph-container">
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

<script>
export default {
  name: 'AboutPage',
};
</script>
