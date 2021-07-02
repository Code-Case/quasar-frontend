<template>
  <div>
    <q-tabs
      v-model="tab"
      no-caps
      class="bg-white text-black shadow-1"
      active-color="orange"
      style="height: 60px"
    >
      <q-tab name="advantage" label="Vorteile" />
      <q-tab name="pricingmodel" label="Preismodelle" />
      <q-tab name="howto" label="So geht's" />
      <q-tab name="tools" label="Tools & Services" />
      <q-tab name="firststeps" label="Erste Schritte" />
      <q-tab name="genobrocker" label="über GENO Brocker" />
      <q-tab name="faq" label="Faq" />
    </q-tabs>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  // name: 'ComponentName',
  setup() {
    return {
      tab: ref("advantage"),
    };
  },
};
</script>
