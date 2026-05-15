<script setup>
const props = defineProps({
  texto: String
})
</script>

<template>
  <button class="button-primary">
    {{ texto }}
  </button>
</template>

<style scoped lang="scss">
.button-primary {
  font-family: 'Zilla Slab', serif;
  font-size: 32px;

  background-color: #BFFF00;
  color: #C8D4A6;

  border: none;
  border-radius: 55px;

  padding: 16px 32px;
  cursor: pointer;

  transition: all 0.3s ease;

  &:hover {
    background-color: #C8D4A6;
    color: #BFFF00;
  }
}
</style>