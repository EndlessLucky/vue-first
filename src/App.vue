<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <AddNewTodo/>
</template>

<script>
import AddNewTodo from './components/AddNewTodo.vue'

export default {
  name: 'App',
  components: {
    AddNewTodo
  }
}
</script>
