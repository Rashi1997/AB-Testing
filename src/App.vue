<template>
  <div>
    <Introduction />
    <AB />
    <Hypotheses />
    <Infographic />
    <Takeaways />
  </div>
</template>

<script>
import Introduction from './components/Introduction.vue'
import AB from './components/AB.vue'
import Hypotheses from './components/Hypotheses.vue'
import Infographic from './components/Infographic.vue'
import Takeaways from './components/Takeaways.vue'

export default {
  name: 'App',
  components: {
    Introduction,
    AB,
    Hypotheses,
    Infographic,
    Takeaways
  }
}
</script>

<style>
</style>
