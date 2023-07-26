<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://images.tokopedia.net/blog-tokopedia-com/uploads/2020/11/10-Hotel-Terbaik-di-Bandung-dari-Segi-Fasilitas-Akses-dan-Pemandangan.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://cf.bstatic.com/xdata/images/hotel/max1024x768/378828506.jpg?k=ea7d10effc56e6e3ded34794423b9a97f43d25c303867e6051d422a08b023480&o=&hp=1',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://kanggo.id/wp-content/uploads/2022/12/221127-kolam-renang-mewah-01.webp',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://www.indonesia.travel/content/dam/indtravelrevamp/en/trip-ideas/12-luxurious-hotel-s-for-your-rest-and-relax-day-s-in-yogyakarta/image2.jpg',
    'alt': 'Picture 4',
  },
  {
    'src': 'https://alacasa.id/lkgallery/images/0jgze5_atlantis_the_palm_dubai_(5).jpg',
    'alt': 'Picture 5',
  },
]

</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>