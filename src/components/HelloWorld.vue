<template lang="pug">
  h1 {{ getTitle }}
</template>

<script>
import { mapGetters } from 'vuex';

export default {
  name: 'HelloWorld',
  computed: mapGetters(['getTitle']),
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
h1
  color: green
</style>
