<template>
  <q-page >
    <h1>Page de contact</h1>
    <p>J'ai {{ age }} ans</p>
  </q-page>
</template>

<script>
export default {
  name: 'PageContact',
  data () {
    return {
      age: 33
    }
  }
}
</script>

<style lang="sass" scoped>
h1
  color: $secondary
</style>
