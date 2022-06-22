<!-- Please remove this file from your project -->
<template>
  <div class="container">
  <p>Joke of the day!</p>
   <template>
    <div>
      <!-- add random joke with styling-->
    </div>
  </template>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  align-content: center;
}
</style>
<script>
export default {
  name: 'NuxtTutorial',
  head () {
    return {
      title: 'Welcome! This page is dedicated to Dad Jokes',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'App built with Nuxt.JS, Vue and the Dad Jokes API'
        }
      ]
    }
  }
}
</script>
