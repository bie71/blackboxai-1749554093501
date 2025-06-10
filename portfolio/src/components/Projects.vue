<template>
  <section id="portfolio" class="py-12">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl mb-8">
        Project Terbaru
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

        
        
        <div class="bg-white rounded-lg shadow-md overflow-hidden">
          <img
            src="https://images.pexels.com/photos/4164418/pexels-photo-4164418.jpeg?auto=compress&cs=tinysrgb&w=400"
            alt="Project Pertama"
            class="w-full h-56 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold text-gray-800 mb-2">
              Project Pertama
            </h3>
            <p class="text-gray-600">
              Membuat Web PortFolio. Yaitu Web Ini Sendiri
            </p>
            <a
              href="https://bie71.github.io/portofolio/"
              target="_blank"
              class="inline-block mt-4 text-blue-600 hover:underline"
            >
              Lihat Project
            </a>
          </div>
        </div>

        
        <div class="bg-white rounded-lg shadow-md overflow-hidden">
          <img
            src="https://images.pexels.com/photos/1598505/pexels-photo-1598505.jpeg?auto=compress&cs=tinysrgb&w=400"
            alt="Project Kedua"
            class="w-full h-56 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold text-gray-800 mb-2">
              Project Kedua
            </h3>
            <p class="text-gray-600">
              Open Music Api. Memiliki Fitur Authentication & Authoriezation, Collaboration, Upload image, dan Export Album. Menggunakan Teknologi JWT (json web token) sebagai autentikasi, Posgresql dan Redis.
            </p>
            <a
              href="https://github.com/bie71/open_music_api"
              target="_blank"
              class="inline-block mt-4 text-blue-600 hover:underline"
            >
              Lihat Project
            </a>
          </div>
        </div>

        
        <div class="bg-white rounded-lg shadow-md overflow-hidden">
          <img
            src="https://images.pexels.com/photos/2661233/pexels-photo-2661233.jpeg?auto=compress&cs=tinysrgb&w=400"
            alt="Project Ketiga"
            class="w-full h-56 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold text-gray-800 mb-2">
              Project Ketiga
            </h3>
            <p class="text-gray-600">
              Aplication Game Store. Yaitu Sebuah Aplikasi yang dapat menggenerate Kode Kupon Otomatis dengan pembelian jumlah tertentu yang Owner inginkan. Teradapat Fitur Authentication & Authoriezation, Input Prefix kode, minimum pembelian, dan kriteria. Pada Aplikasi ini diterapkan Clean Architecture agar dapat mendevelopment lebih mudah. Aplikasi ini menggunakan bahasa Pemograman Golang (GO).
            </p>
            <a
              href="https://github.com/bie71/assignment-final-project"
              target="_blank"
              class="inline-block mt-4 text-blue-600 hover:underline"
            >
              Lihat Project
            </a>
          </div>
        </div>

        
        <div class="bg-white rounded-lg shadow-md overflow-hidden">
          <img
            src="https://images.pexels.com/photos/574160/pexels-photo-574160.jpeg?auto=compress&cs=tinysrgb&w=400"
            alt="Project Keempat"
            class="w-full h-56 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold text-gray-800 mb-2">
              Project Keempat
            </h3>
            <p class="text-gray-600">
              eMeeting adalah aplikasi booking ruang rapat yang dibangun menggunakan bahasa Go dengan framework Fiber dan konfigurasi menggunakan Viper. Data disimpan di database PostgreSQL, sementara pengujian API dilakukan melalui Postman dengan backend cloud Supabase. Dokumentasi API disediakan lengkap menggunakan Swagger untuk memudahkan integrasi dan pengembangan lebih lanjut.
            </p>
            <a
              href="https://github.com/bie71/e-meeting"
              target="_blank"
              class="inline-block mt-4 text-blue-600 hover:underline"
            >
              Lihat Project
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Projects'
}
</script>
