<template>
  <div :class="alertClass">
    <div>
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppAlert',
  props: {
    type: {
      type: String,
      default: 'info',
      validator(value) {
        return ['info', 'success', 'warning', 'error'].includes(value);
      },
    },
  },
  computed: {
    alertClass() {
      return `alert alert-${this.type}`;
    },
  },
}
</script>

<style scoped>
</style>
1 change: 1 addition & 0 deletions1  
src/assets/logo.svg
