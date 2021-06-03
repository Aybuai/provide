<template>
  <div>
    C组件
    <button @click="handleClick">Get the attributes of A component</button>
  </div>
</template>

<script>
export default {
  inject: ['coma', 'title'],
  methods: {
    handleClick() {
      console.log(this.coma)
      console.log(this.title)
    }
  }
}
</script>

<style>

</style>