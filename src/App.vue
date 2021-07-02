<template>
    <div class="row" style="max-width: 1440px; width: 100%; margin: 0 auto;">
      <router-view />
    </div>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App'
})
</script>
