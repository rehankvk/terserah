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
          Saya siswa kelas 11 SMK dengan jurusan Teknik Komputer dan Jaringan
          (TKJ), saya sekolah dan tinggal di Jakarta Barat. Saya memiliki minat
          dalam dunia teknologi, sebagai IT Developer terutama dibidang WEB
          Development. Saya memiliki hobi seperti Coding dan Design.
        </p>
        <router-link
          to="#"
          class="mt-2 py-1 text-center text-base rounded bg-white w-1/2 text-blue-600 hover:bg-blue-600 hover:text-white border-blue-600 border"
          >About ME</router-link
        >
      </div>
    </div>
  </div>
</template>
