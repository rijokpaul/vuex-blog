<template>
  <div id="app">
    <router-view name="navbar"></router-view>
    <b-container>
      <router-view name="default" />
    </b-container>
  </div>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
<style>
@import './assets/styles/style.scss';
</style>
