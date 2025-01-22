<template>
  <h1>{{ helloWorld }}</h1>
</template>

<script>
export default {
  name: 'App',
  data: {
    helloWorld: 'Hello World',
  },
};
</script>

<style>
h1 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
