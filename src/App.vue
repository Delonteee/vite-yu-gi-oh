<script>
export default {
    data() {
      return { count: 0 }
    },
};
</script>

<template>
  <div>
    <h1>
      Template Vite
    </h1>
    <p>
      {{count}}
    </p>
    <button @click="count++">
      Incrementa counter
    </button>
  </div>
</template>

<style scoped>
  /* STILE CSS CON SCOPE A QUESTO FILE */
</style>
