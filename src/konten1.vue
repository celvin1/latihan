<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
   <div class="grid grid-cols-4 gap-4">
  <div> <the-card variant="image" img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSd7zQw0AEvtyDjtBHYvI5YOjS0fwM1cNbWYw&usqp=CAU" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Double Room</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        jos
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="999 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">5.00</p>
      </template>
    </Rating>
  </the-card></div>
  <!-- ... -->
  <div> <the-card variant="image" img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLUFje48RIX3C3YWDXIBP1y4wF9rZ6idJ5wQ&usqp=CAU" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Deluxe Room</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
    enak
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="1000 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">7.95</p>
      </template>
    </Rating>
  </the-card>
</div>
<div>
    <the-card variant="image" img-src="https://backend.parador-hotels.com/wp-content/uploads/2023/04/bolehkah-1-kamar-hotel-diisi-3-orang.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Standard Room</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      cocok buat adik kaka
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="987 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">8.95</p>
      </template>
    </Rating>
  </the-card>
</div>
<the-card variant="image" img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTVWXhpgRTZnz6FDXSHfLOP_aVPeET0PoSkoA&usqp=CAU" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">super room</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
     khusus 
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="1008 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">8.95</p>
      </template>
    </Rating>
  </the-card>
</div>
</template>