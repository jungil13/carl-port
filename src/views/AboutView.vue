<template>
  <section class="container mx-auto px-4 border-black box-border rounded-lg py-1">
    <div class="flex flex-col md:flex-row items-center justify-center space-y-8 md:space-x-8">
      <!-- Image -->
      <div class="w-full md:w-1/2 py-8 my-8">
        <img src="../assets/images/mark.jpg" alt="Owner" class="w-full h-auto rounded-full image-shadow hover:shadow-xl transition duration-300 border border-white">
      </div>
      
      <!-- About Info -->
      <div class="w-full md:full text-center md:text-left py-1 mb-4">
        <h1 class="text-3xl md:text-4xl font-bold mb-4 font-serif text-white shadow-lg text-stroke text-stroke-gray-400 py-1">About Me</h1>
        <p class="text-lg font-sans text-white">I am <span class="font-semibold text-green-500 cursor-pointer">Carl Vincent Arquio </span>a BSIT student at Cordova Public College, I am passionate about delving into the intricacies of computer hardware. With a keen interest and a knack for problem-solving, I've honed my skills to become proficient in troubleshooting and optimizing computer systems. </p>
        <p class="text-lg font-sans text-white">With a steadfast resolve to excel in my studies and a relentless pursuit of knowledge, I am determined to carve out a successful career in the ever-evolving landscape of information technology.</p>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style>
/* Add your custom styles here */
.image-shadow {
  transition: box-shadow 0.3s ease-in-out;
}

.image-shadow:hover {
  box-shadow: 0 10px 10px rgba(248, 3, 3, 0.1), 0 1px 3px rgba(255, 0, 0, 0.08);
}
</style>
