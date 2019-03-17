<template lang="pug">
  .app-header.d-flex
    h1 Todo List
    h2 1 more to do, 1 done
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.app-header {
  align-items: flex-end;
  h1 {
    flex-grow: 1;
  }
  h2 {
    font-size: 1.2rem;
    color: gray;
  }
}
</style>
