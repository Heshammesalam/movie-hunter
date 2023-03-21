<template>
  <div>
   
  <popular-movies/>
  </div>
</template>

<script>
// @ is an alias to /src

import PopularMovies from '../components/PopularMovies.vue'

export default {
  name: 'HomeView',
  components: {
    
    PopularMovies
  }
}
</script>
