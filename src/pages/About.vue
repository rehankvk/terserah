<script>
export default {
  mounted() {
    window.scrollTo(0, 0);
  },
};
</script>

<template>
  <div id="about" class="about">
    <div class="mt-3 w-11/12 mx-auto flex flex-col lg:flex-row-reverse">
      <img
        src="../assets/me.webp"
        alt="saya"
        class="w-full rounded-lg"
      />
      <div class="p-3 flex flex-col">
        <h5 class="text-2xl md:text-3xl font-bold">Hallo, Saya Fajar Raihan</h5>
        <p class="text-justify mt-2 text-base md:text-xl">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <!-- Saya siswa kelas 11 SMK dengan jurusan Teknik Komputer dan Jaringan
          (TKJ), saya sekolah dan tinggal di Jakarta Barat. Saya memiliki minat
          dalam dunia teknologi, sebagai IT Developer terutama dibidang WEB
          Development. Saya memiliki hobi seperti Coding dan Design. -->
        <router-link
          to="#"
          class="mt-2 py-1 text-center text-base rounded bg-white w-1/2 text-blue-600 hover:bg-blue-600 hover:text-white border-blue-600 border"
          >About ME</router-link
        >
      </div>
    </div>
  </div>
</template>
