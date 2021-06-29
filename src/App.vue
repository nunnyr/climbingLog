<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <img alt="Climbing gym" src="./assets/theCliffs.jpeg">
  <HelloWorld />
  <BaseButton text="Submit"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BaseButton from './components/BaseButton.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    BaseButton
  }
}

</script>
