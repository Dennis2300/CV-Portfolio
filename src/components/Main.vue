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
          <div
            @click="changeTab('about')"
            :class="[
              'group w-1/2 h-full flex items-center justify-center cursor-pointer select-none ',
              'transition-all duration-300 ease-out',
              'hover:bg-[var(--primary-color)]/20 hover:shadow-inner',
              'focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-[var(--primary-color)]',
              selectedTab === 'about'
                ? 'bg-[var(--primary-color)] text-white font-semibold'
                : 'text-neutral-300',
            ]"
            class="rounded-bl-xl"
          >
            <span
              class="transition-transform duration-300 group-hover:scale-105"
            >
              About Me
            </span>
          </div>

          <div
            @click="changeTab('projects')"
            :class="[
              'group w-1/2 h-full flex items-center justify-center cursor-pointer select-none',
              'transition-all duration-300 ease-out',
              'hover:bg-[var(--primary-color)]/20 hover:shadow-inner',
              'focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-[var(--primary-color)]',
              selectedTab === 'projects'
                ? 'bg-[var(--primary-color)] text-white font-semibold'
                : 'text-neutral-300',
            ]"
            class="rounded-tr-xl"
          >
            <span
              class="transition-transform duration-300 group-hover:scale-105"
            >
              Projects
            </span>
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
