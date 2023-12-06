<script>
export default {
  name: 'App Component',
  data() {
    return {
      text: 'La mia prima app con Vite!',
    };
  },
};
</script>

<template>
  <h1>{{ text }}</h1>
</template>

<style scoped>
h1 {
  text-align: center;
  padding: 1.875rem;
}
</style>
