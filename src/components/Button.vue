<template>
  <button class="button" :class="{ double, tiple, operation }">
    {{ label }}
  </button>
</template>

<script>
  export default {
    props: {
      label: {},
      operation: { type: Boolean },
      double: { type: Boolean },
      tiple: { type: Boolean }
    }
  }
</script>

<style>

</style>