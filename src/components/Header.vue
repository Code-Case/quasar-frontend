<template>
  <q-header
    style="padding: 1em 2.25em; max-width: 1440px; width: 100%; margin: 0 auto"
    class="header bg-white text-primary row"
  >
    <q-toolbar>
      <div class="col-xs-4 col-md-2">
      <q-toolbar-title>
        <q-item clickable to="/">
          <q-img loading="lazy" class="logo" style="max-width: 256px;" src="/images/logo.png" />
        </q-item>
      </q-toolbar-title>
      </div>
      <div class="col-xs-4 col-md-2 offset-md-6">
      <q-btn
        class="bg-secondary text-white q-mr-xl no-border-radius no-shadow"
        label="Kundenlogin"
        icon="account_circle"
        size=".85rem"
      />
            </div>
      <div class="col-xs-4 col-md-2">
      <q-btn
        class="bg-white text-secondary no-border-radius no-shadow"
        label="Depot wählen"
        icon="insert_chart"
        size=".85rem"
      />
      </div>
    </q-toolbar>
  </q-header>
</template>

<script>
export default {
  // name: 'Header',
  setup() {
    return {};
  },
};
</script>
