<script>
export default {
  name: 'Jumbotron',
  data() {
    return {
      text: 'Jumbotron x bonus',
    };
  },
};
</script>

<template>
  <div class="container">
    <div class="container-jumbo">
      <h2>{{ text }}</h2>
    </div>
  </div>
</template>

<style scoped>
h2 {
  color: rgb(187, 121, 34);
}
.container {
  display: flex;
  justify-content: center;
}
.container-jumbo {
  border-radius: 1%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(240, 248, 255, 0.612);
  width: 50%;
  height: 18.75rem;
}
</style>
