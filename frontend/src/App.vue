<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title>
          Quasar + Express + Docker
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <IndexPage />
    </q-page-container>
  </q-layout>
</template>

<script setup>
import IndexPage from './pages/IndexPage.vue'
</script>
