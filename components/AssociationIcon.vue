<template>
  <div class="ms-4">
    <a :href="href">
      <img class="h-20 w-auto" :src="src" alt="" />
    </a>
  </div>
</template>

<script setup lang="ts">
const props = withDefaults(
  defineProps<{
    src: string
    href?: string
  }>(),
  {
    href: "#"
  }
)
</script>