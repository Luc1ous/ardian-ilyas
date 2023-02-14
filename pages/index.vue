<template>
  <div class="font-nunito selection:bg-violet-800 selection:text-slate-100 selection:p-12">
    <Navbar />
    <section>
      <div class="relative w-full h-screen bg-slate-200 dark:bg-slate-900 dark:text-white flex justify-center items-center">
        <div class="lg:w-3/4 w-full text-center p-4 space-y-4 z-10">
          <h1 class="text-7xl font-dm-serif font-semibold">Ardian Ilyas Fernanda</h1>
          <p class="text-lg font-light text-slate-900 dark:text-white">Hello, I'am a Student that interesting about <span class="text-indigo-900 dark:text-indigo-300 underline underline-offset-4">Fullstack Web Developer</span></p>
        </div>
      </div>
    </section>

    <section class="w-full min-h-screen dark:bg-slate-800 flex flex-col justify-center items-center">
      <div class="w-full my-20">
        <div class="text-center">
          <h1 class="font-dm-serif text-5xl">Skill Stack</h1>
          <p class="text-lg font-light text-slate-900 dark:text-white mt-4">Here is my skill stack</p>
        </div>
        <div class="container w-full mt-16 grid grid-cols-3 place-items-center gap-x-8 gap-y-24">
          <div class="">
            <img src="~/assets/img/php.svg" alt="" width="100">
          </div>
          <div class="">
            <img src="~/assets/img/javascript.svg" alt="" width="80">
          </div>
          <div class="">
            <img src="~/assets/img/bootstrap.svg" alt="" width="80">
          </div>
          <div class="">
            <img src="~/assets/img/tailwindcss.svg" alt="" width="80">
          </div>
          <div class="">
            <img src="~/assets/img/vuejs.svg" alt="" width="80">
          </div>
          <div class="">
            <img src="~/assets/img/laravel.svg" alt="" width="80">
          </div>
          <div class="">
            <img src="~/assets/img/nuxt.svg" alt="" width="80">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>

</script>
