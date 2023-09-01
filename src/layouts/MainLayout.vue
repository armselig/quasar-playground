<template>
  <q-layout view="lHh Lpr lFf">
   <the-header />
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
import TheHeader from "@/components/TheHeader.vue";
</script>
