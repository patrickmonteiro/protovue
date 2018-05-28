<template>
  <v1-grid guides  size="12x8" gap="10">

    <v1-cell size="12x1"> 
      <v1-nav />
    </v1-cell>

    <v1-cell size="3x9" y="1">
      <v1-image center round width="70px" height="70px" />
      <v1-text center rows="3" />
      <v1-avatar count="8" />
    </v1-cell>

    <v1-cell middle size="2x9" y="1" x="10">
      <v1-image center round width="100px" height="100px" />
      <v1-text center rows="7" />
    </v1-cell>

    <v1-cell center middle size="7x8" y="1" x="3" style="text-align: center">
       <img style="align-v:center" src="https://i.pinimg.com/originals/40/f4/a5/40f4a53b243411e246d7af7e24160e51.gif" />
    </v1-cell>

    <v1-cell size="7x1" y="9" x="3">
      <v1-footer />
    </v1-cell>

  </v1-grid>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
