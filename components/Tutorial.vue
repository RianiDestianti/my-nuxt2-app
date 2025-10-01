<template>
  <section class="flex flex-col items-center justify-center min-h-[70vh] text-center p-6">
    <h1 class="text-3xl font-bold text-blue-600 mb-4">
      Selamat Datang di Nuxt 2 🚀
    </h1>
    <p class="text-gray-600 mb-6">
      Ini adalah komponen <span class="font-semibold">Tutorial.vue</span> yang dipanggil di <code>index.vue</code>.
    </p>

    <button 
      @click="count++"
      class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-lg shadow-md transition">
      Klik Saya ({{ count }})
    </button>
  </section>
</template>

<script>
export default {
  name: 'Tutorial',
  data() {
    return {
      count: 0
    }
  }
}
</script>
