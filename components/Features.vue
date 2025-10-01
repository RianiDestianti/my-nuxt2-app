<template>
  <section id="fitur" class="py-20 px-6 bg-gray-50 text-center">
    <h2 class="text-3xl font-bold text-blue-600 mb-10">✨ Fitur Utama</h2>
    <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div class="p-6 bg-white rounded-xl shadow-md hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-3">⚡ Cepat</h3>
        <p>Optimasi bawaan untuk performa website yang cepat.</p>
      </div>
      <div class="p-6 bg-white rounded-xl shadow-md hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-3">📦 Modular</h3>
        <p>Mudah dikembangkan dengan modul-modul bawaan dan pihak ketiga.</p>
      </div>
      <div class="p-6 bg-white rounded-xl shadow-md hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-3">🎨 Fleksibel</h3>
        <p>Dapat dipakai untuk SPA, SSR, hingga Static Site Generator.</p>
      </div>
    </div>
  </section>
</template>

<script>
export default { name: 'Features' }
</script>
