<template>
  <div class="font-sans tracking-wide">
    <!-- accent div -->
    <div class="h-1 bg-orange-700 w-full">&nbsp;</div>

    <header class="bg-blue-950 w-full relative">
     
      <!-- Div with the decorativ divs, Purely Cosmetic -->
      <div class="w-full bottom-0 right-0 h-full absolute overflow-hidden">
        <!-- Decorative divs -->
        <div class="header-baloon--left-top baloon--dark"></div>
        <div class="header-baloon--left-bottom baloon--light"></div>
        <div class="header-baloon--right-bottom baloon--light"></div>
      </div>

      <!-- Home of the navigation and the hero section -->
      <div class="container mx-auto text-white">
        <nav class="py-10 flex">
          <div class="w-1/2">&nbsp;</div>
          <div class="w-1/2">
            <a href="https://twitter.com/kudapara" class="p-6 hover:bg-red-100 border border-2 border-transparent hover:border-white hover:cursor-pointer">Twitter</a>
            <a href="https://github.com/kudapara" class="p-6 border border-2 border-transparent hover:border-white hover:cursor-pointer">Github</a>
            <a href="https://blog.kudapara.co.zw" class="p-6 border border-2 border-transparent hover:border-white hover:cursor-pointer">Blog</a>
          </div>
        </nav>

        <!-- The div to be overflowed by the image -->
        <div class="relative h-88 p-2 z-10">
          <div class="absolute p-10 w-full">
            <div class="flex justify-center items-start">
              <!-- The image -->
              <div class="h-88 w-88 flex-shrink-0 rounded-full mr-8 bg-orange-400 bg-cover border-12 border-translucent shadow shadow-lg" style="background-image: url(/kuda.jpg)">
                &nbsp;
              </div>

              <!-- Brief description and call to action -->
              <div class="max-w-sm">
                <h3 class="mb-4 text-2xl">Kudakwashe Paradzayi</h3>

                <p class="mb-6 font-serif">
                  Hey, I am a full stack web developer. My mission is to build software that will make the lives of people better whilst making profit for your business.
                </p>

                <button class="bg-orange-700 text-white tracking-wide p-4 rounded shadow">Let's build something together</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>

    <section class="bg-red-100 h-screen w-full relative"> Hello</section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.border-translucent {
  border-color: #ffffff88
}


.baloon--light {
  background-color: #413F50;
}

.baloon--dark {
  background-color: #1D1D2F
}

.header-baloon--left-top {
  @apply h-40 w-40 rounded-full absolute;
  bottom: 250px;
  left: 25%;
}

.header-baloon--left-bottom {
  @apply h-80 w-80 rounded-full absolute;
  bottom: -150px;
  left: 10%;
}

.header-baloon--right-bottom {
  @apply h-88 w-88 rounded-full absolute;
  bottom: -100px;
  right: -100px;
}




</style>