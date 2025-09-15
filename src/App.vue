<script setup>
import NavBar from "@/NavBar.vue";
import Buttons from "@/Buttons.vue";
import Header from "@/Header.vue";
</script>

<template>
   <Header></Header>
   <NavBar />
</template>

<style lang="scss">
@use '/style-guide/_core';
@use '/style-guide/_nav';
@use '/style-guide/_logo';
</style>