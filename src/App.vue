<template>
  <div class="container">
    <h1>Vue "todo" application</h1>
    <progresso></progresso>
    <addButton></addButton>
    <items></items>

  </div>



</template>

<script>
import progresso from './components/progresso'
import addButton from './components/addButton'
import items from './components/items'

export default {
  name: 'app',
  components: {
    progresso,
    addButton,
    items
  }
}
</script>

<style lang="sass">
  .container
    width: 960px
    margin: 0 auto
  h1
    text-align: center
</style>
