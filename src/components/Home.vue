<template>
  <div
    class="flex flex-col md:flex-row gap-12 w-full md:w-3/4 min-h-screen py-16 mx-auto"
  >
    <aside
      class="md:w-1/4 w-full h-[550px] bg-gray-500 rounded-xl p-4 flex flex-col"
    >
      <div class="flex flex-col items-center gap-4">
        <img
          src="https://placehold.co/150x150?text=Profile+Picture"
          class="rounded-full"
          alt="Profile picture"
        />
        <h1 class="text-2xl text-center">Dennis-Zixiang Zhou</h1>
      </div>
      <div class="divider my-4"></div>
      <div class="flex flex-col gap-6 flex-grow">
        <div>
          <h2 class="text-sm opacity-70">Email</h2>
          <strong>denniszixiang@gmail.com</strong>
        </div>
        <div>
          <h2 class="text-sm opacity-70">Birthday</h2>
          <strong>October 21st, 2000</strong>
        </div>
        <div>
          <h2 class="text-sm opacity-70">Location</h2>
          <strong>Copenhagen, Denmark</strong>
        </div>
        <div>
          <h2 class="text-sm opacity-70">Socials</h2>
          <div class="flex gap-4">
            <strong>Twitter</strong>
            <strong>Instagram</strong>
            <strong>LinkedIn</strong>
          </div>
        </div>
      </div>
    </aside>
    <main class="md:w-3/4 w-full bg-gray-600 rounded-xl p-6">
      <h1 class="text-2xl mb-4">Content</h1>
    </main>
  </div>
</template>
