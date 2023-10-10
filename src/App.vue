<script setup>
  import ButtonCounter from './components/ButtonCounter.vue'
 
</script>

<template>
     <div class="container mx-auto">
    <div class="flex items-center mt-5">
      <img class="logo" src="./assets/vue.svg" alt="Vue logo" />
      <h1 class="text-2xl">Vue Components</h1>
    </div>
    <div class="mt-10 p-10">
      <p class="mb-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis corporis mollitia fugit dolor quibusdam atque qui fuga laudantium aut porro.
      </p>
      
      <ButtonCounter/><br/><br/>
      <button-counter/><br/><br/>

    </div>
    
  </div>
    
</template>

<style scoped>

</style>