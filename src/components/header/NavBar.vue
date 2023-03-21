<template>
    <div class="flex items-center">

      <img src="@/assets/image/Capture-removebg-preview.png" alt="" class="h-10 w-32 ">
      
      <ul class="flex">
        <li>
            <router-link to="/movies" class="mx-3">
                Movies  
            </router-link>
        </li>
        <li>
            <router-link to="/Actors" class="mx-3">
                Actors  
            </router-link>
        </li>
        <li>
            <router-link to="/Profile" class="mx-3">
                Profile  
            </router-link>
        </li>
      </ul>
      
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>