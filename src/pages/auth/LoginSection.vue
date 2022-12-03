<template>
  <q-page id="loginPage">
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

        <div>
          <q-btn color="black" size="lg" class="full-width">Entrar</q-btn>
        </div>

        <div class="q-px-md q-mt-xl text-center">
          <div class="q-mb-md no-account">Não tem uma conta?</div>
          <q-btn color="teal" outline rounded to="/auth/register" size="15px"
            >Registre agora</q-btn
          >
        </div>
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#loginPage .form-style {
  margin: 0 auto;
  height: calc(100vh - 180px);
  max-width: 500px;
}
.no-account {
  font-size: 17px;
}
</style>
