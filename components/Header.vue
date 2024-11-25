<template>
  <div class="w-full h-fit p-3 bg-white flex drop-shadow">
    <h1 class="text-xl px-3">Liam Wickland</h1>
    <nav>
      <ul class="inline align-middle">
        <li class="inline mx-2">
          <NuxtLink to="/" active-class="text-blue-600" class="text-black hover:text-blue-500">Home</NuxtLink>
        </li>
        <li class="inline mx-2">
          <NuxtLink to="/skills" active-class="text-blue-600" class="text-black hover:text-blue-500">Skills</NuxtLink>
        </li>
        <li class="inline mx-2">
          <NuxtLink to="/projects" active-class="text-blue-600" class="text-black hover:text-blue-500">Projects</NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script setup lang="ts">
</script>