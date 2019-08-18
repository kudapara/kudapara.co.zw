<template>
  <div class="font-sans tracking-wide">
    <!-- accent div -->
    <div class="h-1 bg-orange-700 w-full">&nbsp;</div>

    <SectionHero/>

    <section class="bg-red-100 py-32 text-blue-900">

      <div class="w-full max-w-3xl mx-auto relative">
        <!-- Decorative Div -->
        <div class="absolute blog-baloon--left-center z-10">&nbsp;</div>

        <div class="pb-16 flex justify-between items-baseline w-full">
          <h3 class="text-6xl">Blog</h3>
          <a href="https://dev.to/kudapara" target="_blank" class="font-serif hover:underline">Read all &rightarrow;</a>
        </div>

        <!-- list of articles -->
        <ul class="relative z-20 ">
          <li v-for="(post,i) in blogPosts" :key="i" class="flex justify-between items-center bg-white rounded shadow-lg p-6 mb-6">
            <div class="pr-4">
              <h3 class="text-xl mb-2">{{ post.title }}</h3>
              <p class="font-serif">{{ post.description }}</p>
            </div>
            <a :href="post.url" target="_blank" class="uppercase block tracking-wide border-2 border-blue-900 py-1 px-4 rounded hover:bg-blue-900 hover:text-white">Read</a>
          </li>
        </ul>
      </div>

    </section>
  </div>
</template>

<script>
import SectionHero from '~/components/SectionHero.vue'

export default {
  components: {
    SectionHero
  },

  data() {
    return {
      blogPosts: [
       {
        title: 'How I managed to control my insomnia',
        description: 'I have battled with insomnia for a while now and I have had trouble getting some sleep...',
        url: 'https://dev.to/kudapara/how-i-managed-to-control-my-insomnia-3j25'
      },
       {
        title: 'The day HashNode cured my CMS Hopping Syndrome',
        description: 'Have you ever spent an entire day just struggling to choose which blogging platform to go with?...',
        url: 'https://blog.kudapara.co.zw/the-day-hashnode-finished-my-cms-hopping-syndrome-cjzgyirw1004elcs19n72gesp'
      },
      {
        title: 'Where to find remote internship for software development?',
        description: 'Let us discuss the companies that currently accept remote internship...',
        url: 'https://dev.to/kudapara/do-you-know-where-to-find-remote-internship-for-software-development-325d'
      }
    ]
    }
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.blog-baloon--left-center {
  @apply w-88 rounded-full bg-red-400 z-0;
  background-color: #CCC0C4;
  height: 580px;
  width: 580px;
  top: 18%;
  left: -20%
}
</style>