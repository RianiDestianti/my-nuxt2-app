<template>
  <nav class="fixed top-0 left-0 w-full bg-white shadow-md z-50">
    <div class="max-w-7xl mx-auto px-6 py-3 flex justify-between items-center">
      <!-- Logo -->
      <a href="#hero" class="text-xl font-bold text-blue-600">Sobat Teknologi</a>

      <!-- Menu -->
      <ul class="flex space-x-6 text-gray-700 font-medium">
        <li><a href="#hero" class="hover:text-blue-600">Home</a></li>
        <li><a href="#fitur" class="hover:text-blue-600">Fitur</a></li>
        <li><a href="#about" class="hover:text-blue-600">Tentang</a></li>
        <li><a href="#cta" class="hover:text-blue-600">Kontak</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default { name: 'Navbar' }
</script>
