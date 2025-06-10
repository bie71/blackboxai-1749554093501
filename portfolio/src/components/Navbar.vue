<template>
  <nav class="fixed top-0 left-0 w-full bg-white shadow-md z-50">
    <div class="max-w-7xl mx-auto px-4">
      <div class="flex justify-between items-center h-16">
        <!-- Logo -->
        <div class="flex-shrink-0">
          <a href="#" class="text-xl font-bold text-gray-800">Portfolio</a>
        </div>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex space-x-8">
          <a href="#home" class="text-gray-600 hover:text-gray-900">Beranda</a>
          <a href="#about" class="text-gray-600 hover:text-gray-900">Tentang Saya</a>
          <a href="#portfolio" class="text-gray-600 hover:text-gray-900">Portfolio</a>
          <a href="#clients" class="text-gray-600 hover:text-gray-900">Clients</a>
          <a href="#blog" class="text-gray-600 hover:text-gray-900">Blog</a>
          <a href="#contact" class="text-gray-600 hover:text-gray-900">Contact</a>
        </div>

        <!-- Mobile menu button -->
        <div class="md:hidden">
          <button @click="isOpen = !isOpen" class="text-gray-600 hover:text-gray-900 focus:outline-none">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path v-if="!isOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
              <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
      </div>

      <!-- Mobile Navigation -->
      <div v-if="isOpen" class="md:hidden">
        <div class="px-2 pt-2 pb-3 space-y-1">
          <a href="#home" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Beranda</a>
          <a href="#about" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Tentang Saya</a>
          <a href="#portfolio" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Portfolio</a>
          <a href="#clients" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Clients</a>
          <a href="#blog" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Blog</a>
          <a href="#contact" class="block px-3 py-2 text-gray-600 hover:text-gray-900">Contact</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      isOpen: false
    }
  }
}
</script>
