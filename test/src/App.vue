<template>
  <div id="app">
    <Boodschappen v-bind:boodschappen="boodschappen"/>
  </div>
</template>

<script>
import Boodschappen from './components/Boodschappen.vue'

export default {
  name: 'App',
  components: {
    Boodschappen
  },
  data() {
    return {
      boodschappen: [
        {
          id: 1,
          title: "Kiwi",
          completed: false
        },
        {
          id: 2,
          title: "Aardappel",
          completed: false
        },
        {
          id: 3,
          title: "Chocola",
          completed: false
        },
        {
          id: 4,
          title: "Pasta",
          completed: false
        },
        {
          id: 5,
          title: "Brood",
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>