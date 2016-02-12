<template>
  <div id="app">
    <img class="logo" src="./assets/logo.png">
    <p>this is david's vue demo</p>
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  components: {
    Hello
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
