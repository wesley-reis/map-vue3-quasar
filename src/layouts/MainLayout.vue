<template>
  <q-layout>
    <q-header class="bg-teal">
      <q-toolbar>
        <q-toolbar-title> Map WDev </q-toolbar-title>
        <q-btn flat round dense icon="login" />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated>
      <q-tabs class="text-light bg-teal">
        <q-route-tab to="/map" label="Mapa" icon="explore" />
        <q-route-tab to="/route" label="Rotas" icon="directions" />
        <q-route-tab to="/auth" label="Login" icon="login" />
      </q-tabs>
    </q-footer>
  </q-layout>
</template>

<script setup>
</script>
