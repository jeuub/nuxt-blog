<template>
  <div>
    <Hello />
    <div class="carousel__wrapper">
      <h2 class="carousel__title">Последние статьи:</h2>
      <Carousel />
    </div>
  </div>
</template>

<script>
import Hello from '@/components/HelloComponent.vue';
import Carousel from '@/components/CarouselComponents.vue';

export default {
  name: 'IndexPage',
  components: {
    Hello,
    Carousel,
  },
  layout: 'DefaultLayout',
};
</script>

<style>
.carousel__wrapper {
  height: 100vh;
  max-width: 80%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
