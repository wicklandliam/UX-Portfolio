<script setup>
import {defineComponent} from 'vue'
import Fancybox from "~/components/Fancybox.vue";
</script>

<template>
  <Fancybox
      :options="{
            Carousel: {
              infinite: false,
            },
          }"
  >
  <div>
    <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
      <h2 class="pb-4 text-2xl">Languages</h2>
      <div class="flex flex-wrap">
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/node.png">
            <p class="w-fit mx-auto text-2xl py-2">Node.js</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/tailwind.png">
            <p class="w-fit mx-auto text-2xl py-2">Tailwind</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/java.png">
            <p class="w-fit mx-auto text-2xl py-2">Java</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/c.png">
            <p class="w-fit mx-auto text-2xl py-2">C/C++</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/python.png">
            <p class="w-fit mx-auto text-2xl py-2">Python</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/db.png">
            <p class="w-fit mx-auto text-2xl py-2">SQL</p>
          </div>
        </div>
      </div>
    </div>
    <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
      <h2 class="pb-4 text-2xl">Frameworks</h2>
      <div class="flex flex-wrap">
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img class="w-full p-4" src="/assets/images/vue.png">
            <p class="w-fit mx-auto text-2xl py-2">Vue.js</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img class="w-full p-3" src="/assets/images/nuxt.svg">
            <p class="w-fit mx-auto py-2 text-2xl">Nuxt.js</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img class="w-full p-4" src="/assets/images/nextjs.png">
            <p class="w-fit mx-auto text-2xl py-2">Next.js</p>
          </div>
        </div>
      </div>
    </div>
    <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
      <h2 class="pb-4 text-2xl">Tools</h2>
      <div class="flex flex-wrap">
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/netlify.png">
            <p class="w-fit mx-auto text-2xl py-2">Netlify</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/railway.png">
            <p class="w-fit mx-auto py-2 text-2xl">Railway</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/git.png">
            <p class="w-fit mx-auto text-2xl py-2">Git</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/bitbucket.png">
            <p class="w-fit mx-auto text-2xl py-2">Bitbucket</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/zendesk.png">
            <p class="w-fit mx-auto text-2xl py-2">Zendesk</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/jira.png">
            <p class="w-fit mx-auto text-2xl py-2">Jira</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/basecamp.png">
            <p class="w-fit mx-auto text-2xl py-2">Basecamp</p>
          </div>
        </div>
      </div>
    </div>
    <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
      <h2 class="pb-4 text-2xl">Databases</h2>
      <div class="flex flex-wrap">
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/postgres.png">
            <p class="w-fit mx-auto text-2xl py-2">Postgres</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/mongo.png">
            <p class="w-fit mx-auto py-2 text-2xl">MongoDB</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox class="w-full p-4 h-32 object-contain" src="/assets/images/redis.png">
            <p class="w-fit mx-auto text-2xl py-2">Redis</p>
          </div>
        </div>
        <div class="w-1/4 mx-auto py-2">
          <div class="bg-gray-100 mx-2 rounded-lg drop-shadow h-full">
            <img data-fancybox  class="w-full p-4 h-32 object-contain" src="/assets/images/mysql.png">
            <p class="w-fit mx-auto text-2xl py-2">MySQL</p>
          </div>
        </div>
      </div>
    </div>
      <p>Pssst.. any image can be clicked on for a better look.</p>
  </div>
  </Fancybox>
</template>

<style scoped>

</style>