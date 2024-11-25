<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
  name: "Projects"
})
</script>

<template>
  <div>
    <NuxtLink to="projects/taskApp">
      <div class="flex items-center m-4 bg-white hover:bg-gray-100 p-8 rounded-lg drop-shadow">
        <img class="w-36 rounded-xl" src="/assets/images/task%20app%20screenshot.png">
        <h2 class="p-10 text-2xl">Task App / CSCIUI/UX Project</h2>
        <p class="ml-auto">Aug-Dec 2024</p>
      </div>
    </NuxtLink>
    <NuxtLink to="projects/accessibilityScanner">
      <div class="flex items-center m-4 bg-white hover:bg-gray-100 p-8 rounded-lg drop-shadow">
        <img class="w-36 rounded-xl" src="/assets/images/MSU.png">
        <h2 class="p-10 text-2xl">Accessibility Scanner</h2>
        <p class="ml-auto">Jan-Apr 2024</p>
      </div>
    </NuxtLink>
  </div>
</template>

<style scoped>

</style>