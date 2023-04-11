<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

<div class="w-full max-w-md px-8 py-4 mt-16 bg-white rounded-lg shadow-lg dark:bg-gray-800 bg-green-50">
    <div class="flex justify-center -mt-16 md:justify-end">
        <img class="object-cover w-20 h-20 border-2 border-blue-500 rounded-full dark:border-blue-400" alt="Testimonial avatar" src="pictures.jpg">
    </div>

    <h2 class="mt-2 text-xl font-semibold text-gray-800 dark:text-white md:mt-0">Nurathirah binti Sawal</h2>

    <p class="mt-2 text-sm text-gray-600 dark:text-gray-200">Currently studying in Politeknik Brunei and taking Level 5 Diploma in Web Development</p>

    <div class="flex justify-end mt-4">
      <a href="#" class="text-lg font-medium text-blue-600 dark:text-blue-300" tabindex="0" role="link">21FTT1856@student.pb.edu.bn</a>
    </div>
</div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
