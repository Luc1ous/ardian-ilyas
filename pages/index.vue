<template>
  <div class="font-nunito bg-[#fffffe] selection:bg-violet-800 selection:text-slate-100 selection:p-12">
    <Navbar />

    <!-- Hero Section -->
    <section>
      <div class="relative w-full h-screen bg-[#eaddcf] dark:bg-[#010101] dark:text-white flex justify-center items-center">
        <div class="lg:w-3/4 w-full text-center p-4 space-y-4 z-10">
          <h1 class="text-7xl text-[#020826] dark:text-white font-dm-serif">Ardian Ilyas Fernanda</h1>
          <p class="text-lg font-light text-[#716040] dark:text-white">Hello, I'am a Student that interesting about <span class="text-indigo-900 dark:text-indigo-300 underline underline-offset-4">Fullstack Web Developer</span></p>
        </div>
      </div>
    </section>

    <!-- Skill Section -->
    <section class="w-full min-h-screen dark:bg-[#16161a] flex flex-col justify-center items-center">
      <div class="w-full my-20">
        <div class="text-center">
          <h1 class="font-dm-serif text-[#020826] dark:text-white text-5xl">Skills Stack</h1>
          <p class="text-lg font-light text-[#716040] dark:text-white mt-4">Here is my skill stack</p>
        </div>
        <div class="container w-full mt-16 grid grid-cols-2 md:grid-cols-4 place-items-center gap-x-4 gap-y-24">
          <a href="https://html.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/html-1.svg" alt="" width="80">
          </a>
          <div class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/css.svg" alt="" width="80">
          </div>
          <a href="https://www.php.net/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/php.svg" alt="" width="100">
          </a>
          <a href="https://www.javascript.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/javascript.svg" alt="" width="80">
          </a>
          <a href="https://getbootstrap.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/bootstrap.svg" alt="" width="100">
          </a>
          <a href="https://tailwindcss.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/tailwindcss.svg" alt="" width="100">
          </a>
          <a href="https://laravel.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/laravel.svg" alt="" width="80">
          </a>
          <a href="https://vuejs.org/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/vuejs.svg" alt="" width="80">
          </a>
          <a href="https://nuxt.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/nuxt.svg" alt="" width="100">
          </a>
          <a href="https://www.mysql.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/mysql.svg" alt="" width="120">
          </a>
          <a href="https://www.figma.com/" target="_blank" class="grayscale hover:grayscale-0 transition ease-in-out duration-200 cursor-pointer">
            <img src="~/assets/img/figma2.svg" alt="" width="60">
          </a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="w-full h-36 bg-[#eaddcf] dark:bg-[#010101] flex justify-center items-center">
      <p class="text-lg dark:text-white">Copyright &copy; {{ year }} all rights reserved</p>
    </footer>
  </div>
</template>

<script setup>
  const year = new Date().getFullYear()
</script>
