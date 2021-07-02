<template>
  <q-carousel
    animated
    v-model="slide"
    navigation
    :autoplay="autoplay"
    transition-prev="fade"
    transition-next="fade"
    @mouseenter="autoplay = false"
    @mouseleave="autoplay = true"
    style="height: 580px"
  >
    <q-carousel-slide
      :name="1"
      img-src="//cdn.quasar.dev/img/mountains.jpg"
    />
    <q-carousel-slide
      :name="2"
      img-src="//cdn.quasar.dev/img/parallax1.jpg"
    />
    <q-carousel-slide
      :name="3"
      img-src="//cdn.quasar.dev/img/parallax2.jpg"
    />
    <q-carousel-slide
      :name="4"
      img-src="//cdn.quasar.dev/img/quasar.jpg"
    />
  </q-carousel>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      slide: ref(1),
      autoplay: ref(true),
    };
  },
};
</script>
