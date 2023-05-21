<template>
  <div class="component-container">
    <button type="button" class="component-button button">{{ button }}</button>
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {
    button: {
      type: String,
      default: 'Button',
    },
  },
}
</script>

<style scoped>
.component-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.component-button {
  width: 1200px;
  height: 427px;
  text-align: center;
  border-width: 4px;
  border-radius: 15px;
  background-color: var(--dl-color-primary-500);
}
</style>
