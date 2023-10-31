<template>
  <div>
    <div>My new first component</div>
    <button class="bg-red-800" @click="r++">Click me</button>
    <div>
      {{ r }}
    </div>
    <UCard> Body </UCard>
    <UButton>Button</UButton>
  </div>
</template>

<script setup>
const r = ref(0)
</script>