<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold mt-4">Visi</p>
      <p>Mewujudkan Kehidupan masyarakat Desa yang berbudaya beretikat budiman,damai, Dan Sejahtera</p>
      <p class="text-lg font-semibold mt-4">Misi</p>
      <ul>
        <li>Menjadikan Desa Sumur Batu Menjadi Desa Mandiri</li>
        <li>Meningkatkan kesejahtraan masyarakat desa dengan meningkatkan sarana dan prasarana ekonomi warga</li>
        <li>Meningkatkan sarana dan prasarana pendidikan guna peningkatan sumber daya manusia Desa Sumur Batu</li>
        <li>Melanjutkan pembangunan desa yang belum terlaksana</li>
      </ul>
      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa-sumurbatu.jpeg.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
