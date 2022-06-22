<template>
    <header class='header'>
        <h1 class='title'>Jokes</h1>
    <ul>
        <li>
            <nuxt-link to='/'>Home</nuxt-link>
        </li>
        <li>
            <nuxt-link to='/jokes/jokes-page'>Jokes</nuxt-link>
        </li>
        <li>
            <nuxt-link to='/about-app'>About This App</nuxt-link>
        </li>
    </ul>
    </header>
</template>

<script>
export default {
  data () {
    return {
      jokes: []
    }
  }
}
</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    border-bottom: 1px dotted #ccc;
}

.header .title {
    font-size: 3rem;
    color: #526488;
}

.header ul {
    display: flex;
    list-style-type: none;

}

.header a {
    display: inline-block;
    background: transparent;
    color: #526488;
    padding: 0.3rem 1rem;
    margin-right: 0.5rem;
}

</style>
