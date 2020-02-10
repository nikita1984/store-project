<template>
  <div>
    <Header />
    <router-view />
    <div class="footer">Footer</div>
  </div>
</template>

<script>
import Header from './elements/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
.app {
  background-color: aqua;
}
</style>