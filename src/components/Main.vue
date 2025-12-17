<template>
  <main
    class="md:w-3/4 w-full bg-(--primary-color) rounded-xl border-2 border-(--tertiary-color) pb-8"
  >
    <div class="flex flex-row">
      <div class="w-1/2"></div>
      <div
        class="w-1/2 h-[50px] bg-(--secondary-color) text-white rounded-tr-xl border-b-2 border-l-2 border-(--tertiary-color) rounded-bl-xl"
      >
        <div
          class="h-full flex flex-row items-center overflow-hidden bg-neutral-800/40 backdrop-blur rounded-bl-xl"
        >
          <div @click="changeTab('about')" class="rounded-bl-xl">About Me</div>

          <div @click="changeTab('projects')" class="rounded-tr-xl">
            Projects
          </div>
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
