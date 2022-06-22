<template>
  <div>
    <h1>About the Site</h1>
    <p> Site was built on using nuxt.js and Vue. All jokes are taken from the <a href="https://icanhazdadjoke.com/api">Dad Jokes API</a>.</p>
  </div>
</template>
<script>
export default {
  head () {
    return {
      title: 'About This App',
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
