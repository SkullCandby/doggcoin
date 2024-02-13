<template>
    <div class="header-title">
      <h2 style="font-size: 1.6em; font-weight: bold; color: black;">DogeBaby</h2>
      <p style="font-weight: bold; font-size: 1.5em;"> BabyDoge is reborn on Solana </p>
      <div>
      <img :src="imagePath1" alt="Title Image" class="header-image">
      <img :src="imagePath2" alt="Title Image" class="header-image">
      <img :src="imagePath3" alt="Title Image" class="header-image">
    </div>
      <p style="font-weight: bold; color:black; font-size: 2em;"> CA: 52mE2VRk8qGmLFWmRABYvGHxMwDMCM4jnXpJPazCJ2fu</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeaderTitleSection',
    computed: {
      imagePath1() {
        // The require function will tell Webpack to process this image
        return require('@/assets/solana-sol-logo.png');
      },
      imagePath2() {
        // The require function will tell Webpack to process this image
        return require('@/assets/baby_doge.png');
      },
      imagePath3() {
        // The require function will tell Webpack to process this image
        return require('@/assets/solana-sol-logo.png');
      }
    }
  }
  </script>
  
  <style scoped>
 .header-title {
  background-color: #FFE971; /* Adjusted the comment to reflect the actual color */
  color: white;
  text-align: center;
  padding: 1rem 0;
}

.header-image {
  max-width: 20vw; /* 10% of the viewport's width */
  max-height: 20vw; /* 10% of the viewport's width to keep the aspect ratio */
  object-fit: cover;
  margin: 1vw; /* Adjusts margin based on the viewport's width */
}
  
  .title-content {
    display: inline-block;
    padding: 0.5rem 1rem;
    /* Additional styling to match your specific design requirements */
  }
  
  .title-content h1 {
    font-size: 2em; /* Adjust the size as needed */
    margin: 0.5rem 0;
  }
  
  .title-content p {
    font-size: 2.2em; /* Adjust the size as needed */
    margin: 0.5rem 0;
    color: pink;
  }
  </style>
  
