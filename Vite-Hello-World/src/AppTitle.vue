<script>
  import AppHero from "./components/AppHero.vue";
  export default {
    data() {
      return {
        title: 'Vite Hello World',
      }
    },

    components: {
      AppHero,
    }
  }
</script>

<template>
  <body>
    
    <h1>{{ this.title }}</h1>

    <AppHero></AppHero>
    
  </body>
</template>

<style>

body {
  background-color:antiquewhite;
}

h1 {
  text-align: center;
  color: #36255b;
  margin-top: 4rem;
  font-size: 3rem;
}

</style>
