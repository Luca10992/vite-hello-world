<script>
  export default {
    data() {
      return {
        img: 'https://miro.medium.com/v2/resize:fit:1400/1*C8xdSMN_IkeXDsTLt6EACA.png'
      }
    }
  }

</script>

<template>

  <div class="container">
    <img :src="this.img" alt="Vue+Vite">
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
