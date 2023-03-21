<template>
  <div>
    <h2 class="font-semibold text-4xl my-10 ">Cast</h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3  lg:grid-cols-4">
       <div class="flex flex-col mb-10">
        <img src="@/assets/image/hollywood-highest-paid-actor-actress.webp" alt=""  class="w-80">
        <span  class="text-gray-500">Mark Wahlberg</span>
       </div>
       <div class="flex flex-col mb-10">
        <img src="@/assets/image/hollywood-highest-paid-actor-actress.webp" alt=""   class="w-80">
        <span  class="text-gray-500">Mark Wahlberg</span>
       </div>
       <div class="flex flex-col mb-10">
        <img src="@/assets/image/hollywood-highest-paid-actor-actress.webp" alt=""   class="w-80">
        <span  class="text-gray-500">Mark Wahlberg</span>
       </div>
       <div class="flex flex-col mb-10">
        <img src="@/assets/image/hollywood-highest-paid-actor-actress.webp" alt=""   class="w-80">
        <span  class="text-gray-500">Mark Wahlberg</span>
       </div>
       <div class="flex flex-col mb-10">
        <img src="@/assets/image/hollywood-highest-paid-actor-actress.webp" alt=""  class="w-80">
        <span  class="text-gray-500">Mark Wahlberg</span>
       </div>
      </div>
     
  </div>
</template>

<script>
export default {
  created(){
    console.log(process.env.ROOT_API)
  }
};
</script>

<style scoped></style>
