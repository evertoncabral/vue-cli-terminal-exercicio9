<template>
  <div id="app">
    <h1 :teste="testando">Diretiva v-bind</h1>
    <Title titulo="Titulo 1"/>
    <Title titulo="Titulo 2"/>

  </div>
</template>

<script>

import Title from './Title.vue';

export default {
  name: "App",
  components: {
    Title,
  },
  data() {
    return {
      testando: "hello World",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
