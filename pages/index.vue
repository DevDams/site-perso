<template>
  <PortfolioLayout>
    <div class="bg-[#0A0A0A] w-full min-h-screen pb-40">
      <div class="w-11/12 sm:w-9/12 md:w-7/12 mx-auto pt-16">
        <div class="relative w-44 h-56 mx-auto h-24 rounded-xl border border-stone-600 p-1">
          <img src="~/assets/images/MOI_3.jpeg" alt="artboard" class="w-full h-full object-contain rounded-lg" />
        </div>
        <h1 class="text-4xl sm:text-5xl text-white text-center font-extrabold mt-10">
          Adams Aimé-Désiré
        </h1>
        <h1 class="text-lg sm:text-xl text-white text-center font-semibold mt-2">
          Javascript developer
        </h1>
        <div class="flex items-center justify-center gap-x-2 mt-4">
          <div class="w-3 h-3 rounded-full border border-green-500 flex items-center justify-center">
            <div class="w-1.5 h-1.5 rounded-full bg-green-500"></div>
          </div>
          <p class="text-sm text-zinc-400 text-center font-normal">
            Available for new opportunities
          </p>
        </div>
        <div class="flex items-center justify-center gap-x-10 mt-8">
          <a href="https://twitter.com/dams9ix" target="_blank" rel="noopener noreferrer">
            <div
              class="text-neutral-400 text-base sm:text-lg md:text-xl font-semibold flex items-center justify-center gap-x-1">
              <UIcon name="i-mdi-twitter" />
              <span>Twitter</span>
            </div>
          </a>
          <a href="https://linkedin.com/in/aimedesireofficial" target="_blank" rel="noopener noreferrer">
            <div
              class="text-neutral-400 text-base sm:text-lg md:text-xl font-semibold flex items-center justify-center gap-x-1">
              <UIcon name="i-mdi-linkedin" />
              <span>Linkedin</span>
            </div>
          </a>
          <a href="https://github.com/devDams" target="_blank" rel="noopener noreferrer">
            <div
              class="text-neutral-400 text-base sm:text-lg md:text-xl font-semibold flex items-center justify-center gap-x-1">
              <UIcon name="i-mdi-github" />
              <span>Github</span>
            </div>
          </a>
        </div>

        <div class="md:w-96 mx-auto mt-10 flex justify-center">
          <a href="https://calendly.com/aime-desire/quick-chat" target="_blank" rel="noopener noreferrer">
            <button
              class="relative w-80 h-12 rounded-full bg-[#282828] text-stone-400 text-center text-sm font-semibold flex items-center justify-center gap-x-2 hover:bg-neutral-700 hover:text-stone-200">
              <UIcon name="i-mdi-laptop-account" class="text-xl" /> Book a 30
              minutes call
            </button>
          </a>
        </div>
      </div>

      <div class="relative w-11/12 sm:w-[600px] mx-auto pt-24 px-2 sm:px-10 md:px-0">
        <h3 class="text-lg text-white font-bold">About me</h3>
        <p class="text-stone-400 font-normal mt-5">
          I'm Aimé-Désiré, a passionate and experienced javascript developer,
          cat lover, AI enthusiast based in Abidjan. With over 3 years of
          expertise in the field, I have dedicated myself to creating
          exceptional user interfaces that blend functionality and aesthetics
          seamlessly.
        </p>
        <p class="text-stone-400 font-normal mt-5">
          Specialized in web development, I strive to solve complex problems by
          understanding users' needs, behaviors, and emotions to design elegant,
          simple solutions that delight people.
        </p>

        <nuxt-link to="/about"
          class="bg-[#282828] hover:bg-[#3e3e3e] w-full h-11 text-white flex items-center justify-center gap-x-2 rounded-lg border border-[#2e2e2e] mt-10">
          Know more
          <UIcon name="i-mdi-arrow-right" />
        </nuxt-link>
      </div>

      <div class="w-11/12 sm:w-[600px] mx-auto pt-16 px-2 sm:px-10 md:px-0">
        <h3 class="text-lg text-white font-bold">Work experience</h3>

        <div class="mt-10 flex items-start justify-between">
          <div class="w-[220px]">
            <p class="text-stone-600 text-sm font-semibold">Sep. 2022 - Now</p>
          </div>
          <div class="w-fit">
            <p class="text-stone-400 font-normal">
              This marks the start of my adventure with Skan Technologie as a web developer, using ReactJS, Vuejs and Wordpress. I participate in the development of new customer applications, but also in the realization of internal projects.
            </p>
          </div>
        </div>

        <div class="mt-5 flex items-start justify-between">
          <div class="w-[220px]">
            <p class="text-stone-600 text-sm font-semibold">
              Mar. 2022 - Sep. 2022
            </p>
          </div>
          <div class="w-fit">
            <p class="text-stone-400 font-normal">
              I joined SITC (Southern IT Consulting) as a full-stack developer, helping to develop existing projects as well as participating in the realization and delivery of customer projects. The main technologies used were Angulare, Nestjs and MySQL.
            </p>
          </div>
        </div>

        <nuxt-link to="/about"
          class="bg-[#282828] hover:bg-[#3e3e3e] w-full h-11 text-white flex items-center justify-center gap-x-2 rounded-lg border border-[#2e2e2e] mt-10">
          Know more
          <UIcon name="i-mdi-arrow-right" />
        </nuxt-link>
      </div>

      <div class="w-11/12 sm:w-[600px] mx-auto pt-24 px-2 sm:px-10 md:px-0">
        <h2 class="text-3xl text-center text-white font-semibold">
          Got a question or project idea? Contact me and let's discuss how we
          can work together to bring your ideas to life.
        </h2>

        <div class="relative mt-14 w-full flex flex-col items-center justify-center gap-y-2">
          <a href="mailto:ad.aimedesire@gmail.com">
            <button class="bg-indigo-500 w-80 h-12 rounded-full text-lg sm:text-xl text-white font-bold">
              ad.aimedesire@gmail.com
            </button>
          </a>

          <span class="text-lg font-semibold text-stone-500">or</span>

          <img src="~/assets/images/art_7.png" alt="artboard" class="absolute top-10 right-20 w-14" />

          <a href="https://notionforms.io/forms/leave-a-message-jzrxto" target="_blank" rel="noopener noreferrer">
            <button class="bg-stone-900 w-80 h-12 rounded-full text-lg sm:text-xl text-white font-bold">
              Leave a message
            </button>
          </a>
        </div>
      </div>
    </div>
  </PortfolioLayout>
</template>

<script setup>
import PortfolioLayout from "~/layouts/PortfolioLayout.vue";

useSeoMeta({
  title: 'Adams Aimé-Désiré - Developer javascript',
  description: 'I\'m a passionate and experienced javascript developer, cat lover, AI enthusiast based in Abidjan',
  // reactive example
  // ogImage: () => someData.value?.image
})
</script>

<style></style>
