<template>
  <section id="hero" class="flex flex-col items-center justify-center min-h-screen text-center bg-blue-600 text-white px-6">
    <!-- Logo -->
    <img src="/img/sobat-logo.png" alt="Logo Sobat Teknologi" class="w-32 h-auto mb-6">

    <h1 class="text-5xl font-extrabold mb-6">Selamat Datang di Sobat Teknologi</h1>
    <p class="text-lg mb-8 max-w-2xl">
      Sobat Teknologi memudahkan Anda membangun website modern dengan Vue.js. 
      Cepat, powerful, dan mudah dikustomisasi.
    </p>
    <a href="#fitur"
       class="bg-white text-blue-600 font-semibold px-6 py-3 rounded-lg shadow-lg hover:bg-gray-200 transition">
      Lihat Fitur
    </a>
  </section>
</template>

<script>
export default { name: 'Hero' }
</script>
