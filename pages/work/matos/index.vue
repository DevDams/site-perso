<template>
  <PortfolioLayout>
    <div class="bg-[#0A0A0A] w-full min-h-screen pb-40">
      <div
        class="relative w-11/12 sm:w-9/12 md:w-7/12 max-w-5xl mx-auto pt-10 pb-"
      >
        <nuxt-link to="/work">
          <div
            class="w-11 h-11 rounded-full bg-neutral-800 flex items-center justify-center text-2xl text-white border border-stone-700"
          >
            <UIcon name="i-mdi-arrow-left" />
          </div>
        </nuxt-link>
        <h1 class="text-4xl sm:text-5xl text-white text-center font-bold mt-5">
          Matos
        </h1>
        <p class="text-center text-stone-500 text-lg font-semibold mt-5">
          Corporate equipment management application
        </p>

        <div class="w-full h-40 rounded-2xl bg-orange-500 mt-10">
          <img src="~/assets/images/matos.png" class="w-full h-full object-cover rounded-2xl" />
        </div>

        <div class="w-full lg:w-9/12 mx-auto rounded-2xl mt-10">
          <h3 class="text-3xl text-white font-semibold">Overview</h3>
          <p class="mt-3 text-stone-400">
            Faced with difficulties in managing its IT equipment and hardware,
            Souther IT Consulting needed a tool that would enable it to manage
            and track this equipment. Hence the creation of Matos, a web-based
            asset management application. Its main functionalities were
            equipment registration, company staff registration, equipment
            allocation to staff, allocation history...
          </p>

          <h3 class="text-3xl text-white font-semibold mt-8">Stack</h3>
          <p class="mt-3 text-stone-400">For this project I used javascript technologies.</p>
          <ul class="mt-3 text-stone-400">
            <li>- Angular</li>
            <li>- Tailwindcss</li>
            <li>- Nestjs</li>
            <li>- TypeORM</li>
            <li>- MySQL</li>
          </ul>
        </div>
      </div>
    </div>
  </PortfolioLayout>
</template>

<script setup>
import PortfolioLayout from "~/layouts/PortfolioLayout.vue";
</script>

<style></style>
