<template>
  <div class="px-8 text-(--quaternary-color)">
    <h1 class="text-5xl">About Me</h1>
    <div
      class="divider w-[50px] before:bg-(--secondary-color) after:bg-(--secondary-color)"
    ></div>
    <div class="flex flex-col gap-4">
      <p>
        I am a student with a strong interest in programming, currently pursuing
        development primarily in my free time. While my studies are paused, I
        continue to build my technical skills through personal projects,
        experimentation, and self-directed learning.
      </p>
      <p>
        I enjoy working hands-on with code and learning by doing—breaking
        problems down, testing ideas, and refining solutions until they are
        clean and reliable. I focus on writing understandable, maintainable code
        and steadily improving my understanding of both core concepts and modern
        tools.
      </p>
      <p>
        Programming is something I approach with curiosity and discipline rather
        than formality. I am motivated by progress, practical problem-solving,
        and the satisfaction of building things that work well. I aim to keep
        developing my skills with the long-term goal of turning this interest
        into professional-level competence.
      </p>
    </div>
    <div class="mt-10">
      <h1 class="text-3xl">What I'm doing</h1>
      <div
        class="divider mt-0 before:bg-(--secondary-color) after:bg-(--secondary-color)"
      ></div>
      <div class="grid grid-cols-2 gap-4 mt-2">
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/vue.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Web Development</h1>
            <p class="pr-6">
              I primarily use the Vue.js framework for all my projects.
            </p>
          </div>
        </div>
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/database.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Basic Database Design</h1>
            <p class="pr-6">
              I’ve mainly worked with Supabase and am eager to learn more
              advanced database design.
            </p>
          </div>
        </div>
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/photo-camera.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Photography</h1>
            <p class="pr-6">
              I enjoy capturing moments while traveling and turning them into
              lasting memories.
            </p>
          </div>
        </div>
      </div>
      <h1 class="text-3xl mt-10">What i'm learning or want to learn</h1>
      <div
        class="divider mt-0 before:bg-(--secondary-color) after:bg-(--secondary-color)"
      ></div>
      <div class="grid grid-cols-2 gap-4">
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/joystick.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Blender 3D Design</h1>
            <p class="pr-6">I’m curious about 3D and environment design.</p>
          </div>
        </div>
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/database.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Advanced Database Design</h1>
            <p class="pr-6">
              I enjoy working with data and am eager to deepen my knowledge of
              database design.
            </p>
          </div>
        </div>
        <div class="bg-(--bg-color) h-[150px] w-full flex rounded-2xl">
          <div class="w-1/4 flex justify-center items-center">
            <img class="w-16" src="./../assets/teamwork.svg" alt="" />
          </div>
          <div class="w-3/4 flex flex-col justify-center">
            <h1 class="text-2xl">Agile Development</h1>
            <p class="pr-6">
              I’ve studied Agile Development and am eager to gain real-world,
              hands-on experience.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
