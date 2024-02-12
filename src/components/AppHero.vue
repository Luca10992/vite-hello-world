<script>
  export default {
    data() {
      return {
        img: '01.png'
      }
    },

    methods: {
      buildImagePath(imageName) {
        return new URL('../assets/img/' + imageName, import.meta.url).href;
      }
    }
  }

</script>

<template>

  <div class="container">
    <img :src="buildImagePath(img)" alt="Vue+Vite">
  </div>
  
</template>

<style>

.container {
  width: 75%;
  border-radius: 25px;
  overflow: hidden;
  margin: 0 auto;
  box-shadow: 0px 0px 5px 0px;
}

img {
  width: 100%;
}

</style>
