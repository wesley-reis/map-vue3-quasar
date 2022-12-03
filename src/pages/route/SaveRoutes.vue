<template>
  <q-page id="saveRoutes">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>Rotas Salvas</q-toolbar-title>
      <q-btn flat round dense icon="add" size="20px" />
    </q-toolbar>
    <div class="section-title">
      <div class="text-h6 q-mx-sm text-blue-grey-7">
        selecione uma de suas rotas salvas!
      </div>
    </div>

    <div class="text-center q-pt-lg">
      <q-btn flat round dense icon="add_circle_outline" />
      <div class="text-h6">Adicione algumas rotas!</div>
      <div class="q-pa-md info">
        Aqui que você pode adicionar suas viagens favoritas ou comuns!
      </div>
    </div>

    <q-scroll-area class="form-list">
      <q-list>
        <q-item>
          <q-item-section top avatar>
            <q-avatar color="green" text-color="white" icon="directions" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Uma nova rota legal!</q-item-label>
            <q-item-label caption>
              <div class="q-px-sm"><b>A partir de</b>: esta é a seção de</div>
              <div class="q-px-sm"><b>Para</b>: esta é a seção de</div>
              <div class="q-px-sm"><b>Raio de busca</b>: 3</div>
            </q-item-label>
          </q-item-section>

          <q-item-section side bottom>
            <q-btn class="q-ma-sm" label="Ver mapa" size="sm" color="green" />
            <q-btn class="q-mx-sm" label="Deletar" size="sm" color="red" />
          </q-item-section>
        </q-item>

        <q-separator spaced inset />
      </q-list>
    </q-scroll-area>
  </q-page>
</template>

<script setup>
</script>

<style>
#saveRoutes section-title {
  padding: 12px 10px 8px 10px;
  max-width: 510px;
  margin: 0 auto;
}

.info {
  font-size: 16px;
}

.form-list {
  margin: 0 auto;
  height: calc(100vh - 250px);
  max-width: 500px;
}
</style>
