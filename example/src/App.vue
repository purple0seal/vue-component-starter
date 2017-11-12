<template>
  <div id="app">
    <custom-component></custom-component>
  </div>
</template>

<script>
  import Component from '../../src/Component.vue'

  export default {
    name: 'app',
    components: { 'custom-component': Component }
  }
</script>
