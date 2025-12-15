<template>
  <div
    class="flex flex-col md:flex-row gap-12 w-full md:w-3/4 min-h-screen py-16 mx-auto"
  >
    <Aside />
    <Main />
  </div>
</template>

<script setup>
import Aside from "./Aside.vue";
import Main from "./Main.vue"
</script>
