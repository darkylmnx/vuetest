<template>
  <div id="app">
    <router-link class="button is-primary" to="/">hello</router-link>
    <router-link class="button is-primary" to="/page1">page1</router-link>
    <router-link class="button is-primary" to="/page2">page2</router-link>
    <router-view class="box"></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
@import '~bulma';

.box {
  margin: 20px;
}

#app {
  padding: 20px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
