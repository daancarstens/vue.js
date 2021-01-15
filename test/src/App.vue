<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {

  },
  data() {
    return {
      films: [
        {
          id: 1,
          title: "film 1",
          completed: false
        },
        {
          id: 2,
          title: "film 2",
          completed: true
        },
        {
          id: 3,
          title: "film 3",
          completed false
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

  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
