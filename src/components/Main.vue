<template>
  <main
    class="md:w-3/4 w-full bg-[#393E46] rounded-xl border border-[#DFD0B8] pb-8"
  >
    <div class="flex flex-row">
      <div class="w-1/2"></div>
      <div
        class="w-1/2 h-[50px] bg-gray-700 text-white rounded-tr-xl border-b-2 border-l-2 border-[#DFD0B8] rounded-bl-xl"
      >
        <div class="h-full flex flex-row justify-around items-center">
          <p @click="changeTab('about')" class="cursor-pointer">About Me</p>
          <p @click="changeTab('projects')" class="cursor-pointer">Projects</p>
        </div>
      </div>
    </div>

    <AboutMe v-if="selectedTab === 'about'" />
    <Projects v-if="selectedTab === 'projects'" />
  </main>
</template>

<script setup>
import { ref } from "vue";
import AboutMe from "./AboutMe.vue";
import Projects from "./Projects.vue";

const selectedTab = ref("about");

function changeTab(tab) {
  selectedTab.value = tab;
}
</script>
