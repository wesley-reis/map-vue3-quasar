<template>
  <q-page id="addRoute">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Adicionar Rota </q-toolbar-title>
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
        Salve suas rotas favoritas!
      </div>
      <span class="text-body1 q-pb-md">escolha um nome para esta rota</span>

      <q-input
        outlined
        stack-label
        color="blue-grey-4"
        class="q-pb-md"
        label="Nome"
      >
        <template v-slot:append>
          <q-icon name="close" />
        </template>
      </q-input>

      <span class="text-body1 q-pt-md">escolha um nome para esta rota</span>
      <q-input outlined stack-label color="blue-grey-4" label="Partida">
        <template v-slot:append>
          <q-icon name="close" />
        </template>
      </q-input>
      <q-input
        outlined
        stack-label
        color="blue-grey-4"
        class="q-pt-md"
        label="Destino"
      >
        <template v-slot:append>
          <q-icon name="close" />
        </template>
      </q-input>

      <div class="q-pt-md">
        <q-btn size="lg" class="full-width" color="black" label="Salvar Rota" />
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#addRoute .form-style {
  margin: 0 auto;
  height: calc(100vh - 180px);
  max-width: 500px;
}
</style>
