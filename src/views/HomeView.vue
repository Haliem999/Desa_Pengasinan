<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terwujudnya Pengasinan sebagai Desa yang MANDIRI, dan MAJU untuk mencapai masyarakat yang SEHAT, CERDAS, KREATIF, BERAKHLAK MULIA dengan mengutamakan MUSYAWARAH dan GOTONG ROYONG serta bersinergi dengan semua unsur masyarakat.”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Meningkatkan pembangunan infrastruktur yang mendukung perekonomian desa, seperti jalan, jembatan serta infrastruktur lainnya;
        </li>
        <li>
          2. Meningkatkan pembangunan di bidang kesehatan untuk mendorong derajat kesehatan masyarakat agar dapat bekerja lebih optimal dan memiliki harapan hidup yang lebih panjang.;
        </li>
        <li>
          3. Meningkatkan pembangunan di bidang pendidikan untuk mendorong peningkatan kualitas sumber daya manusia agar memiliki kecerdasan dan daya saing yang lebih baik. ;
        </li>
        <li>
          4. Meningkatkan pembangunan ekonomi dengan mendorong semakin tumbuh dan berkembangnya pembangunan di bidang pertanian dalam arti luas, industri, perdagangan dan pariwisata.;
        </li>
        <li>
          5. Menciptakan tata kelola pemerintahan yang baik (good governance) berdasarkan demokratisasi, transparansi, penegakan hukum, berkeadilan, kesetaraan gender dan mengutamakan pelayanan kepada masyarakat.;
        </li>
        <li>
          6. Menciptakan sinergi antara Pemerintahan Desa dengan semua unsur masyarakat, mengedepankan Musyawarah dan gotong royong untuk terciptanya pembangunan yang merata dan Adil berdasarkan demokrasi;
        </li>
      
      </ul>
    </div>

  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
