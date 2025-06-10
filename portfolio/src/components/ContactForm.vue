<template>
  <section id="contact" class="py-12 bg-gray-100">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl mb-8">
        Hubungi Kami
      </h2>
      <form class="space-y-6">
        <div>
          <label for="name" class="block text-sm font-medium text-gray-700">Nama</label>
          <div class="mt-1">
            <input
              type="text"
              id="name"
              class="shadow-sm focus:ring-blue-500 focus:border-blue-500 block w-full sm:text-sm border-gray-300 rounded-md"
            />
          </div>
        </div>

        <div>
          <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
          <div class="mt-1">
            <input
              type="email"
              id="email"
              class="shadow-sm focus:ring-blue-500 focus:border-blue-500 block w-full sm:text-sm border-gray-300 rounded-md"
            />
          </div>
        </div>

        <div>
          <label for="phone" class="block text-sm font-medium text-gray-700">Telepon</label>
          <div class="mt-1">
            <input
              type="tel"
              id="phone"
              class="shadow-sm focus:ring-blue-500 focus:border-blue-500 block w-full sm:text-sm border-gray-300 rounded-md"
            />
          </div>
        </div>

        <div>
          <label for="message" class="block text-sm font-medium text-gray-700">Pesan</label>
          <div class="mt-1">
            <textarea
              id="message"
              rows="4"
              class="shadow-sm focus:ring-blue-500 focus:border-blue-500 block w-full sm:text-sm border-gray-300 rounded-md"
            ></textarea>
          </div>
        </div>

        <div>
          <button
            type="submit"
            class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500"
          >
            Kirim
          </button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactForm'
}
</script>
