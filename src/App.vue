<script setup>
import "./router";
import FooterWeb from "./components/Footer.vue";
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <div class="w-full">
    <Navbar />
    <router-view></router-view>
    <FooterWeb />
  </div>
</template>
