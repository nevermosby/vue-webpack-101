<template lang="jade">
div.content
  i {{ content }}
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      content: 'David is using jade here'
    }
  }
}
</script>
