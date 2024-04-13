<template>
 <!-- Projects -->
 <section class="py-16 px-4 sm:px-8 lg:px-16 bg-zinc-900">
    <h1 class="text-4xl font-bold mb-8 text-center text-amber-500">My Projects</h1>
    <div class="max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div
        class="group bg-white rounded-lg overflow-hidden shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1 hover:shadow-xl"
      >
        <img
          src="../assets/images/project1.jpg"
          alt="Project 1"
          class="w-full h-56 object-cover"
        />
        <div class="p-4">
          <h2 class="text-lg font-extrabold mb-2 text-center">Chat App</h2>
          <p class="text-gray-600 text-center font-bold">Description of Project 1</p>
        </div>
      </div>

      <!-- Card 2 -->
      <div
        class="group bg-white rounded-lg overflow-hidden shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1 hover:shadow-xl"
      >
        <img
          src="../assets/images/project2.jpg"
          alt="Project 2"
          class="w-full h-56 object-cover"
        />
        <div class="p-4">
          <h2 class="text-lg font-extrabold mb-2 text-center">Spotify API</h2>
          <p class="text-gray-600 text-center font-bold">Description of Project 2</p>
        </div>
      </div>

      <!-- Card 3 -->
      <div
        class="group bg-white rounded-lg overflow-hidden shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1 hover:shadow-xl"
      >
        <img
          src="../assets/images/project3.jpg"
          alt="Project 3"
          class="w-full h-56 object-cover"
        />
        <div class="p-4">
          <h2 class="text-lg font-extrabold mb-2 text-center">Library Management</h2>
          <p class="text-gray-600 text-center font-bold">Description of Project 3</p>
        </div>
      </div>
    </div>
  </section>
</template>