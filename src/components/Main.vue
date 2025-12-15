<template>
  <main
    class="md:w-3/4 w-full bg-gray-600 rounded-xl border-1 border-solid pb-8"
  >
    <div class="flex flex-row">
      <div class="w-1/2"></div>
      <div
        class="w-1/2 h-[50px] bg-gray-900 rounded-tr-xl border-b-1 border-l-1 border-solid rounded-bl-xl"
      >
        <div class="h-full flex flex-row justify-around items-center">
          <p>About Me</p>
          <p>Projects</p>
        </div>
      </div>
    </div>
    <div class="px-8">
      <h1 class="text-3xl">About Me</h1>
      <div class="divider w-[50px]"></div>
      <div class="flex flex-col gap-4">
        <p>
          I am a student with a strong interest in programming, currently
          pursuing development primarily in my free time. While my studies are
          paused, I continue to build my technical skills through personal
          projects, experimentation, and self-directed learning.
        </p>
        <p>
          I enjoy working hands-on with code and learning by doing—breaking
          problems down, testing ideas, and refining solutions until they are
          clean and reliable. I focus on writing understandable, maintainable
          code and steadily improving my understanding of both core concepts and
          modern tools.
        </p>
        <p>
          Programming is something I approach with curiosity and discipline
          rather than formality. I am motivated by progress, practical
          problem-solving, and the satisfaction of building things that work
          well. I aim to keep developing my skills with the long-term goal of
          turning this interest into professional-level competence.
        </p>
      </div>
      <div class="mt-10">
        <h1 class="text-3xl">What I'm doing</h1>
        <div class="grid grid-cols-2 gap-4 mt-2">
          <div class="bg-gray-800 h-[150px] w-full flex rounded-2xl">
            <div class="w-1/3 flex justify-center items-center">
              <img class="w-16" src="./../assets/vue.svg" alt="" />
            </div>
            <div class="w-2/3 flex flex-col justify-center">
              <h1 class="text-2xl">Web Development</h1>
              <p class="pr-6">
                Mainly using Vue.js framework for all my projects.
              </p>
            </div>
          </div>
          <div class="bg-gray-800 h-[150px] w-full flex rounded-2xl">
            <div class="w-1/3 flex justify-center items-center">
              <img class="w-16" src="./../assets/database.svg" alt="" />
            </div>
            <div class="w-2/3 flex flex-col justify-center">
              <h1 class="text-2xl">Basic Database Design</h1>
              <p class="pr-6">
                Mainly used Supabase, but eager to learn more advanced database
                design.
              </p>
            </div>
          </div>
          <div class="bg-gray-800 h-[150px] w-full flex rounded-2xl">
            <div class="w-1/3 flex justify-center items-center">
              <img class="w-16" src="./../assets/photo-camera.svg" alt="" />
            </div>
            <div class="w-2/3 flex flex-col justify-center">
              <h1 class="text-2xl">Photography</h1>
              <p class="pr-6">
                I enjoy capturing moments while traveling, turning the beauty of
                new places into memorable photographs.
              </p>
            </div>
          </div>
        </div>
        <h1 class="text-3xl mt-10">What i'm learning or want to learn</h1>
        <div class="grid grid-cols-2 gap-4">
          <div class="bg-red-900 h-[150px]">
            <h1>Video Game Development</h1>
          </div>
          <div class="bg-red-900 h-[150px]">
            <h1>Blender 3D Design</h1>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
