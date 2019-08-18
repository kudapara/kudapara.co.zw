<template>
  <div class="font-sans tracking-wide">
    <!-- accent div -->
    <div class="h-1 bg-orange-700 w-full">&nbsp;</div>

    <SectionHero/>

    <SectionBlog/>

    <section class="flex justify-center -mt-24 pb-32">
      <div style="height:161px; width:780px;" class="rounded shadow-2xl bg-red-200 overflow-hidden">
        <iframe src="https://anchor.fm/kudapara/embed" height="200px" width="100%" frameborder="0" scrolling="no"></iframe>
      </div>
    </section>
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