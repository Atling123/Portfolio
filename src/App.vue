<template>
  <NavigateHead></NavigateHead>
  <NavigateBody></NavigateBody>
  <NavigateProjects></NavigateProjects>
  <NavigateFoot></NavigateFoot>
</template>

<script>
import NavigateHead from './components/NavigateHead.vue'
import NavigateBody from './components/NavigateBody.vue'
import NavigateProjects from './components/NavigateProjects.vue'
import NavigateFoot from './components/NavigateFoot.vue'

export default {
  name: 'App',
  components: {
    NavigateHead,
    NavigateBody,
    NavigateProjects,
    NavigateFoot
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1d1a1a;
}

</style>
