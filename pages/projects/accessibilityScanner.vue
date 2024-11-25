<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
  name: "accessibilityScanner",
})
</script>

<template>
  <div>
    <div class="m-4 bg-white p-8 rounded-lg drop-shadow">
      <h1 class="text-2xl">Accessibility Scanner</h1>
      <h3>Jan-Apr, 2024</h3>
      <h2 class="text-xl py-4">The Problem</h2>
        <p class="py-2">
          MSU's current accessibility scanner currently displays Accessibility Tasks that the user must complete:
        </p>
        <img class="py-2" data-fancybox src="/assets/images/AccessibilityScannerCurrent.png">
        <p class="py-2">
          The primary issue with the existing scanner is its high level of inaccuracy and time to complete a scan.
        </p>
      <h2 class="text-xl py-4">Tools Used</h2>
        <p>
          I worked with Node.js, Express.js, MongoDB, and Axios on the backend.
          On the frontend, Node.js and Vue.js were used, but is not a complete product at this time.
        </p>
      <h2 class="text-xl py-4">Discovery / Process</h2>
        <p class="py-2">
          The entire project started with the backend, building in incremental stages.  The first issue would be to grab all of the individual pages
          from a "site", typically categorized by department (Communications, College of Engineering, Physics, etc.).
          By generating and populating a mongoDB database with entries for each site and mapping these to unique ids,
          the ids could be used to hit the University CMS (Content Management System) API and pull a list of a site's
          pages down to be scanned and parsed.  By performing an HTTP GET request on each of those pages via fetch,
          we could parse through the HTTP of each page and build scanning functions that would flag when a certain
          pattern was found- for example, an image missing an "alt" tag.
        </p>
        <p class="py-2">
          After all of the errors were found for an entire site, the errors were fed back up, containing data like the
          XPath (pointing to exactly where the error was on the page), the type of accessibility error, etc.  This could
           also be done on a page-by-page basis.
        </p>
        <p class="py-2">
          After the basic scanning functions were complete, the task of checking broken links was the next at hand. To
          be honest, this part of the project was and still is the largest roadblock of this project.  To check for a
          broken link, the scanner would have to perform an HTTP GET request on every link on a page and check the
          response code.  If the response code was not good, the link was broken.  This was a very time-consuming process
          when scanning large sites, one of which has over 10,000 pages.  Some GET requests would take a long time to
          complete, or would hang up completely.  While improvements like memoization were possible, I could not get
          consistent results across all sites and would be catching lots of edge cases.  Because of this, the broken link
          scanner is not currently in the product.
        </p>
      <h2 class="text-xl py-4">Results</h2>
      <p>
        The scanner is currently in a state where it can scan a site and return a list of errors.  The next steps would be to
        implement a frontend that would display these errors in a more user-friendly way, and to implement the broken link
        scanner.  A frontend was at one point developed by another team member, but entered a stage of major revisions and
        other priorities/projects ended up taking over.  I hope to continue the project and someday get the broken link
        checker working, as well as get a frontend up and running.
      </p>
    </div>
  </div>
</template>

<style scoped>

</style>