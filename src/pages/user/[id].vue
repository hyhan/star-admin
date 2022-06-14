<script setup lang="ts">
const props = defineProps({
  id: String,
})
const id = useVModel(props, 'id')
</script>

<template>
  <div>
    {{ id }}
    <div i-carbon-campsite />
  </div>
</template>

<style lang="scss" scoped>

</style>

<router lang="yaml">
meta:
  layout: default
</router>
