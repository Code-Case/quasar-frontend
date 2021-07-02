<template>
  <div
    style="max-width: 1440px; width: 100%; margin: 0 auto; padding: 3em 4.5em;"
    class="bg-primary text-white row"
  >
    <div class="col-12 col-md-4">
      <p class="text-bold q-mb-xl" style="font-size: 24px;">Sie haben noch Fragen?</p>
      <p>
        Sie erreichen das GENO Broker Team per Telefon, Kontaktformular oder mit
        einer E-Mail an <strong>service@genobroker.de</strong>. Unser starker
        Partner steht Ihnen jederzeit zur Verfügung!
      </p>
    </div>
    <div class="col-12 col-md-6">
      <q-list dense padding class="center footer-meta--links">
        <q-item clickable> Datenschutz </q-item>
        <q-item clickable> Formulare </q-item>
        <q-item clickable> Nutzungsbedingungen </q-item>
        <q-item clickable> Impressum </q-item>
        <q-item clickable> AGB </q-item>
      </q-list>
    </div>
  </div>
  <div
    class="footer-meta row"
    style="max-width: 1440px; width: 100%;  margin: 0 auto; padding: 16px 84px"
  >
    <div class="col-12 col-md-3">Logo</div>
    <div class="col-12 col-md-5 offset-md-4">
      <span>Telefon +49 (0)69 – 210 875 181</span>
      <q-btn
        class="bg-green text-white float-right no-border-radius"
        label="Zum Kontaktformular"
        icon="exit_to_app"
      />
    </div>
  </div>
</template>

<script>
export default {
  // name: 'Footer',
  setup() {
    return {};
  },
};
</script>
