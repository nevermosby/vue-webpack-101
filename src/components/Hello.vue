<template lang="jade">
div.hello
  h1 {{ msg }}
  jade-temp
</template>

<script>
import JadeTemp from './jadeTemp'
export default {
  components: { JadeTemp },
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello World!'
    }
  }
}
</script>
