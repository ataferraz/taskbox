<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <inbox-screen />
  </div>
</template>

<script>
  import store from './store';
  import InboxScreen from './components/InboxScreen.vue';
  export default {
    name: 'app',
    store,
    components: {
      InboxScreen,
    },
  };
</script>
<style>
  @import './index.css';
</style>