<template>
  <div id="home">
    <nav-bar></nav-bar>>
  </div>
</template>

<script>
import NavBar from 'components/common/navbar/NavBar';
export default {
  name: 'home',
  components: {
      NavBar
  },
  props: {
    path: {
      type: String,
      required: true
    }
  }
}
</script>
<style>

</style>>
