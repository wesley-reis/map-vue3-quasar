<template>
  <q-page id="myDetailsPage">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Meus Dados</q-toolbar-title>
    </q-toolbar>

    <q-scroll-area class="form-style">
      <div class="q-pa-md q-gutter-md">
        <div class="text-h6 q-pb-md text-blue-grey-7">Atualisar seu dados!</div>

        <q-input outlined stack-label color="blue-grey-4" label="Nome">
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label color="blue-grey-4" label="Sobrenome">
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <div class="text-yellow-10 text-bold q-mt-md">
          OBS: este e-mail é somente para leitura
        </div>
        <q-input
          outlined
          stack-label
          readonly
          color="blue-grey-4"
          label="E-mail"
        >
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <div>
          <q-btn color="black" size="lg" class="full-width">Atualizar</q-btn>
        </div>
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#myDetailsPage .form-style {
  margin: 0 auto;
  height: calc(100vh - 180px);
  max-width: 500px;
}
.no-account {
  font-size: 17px;
}
</style>
