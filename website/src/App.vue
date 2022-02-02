<script setup lang="ts">
import NavBar from "./components/NavBar.vue"
</script>

<template>
<div class="_container">
    <NavBar />
    <router-view></router-view>
</div>
</template>

<style>
@import '@/assets/base.css';
@import url("https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css");
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@500&display=swap');

</style>
