<template>
  <demo-container>
    <div class="counter">
      <counter-button @action="decrement">-</counter-button>

      <counter-value :value="count" />

      <counter-button @action="increment">+</counter-button>
    </div>
  </demo-container>
</template>

<script setup>
import CounterButton from "./CounterButton.vue";
</script>

<style lang="scss" scoped>
.counter {
  display: flex;
  align-items: center;
}
</style>
