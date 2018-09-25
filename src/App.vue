<template>
  <div class="zs-admin">
    <h3>zhushan</h3>
    <HelloWorld :msg="msg"></HelloWorld>
    <HelloWorld :name="name"></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data() {
    return {
      msg: { name: 111 },
      name: '999'
    };
  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
