<template>
  <div class="joke">
      <p>{{ joke }}</p>
  </div>
</template>

<script>
export default {
  name: 'jokes-component',
  props: ['joke', 'id']
}
</script>

<style>
.joke {
    padding: 1rem;
    border:'1px dotted gray';
    margin: 1rem;
}

</style>
