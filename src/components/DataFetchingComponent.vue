<script setup>
import {reactive, onBeforeMount, onMounted} from 'vue'
const apiResponse = reactive([])

onBeforeMount(() => {
  console.log('before mount')
  fetch('https://jsonplaceholder.typicode.com/todos/1')
    .then(response => response.json())
    .then(json => {
      apiResponse.push(json)
    })
})


onMounted(() => {
  console.log(apiResponse);
})

</script>

<template>

</template>   