<template>
  <div id="app"><Todos v-bind:todos="todos" /></div>
</template>

<script>
import Todos from './components/ToDos'

export default {
  name: 'App',
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title:'One Title',
          completed: false
        },
        {
          id: 2,
          title:'Second Title',
          completed: false
        },
        {
          id: 3,
          title:'Third Title',
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
