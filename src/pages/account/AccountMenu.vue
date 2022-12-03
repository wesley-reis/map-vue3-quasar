<template>
  <q-page id="accountMenu">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Minha Conta</q-toolbar-title>
    </q-toolbar>
    <div class="text-h6 text-center q-pa-xl">
      <q-avatar size="60px" color="green">WR</q-avatar>
      <div>Wesley Reis</div>
    </div>

    <div class="menu">
      <q-separator inset />
      <q-list class="q-mx-md">
        <q-item clickable v-ripple>
          <q-item-section avatar>
            <q-avatar
              rounded
              color="primary"
              text-color="white"
              icon="account_box"
            />
          </q-item-section>

          <q-item-section class="text-size">Meus Dados</q-item-section>

          <q-item-section side>
            <q-icon name="arrow_right" size="35px" />
          </q-item-section>
        </q-item>
      </q-list>
      <q-separator inset />

      <q-list class="q-mx-md">
        <q-item clickable v-ripple>
          <q-item-section avatar>
            <q-avatar rounded color="red" text-color="white" icon="logout" />
          </q-item-section>

          <q-item-section class="text-size">Sair</q-item-section>

          <q-item-section side>
            <q-icon name="arrow_right" size="35px" />
          </q-item-section>
        </q-item>
      </q-list>
      <q-separator inset />
    </div>
  </q-page>
</template>

<script setup>
</script>

<style>
#accountMenu .menu {
  margin: 0 auto;
  max-width: 500px;
}
.text-size {
  font-size: 18px;
}
</style>
