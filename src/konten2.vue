<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
   <div class="grid grid-cols-4 gap-4">
  <div> <the-card variant="image" img-src="https://www.ocbcnisp.com/asset/media/Feature/Article/image-stock/Pexels-Images/Random-Things/food-and-beverage.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">makan pagi</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      makan aja
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
  <div> <the-card variant="image" img-src="https://asset-2.tstatic.net/wartakota/foto/bank/images/Ilustrasi-kuliner-1.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">makan malam</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      makan
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
    <the-card variant="image" img-src="https://cdn.idntimes.com/content-images/community/2020/02/full-english-page-74f2d2cc63e99c1160001782a622c7ce_600x400.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">makan siang</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        makan
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
<the-card variant="image" img-src="https://fnbpreneur.id/wp-content/uploads/2021/09/Apa-itu-FB-Pengertian-Manfaat-dan-Tren-FB.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">makan sore</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
     makan
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
</template>