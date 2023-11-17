<template>
  <div id="app">
    <NoteList />
    <NoteForm />
  </div>
</template>

<script>
import NoteList from './components/Notes/NoteList.vue'
import NoteForm from './components/Form/NoteForm.vue'

export default {
  name: 'App',
  components: {
    NoteList,
    NoteForm
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
