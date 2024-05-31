<script setup>
import FancyButton from './components/FancyButton.vue';
</script>

<template>
  <div class="content">
  
    <FancyButton>
      <template v-slot:icon="slotProps">
     {{ slotProps.hover ? '' : '' }}
      </template>
      <template v-slot:default>
      <strong>New software update available</strong>
    </template>
    </FancyButton>

    <FancyButton>
      <template v-slot:icon="slotProps">
     {{ slotProps.hover ? '' : '' }}
      </template>
      <template v-slot:default>
      <strong>Your Purchase has been cofirmed</strong>
    </template>
    </FancyButton>

    <FancyButton>
      <template v-slot:icon="slotProps">
     {{ slotProps.hover ? '' : '' }}
      </template>
      <template v-slot:default>
      <strong>Warning: Invalid email address!</strong>
    </template>
    </FancyButton>

    <FancyButton>
      <template v-slot:icon="slotProps">
     {{ slotProps.hover ? '' : '' }}
      </template>
      <template v-slot:default>
      <strong>Error! Task failed successfully</strong>
    </template>
    </FancyButton>


   
  </div>
</template>

<style scoped>
</style>
  


<style scoped>
</style>