<script setup>
import AppAlert from './components/AppAlert.vue'
</script>

<template>
  <template>
  <div id="app">
    <AppAlert type="info">
      New software update available
    </AppAlert>
    <AppAlert type="success">
      Your purchase has been confirmed!
    </AppAlert>
    <AppAlert type="warning">
      Warning: Invalid email confirmed!.
    </AppAlert>
    <AppAlert type="error">
      Error! task failed succefully.
    </AppAlert>
  </div>
</template>
</template>

<style scoped>
@import './assets/tailwind.css';
</style>