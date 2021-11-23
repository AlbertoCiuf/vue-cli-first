<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Title/>
    <Hero />
  </div>
</template>

<script>
import Title from "./components/Title.vue"
import Hero from "./components/Hero.vue"

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
