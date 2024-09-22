<script setup>
import Button from 'primevue/button';
import Drawer from 'primevue/drawer';
import { ref } from 'vue';
const visibleRight = ref(false);
</script>
<template>
  <div class="card flex justify-center">
    <Drawer v-model:visible="visibleRight" header="Illa Cloud Pricing" position="right">
      <div class="flex flex-col gap-4">
        <RouterLink to="/" @click="visibleRight = false" class="">Home</RouterLink>
        <RouterLink to="/illa-flow" @click="visibleRight = false" class="">ILLA Flow</RouterLink>
        <RouterLink to="/integrations" @click="visibleRight = false" class=""
          >Integrations</RouterLink
        >
      </div>
    </Drawer>
    <Button icon="pi pi-arrow-left" severity="secondary" @click="visibleRight = true" />
  </div>
</template>
