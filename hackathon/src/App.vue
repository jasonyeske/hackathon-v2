<template>
  <TheNavBar />
  <TheFooter />

  
 
</template>

<script>
import TheNavBar from './components/layout/TheNavBar.vue'
import TheFooter from './components/layout/TheFooter.vue'

export default {
  name: 'App',
  components: {
    TheNavBar, TheFooter, 
  }
}
</script>

