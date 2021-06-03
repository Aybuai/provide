<template>
  <div>
    A组件
    <Comb></Comb>
  </div>
</template>

<script>
import Comb from './comb.vue'
export default {
  components: { Comb },
  data() {
    return {
      title: 'A标题'
    }
  },
  provide() {
    return {
      coma: this,
      title: this.title
    }
  }
}
</script>

<style>

</style>