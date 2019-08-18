<template>
  <div class="font-sans tracking-wide">
    <!-- accent div -->
    <div class="h-1 bg-orange-700 w-full">&nbsp;</div>

    <SectionHero/>

    <SectionBlog/>

  </div>
</template>

<script>
import SectionHero from '~/components/SectionHero.vue'
import SectionBlog from '~/components/SectionBlog.vue'

export default {
  components: {
    SectionHero,
    SectionBlog
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>