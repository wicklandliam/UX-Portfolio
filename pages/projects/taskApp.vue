<script lang="ts">
import {defineComponent} from 'vue'
import Fancybox from "~/components/Fancybox.vue";
export default defineComponent({
  name: "taskApp",
  components: {Fancybox}
})
</script>

<template>
  <div>
      <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
        <h1 class="text-2xl">Task App</h1>
        <h3>CSCI 443: User Interface Design</h3>
        <h3>Aug-Dec, 2024</h3>
        <h2 class="text-xl py-4">The Problem</h2>
        <p class="py-2">
          The task app aims to solve the challenges faced by college students and young professionals in transitioning
          to higher workloads by providing tools for efficient organization, task management, and collaboration. It
          seeks to empower users to reduce stress, improve productivity, and achieve a healthy work-life balance.
        </p>
        <h2 class="text-xl py-4">Tools Used</h2>
        <p>
          To create the Task App, I used the UX design process, Empathy Maps, Google Forms, Persona Maps, a Business
          Model Canvas, Walt Disney's Creative Strategy Map, Notability, and Figma.
        </p>
        <h2 class="text-xl py-4">Discovery / Process</h2>
        <h3 class="text-lg py-2">Stage 1</h3>
        <p class="py-2">
          Stage 1 of the project included defining the problem I was trying to solve, and conducting user research to
          determine my target demographic.  From my research, I found my my target demographic to be undergraduate
          college students between the ages of 18-24, with a gender distribution of 42.7% male, and 57.3% female.  I
          found interview participants which ended up being 2 Males, 3 Females between ages 20-27.  While this did not
          meet my target demographic exactly, I was able to get a good idea of what my target demographic would want in
          a task app. I created empathy maps for each interviewee, and sent out a survey with similar questions out to
          more people to gather more data. Stage 1 gave me a level of insight that I didn't have before and helped me
          figure out how to move forward throughout the project.
        </p>
        <h3 class="text-lg py-2">Stage 2</h3>
        <p class="py-2">
          Stage 2 involved honing in more on what we'd do in Stages 3 & 4.  This stage involved creating a persona map
          from the empathy maps in Stage 1.  Additionally, I created a Business Model.  This stage allowed me to see the
          project from a larger perspective and figure out who I was designing for and what I was designing.
        </p>
        <h3 class="text-lg py-2">Stage 3</h3>
        <p class="py-2">
          In this stage, I utilized Walt Disney's Creative Strategy to come up with ideas for the Task App.  The dreamer
          Phase allowed me to come up with whatever ideas I wanted, regardless of real world constraints.  The Realist
          Phase was similar, but I had to think about how I could actually implement these ideas.  The Critic Phase was
          where I had to think about what could go wrong with the ideas I had come up with.  This stage was harder than
          the other two, as I felt as if it overlapped too much with the Realist phase, but it was still a good exercise
          to go through.  This stage allowed me to come up with a lot of ideas that I wouldn't have thought of otherwise.
        </p>
        <h3 class="text-lg py-2">Stage 4</h3>
        <p class="pb-4 pt-2">
          In this stage, I used Figma to create a prototype of the Task App. I used the ideas from Stage 3, and did my
          best to implement what I could in a reasonable amount of time. I used Figma for the first time, learning to
          build components and variants and use them to create a real design.  This stage was the most fun for me, as I
          got to learn a new tool and while it wasn't perfect, it was a good prototype that could be used for a real
          product in the future.
        </p>
        <a
            class="p-2 bg-blue-600 hover:bg-blue-500 text-white rounded-lg"
            href="https://www.figma.com/proto/afhe27XGJ2SMBoImiFZG14/UI%2FUX?node-id=0-1&t=oISF32dCNvT5EzOz-1"
            target="_blank">
          Figma Prototype
        </a>
        <h2 class="text-xl py-4">Results</h2>
        <p class="py-2 pb-4">
          The Task App is still not complete, as stage 5 still remains.  However, the prototype is a good start and
          I think the Task App has the potential to become a real project, with a rename at the very least.  I think
          the Task App could be a great tool for college students and young professionals, and I hope to continue
          working on it in the future.
        </p>
        <a class="p-2 bg-blue-600 hover:bg-blue-500 text-white rounded-lg"
           href="https://new.express.adobe.com/webpage/zrdn4mkp2CoH7"
          target="_blank">
          Adobe Express Link</a>
      </div>
  </div>
</template>

<style scoped>

</style>

<style scoped>

</style>