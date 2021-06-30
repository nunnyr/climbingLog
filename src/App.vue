<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <img alt="Climbing gym" src="./assets/theCliffs.jpeg">
  <HelloWorld />
  <HomePage text="Hello"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HomePage
  }
}
</script>