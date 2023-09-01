<template>
  <q-layout view="lHh Lpr lFf">
    <the-header />
    <q-page-container>
      <router-view />
    </q-page-container>
    <the-footer />
  </q-layout>
</template>

<script setup>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";
</script>
