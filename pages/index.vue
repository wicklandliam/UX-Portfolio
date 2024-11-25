<template>
  <div class="flex m-4 bg-white p-8 rounded-lg drop-shadow">
    <div class="justify-items-center w-1/4">
      <div>
      <img class="rounded-full w-full" src="/assets/images/Liam%20Wickland%20LinkedIn.jpeg" alt="Picture of Liam Wickland">
      <h2 class="text-3xl py-2 text-center">About Me</h2>
      <div class="w-full">

          <div class="flex pb-3">
            <a class="ml-auto px-2" href="https://github.com/wicklandliam">
              <img class="w-8" src="/assets/images/github.png" alt="">
            </a>
            <a class="mr-auto px-2" href="https://www.linkedin.com/in/liam-wickland/">
              <img class="w-8" src="/assets/images/linkedin.png" alt="">
            </a>
          </div>
          <div class="flex">
            <a class="bg-blue-600 hover:bg-blue-500 text-white text-lg py-1 px-3 rounded-lg mx-auto" data-fancybox="gallery" href="/Liam%20Wickland%20Resume.pdf">Resume</a>
          </div>
      </div>
    </div>
    </div>
    <div class="ml-8 w-3/4 flex">
      <ul class="my-auto">
        <li class="pb-3">
          <h3 class="text-2xl font-medium">&#x1F60E Who am I?</h3>
          <p>
            I am a senior at Montana State University, pursuing a bachelor's degree in Computer Science.  Expected graduation Spring of 2025!
          </p>
          <h3 class="text-lg font-bold"></h3>
        </li>
        <li class="py-3">
          <h3 class="text-2xl font-medium">&#x1F4BC Work</h3>
          <p>Software Engineering Intern for Web & Digital Communications @ Montana State University.
          I do both frontend and backend development, working primarily with Node.js in frameworks like Vue, Nuxt, and Next.js.</p>
          <h3 class="text-lg font-bold"></h3>
        </li>
        <li class="py-3">
          <h3 class="text-2xl font-medium">&#x1F699 Hobbies</h3>
          <p>I love working on cars, tinkering with computers, skiing, and building projects in the garage.</p>
          <h3 class="text-lg font-bold"></h3>
        </li>
      </ul>
    </div>
  </div>
</template>
<script setup lang="ts">
</script>