<template>
  <q-page>
    <Carousel/>
    <Navigation/>
    <Accordion/>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';
import Accordion from 'components/Accordion'
import Carousel from 'components/Carousel'
import Navigation from 'components/Navigation'

export default defineComponent({
  name: 'PageIndex',
    components: {
      Accordion,
      Carousel,
      Navigation
  }
})
</script>
