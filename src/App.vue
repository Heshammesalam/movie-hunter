<template>
  <div id="app" class="container mx-auto bg-gray-900 text-white">
    <div
      class="flex justify-between items-center mt-5 border-b border-gray-700 pb-5"
    >
      <NavBar />
      <SearchBar />
    </div>
    <router-view />
  </div>
</template>

<script>
import NavBar from "@/components/header/NavBar.vue";
import SearchBar from "@/components/header/SearchBar.vue";
export default {
  components: {
    NavBar,
    SearchBar,
  },
  created(){
   
    this.$axios.get('unicorns')
    .then(res =>{
      console.log(res.data)
    })
  }
};
</script>

<style>
</style>
