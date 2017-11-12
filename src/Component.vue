<template>
  <h1>Hello {{ text }}!!</h1>
</template>

<script>
  export default {
    name: 'custom-component',
    props: {
    },
    data () {
      return {
        text: 'world'
      }
    },
    computed: {
    },
    methods: {
    }
  }
</script>
