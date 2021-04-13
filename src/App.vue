<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AddTodos />
    <FilterTodos />
    <Todos />
  </div>
</template>

<script>
import AddTodos from "./components/AddTodos"
import FilterTodos from './components/FilterTodos.vue'
import Todos from './components/Todos.vue'

export default {
  name: 'App',
  components: {
    AddTodos,
    FilterTodos,
    Todos
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
