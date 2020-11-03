<template>
  <div class="container">
    <h1>{{ message }}</h1>
    <h2>{{name}} </h2>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Using Parcel In A Vue.js App',
      name: 'Andy'
    };
  },
};
</script>

<style scoped>
  .container {
    width: 600px;
    margin: 50px auto;
    text-align: center;
  }
</style>