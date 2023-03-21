<template>
  <div>
    <h2 class="my-5 text-yellow-500 text-lg font-semibold">Popular Movies</h2>
    <div class="grid grid-cols-1 sm:grid-cols-3 md:grid-cols-4">
        <movie-items/>
        <movie-items/>
        <movie-items/>
        <movie-items/>
    </div>
  </div>
</template>

<script>
import MovieItems from './items/MovieItems.vue';
export default {
  components: { MovieItems },};
</script>

<style lang="scss" scoped>
</style>