<template>
  <q-page id="routeSelect">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Rota</q-toolbar-title>
      <q-btn
        to="/route/saved-routes"
        flat
        round
        dense
        icon="favorites"
        color="red"
      />
    </q-toolbar>

    <q-scroll-area class="q-pa-md form-style">
      <div class="text-h6 q-pb-md text-blue-grey-7">
        onde você gostaria de ir?
      </div>
      <q-input outlined stack-label color="blue-grey-4" label="Partida">
        <template v-slot:append>
          <q-icon name="close" />
        </template>
      </q-input>

      <q-input
        class="q-pt-md"
        outlined
        stack-label
        color="blue-grey-4"
        label="Destino"
      >
        <template v-slot:append>
          <q-icon name="close" />
        </template>
      </q-input>

      <div class="q-pt-md">
        <q-btn size="lg" class="full-width" color="black" label="Procurar" />
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#routeSelect .form-style {
  margin: 0 auto;
  height: calc(100vh - 180px);
  max-width: 500px;
}
</style>
