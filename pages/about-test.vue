<template>
  <div class="about">
    <heading-test :heading="heading"></heading-test>
  </div>
</template>
<script>
import HeadingTest from '../components/HeadingTest.vue'

export default {
  components: {
    HeadingTest,
  },

  data() {
    return {
      heading: 'hello, Vue.JS',
    }
  },
}
</script>
