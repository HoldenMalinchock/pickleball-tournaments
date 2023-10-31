<template>
  <div>
    <div>
      My new first component
    </div>
    <button @click="r++">Click me</button>
    <div>
      {{ r }}
    </div>
    <UCard >
    <template #header />
    Body
    <template #footer />
  </UCard>
  <UButton>Button</UButton>
    </div>
</template>

<script setup>
const r = ref(0)
</script>