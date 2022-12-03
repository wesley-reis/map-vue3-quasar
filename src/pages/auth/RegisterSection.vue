<template>
  <q-page id="registrationPage">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Registrar</q-toolbar-title>
    </q-toolbar>

    <q-scroll-area class="q-pa-md form-style">
      <div class="text-h6 text-center q-pt-md">
        <q-img src="favicon.ico" height="60px" width="60px" />
        <div>Map WDev</div>
      </div>
      <div class="q-pa-md q-gutter-md">
        <div class="text-center">Registre-se e obtenha recursos extras!</div>

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

        <q-input outlined stack-label color="blue-grey-4" label="E-mail">
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label color="blue-grey-4" label="Senha">
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input
          outlined
          stack-label
          color="blue-grey-4"
          label="Confirmar Senha"
        >
          <template v-slot:append>
            <q-icon name="close" />
          </template>
        </q-input>

        <div>
          <q-btn color="black" size="lg" class="full-width">Registrar</q-btn>
        </div>
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#registrationPage .form-style {
  margin: 0 auto;
  height: calc(100vh - 180px);
  max-width: 500px;
}
</style>
