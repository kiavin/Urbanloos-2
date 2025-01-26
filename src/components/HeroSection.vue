<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

// Array of image URLs
const images = ref([
  '/img/IMG_20241227_084125_003.jpg',
  '/img/IMG_20241227_084104_290.jpg',
//   '/img/IMG_20241227_144539_503.jpg',
'/img/IMG_20241227_083942_753.jpg'
])

// Current index
const currentIndex = ref(0)

// Function to show the next image
const nextImage = () => {
  currentIndex.value = (currentIndex.value + 1) % images.value.length
}

// Function to show the previous image
const prevImage = () => {
  currentIndex.value =
    (currentIndex.value - 1 + images.value.length) % images.value.length
}

// Timer to automatically switch images
let timer

onMounted(() => {
  // Start the timer to switch images every 5 seconds
  timer = setInterval(nextImage, 5000)
})

onUnmounted(() => {
  // Clear the timer when the component is destroyed
  clearInterval(timer)
})
</script>

<template>
  <!-- <div
    class="relative bg-gradient-to-r from-purple-600 to-blue-600 h-screen text-white overflow-hidden mb-5"
  > -->
  <!-- Carousel Container -->
  <div class="relative h-full">
    <!-- Current Image -->
    <img
      :src="images[currentIndex]"
      alt="Carousel Image"
      class="object-cover object-center w-full h-screen transition-all duration-700"
    />

    <!-- Navigation Controls -->
    <button
      @click="prevImage"
      class="absolute top-1/2 left-4 transform -translate-y-1/2 bg-white text-black rounded-full p-2 shadow-lg"
    >
      <
    </button>
    <button
      @click="nextImage"
      class="absolute top-1/2 right-4 transform -translate-y-1/2 bg-white text-black rounded-full p-2 shadow-lg"
    >
      >
    </button>
  </div>
  <!-- </div> -->
</template>
