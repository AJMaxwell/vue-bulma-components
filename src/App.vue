<template>
  <div id="app">
    <hr/>
    <Grid/>
    <hr/>
    <Box/>
    <hr/>
    <FormComponent/>
  </div>
</template>

<script>
import Grid from './example/grid.vue'
import Box from './example/box.vue'
import FormComponent from './example/form.vue'

export default {
  name: 'app',
  components: {
    Grid,
    Box,
    FormComponent
  }
}
</script>

