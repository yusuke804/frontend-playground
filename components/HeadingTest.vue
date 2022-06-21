<template>
  <div id="heading">
    <h1>{{ heading }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    heading: {
      type: String,
      default: 'No Heading',
      required: true,
    },
  },
}
</script>

<style lang="sass" scoped>
#heading
  border-bottom: 1px solid #ddd
  border-top: 1px solid #ddd
h1
  color: #f00
</style>
