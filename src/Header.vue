<script setup lang="ts">

</script>

<template>
   <section class="logo">
      <img class="logo" alt="FreeComETT" src="/assets/FreeComETT-logo.png" />
      <img class="logo smaller" alt="FreeREG" src="/assets/FreeREG-logo.jpg" />
   </section>
</template>

<style scoped lang="scss">
section.logo {
   display:flex;
   background:white;
   height:50px;
   justify-content: space-between;
   img {
      scale: 0.8;
      &.smaller {
         scale: 0.7;
      }
   }
}
</style>