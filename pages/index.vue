<template>
  <div class="relative">
    <div class="hero-background">
    </div>
    <div class="">
      <NavBar />
      <HomeSearch />
    </div>
  </div>
</template>

<script>
export default {}
</script>
<style scoped>
  .hero-background {
    animation: fadeInFadeOut 60s infinite;
    animation-timing-function: ease-in-out;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position:absolute;
    z-index:-1;
    width:100%;
    height:100vh;
    opacity: 0;
    transition-property:opacity;
    transition-duration:.2s;
  }
  @keyframes fadeInFadeOut {
    0% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/bb5958e41c91bb37f4afe2a318b71599-1599344049984/bg-hero-1-1792-x2.png');
      opacity:1;
    }
    20% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/2413b8415dda9dbd7756d02cb87cd4b1-1599595203021/bg-hero-2-1792-x2.png');
      opacity:1;
    }
    40% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/d14871e2d118f46db2c18ad882619ea8-1599835783974/bg-hero-3-1792-x2.png');
      opacity:1;
    }
    60% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/93085acc959671e9e9e77f3ca8147f82-1599427734106/bg-hero-4-1792-x2.png');
      opacity:1;
    }
    80% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/bb5958e41c91bb37f4afe2a318b71599-1599344049977/bg-hero-5-1792-x2.png');
      opacity:1;
    }
    100% {
      background-image: url('https://fiverr-res.cloudinary.com/image/upload/q_auto,f_auto/v1/attachments/generic_asset/asset/bb5958e41c91bb37f4afe2a318b71599-1599344049984/bg-hero-1-1792-x2.png');
      opacity:1;
    }
  }

  /* .hero-background:before {
    content:"";
    position:absolute;
    top:0;
    bottom:0;
    left:0;
    right:0;
    background-color:black;
    opacity:0.3;
  } */
</style>
